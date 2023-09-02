---
layout: post
---

# Research on Edge/Fog Computing System
- Edge Computing is a distributed computing paradigm that brings computation and data storage closer to the sources of data
- Fog Computing is an architecture that uses edge devices to carry out a substantial amount of computation, storage and communication locally and routed over the Internet backbone
- The DMS Edge team is currently researching about
        - Autonomic Provisioning Edge Cluster System
        - Smart Gateway for onboarding IoT devices to Edge Cluster
<br/>
<img src="/assets/img/edge_architecture.png" height="350" title="edge_architecture"/>
<br/>

## Autonomic Provisioning Edge Cluster System

##### Container Based Distributed Smart Infrastcuture
- Container deployment is the act of deploying containers to their target environment, such as a cloud or on-premises server. Containers are similar to virtual machines, but it
 has relaxed isoloation properties to share the Operating System among the applications. Therefore, containers are considered lightweight. Similar to a VM, a container has its
own filesystem, share of CPU, memory, process space, and more.
- Edge Computing is similar to Cloud Computing, and it refers to processing the data on the edge device and very close to the device. This massive volume of data might be hard to handle entirely on the CLoud Computing network. Not only network problem, their could be more problems; Privacy, Security, and more.
- Also Edge Cluster might require more server resources to compute a computational task which requested from edge device. Not only provisioning the server nodes but also need t
o offload some datas to Fog / Cloud system to compute.
- Hence, we propse a framework, Container Based Distributed Smart Infrastructure which can; be autonomic provisioned with client's requirements, reconfigure the system components dynamically, and edge devices will be onboarded to.

<br/>

<img src="/assets/img/smartgw_architecture.png" height="350" title="smartgw_architecture"/>
<br/>

## Smart Gateway for onboarding IoT devices to Edge Cluster

##### Autonomic Onboarding IoT Devices to Edge Cluster
- Smart Gateway is a gateway specifically designed for the connection of IoT devices. These gateways offer additional functionality in comparison to traditional gateways such as data aggregation and data pre-processing.
- It can expand compatibility for consumer devices and make development easier for manufacturers. The vision of this gateway is to ensure that smart home products are simple, reliable, secure, and easy to use.
- We investigate the research problems that are related to secure bootstrapping in IoT. We identified an important challenge in the area of secure bootstrapping and provide solutions for these problems through theoretical and practical approach. Development of newly secure bootstrapping methods where new discovered devices are separated into isolated network.
        - Development and evaluation of two Diffie-Hellman based secure protocols
        - CPN model design and evaluation of proposed secure protocols
        - Wrap up proposed protocols into one system with dynamically reconfigurable framework

## Current Studies
- Matter, connectivity protocol, for smart gateway onboarding system
- K3S, container based distributed system, for container based distributed smart infrastructure

## Research Results
