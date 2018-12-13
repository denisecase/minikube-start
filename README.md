# Getting Started with MiniKube (Kubernetes) 

## Install Chocolatey

Install [Chocolatey](https://chocolatey.org/) Windows Package Manager.

## Install VirtualBox

Open PowerShell as Administrator and run:

```PowerShell
choco install virtualbox
```

## Restart Windows

After installing VirtualBox, restart your Windows machine. 

## Install MiniKube

Open PowerShell as Administrator and run:

```PowerShell
choco install minikube
```

## Start MiniKube

In PowerShell as Administrator run:

```PowerShell
minikube start
```

## Time Out Error

If you get an error restarting due to a time out, in PowerShell as Administrator run:

```PowerShell
minikube delete
minikube start
```

Success!

```PowerShell
Everything looks great. Please enjoy minikube!
```

## Using MiniKube

In PowerShell as Administrator:

```PowerShell
minikube status
kubectl get nodes
kubectl get services
kubectl get pods
kubectl get deployments
minikube dashboard 

## Terms

- Chocolatey
- [Docker](https://www.docker.com/) container platform
- [Kubernetes](https://kubernetes.io/) container-orchestration system
- VirtualBox hypervisor

## [Kubernetes Concepts](https://kubernetes.io/docs/concepts/)

- Deployment - a controller that defines Pods and ReplicaSets
- Node - worker machine
- Pod - smallest unit of deployment, starts and ends
- Service - an abstraction layer to access Pods and more



