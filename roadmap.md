# VCS : Github
Git is a free tool used for source code management. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development.

## Base commands

``git init``
```
PS C:\Users\btc\Desktop\DevOps> git init
Initialized empty Git repository in C:/Users/btc/Desktop/DevOps/.git/
```

``git config --list``
```
PS C:\Users\btc\Desktop\DevOps> git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
core.fsmonitor=true
core.editor="C:\\Program Files\\Notepad++\\notepad++.exe" -multiInst -notabbar -nosession -noPlugin
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=codecrafter1994@gmail.com
user.name=rahimbtc
user.username=codecrafteroot
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
```

``git config user.email``
``git config user.name``

``git status``
```
PS C:\Users\btc\Desktop\DevOps> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        roadmap.md

nothing added to commit but untracked files present (use "git add" to track)
```

``git add``
``git commit -m "first commit"``
``git branch -M main``
``git remote add origin https://github.com/rajites756ofionk/roadmap.git``
``git push -u origin main``


# Scripting language : Python
Python is a multi-paradigm language. Being an interpreted language, code is executed as soon as it is written, and the syntax allows for writing code in different ways. Python is frequently recommended as the first language new coders should learn, because of its focus on readability, consistency, and ease of use.

# Linux & scripting : Ubuntu & bash
An Operating system serves as a bridge between a computer's user and its hardware. Its function is to offer a setting in which a user can conveniently and effectively run programs.

# Networking
DNS, HTTP, HTTPS, SSL/TLS, SSH

# Server management
Reverse Proxy Nginx
Forward Proxy 
Caching proxy
Load balancing
firewalls

# Log management : ELK

# Containers : Docker
Docker is by far the most popular container technology today. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries, and settings. Here you need to know how to run containers, Docker Networking, Volumes, Dockerfiles, and run multiple containers with Docker-Compose.

# Orchestration : Docker swarm

# Configuration management : Ansible

# CI/CD : Github Actions & jenkins