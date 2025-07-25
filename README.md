# Linux VM Cluster

## 📌 Objective
The goal of this project is to simulate a distributed computing environment by creating and configuring a virtualized cluster of three Ubuntu Server VMs using VirtualBox. The main objectives include:
- Creating and configuring three Ubuntu Server virtual machines.
- Establishing a dual-network setup using NAT (for internet access) and an internal network (for inter-node communication).
- Assigning static IP addresses and editing /etc/hosts for proper hostname resolution.
- Setting up passwordless SSH from the control node (ctrl-node) to the worker nodes (work-node-1, work-node-2).
- Verifying full connectivity across all nodes in preparation for hosting distributed applications.




## 💡 Skills Learned
- Virtual machine provisioning and configuration
- Network design and subnet configuration
- Static IP assignment and hostname resolution using Netplan
- Secure shell (SSH) key generation and distribution for passwordless access
- Troubleshooting and verifying connectivity across nodes
- Building foundational infrastructure for distributed systems


## 🔧 Tools Used
- Oracle VirtualBox – to create and manage virtual machines
- Ubuntu Server – for lightweight, terminal-based VM operating systems
- Netplan – for configuring network interfaces and static IP addresses
- OpenSSH – for remote login and passwordless SSH setup
- Command-line tools – such as ping, ip a, nano, and hostnamectl for system configuration and verification


## 📂 Lab Documentation

- <a href="https://github.com/nadiansh/Linux-VM-Cluster/blob/main/Linux%20VM%20Cluster.pdf">Linux VM Cluster Lab Documentation</a>


## Network Topology

![image alt](https://github.com/nadiansh/Linux-VM-Cluster/blob/main/NT.jpeg?raw=true)
