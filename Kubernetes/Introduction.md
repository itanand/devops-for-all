## Kubernetes tutorials

Kubernetes is a portable, extensible, open source platform for managing containerized workloads and services, that facilitates both declarative configuration and automation. It has a large, rapidly growing ecosystem. Kubernetes services, support, and tools are widely available.

- [What is Kubernetes ? ](#what-is-kubernetes-k8s-)
- [Kubernetes Architecture ](#open-source-cloud-platforms)
- [Main K8S Components in Details?](#main-k8s-components)
- [What is Minikube and Kubectl ?](#cloud-platforms)
- [Main Kubectl & Minicube Commands ](#cloud-platforms)


![image](https://github.com/itanand/devops-for-all/assets/38817976/a2d162f9-3df3-455a-a49e-e75c931c37aa)


## What is Kubernetes (k8s) ?

Kubernetes is an open-source Container Management tool that automates container deployment, container scaling, descaling, and container load balancing (also called a container orchestration tool). It is written in Golang and has a vast community because it was first developed by Google and later donated to CNCF (Cloud Native Computing Foundation). Kubernetes can group ‘n’ number of containers into one logical unit for managing and deploying them easily. It works brilliantly with all cloud vendors i.e. public, hybrid, and on-premises. 

> It's an Open Source Container orchestration tool, Developed by Google.

### Going Back in time 

Let's take a look at why Kubernetes is so useful by going back in time.

![image](https://github.com/itanand/devops-for-all/assets/38817976/4be1cf3f-93ad-4ff7-8efc-ced1c05a2a05)


#### Traditional deployment era:

Early on, organizations ran applications on physical servers. There was no way to define resource boundaries for applications in a physical server, and this caused resource allocation issues. For example, if multiple applications run on a physical server, there can be instances where one application would take up most of the resources, and as a result, the other applications would underperform. A solution for this would be to run each application on a different physical server. But this did not scale as resources were underutilized, and it was expensive for organizations to maintain many physical servers.

#### Virtualized deployment era:

As a solution, virtualization was introduced. It allows you to run multiple Virtual Machines (VMs) on a single physical server's CPU. Virtualization allows applications to be isolated between VMs and provides a level of security as the information of one application cannot be freely accessed by another application.

Virtualization allows better utilization of resources in a physical server and allows better scalability because an application can be added or updated easily, reduces hardware costs, and much more. With virtualization you can present a set of physical resources as a cluster of disposable virtual machines.

> Each VM is a full machine running all the components, including its own operating system, on top of the virtualized hardware.

#### Container deployment era:

Containers are similar to VMs, but they have relaxed isolation properties to share the Operating System (OS) among the applications. Therefore, containers are considered lightweight. Similar to a VM, a container has its own filesystem, share of CPU, memory, process space, and more. As they are decoupled from the underlying infrastructure, they are portable across clouds and OS distributions.

## Kubernetes Architecture 



## Main K8S Components 

When you deploy Kubernetes, you get a cluster.

A Kubernetes cluster consists of a set of worker machines, called nodes, that run containerized applications. Every cluster has at least one worker node.

The worker node(s) host the Pods that are the components of the application workload. The control plane manages the worker nodes and the Pods in the cluster. In production environments, the control plane usually runs across multiple computers and a cluster usually runs multiple nodes, providing fault-tolerance and high availability.

This document outlines the various components you need to have for a complete and working Kubernetes cluster.

<ol>
  <li>Pod  </li>
  <li>Service </li>
  <li>Volumes  </li>
  <li>Ingress </li>
  <li>Secrets </li>
  <li> Ingress </li>
  <li>Config Map </li>
  <li>Deployment </li>
  <li> Stateful Sets</li>
</ol>

![image](https://github.com/itanand/devops-for-all/assets/38817976/9724a4b5-5eaa-4acd-aed2-1e30fd371054)



![image](https://github.com/itanand/devops-for-all/assets/38817976/402d20c0-21cc-4f59-90b6-d8b1ea690287)


