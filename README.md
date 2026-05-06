
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

## Part 1: Environment Setup & Provisioning
The objective of this phase was to establish a unified cloud environment where multiple virtual machines could communicate securely within the same network segment.

### 1. Resource Group Creation
I created a dedicated **Resource Group** to organize all laboratory assets, ensuring easy management and cost-effective cleanup.

### 2. Virtual Network (VNet) Configuration
* Deployed a **Virtual Network (VNet)** and a corresponding **Subnet**.
* This network serves as the backbone for internal communication between the Windows and Linux instances.

### 3. Virtual Machine Deployment
* **Windows 10 VM:** Provisioned as the primary "Analyst Workstation" where Wireshark was installed.
* **Ubuntu Linux VM:** Provisioned as the "Target Node" to facilitate traffic observation and firewall testing.
* **Network Alignment:** Both VMs were assigned to the same VNet and Subnet to ensure direct internal connectivity (Private IP communication).



---

## Part 2: Observing Network Traffic & ICMP
*(Next section coming soon as we continue the lab documentation...)*
