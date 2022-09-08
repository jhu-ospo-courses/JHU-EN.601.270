# Setting up for Labs

## Technology
I imagine students mostly live on Mac OSX or Windows machines. From that perspective we are going to set up a simplified, container-based, virtual machine environment using Docker. 

Docker is free technology available from Docker Inc. for defining light weight virtual environments and can be downloaded from here: https://www.docker.com/get-started.

Creating a virtual machine means creating disk space and memory on your regular student machine that will be used to run a new smaller computer 'virtually.' 
This is the same technology that allows you to organize a very large server into many smaller virtual servers to distribute workloads and isolate them from one another. 
Once you log on to that virtual machine, everyone will be looking at the same environment for labs. 

It is important to remember that virtual machines still take up disk space when they are not running, and memory as well when they are running. 
If you experiment with too many virtual machine images, you may discover you run out of space for all the other files and apps you want to run. 

Additionally you will need a UNIX-like command line environment on your computer. 
If you are running a Mac, then you can use a tool like iTerm (available here): https://iterm2.com/ 

On a Windows machine, you can install the Windows Terminal which is a better command line shell, https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701

Having `git` installed will make things easier for labs as you can clone the exercise files directly instead of creating them. 
The 'git' version control tools are available from here: https://git-scm.com/downloads


## Getting Ready
Assuming you have installed the prerequisite Docker software, and are in your home directory in a command shell, 
start a clean containerized environment in which you will explore the project. 
```
$ docker run -it -d -p 8080:80 ubuntu
Unable to find image 'ubuntu:latest' locally
latest: Pulling from library/ubuntu
da7391352a9b: Pull complete
14428a6d4bcd: Pull complete
2c2d948710f2: Pull complete
Digest: sha256:c95a8e48bf88e9849f3e0f723d9f49fa12c5a00cfc6e60d2bc99d87555295e4c
Status: Downloaded newer image for ubuntu:latest
f1eac0505442d31e4247b94242010e4347b8fadd950326c7d688594d4ac43778
$
``` 
Get the name of the container using `docker ps -a`.
```
$ docker ps -a
CONTAINER ID   IMAGE     COMMAND       CREATED              STATUS              PORTS                  NAMES
f1eac0505442   ubuntu    "/bin/bash"   About a minute ago   Up About a minute   0.0.0.0:8080->80/tcp   vigilant_wilson
```
The container has a made up name (`vigilant_wilson` in this example) and a container ID. 
Attach to the container and login to an interactive shell. 
```
$ docker exec -it vigilant_wilson /bin/bash
root@f1eac0505442:/#
``` 
Remember, when you see a `#` symbol at the end of the prompt, this is a root-privileged shell. Your account is all powerful, and mistakes can be costly. 
In the real world, we would immediately create a less privileged account on a virtual machine, and then login with that account.  
```
root@f1eac0505442:/# ls -a
.  ..  .dockerenv  bin  boot  dev  etc  home  lib  lib32  lib64  libx32  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
root@f1eac0505442:/# cd home
root@f1eac0505442:/home# ls 
root@f1eac0505442:/home#
```
We are back in the empty home directory, ready to begin. 
Let's setup the environment for building software with the tools we will likely need using `apt`.
You can list multiple packages on the `apt` command line, forcing acceptance with a `-y` option. 
First we will update our `apt` database. 
```
root@f1eac0505442:/home# apt-get update
Get:1 http://security.ubuntu.com/ubuntu focal-security InRelease [109 kB]
...
Get:17 http://archive.ubuntu.com/ubuntu focal-backports/universe amd64 Packages [4248 B]
Fetched 16.6 MB in 4s (4021 kB/s)
Reading package lists... Done
root@f1eac0505442:/home# apt-get install -y curl gcc make cloc
Reading package lists... Done
Building dependency tree
...
Processing triggers for libc-bin (2.31-0ubuntu9.1) ...
Processing triggers for ca-certificates (20201027ubuntu0.20.04.1) ...
Updating certificates in /etc/ssl/certs...
0 added, 0 removed; done.
Running hooks in /etc/ca-certificates/update.d...
done.
root@f1eac0505442:/home#
```
At this point, you have a basic Ubuntu machine on which to test build the project, you are logged into it.
As you build the softfware, you may indeed encounter other dependencies for tools. 
You can use `apt-get` to pull any other tooling you might need. (You might even note it in the report.) 

## Cleaning up after the lab 
Once the lab is done, you will likely want to clean up all the disk space used in the lab.

You can see all the Docker containers running, and then remove each container. 
You can see all the Docker container images as well, and remove them as well. 
If you are using the `bash` shell on a Mac, you can remove them all in one command as follows. 
Otherwise, you can remove each container one-at-a-time, after listing them. 
The same applies for removing container images. 
```
$ docker rm $(docker ps -a -q)
... list of removed docker containers by container id ... 
$ docker rmi $(docker images -a -q)
Untagged: ubuntu:latest
Untagged: ubuntu@sha256:c95a8e48bf88e9849f3e0f723d9f49fa12c5a00cfc6e60d2bc99d87555295e4c
Deleted: sha256:f643c72bc25212974c16f3348b3a898b1ec1eb13ec1539e10a103e6e217eb2f1
Deleted: sha256:9386795d450ce06c6819c8bc5eff8daa71d47ccb9f9fb8d49fe1ccfb5fb3edbe
Deleted: sha256:3779241fda7b1caf03964626c3503e930f2f19a5ffaba6f4b4ad21fd38df3b6b
Deleted: sha256:bacd3af13903e13a43fe87b6944acd1ff21024132aad6e74b4452d984fb1a99a
$
```
You likely will have seen a different set of images deleted. This is just an example. 
