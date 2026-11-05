# Hi, I'm Nishan Rajmulik 👋

**IT Support & Infrastructure | Azure · AWS · M365 · Networking | Security+ | Master of Cyber Security (USC) | Homelab: DevOps, Cloud & Security Projects**

I'm a IT professional. My hands-on experience is in IT support and a cyber analyst internship. Alongside that, I run a Proxmox homelab set up like a small company network, where I build and test hybrid Active Directory and Entra ID, Microsoft 365 and Intune-managed endpoints, firewall VLAN networks, Azure networking and security monitoring. I'm now extending it with DevOps tooling: Terraform, Ansible and containers.

All projects on this profile are self-directed lab work, documented step by step.

---

## What I work on

- **IT support & endpoints** - Windows 11, Microsoft 365 administration, Intune and Autopilot, user and access management, troubleshooting
- **Systems & identity** - Active Directory, Entra ID hybrid identity (Entra Connect), Windows Server 2022/2025, Linux
- **Networking** - VLANs, trunking, inter-VLAN routing, OSPF, HSRP, EtherChannel, DHCP, ACLs, subnetting · Wireshark, GNS3, EVE-NG
- **Firewalls** - pfSense, FortiGate, Palo Alto · policies, NAT, IPsec/SSL VPN, zone segmentation
- **Cloud** - Azure VNets, peering, NSGs, Bastion, VPN gateway, hybrid connectivity · AWS
- **Security** - Microsoft Sentinel, Defender XDR, Splunk, KQL · MITRE ATT&CK, NIST CSF, ACSC Essential Eight
- **DevOps & automation (learning)** - PowerShell, Bash, Python, Terraform, Ansible, Docker, Kubernetes, Jenkins

---

## Homelab

A Proxmox host running a small company-style environment:

- **pfSense** firewall with VLAN segmentation (LAN, management, DMZ)
- **Windows Server** domain controller and member server, synced to **Entra ID** with Entra Connect
- **Windows 11** endpoints enrolled through **Autopilot** into a **Microsoft 365** tenant

---

## Featured Projects

### Infrastructure & Cloud

#### [Hybrid Identity: Active Directory + Entra ID](https://github.com/nishanrajmulik1/microsoft-hybrid-ad)
Built an on-prem Windows Server domain (AD DS and DNS) and synced users to a Microsoft Entra ID tenant with Entra Connect.

**Stack:** Windows Server · AD DS · DNS · Entra ID · Entra Connect

#### [Multi-Region Azure VNet Peering](https://github.com/nishanrajmulik1/azure-vnet-peering-multiregion)
Connected VNets in East US and North Europe with VNet peering, so VMs in different regions talk over private IP addresses.

**Stack:** Azure VNets · VNet peering · Azure VMs

#### [CCNA Enterprise Network Lab](https://github.com/nishanrajmulik1/ccna-lab)
Redundant three-tier network with departmental VLANs, inter-VLAN routing, VTP, EtherChannel, HSRP gateway redundancy, OSPF, DHCP and a basic BGP link to a simulated ISP.

**Stack:** Cisco IOS · VLANs · OSPF · HSRP · BGP

### Security & Monitoring

#### [Hybrid AD + Microsoft Defender XDR + Sentinel](https://github.com/nishanrajmulik1/Microsoft-Hybrid-AD-XDR-Sentinel-Project)
Connected on-prem Active Directory to Microsoft Entra ID with Azure AD Connect. Simulated credential dumping (Mimikatz) and brute-force attacks, then confirmed the detections in Defender XDR and Sentinel using custom analytics rules and hunting queries.

**Stack:** AD DS · Entra ID · Defender for Endpoint · Microsoft Sentinel · KQL

#### [Cloud SOC Honeynet](https://github.com/nishanrajmulik1/Cloud-SOC-Honeynet)
Deployed a honeynet in Azure and sent its logs to Microsoft Sentinel through Log Analytics. Analysed real brute-force, SSH scanning, malware download and RDP attempts.

**Stack:** Azure VMs · NSGs · Bastion · Log Analytics · Microsoft Sentinel · Defender XDR

#### [Splunk + n8n + Slack Alert Automation](https://github.com/nishanrajmulik1/splunk-siem-n8n-slack-automation-project)
Attacks launched from Kali against a Windows Server domain behind pfSense. Logs collected in Splunk, triage dashboards built, and alerts enriched and sent to Slack through n8n.

**Stack:** Splunk · Windows Server 2022 · pfSense · Kali Linux · n8n · Slack

### More labs

- **[Windows Login Detection](https://github.com/nishanrajmulik1/Windows-Login-Detection)** - Simulating and detecting successful (4624) and failed (4625) Windows logins, with PowerShell checks for brute-force attempts
- **[PowerShell Log Analysis](https://github.com/nishanrajmulik1/PowerShell-Log-Analysis)** - PowerShell scripts that find suspicious PowerShell activity in Windows event logs, mapped to MITRE ATT&CK
- **[Splunk SIEM Setup](https://github.com/nishanrajmulik1/Splunk-SIEM-Setup)** - Splunk on Ubuntu collecting Windows event data, with detections mapped to MITRE ATT&CK

---

## Tech Stack

![Azure](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=flat&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat&logo=microsoftoffice&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat&logo=proxmox&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat&logo=pfsense&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=flat&logo=microsoft&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)

---

## Certifications

| Certification | Issuer | Verify |
|---|---|---|
| **CompTIA Security+** | CompTIA | [Credly ↗](https://www.credly.com/badges/573933fa-0270-46c7-ad75-693ed1a6fd2a) |
| **Microsoft SC-900** | Microsoft | [Credly ↗](https://www.credly.com/badges/8be875c0-9218-4cc7-9388-b15d4a4a9567) |
| **Juniper JNCIA-Junos** | Juniper Networks | [Credly ↗](https://www.credly.com/badges/85df1188-b41e-4b15-b295-8ba6c991057d) |

**Currently studying:** AZ-104 · RHCSA

---

## Education

- **Master of Cyber Security & Forensics** - University of the Sunshine Coast
- **Bachelor of Information Technology** - Victoria University

---

## Connect

[LinkedIn](https://www.linkedin.com/in/nrajmulik/)

