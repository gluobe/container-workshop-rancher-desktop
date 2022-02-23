# Lab 00 - Prerequisites

A couple of requirements before we can start with the actual labs.

## Task 1: Docker Hub account

If you do not yet have a Docker Hub account, please sign up for a free one at:

https://hub.docker.com/signup

## Task 2: Install Rancher Desktop

Folllow the the Rancher Desktop installation instruction from the following website:

https://docs.rancherdesktop.io/getting-started/installation

Validate that Docker has been installed succesfully by issuesing the command below and validating your output looks similar:

```
C:\Users\Steven Trescinski\Documents > docker version

---

You should see output similar to the output below:
Client:
 Version:           20.10.9
 API version:       1.41
 Go version:        go1.16.8
 Git commit:        c2ea9bc
 Built:             Thu Nov 18 21:19:50 2021
 OS/Arch:           windows/amd64
 Context:           default
 Experimental:      true

Server:
 Engine:
  Version:          20.10.11
  API version:      1.41 (minimum version 1.12)
  Go version:       go1.17.3
  Git commit:       847da184ad5048b26f5bdf9d53d070f731b43180
  Built:            Thu Nov 19 03:06:35 2021
  OS/Arch:          linux/amd64
  Experimental:     false
 containerd:
  Version:          1.5.9
  GitCommit:        894b81a4b802e4eb2a91d1ce216b8817763c29fb
 runc:
  Version:          1.0.2
  GitCommit:        425e105d5a03fabd737a126ad93d62a9eeede87f
 docker-init:
  Version:          0.19.0
  GitCommit:        
```