![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
# Azure Network Traffic Analysis & Security Lab

## Introduction
This lab demonstrates the deployment of cloud-based virtual machines (VMs) in Azure and the analysis of network traffic using Wireshark. By configuring a virtual network and implementing Network Security Group (NSG) rules, I simulated real-world scenarios to observe and secure various protocols, including ICMP, SSH, DNS, DHCP, and RDP.

---

## Technical Skills & Tools
* **Cloud Platform:** Microsoft Azure
* **Operating Systems:** Windows 10, Linux (Ubuntu 20.04)
* **Network Security:** Network Security Groups (Firewalls), Inbound/Outbound Security Rules
* **Traffic Analysis:** Wireshark (Packet Capture & Protocol Inspection)
* **Connectivity:** Remote Desktop Protocol (RDP), SSH, ICMP (Ping)
* **Networking Protocols:** DNS, DHCP, TCP, UDP

---

## Part 1: Environment Setup & Infrastructure Provisioning
The objective of this phase was to engineer a unified cloud environment where multiple virtual machines could communicate securely within a shared network segment.

### 1. Resource Group & Virtual Network Deployment
* **Resource Management:** Created a dedicated **Resource Group** to house all laboratory assets, ensuring streamlined management and an easy cleanup process to manage Azure consumption costs.
* **Network Architecture:** Deployed a **Virtual Network (VNet)** and a corresponding **Subnet**. This private network serves as the backbone for all internal communication between the Windows workstation and the Linux target.

### 2. Virtual Machine Provisioning
* **Windows 10 VM (Analyst Workstation):** Provisioned as the primary interface for the lab. This VM was configured to host Wireshark for deep packet inspection and network analysis.
* **Ubuntu Linux VM (Target Node):** Provisioned as the network target. To ensure connectivity, this VM was assigned to the **same VNet and Subnet** as the Windows instance.
* **Network Interface (NIC) Configuration:** Assigned private IP addresses to both instances within the virtual subnet, allowing for direct communication without exposing all services to the public internet.

<p align="center">
  <img src="assets/vmCreation.png" width="800" alt="Azure VM Creation Overview" />
  <br>
  <i>Figure 1: Successful provisioning of Windows and Linux nodes within the unified Azure Resource Group.</i>
</p>

---

## Part 2: Observing Network Traffic & ICMP
*(Next section coming soon as we continue the lab documentation...)*
