<p align="center">
    <img src="https://github.com/kubernetes/kubernetes/raw/master/logo/logo.png" width="100">
</p>

<p align="center">
    Configuration of my home-lab K8s cluster
</p>

## Prerequisites

| Tool | Description |
|:-----|:------------|
| [Docker Engine](https://docs.docker.com/get-docker/) | Docker is an open platform for developing, shipping, and running applications.
| [K3d](https://k3d.io/v5.4.6/) | k3d is a lightweight wrapper to run k3s (Rancher Lab’s minimal Kubernetes distribution) in docker. k3d makes it very easy to create single- and multi-node k3s clusters in docker, e.g. for local development on Kubernetes.
| [Taskfile](https://taskfile.dev/) | Task is a task runner / build tool that aims to be simpler and easier to use than, for example, GNU Make. Since it's written in Go, Task is just a single binary and has no other dependencies, which means you don't need to mess with any complicated install setups just to use a build tool.

## Setup
```yaml
Initialize the cluster:
    task init
Destroy the cluster:
    task destroy
View available commands:
    task -a
```