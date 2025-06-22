# Linux Fundamentals with Vagrant

This project demonstrates foundational Linux operations using a Vagrant-managed virtual machine. It includes basic tasks such as filesystem navigation, permission management, package installation, and connectivity testing.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Vagrant Setup](#vagrant-setup)  
3. [Exploring Linux File System](#exploring-linux-file-system)  
4. [Managing File Permissions and Ownership](#managing-file-permissions-and-ownership)  
5. [Installing and Configuring a Package](#installing-and-configuring-a-package)  
6. [Testing Remote Connectivity](#testing-remote-connectivity)  
7. [Conclusion](#conclusion)  

---

## Project Overview

This repository contains exercises that showcase Linux fundamentals inside a Vagrant-provisioned Ubuntu virtual machine. The goal is to gain hands-on experience with Linux operations in a controlled development environment.

---

## Vagrant Setup

We begin by initializing and provisioning a Vagrant Ubuntu server.

**Screenshot #1: Vagrant Initialization and SSH Login**  
_Description: The image below shows my screen after `vagrant init` & `vagrant up`, while logging in using `vagrant ssh`._

![Vagrant Init and SSH](https://github.com/user-attachments/assets/f18ac81d-3ce7-4204-9773-58d453ebfc3d)

---

## Exploring Linux File System

We navigate the Linux file system and create a custom folder structure.

**Screenshot #2: Custom Folder Structure**  
_Description: This folder structure `/home/vagrant/projects/devops` was created and populated with list.txt and todo.csv. The pwd can be seen._

![Folder Structure](https://github.com/user-attachments/assets/de4f699a-9397-4d9b-8106-fd70188d19ad)


---

## Managing File Permissions and Ownership

We use `chmod` and `chown` to modify file permissions and ownership.

**Screenshot #3: File Permission and Ownership Changes**  
_Description: The file `list.txt` was set to `700` while todo.csv was set to '744'._

![Permissions and Ownership](https://github.com/user-attachments/assets/b9e9685a-9955-437f-99ee-4a9eace04d03)


## Installing and Configuring a Package

We install a common Linux package (e.g., `nginx`) using `apt`.

**Screenshot #4: Package Installation**  
_Description: `nginx` was installed successfully using 'sudo apt install nginx'`._

![Package Installation](https://github.com/user-attachments/assets/33b475c6-77e1-4c0a-b5e9-fc4cde2e7858)

---

## Testing Remote Connectivity

We test network connectivity using the `ping` command.

**Screenshot #5: Ping Test**  
_Description: Pinging `google.com` confirms external network access. The output shows the response time._

![Ping Test](https://github.com/user-attachments/assets/8cbdc131-418b-4cc2-8bda-d9a8dbb352bc)

---

## Conclusion

This exercise reinforced basic Linux operations within a virtual environment. It covered system navigation, permissions, package management, and connectivity—core skills every DevOps and Linux enthusiast should have.

---

## Repository Structure


![image](https://github.com/user-attachments/assets/d1e1bf3a-84ce-4e04-91e9-2001b30f6ce2)


![image](https://github.com/user-attachments/assets/759c5476-7c99-4e72-bc61-45ea34d0d63d)




![image](https://github.com/user-attachments/assets/97e2c47b-2043-4da6-b30f-67e96e1c2c2f)







![image](https://github.com/user-attachments/assets/72301e88-bc17-4f4b-bc80-6f3a24aabfbe)






