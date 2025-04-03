# 🚀 Ansible Hands-On Guide

## 📌 Overview
This hands-on guide covers various Ansible automation tasks, including:
- 📂 Using Ansible **roles** for managing **Apache** and **Nginx**
- 🌍 Implementing **dynamic inventory** for **AWS EC2**
- ☁️ Creating **EC2 instances**
- 🔧 Managing services (**starting**, **stopping**, and **reversing** Apache & Nginx)

## 🛠 Prerequisites
- ✅ **Ansible** installed on the control node
- ✅ **AWS credentials** configured for EC2 access
- ✅ **SSH key-based authentication** set up between the control node and target hosts
- ✅ **Python** and required dependencies installed on managed nodes

## 📦 Ansible Roles
### 🌐 Apache Role
- 📥 Installs **Apache**
- ▶️ Starts the **Apache service**
- ⏹ Stops the **Apache service**
- 🔄 Reverses changes if needed

### 🚦 Nginx Role
- 📥 Installs **Nginx**
- ▶️ Starts the **Nginx service**
- ⏹ Stops the **Nginx service**
- 🔄 Reverses changes if needed

## 🏗 Dynamic Inventory for EC2
- 🔍 Uses **AWS EC2 dynamic inventory plugin** to fetch instances
- 📊 Retrieves **instance details dynamically**
- 📡 Enables running **playbooks on live EC2 instances** without manual updates

## ☁️ EC2 Instance Management
- 🏗 **Creating EC2 instances** using Ansible playbooks
- 🔒 Assigning **security groups** and **key pairs**
- ⚙️ Configuring instance details like **AMI, instance type, and tags**

## 🔄 Service Management
- ▶️ **Start** and ⏹ **stop** Apache and Nginx services
- 🔄 **Reverse service states** (e.g., restart Nginx after stopping)

## 📜 Execution Workflow
1. 🔍 **Configure dynamic inventory** for EC2
2. 📦 **Apply Ansible roles** for Apache/Nginx setup
3. 🏗 **Manage EC2 instances** with Ansible
4. 🔄 **Control services** as per requirement

## 🎯 Conclusion
This hands-on project demonstrates **Ansible automation** for web server management and EC2 operations, enhancing **infrastructure automation skills**. 🚀

