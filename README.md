<h1 align="center">🖥️ Cybersecurity Lab Setup – Week 1 </h1>

# Overview
This repository documents the setup of a Kali Linux virtual machine using Oracle VirtualBox, forming the foundation environment for hands-on cybersecurity practice. 
# Tools Used
- Hypervisor: Oracle VirtualBox
- Guest OS: Kali Linux
# Setup Summary
1.	Installed VirtualBox on the host machine
2.	Downloaded the official Kali Linux VM image
3.	Set network adapter to NAT for internet access
   <img width="1518" height="806" alt="image" src="https://github.com/user-attachments/assets/66fec8fa-8e94-46fc-a5a2-873d7791641e" />

4.	Imported the VM into VirtualBox and configured RAM/CPU/storage
5.	Booted Kali Linux and verified successful installation
6.	Verified and adjusted Kali's network settings to confirm proper connectivity
<img width="1518" height="806" alt="image" src="https://github.com/user-attachments/assets/96f80f6a-b0d1-402d-9f09-dbe940707cd6" />

8.	Took a baseline snapshot of the fresh VM for easy rollback before future labs

# What I Learned

Setting up this lab reinforced several core networking and VM concepts:

1. **NAT vs. NAT Network –** Regular NAT only lets a VM reach the outside world, while a NAT Network lets multiple VMs talk to each other and get external access — key for building a multi-VM lab later.
2. **Virtual Networking Basics –** How VirtualBox's virtual adapters determine whether and how VMs can see each other on the network.
3. **Static IP Setup –** How to manually configure and verify IPv4 address, subnet mask, gateway, and DNS on Kali.
4. **Snapshots as Safety Nets –** Always snapshot a clean VM state before testing anything risky, so you can roll back instantly.
5. **Documentation Matters –** Logging commands, configs, screenshots, and issues along the way is part of doing this professionally, not an afterthought.

# Outcome
A fully functional, isolated Kali Linux environment — with a clean rollback point — ready for future labs on scanning, footprinting, and penetration testing.
