# Enterprise Home Lab – Active Directory & Network Security

## Overview
This project documents a virtual enterprise-style home lab designed to build hands-on experience with Windows Active Directory, domain administration, and basic network security concepts.

The environment simulates a small Windows domain to better understand identity management, authentication, access control, and network traffic behavior in an enterprise setting.

## Lab Environment
- Windows Server 2022 (Domain Controller)
- Windows 11 (Domain-joined client)
- VMware Workstation
- Isolated internal virtual network

## Repository Structure

- **architecture/**  
  High-level overview of the lab design and isolated network layout.

- **setup/**  
  Domain controller configuration and Windows 11 domain join documentation.

- **security/**  
  Role-based access control and least-privilege implementation notes.

- **monitoring/**  
  Network traffic observations related to domain authentication using Wireshark.


## Key Objectives
- Deploy and configure a Windows Server Domain Controller
- Implement Active Directory users, groups, and organizational units
- Apply least-privilege access using group-based permissions
- Join Windows 11 clients to the domain
- Observe authentication and network traffic using Wireshark

## What I Learned
- How Active Directory manages identity and authentication in a domain environment
- Practical application of least-privilege access controls
- Fundamentals of enterprise Windows infrastructure
- How authentication traffic appears at the network level

## Disclaimer
This lab was built for educational purposes in an isolated environment.
