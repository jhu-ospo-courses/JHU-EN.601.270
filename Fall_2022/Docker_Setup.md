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

Lastly, having `git` installed will make things easier for labs as you can clone the exercise files directly instead of creating them. 
The 'git' version control tools are available from here: https://git-scm.com/downloads


## Getting Ready
Assuming you have installed the prerequisite software, and are in your home directory, clone this repo. 
(If you organize your directories differently, you should be able to change directory and clone the repo into a different place.)

> The shell command prompt is shown as a `$`, sometimes with a machine+directory identifier (e.g. `MacBook-Pro labs$`).
> Expected output then follows (possibly truncated with `...` if there is a lot of output). 
> You are expected to type what follows the `$`, hitting a `<RETURN>` key at the end of the command.
> In the following example, you will type `git clone https://github.com/stephenrwalli/JHU-EN.601.210.git<RETURN>`, see the displayed output, 
> then type `ls<RETURN>`. 

```
$ git clone https://github.com/stephenrwalli/JHU-EN.601.210.git
Cloning into 'JHU-EN.601.210'...
remote: Enumerating objects: 62, done.
remote: Counting objects: 100% (62/62), done.
remote: Compressing objects: 100% (53/53), done.
remote: Total 62 (delta 7), reused 11 (delta 0), pack-reused 0
Receiving objects: 100% (62/62), 28.69 KiB | 103.00 KiB/s, done.
Resolving deltas: 100% (7/7), done.
stephenrwalli@Stephens-MacBook-Pro Projects$ cd JHU-EN.601.210/
$ ls
LICENSE   README.md labs      lessons
$
```

## Cleaning up after the course 
Once the course is over, you will likely want to clean up all the disk space used in the labs for EN.601.210.

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
