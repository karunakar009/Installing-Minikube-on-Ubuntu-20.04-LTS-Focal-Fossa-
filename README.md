# Installing-Minikube-on-Ubuntu-20.04-LTS-Focal-Fossa-
Installing Minikube on Ubuntu 20.04 LTS (Focal Fossa)

## Overview

Before learning about Minikube, we should at least know about Kubernetes, because Minikube is one kind of Kubernetes which is commonly used.

Kubernetes is a portable, extensible, open source platform for managing containerized workloads and services, that facilitates both declarative configuration and automation. In other words, Kubernetes is a container manager which manages several containers to serve at one end and prevents the service of being down or overloaded by weighing all loads and balancing them throughout all containers at the same time. Put simply, Kubernetes is a multi-service manager. For more information about Kubernetes, please read the concept from its official website https://kubernetes.io/docs/concepts/overview/.

Minikube is a lightweight Kubernetes implementation that creates a VM on your local machine and deploys a simple cluster containing only one node (node = machine/server). Minikube is available for Linux, macOS, and Windows systems. Minikube is the simplest and easiest to use type of Kubernetes if you have only one single server to run.
## Prerequisites
* A server running on one of the following operating systems: Ubuntu 22.04, 20.04, 18.04, 16.04 or any other Debian-based distribution like Linux Mint
* It’s recommended that you use a fresh installed OS to prevent any unexpected issues
* Access to the root user
## Installation Steps
* Step 1. Installing Docker
In this article, we will be using Docker container as a base for Minikube. In case Docker is not installed yet on your Ubuntu system then use following link to install it: Installing Docker on Ubuntu 20.04 LTS (Focal Fossa)

* Step 2. Updating system packages and installing Minikube dependencies

``` $ sudo apt update & sudo apt upgrade
$ sudo apt install -y curl wget apt-transport-https
```
