# IT Infrastructure Home Lab Portfolio
Charalampos Ignatiadis | IT Infrastructure & Operations Candidate

This repository serves as public documentation for my personal IT infrastructure projects, demonstrating hands-on proficiency in Linux system administration, virtualization, networking, and resilient data storage.

This work supports my career transition goal into a structured IT Internship (Praktikum) role.

## 1. Resilient Storage: ZFS High-Availability File Server
This project focuses on building and managing a robust file server environment, ensuring data integrity and availability.

Platform: Custom-built PC hardware running Proxmox (Debian Linux) as the core operating system and supervisor.

Key Technology: Implementation and ongoing management of a ZFS (Zettabyte File System) pool.

Functionality: The ZFS pool is configured for data redundancy (RAID-Z1) to protect against hardware failure.

Access Layer: Configured Samba to enable secure file sharing across the network for Windows, Linux, and Mac clients.

Skills Demonstrated: Data Storage Management, Resilience Planning, Linux Service Configuration, File System Management.

## 2. Virtualization and Network Isolation Environment
To ensure safe testing and system maintenance, a dedicated virtualization platform was implemented.

Objective: Create isolated, segmented environments for testing network configurations and running containerized services without impacting the production network.

Platform: Running multiple Virtual Machines (VMs) and containers (vaultwarden, pihole, jellyfin, openwebui-ollama, pfsense, home assistant) for simulating different server roles (e.g., testing new configurations before deployment).

Application Testing: Utilized the VMs to host various web applications in a controlled environment.

Skills Demonstrated: Virtualization Management, Network Segmentation, System Testing, Resource Allocation, Environmental Isolation.

## 3. Network & Perimeter Security Configuration
This project involved manually configuring networking equipment and implementing security policies to manage internal and external traffic flow.

Logical Structure: Designed and documented the subnet layout and IP addressing scheme of the home network.

Firewall Rules: Implemented specific and restrictive firewall rules on the virtual router to segment traffic, block unauthorized external access, and manage access control lists (ACLs) for internal devices.

Configuration: Managed and updated firmware and configurations for the primary network router and Wi-Fi access points.

Skills Demonstrated: Network Administration, Firewall Policy Management, Network Security Principles, Router Configuration.

## 4. Home Assistant (IoT) Integration & Automation
A demonstration of integrating multiple systems and devices through a central platform, using API and scripting knowledge.

Platform: Home Assistant running on a dedicated machine for centralizing all smart devices.

Integration: Wrote configurations and scripts to integrate various devices, including cameras, audio equipment, and the home theater system.

Skills Demonstrated: Systems Integration, API Interaction, YAML Configuration (or other scripting used), Troubleshooting Interoperability Issues.
