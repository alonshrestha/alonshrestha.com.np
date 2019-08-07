---
title: Introduction to Virtualization | Beginner's Guide
date: '2019-08-03'
layout: post
headerImage: true
tag:
- virtualization
- IBM
- Hypervisor
- VMware
- linux
- cloud server
- jekyll
- gh-pages
- nepal
star: true
category: blog
author: alonshrestha
---



![](/assets/images/blog/2019-08-03/4.jpg) 

The era of [virtualization](https://en.wikipedia.org/wiki/Virtualization){:target="_blank"} might not end for couple more decade. Since the last 60 years, virtualization has been providing a significant range of benefits in Information Technology like no other advance technology has. This technology has changed the determining world with virtualization. The simple concept of virtualization is making high impact on server data centers. The world is being assumed as an insider of virtualization and technician are engaged to make it real sooner or later. Though this concept is leading the world when it comes to understanding and arguments, people think to have multiple operating systems in a single machine as virtualization which means dividing a single physical machine into multiple virtual machines. Living in today's world this explanation might not be enough to understand the working of virtualization. This article is for those who are enthusiastic and beginner to the virtualization.
# What is Virtualization?
In a very simple way, virtualization is the creation of [virtual(**rather than actual**)](https://en.wikipedia.org/wiki/Virtual){:target="_blank"}. This technology lets you run multiple virtual machines on a single physical machine. The resources of a single physical machine are being shared with multiple virtual machines. Each virtual machine can run and interact independently with others. They are isolated with each other due to which if one crashes, it doesn't affect others.

# History 
In 1960 [IMB](https://www.ibm.com/){:target="_blank"} first invented virtualization for their mainframe machine as an approach to time-sharing. [Hypervisor](https://www.ibm.com/cloud/learn/hypervisors){:target="_blank"} made it possible to use multiple systems in a single machine. It is the process of separating the operating system and application between underlying hardware by creating an absolute layer between the software and hardware accessing the resources like storage, network and the memory of the hardware. You might have used virtualization if your desktop hard disk is partition into multiple disks. i.e [Disk (C:), (D:), (E:)](). This is known as [**storage virtualization**](https://en.wikipedia.org/wiki/Storage_virtualization){:target="_blank"}.
# Different types of Virtualization
### Application Virtualization
It might be of a server-based approach, where the application is installed and the client can access the application without installing them on individual machines. eg:[ App-V](https://en.wikipedia.org/wiki/Microsoft_App-V){:target="_blank"}, [Vmware ThinApp](https://www.vmware.com/latam/products/thinapp.html){:target="_blank"}. 
### Desktop Virtualization
This is a client-server based approach, which lets you remotely log access from any location through the network.
### Hardware Virtualization
It is also known as virtualization, where hypervisor or [VMM(Virtual Machine Manager)](https://virt-manager.org/){:target="_blank"} is installed on the server which serves multiple different Operating System simultaneously and isolated. eg([VMware Sphere](https://www.vmware.com/products/vsphere.html){:target="_blank"}, [ESXi](https://www.vmware.com/products/esxi-and-esx.html){:target="_blank"})
###  Network Virtualization
This virtualization uses network resources of a physical server and provides service of computing applications of all virtual machine in a single pool.

# Why Virtualization?
1.95 billion websites are live and running in the cloud server today, but the number of serves isn't the same. More than half the number of websites can be used for the server. In global, most of the organization has implemented virtualization for optimizing the result. Not only the organization but also by the developers for developing or testing their products, virtualization is set up according to their required environment. This does not affect the original environment incase the result may fail.
## Merits
- Efficient in IT operation.
- Reduce time spent
- Reduce cost
- Increase productivity
- Ease backup and swift recovery
- Security
- Shifting to cloud

## Demerits
- High cost of implementation
- Speed can be reduced if the physical hardware has low resources.
- Not sure of every hardware and software can virtualize