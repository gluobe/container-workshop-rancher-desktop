## Lab 00 - Prerequisites

A couple of requirements before we can start with the actual labs.

## Task 0: Docker Hub account

If you do not yet have a Docker Hub account, please sign up for a free one at:

https://hub.docker.com/signup

## Task 1: Install Podman

Folllow the Podman installation instruction from the following website:

https://podman.io/getting-started/installation 

Validate that Podman has been installed succesfully by issuesing the command below and validating your output looks similar:

```
 ~/Documents/git/gluo> podman version
Client:       Podman Engine
Version:      4.0.1
API Version:  4.0.1
Go Version:   go1.17.7
Git Commit:   c8b9a2e3ec3630e9172499e15205c11b823c8107
Built:        Thu Feb 24 12:12:50 2022
OS/Arch:      linux/amd64
      
```

## Task 2: Configure Docker Hub registry

Before starting with the exercises, ensure that you have configured the Docker Hub registry. 
To configure the registry, the file ```/etc/containers/registries.conf``` needs to have the following two lines configured and uncommented:

```
[registries.search]
registries = ['docker.io']
```

## Task 3: Login to Docker Hub
```
podman login docker.io

Username: yourusername
Password:

Login Succeeded!
```