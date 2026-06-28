# Active Directory Enterprise Lab

## Project Overview

This project documents the deployment and administration of an enterprise-style Active Directory environment using Windows Server 2022 and Windows 11 in a VMware Workstation Pro homelab.

The lab focuses on centralized identity management, domain authentication, Organizational Units, user accounts, security groups, Group Policy, password policy, account lockout policy, and basic Help Desk administration tasks.

This project is part of my Cybersecurity Homelab Portfolio and demonstrates practical Windows Server and Active Directory administration skills.

## Lab Environment

| Component | Details |
|-----------|---------|
| Hypervisor | VMware Workstation Pro |
| Host Operating System | Windows 11 Pro |
| Server Operating System | Windows Server 2022 |
| Client Operating System | Windows 11 Enterprise |
| Domain Name | BENLAB.LOCAL |
| Domain Controller | DC01 |
| Network | 10.20.20.0/24 |
| DNS Server | DC01 |
| Project Type | Enterprise Active Directory Administration |

## Technologies & Skills Demonstrated

### Technologies

- Windows Server 2022
- Windows 11 Enterprise
- Active Directory Domain Services (AD DS)
- DNS
- DHCP
- Group Policy Management
- PowerShell
- VMware Workstation Pro
- Git
- GitHub
- LibreOffice

### Skills Demonstrated

- Deploying Active Directory Domain Services
- Promoting a Domain Controller
- Configuring DNS
- Creating Organizational Units (OUs)
- Creating and managing domain user accounts
- Creating and managing security groups
- Assigning users to security groups
- Configuring Password Policies
- Configuring Account Lockout Policies
- Applying Group Policy updates
- Resetting user passwords
- Unlocking user accounts
- Verifying domain authentication using PowerShell
- Troubleshooting Active Directory
- Documenting enterprise infrastructure

## Repository Structure

```text
Active-Directory-Enterprise-Lab
│
├── README.md
├── Commands.md
├── ProjectReport.odt
├── ProjectReport.pdf
│
├── DHCP
├── DNS
├── DomainController
├── GroupPolicy
├── Groups
├── Notes
├── Resources
├── Screenshots
└── Users
```
## Documentation

This repository includes complete project documentation and supporting resources.

- 📄 **ProjectReport.pdf** – Complete implementation report with screenshots and explanations.
- 📝 **ProjectReport.odt** – Editable LibreOffice project report.
- 💻 **Commands.md** – PowerShell and administrative commands used throughout the project.
- 📷 **Screenshots/** – Evidence collected during the implementation and testing phases.

## Future Improvements

This Active Directory environment will continue to evolve as additional enterprise services are deployed. Planned improvements include:

- Deploy additional Windows client workstations
- Implement Windows File Server role with advanced NTFS permissions
- Configure roaming profiles and Folder Redirection
- Deploy Microsoft LAPS for local administrator password management
- Integrate Wazuh SIEM for centralized log monitoring
- Perform vulnerability assessments using Nessus
- Expand Group Policy Objects (GPOs) for workstation hardening
- Implement centralized auditing and security monitoring

## Author

**Benvindo Kiazayamoko**

Cybersecurity Student | Homelab Builder | IT Support & Windows Administration

This project is part of my enterprise cybersecurity homelab portfolio, documenting hands-on experience with Windows Server administration, networking, and enterprise security technologies.