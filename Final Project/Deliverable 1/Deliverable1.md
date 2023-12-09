---
name: Jonathan Rodriguez
course: cis106
semester: Fall 2023
---

# Deliverable 1 

> Tutorial can be found [here](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-22-04)


## Concepts I don't understand 

+ Firewall
  + computer network security system that restricts internet traffic in, out, or withing a private network
  + It's intended to help protect your device from selectively blocking certain data packets.
+ Apache
  + Apache is a software that runs on an http server. The job of the software is to establish a connection between a server and the browsers of website visitors.
+ Commands for Apache
  + Linux has apache built in to it's software so all we need to do is access it via to Linux terminal. The website shows a list of examples of different commands for manipulating, changing, or viewing different parts of the Apache software within Ubuntu.

## What is a web server? Hardware an software side

+ Hardware
  + Server is a computer that stores web server software and a website's components files (The main files withing like HTML, CSS, JavaScript)
  + These servers are responsible for interchanging data between the server adn the client
+ Software 
  + Web server has several parts that control the way users access the servers hosted files
  + HTTP server is the bare minimum, These servers are responsible for interpreting HTTP requests
  + HTTP servers can be accessed through domain names.
+ Example
  + A request is made by a client and reaches the server hardware where the software can see what the client wants and decide what to send back
    + There are multiple status codes like 404 that give your user feedback on errors.
    + 200 is the successful connection status code

## What are some different web server applications

### Example 1
![](ResizedApache.webp)
+ Apache 
  + Apache is available on all platforms, this open license web application was made popular by its easy deployment of PHP and understandable user accessability.Apache offered a large collection of modules which expanded the functionality of the base application even further. Despite being released in 1995 Apache remains a popular choice for running a web server.

### Example 2
![](ResiedNgineX.webp)
+ Nginx
  + As our technological needs improved we needed to have applications running on servers that could handle thousands of concurrent connections and NgineX provided us a solution. Released in 2002 as a competitor to Apache NgineX grew in popularity thanks to its static-file-handling, and impressive load balancing capabilities.
### Example 3
![](ResizedCaddy.webp)
+ Caddy
  + Caddy is the most recent of these applications released in 2015. This web application functions more like an Nginx like web server. By simplifying complex codes into simple command this framework is extremely easy to work. One reason why this framework has gained popularity is because HTTPS is automatically enabled without the need to install or renew SSL certifications. 

## What is virtualization?

+ Virtualization is defined as creating virtual versions of something. We use virtualization on computers to run multiple operating systems on one physical machine.Each virtual machine would divide the original machines hardware specs into how many virtual computers are running.
+ As we move forward virtualization can be used to simulate multiple physical servers on one machine.

## What is virtualbox?
![](ResizedVirtualBox.webp)
+ VirtualBox is an application that can run virtual machines on a host computer. Different companies have different softwares that provide the same functionality but virtual box is Open Source and available to the public for free.

## What is virtual machine?

+ A virtual machine is simple the machine that is being simulated on the virtualBox app or other virtualization software. For example if you run the linux operating system through the virtualBox that linux machine becomes your virtual machine. Virtual machines will run using the hosts machine hardware specs.

## What is Ubuntu Server?
![](ResizedUbuntu.webp)
+ An ubuntu server is ubuntu product that is designed to run a server using Linux Ubuntu. This type of server removed the Graphical user Interface for terminal navigation as most of the other Ubuntu built in software.

## What is a firewall?

+ A firewall is a network security e\device that monitors traffic coming in and out of a organizations devices. A firewall's purpose is to protect users and a users information from malicious files, this is done by filtering out files that are flagged as risky or limiting who can access the machine in the first place. 

## What is SSH?

+ Secure Socket Shell 
  + is a network protocol that gives users, particularly system administrators, a secure way to access a computer over an unsecured network.
  + SSH is strong on encryption which protects your data by scrambling.
+ How it works 
  + Created to replace insecure login programs or terminal emulators. This service is installed on most computers software and allows for the secure communication between computers. From clients to hosts as well as remote access and virtualization.

