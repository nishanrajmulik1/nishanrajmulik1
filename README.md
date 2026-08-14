## 👋 Hi, I'm Nishan Rajmulik 

Security Analyst | SOC & Detection Engineering · Cloud & Network Security | Microsoft Sentinel · Defender XDR · Azure · pfSense | Security+ · SC-900 · JNCIA-Junos

I build and secure hybrid AD + Azure environments and run the full detect → triage → respond chain in a hands-on SOC home lab on Proxmox, writing KQL/SPL detections mapped to MITRE ATT&CK, investigating incidents through to root cause, and documenting NIST-aligned response playbooks. This is backed by network and firewall engineering, as well as Azure cloud networking.

Certified: CompTIA Security+ · Microsoft SC-900 · Juniper JNCIA-Junos

---

My focus areas:

- **Threat detection & hunting** - writing analytic rules in KQL and SPL, mapped to MITRE ATT&CK
- **Blue team operations** - Microsoft Sentinel, Splunk, Defender XDR, Wazuh
- **Incident response** - investigation, root cause analysis, NIST-aligned playbooks
- **SOC automation** - n8n + Slack workflows for alert enrichment and notification
- **Cloud security** - Azure hardening, hybrid identity, secure networking
- **Systems & identity** - Active Directory, Entra ID hybrid identity, Windows Server 2022/2025
- **Firewalls** - FortiGate, Palo Alto, pfSense security policies, NAT, IPsec/SSL VPN, zone segmentation
- **Routing & switching** - VLANs, inter-VLAN routing, trunking, OSPF, ACLs

---

## Featured Projects

### [Hybrid AD + Microsoft XDR + Sentinel Detection Lab](https://github.com/nishanrajmulik1/Microsoft-Hybrid-AD-XDR-Sentinel-Project)
Integrated on-prem Active Directory with Microsoft Entra ID via Azure AD Connect. Simulated **credential dumping (Mimikatz)** and **brute-force attacks**, then validated detections across Microsoft Defender XDR and Sentinel using custom Analytics Rules and Hunting Queries.

**Stack:** AD DS · Entra ID · Microsoft Defender for Endpoint · Microsoft Sentinel · KQL
**Skills:** Identity attack detection · KQL rule authoring · MITRE ATT&CK mapping

---

### [Cloud SOC Honeynet](https://github.com/nishanrajmulik1/Cloud-SOC-Honeynet)
Designed and deployed a honeynet in Azure to capture real attacker behaviour. Ingested telemetry into Microsoft Sentinel via Log Analytics; observed and analysed **brute-force, SSH scanning, malware downloads, and RDP infiltration** attempts.

**Stack:** Azure VMs · Microsoft Sentinel · Log Analytics · Defender XDR · NSGs · Bastion
**Skills:** Cloud security monitoring · Attack analysis · Detection tuning

---

### [Splunk + n8n + Slack SOAR Automation Lab](https://github.com/nishanrajmulik1/splunk-siem-n8n-slack-automation-project)
End-to-end SIEM + SOAR pipeline simulating Tier 1 SOC workflows. Attacks launched from Kali, logs ingested into Splunk, dashboards built for triage, and alerts auto-enriched and routed to Slack via n8n.

**Stack:** Splunk · Windows Server 2022 DC · pfSense · Kali Linux · n8n · Slack
**Skills:** SPL queries · SOAR workflows · Multi-source log correlation

---

### [Windows Login Detection Rules](https://github.com/nishanrajmulik1/Windows-Login-Detection)
Custom detection rules for **failed login patterns, unusual authentication behaviour, and lateral movement indicators** built on Windows Event Logs.

**Skills:** Behavioural detection logic · Event log analysis · False-positive tuning

---

### [PowerShell Log Analysis & Script Monitoring](https://github.com/nishanrajmulik1/PowerShell-Log-Analysis)
PowerShell scripts to collect, parse, and analyse Windows event logs for **suspicious execution, encoded commands, and admin privilege abuse**.

**Skills:** PowerShell scripting · Log parsing · Living-off-the-land detection

---

### [Splunk SIEM Setup & Dashboarding](https://github.com/nishanrajmulik1/Splunk-SIEM-Setup)
Splunk environment ingesting Sysmon and Winlogbeat data, with dashboards visualising **brute-force activity, malware execution, and suspicious PowerShell**.

**Skills:** SIEM deployment · SPL · Dashboard design

---

## Networking & Infrastructure Foundations

- **[Microsoft Azure Labs](https://github.com/nishanrajmulik1/microsoft-hybrid-ad)** - Hybrid AD environments, secure networking
- **[Azure JumpServer & VNet Peering](https://github.com/nishanrajmulik1/azure-vnet-peering-multiregion)** - Secure access patterns, network isolation
- **[CCNA Labs](https://github.com/nishanrajmulik1/ccna-lab)** - Routing, switching, VLANs, ACLs

---

## Tech Stack

![Azure](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=flat&logo=microsoftazure&logoColor=white)
![Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-0078D4?style=flat&logo=microsoft&logoColor=white)
![Defender](https://img.shields.io/badge/Defender_XDR-0067B8?style=flat&logo=microsoftdefender&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-0054A6?style=flat&logo=wazuh&logoColor=white)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat&logo=kalilinux&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat&logo=pfsense&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)

---

##  Skills

**SIEM & Detection:** Microsoft Sentinel · Splunk · Wazuh · KQL · SPL · threat hunting · alert triage
**Incident Response:** investigation · root cause analysis · NIST-aligned playbooks · MITRE ATT&CK
**Endpoint & Identity:** Microsoft Defender XDR · Sysmon · Active Directory · Microsoft Entra ID · IAM · MFA · RBAC
**Automation & Scripting:** PowerShell · Ansible · Bash · n8n (SOAR)
**SIEM & Detection:** Microsoft Sentinel · Splunk · Wazuh · KQL · SPL
**Cloud networking:** Azure VNets · peering · NSGs · VPN gateway · hybrid connectivity
**Firewalls:** FortiGate · Palo Alto · pfSense · policies · NAT · IPsec/SSL VPN · zone segmentation
**Routing & switching:** VLANs · inter-VLAN routing · trunking · OSPF · ACLs · subnetting
**Systems:** Active Directory · Entra ID · Azure AD Connect · Windows Server 2022/2025 · Proxmox · Linux
**Frameworks:** MITRE ATT&CK · NIST CSF · ACSC Essential Eight
**Automation & Scripting:** PowerShell · Bash · n8n (SOAR)
**Tools:** Wireshark · GNS3 · EVE-NG · Proxmox · PowerShell · Bash

---

##  Certifications

| Certification | Issuer | Verify |
|---|---|---|
| **CompTIA Security+** | CompTIA | [Credly ↗](https://www.credly.com/badges/573933fa-0270-46c7-ad75-693ed1a6fd2a) |
| **Microsoft SC-900** | Microsoft | [Credly ↗](https://www.credly.com/badges/8be875c0-9218-4cc7-9388-b15d4a4a9567) |
| **Juniper JNCIA-Junos** | Juniper Networks | [Credly ↗](https://www.credly.com/badges/85df1188-b41e-4b15-b295-8ba6c991057d) |

---

##  Connect With Me
 
[LinkedIn](https://www.linkedin.com/in/nrajmulik/)

*Always happy to chat about blue team detection, SOC automation, cloud security, systems and network & firewall engineering.*
