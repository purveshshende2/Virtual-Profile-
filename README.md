# Virtual-Profile-
Virtual Profile project [Locally]
**It's only for MacOS M1 & M2 chip**

Simple Devops project mangement manually in local machine.

**Objectives**
- VM automation locally
- Real world project setup Locally for [R &D]

**About the project**
- Multi tier web application Stack
- Setup on Laptop/ Desktop
- Helps you setup any project locally

**Tools**
- Hypervisor
- Vagrant for automation
- CLI git bash
- IDE - VS Code


**Architecture**
- NGINX
- TOMCAT
- RABBITMQ
- MEMCACHED
- MYSQL

 **NGINX** 
 - common to provide load balancer experience 
 **TOMCAT**
 - Java web app service, to host java web application
**NFS**
 - shared storage, If you have clusterised server and you need centralised storage you can use NFS
 **Memcahed** 
 - Request comes to accessing the chache second time it call the data from here
**MYSQL**
- Login details saved in MYSQL 
**RabbitMQ** 
- connected to tomcat Quetiong agent , to connect apps, message broker
- Its just dummy in this project to create complexity.


**Vagrant Hostmaanger**
- when you mentioned the Ip address and hostname of every Vm’s hostfiles `/etc/hosts` this file should have entry and matching IP address
Global setting.

- `$ vagrant plugin install vagrant-hostmanager`
- `$ vagrant hostmanager`


**VM Setup**

- `$vagrant up`
