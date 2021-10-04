# Deployment of 5G core in an EKS cluster
SA 5G core deployment in AWS EKS cluster in an attempt to demonstrate the deployment possibilities and management of the 5G network.

**Table of Contents**

- [Project Overview](#project-overview)
- [Documentation](#documentation)
    * [Launching and managing of an EC2 instance]()
  - [Kubernetes](https://github.com/Rawlings-bit/5G_deployment/tree/main/free5gc/k8s-manifests)
    - [Prerequisites](https://github.com/Edwin-programmer/Project5G-ansible-deployment/tree/main/Kubernetes%20deployment#prerequisites)
    - [Overview](https://github.com/Edwin-programmer/Project5G-ansible-deployment/tree/main/Kubernetes%20deployment#overview)
    - [Configuration](https://github.com/Edwin-programmer/Project5G-ansible-deployment/tree/main/Kubernetes%20deployment#configuration)
      - [IP tables](https://github.com/Edwin-programmer/Project5G-ansible-deployment/tree/main/Kubernetes%20deployment#ip-tables)
      - [Minikube](https://github.com/Edwin-programmer/Project5G-ansible-deployment/tree/main/Kubernetes%20deployment#minikube)
      - [Kubectl](https://github.com/Edwin-programmer/Project5G-ansible-deployment/tree/main/Kubernetes%20deployment#kubectl)
    - [Openvswitch, Multus and OVS-CNI Containers](https://github.com/Edwin-programmer/Project5G-ansible-deployment/tree/main/Kubernetes%20deployment#kubectl)
    - [Kube-flannel & etcd-ha-operator](https://github.com/Edwin-programmer/Project5G-ansible-deployment/tree/main/Kubernetes%20deployment#kubectl)
    - [Deployments](https://github.com/Edwin-programmer/Project5G-ansible-deployment/tree/main/Kubernetes%20deployment#Deployments)

## Project Overview

The aim of this project is to deploy 5G core in AWS EKS cluster and run a test of the connectivity with an application. The test will be done by providing different network slices to some application and monitoring the network performance.

## Documentation

User documentation can be found below for the two options deployed for the project
- [Launching and managing of an EC2 instance]
- [Project setup using Kubernetes](https://github.com/Edwin-programmer/Project5G-ansible-deployment/tree/main/Kubernetes%20deployment/README.md)
- Additional documentation can be found within the repository Wiki page  [Full documentation](https://github.com/Edwin-programmer/Project5G-ansible-deployment/wiki)
        
