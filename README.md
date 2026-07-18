# Enterprise Windows Active Directory Infrastructure Lab

## Overview

This project demonstrates the deployment of an enterprise Windows infrastructure using Windows Server 2022 in a virtualized environment. The lab focuses on implementing core Microsoft enterprise services, including Active Directory Domain Services (AD DS), DNS, DHCP, and domain-based authentication.

The environment simulates a basic enterprise network where a Windows Server 2022 Domain Controller centrally manages users, authentication, name resolution, and IP address allocation for a Windows 11 client.

---

## Objectives

- Deploy Windows Server 2022 as a Domain Controller.
- Install and configure Active Directory Domain Services (AD DS).
- Configure DNS Server.
- Configure DHCP Server.
- Join a Windows 11 client to the Active Directory domain.
- Validate domain communication and network services.

---

## Technology Stack

### Operating Systems
- Windows Server 2022
- Windows 11

### Virtualization
- Oracle VirtualBox

### Windows Server Roles
- Active Directory Domain Services (AD DS)
- DNS Server
- DHCP Server

### Networking
- IPv4
- TCP/IP
- DHCP
- DNS

### Administration Tools
- Server Manager
- Active Directory Users and Computers
- DNS Manager
- DHCP Manager
- Group Policy Management

---

## Infrastructure Components

### Domain Controller (DC01)

The Windows Server 2022 machine functions as the Domain Controller responsible for:

- Active Directory Domain Services
- DNS Server
- DHCP Server
- Domain Authentication
- Centralized User Management

### Client Workstation (CLIENT01)

The Windows 11 client is configured to:

- Join the Active Directory domain
- Receive IP configuration from DHCP
- Resolve domain names through DNS
- Authenticate using Active Directory credentials

---

## Project Workflow

1. Install Oracle VirtualBox.
2. Create the Windows Server 2022 virtual machine.
3. Install Active Directory Domain Services.
4. Promote the server to a Domain Controller.
5. Configure the DNS Server.
6. Configure the DHCP Server.
7. Create a DHCP Scope.
8. Deploy the Windows 11 client.
9. Join the client to the Active Directory domain.
10. Validate infrastructure functionality.

---

## Validation

The infrastructure was validated using the following:

- Active Directory Users and Computers
- DNS Manager
- DHCP Address Leases
- Domain Join Verification
- IP Configuration Verification
- Network Connectivity Tests
- Group Policy Management

---

## Skills Demonstrated

- Windows Server Administration
- Active Directory Administration
- DNS Administration
- DHCP Administration
- Domain Management
- Enterprise Networking
- Windows Client Administration
- Infrastructure Deployment
- Network Troubleshooting

---

## Learning Outcomes

This project provided practical experience in deploying and managing a Windows enterprise infrastructure. It strengthened knowledge of domain services, centralized authentication, DNS, DHCP, Windows administration, and enterprise networking concepts.

---

## Future Enhancements

Future versions of this lab will include:

- OPNsense Firewall
- Wazuh SIEM
- Splunk
- Sysmon
- Windows Event Forwarding (WEF)
- Centralized Logging
- Security Monitoring
- Threat Detection
- Security Hardening

---

## Author

Ambati Srinesh Reddy

B.Tech Computer Science and Engineering (Cybersecurity)

GD Goenka University

---

## License

This project is licensed under the MIT License.
