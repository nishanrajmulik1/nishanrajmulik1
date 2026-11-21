# Hi, I'm Nishan Rajmulik 👋

**Cybersecurity Analyst | SOC Operations & Threat Detection | IT Infrastructure | Security+ | Master of Cyber Security**

I'm a cybersecurity and IT infrastructure professional with hands-on experience from a cyber analyst internship and IT support roles. Because effective threat detection relies on understanding the environment underneath, I run a Proxmox homelab built like a small enterprise network—combining hybrid Active Directory, Entra ID, pfSense VLAN segmentation, Microsoft 365/Intune endpoints, and Azure networking with SIEM/XDR telemetry and attack simulation. I'm currently extending the lab with automation and DevOps tooling including Terraform, Ansible, and containers.

All projects on this profile are self-directed lab builds, documented step by step.

---

## Core Focus Areas

- **SOC operations & threat detection** - Microsoft Sentinel, Defender XDR, Splunk, KQL, log analysis, SOAR/alert automation (n8n) · MITRE ATT&CK, NIST CSF, ACSC Essential Eight
- **Firewalls & network security** - pfSense, FortiGate, Palo Alto · policies, NAT, IPsec/SSL VPN, zone segmentation
- **Cloud & hybrid infrastructure** - Azure VNets, peering, NSGs, Bastion, VPN Gateway, Log Analytics · AWS
- **Identity & systems** - Active Directory, Entra ID hybrid identity (Entra Connect), Windows Server 2022/2025, Linux
- **Networking** - VLANs, trunking, inter-VLAN routing, OSPF, HSRP, EtherChannel, DHCP, ACLs, subnetting · Wireshark, GNS3, EVE-NG
- **Endpoints & IT support** - Windows 11, Microsoft 365 administration, Intune, Autopilot, access management, troubleshooting
- **Automation & DevOps (learning)** - PowerShell, Bash, Python, Terraform, Ansible, Docker, Kubernetes, Jenkins

---

## Homelab

A Proxmox environment modeled after a small enterprise network for building, attacking, and defending real infrastructure:

- **Detection & monitoring** - Log ingestion, alert triage, and custom detection rules in **Splunk**, **Microsoft Sentinel**, and **Defender XDR**, validated with Kali Linux attack simulations
- **Network & perimeter** - **pfSense** firewall with VLAN segmentation (LAN, management, DMZ)
- **Identity & servers** - **Windows Server** domain controller and member server synced to **Entra ID** via Entra Connect
- **Endpoints** - **Windows 11** machines enrolled through **Autopilot** into a **Microsoft 365** tenant

---

## Featured Projects

### SOC Operations & Threat Detection

#### [Hybrid AD + Microsoft Defender XDR + Sentinel](https://github.com/nishanrajmulik1/Microsoft-Hybrid-AD-XDR-Sentinel-Project)
Connected on-prem Active Directory to Microsoft Entra ID with Entra Connect. Simulated credential dumping (Mimikatz) and brute-force attacks, then validated detections in Defender XDR and Sentinel using custom analytics rules and KQL hunting queries.

**Stack:** Microsoft Sentinel · Defender for Endpoint · KQL · AD DS · Entra ID

#### [Cloud SOC Honeynet](https://github.com/nishanrajmulik1/Cloud-SOC-Honeynet)
Deployed an internet-facing honeynet in Azure and streamed logs to Microsoft Sentinel via Log Analytics. Analyzed live brute-force, SSH scanning, RDP, and malware download attempts.

**Stack:** Microsoft Sentinel · Defender XDR · Log Analytics · Azure VMs · NSGs · Bastion

#### [Splunk + n8n + Slack Alert Automation](https://github.com/nishanrajmulik1/splunk-siem-n8n-slack-automation-project)
Simulated attacks from Kali Linux against a Windows Server domain behind pfSense. Ingested logs into Splunk, built triage dashboards, and automated alert enrichment and delivery to Slack via n8n.

**Stack:** Splunk · n8n · Slack · Windows Server 2022 · pfSense · Kali Linux

### Detection & SIEM Labs

- **[Windows Login Detection](https://github.com/nishanrajmulik1/Windows-Login-Detection)** - Simulating and detecting successful (4624) and failed (4625) Windows logins, with PowerShell checks for brute-force patterns
- **[PowerShell Log Analysis](https://github.com/nishanrajmulik1/PowerShell-Log-Analysis)** - PowerShell scripts to hunt suspicious script execution in Windows event logs, mapped to MITRE ATT&CK
- **[Splunk SIEM Setup](https://github.com/nishanrajmulik1/Splunk-SIEM-Setup)** - Splunk deployment on Ubuntu ingesting Windows event logs with detections mapped to MITRE ATT&CK

### IT Infrastructure & Cloud

#### [Hybrid Identity: Active Directory + Entra ID](https://github.com/nishanrajmulik1/microsoft-hybrid-ad)
Built an on-prem Windows Server domain (AD DS and DNS) and synced identities to a Microsoft Entra ID tenant using Entra Connect.

**Stack:** Windows Server · AD DS · DNS · Entra ID · Entra Connect

#### [Multi-Region Azure VNet Peering](https://github.com/nishanrajmulik1/azure-vnet-peering-multiregion)
Connected Azure VNets across East US and North Europe via global VNet peering for private cross-region VM communication.

**Stack:** Azure VNets · VNet Peering · Azure VMs

#### [CCNA Enterprise Network Lab](https://github.com/nishanrajmulik1/ccna-lab)
Redundant three-tier enterprise network with departmental VLANs, inter-VLAN routing, VTP, EtherChannel, HSRP gateway redundancy, OSPF, DHCP, and BGP peering to a simulated ISP.

**Stack:** Cisco IOS · VLANs · OSPF · HSRP · BGP

---

## Tech Stack

![Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=flat&logo=microsoft&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat&logo=pfsense&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=flat&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat&logo=microsoftoffice&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat&logo=proxmox&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

## Certifications

| Certification | Issuer | Verify |
|---|---|---|
| **CompTIA Security+** | CompTIA | [Credly ↗](https://www.credly.com/badges/573933fa-0270-46c7-ad75-693ed1a6fd2a) |
| **Microsoft SC-900** | Microsoft | [Credly ↗](https://www.credly.com/badges/8be875c0-9218-4cc7-9388-b15d4a4a9567) |
| **Juniper JNCIA-Junos** | Juniper Networks | [Credly ↗](https://www.credly.com/badges/85df1188-b41e-4b15-b295-8ba6c991057d) |

**Currently studying:** SC-200 · AZ-104 · RHCSA

---

## Education

- **Master of Cyber Security & Forensics** - University of the Sunshine Coast
- **Bachelor of Information Technology** - Victoria University

---

## Connect

[LinkedIn](https://www.linkedin.com/in/nrajmulik/)
