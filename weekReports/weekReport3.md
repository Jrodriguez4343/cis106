---
name: Jonathan Rodriguez
semester: Fall 23
course: cis106
---

# Week Report 3

## Summary Of Presentations

### **Introduction To Linux**

**What is an operating system?**

Provides all of the fundamental features of a computer.

**Aside from a kernel, what other parts make an operating system?**
+ Command - Line Shells
  + Commands on a shell to interact with computer
+ Graphical User Interface
  + Icons, Menus, and mouse pointer to interact with computer
+ Utility and Productivity Programs
  + Tools like
    + Web Browsers
    + Document Processors
    + Text Editors
+ Libraries
  + collections of programming functions
  
**What is a Linux distribution?**

Linux Distribution is the complete Linux system package
Made up of
+ Linux Kernel
+ Core Unix Tools
+ Supplemental Software
+ Startup Scripts
+ An Installer
  
**What is Ubuntu?**

A Linux Distribution based on 4 principles
+ Free Of Charge
+ Usable by people in local language and with any disabilities
+ Freedom to Customize and Alter
+ Software to whatever they see fit

**Define the following terms: Open Source, Closed source, free software**

+ Open Source
  + The software may be distributed for a fee or free. The source code is distributed with the software
+ Closed Source
  + the software is not distributed with the source code. The user is restricted from modifying the code.
    + Freeware 
      + Software is free but the source code is not available
    + Shareware
      + the software is free on a trial basis
  + Free Software
    + The software is distributed with the source code. The software can be free of charge or obtained by a fee.
  
**What are the 4 freedoms defined by the free software foundation?**

1. Freedom 0
   1. Use the software for any purpose
2. Freedom 1
   1. Examine the source code and modify it as you see fit
3. Freedom 2
   1. Redistribute the software
4. Freedom 3 
   1. redistribute your modified software


### **The Basics Of Virtualization**


**What is virtualization?**

Creating virtual versions of a computer, allowing you to run multiple machines inside of one

**List 3 benefits of virtualization**

+ Multiple OS Running At Same Time
+ Reducing Cost Of Physical Hardware By Not Having To Purchase An Entire Network
+ Save State Will Allow You To Save A Computers State Before Any Changes Are Made To Test For Bugs Or Errors

**What is a hypervisor?**

Software or Hardware in charge of creating, managing, and running virtual machines.

**What is virtualbox**

An Application/Program That Allows For Virtualization


### **Exploring Desktop Enviorments**

**What is a desktop environment? (Provide 3 examples)**

An implementation of the desktop metaphor made up of a bundle of programs running on top of an Operating System

+ Desktop Settings
  + Programs that allow you to make configurations
+ Display Manager
  + Choose between desktop environments and users
+ File Manager
  + This Program Allows you to perform file maintenance 

**List 4 common elements of desktop environments**

+ Icons
+ Menus
+ Favorites Bar
+ Desktop Settings

**What is Ubuntu’s default desktop environments?**

Gnome DE is the default desktop in ubuntu.

**What are the official flavors of Ubuntu?**

Ubuntu Flavors are a unique way to experience Ubuntu. They all carry their own default applications and settings. Developed mostly to fit specific groups of people.

+ Edubuntu
  + Crafted specifically for education world. Comes with a large ecosystem of education softwares and educational tools.
+ Kubuntu
  + Productivity based applications like office, email, photography and music.
+ Lubuntu 
  + Mainly on Using the Internet, chatting, and playing 
+ Ubuntu Budgie
  + fast, fully customizable version of Ubuntu
+ Ubuntu Cinnamon
  + Provides a traditionally more modern experience in using Ubuntu
+ Ubuntu Kylin
  + Chinese based version of Ubuntu primarily focused on new users
+ Ubuntu MATE
  + Usable with very old computers since it requires so little specs to run properly
+ Ubuntu Studio
  + Focoused on studio work applications such as, musicians, graphic designers, or streamers
+ Ubuntu Unity 
  + Unity is focused on presenting a slick and elegant way of having a designated workflow
+ Xubuntu
  + usable on older and newer computers Xubuntu prioritizes a smooth desktop experience


### What Is A Shell

**What is Bash?**

A program that provides interactive access to the Linux system.

**How do you access the Linux CLI?**

Runs as a regular program that is tarted whenever a user logs into a terminal

**What is a console terminal?**

A console terminal is a text interface for your machine that uses Command Line Interface

**What is a terminal emulator?**

A program that allows you to access the linux CLI (Command Line Interface)

**Provide 3 examples of Linux commands**

sudo apt install pink-pony 
+ Installs the racing game on Ubuntu using apt package from Debian

clear 
+ clears the terminal

python3
+ Allows the Bash Shell to access and run python code


### Managing Software

**Which command is used for updating ubuntu**

sudo apt update
+ sudo gives you administrator control
+ apt is the Debian package for official Ubuntu updates and software
+ update is the command that tells the computer to update

**Which command is used for installing software. Provide an **example.**

sudo apt install pink-pony 
+ Installs the racing game on Ubuntu using apt package from Debian


**Which command is used for removing software. Provide an example.**

sudo apt remove pink-pony
+ Removes the game pink-pony from your machine since it cannot run the game smoothly and it is trash.

**Which command is used for searching for software. Provide an example.**

apt search "racing game"
+ will give you a list of software that matches the description of what is between the quotes.

**Definition of the following terms:**



Package
+ archives of software, configuration files, and info on dependencies. (The same as a .exe file on windows)
Library
+ Reusable code that can be used by more than one function or program
Repository
+ Large collection of software for downloading
  + Linux has
    + Main - Canonical free and open source (from the distributors)
    + Universe - Community maintained 
    + Restricted - proprietary drivers for devices
    + Multiverse - restricted by copyright or legal issues