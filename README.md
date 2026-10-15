<div align="center">

# Cybersecurity Portfolio

### Security Operations | Network Security | Incident Investigation

**Microsoft Sentinel · KQL · Wireshark · Nmap · Windows Security**

Hands-on cybersecurity projects focused on security monitoring, network traffic analysis, threat detection, and defensive investigations.

<p>
  <a href="https://github.com/juancarranza-cyber">
    <img src="https://img.shields.io/badge/GitHub%20Profile-334155?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" />
  </a>
  <a href="https://www.linkedin.com/in/juanjosecarranzamarin">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile" />
  </a>
  <a href="mailto:juanjosecm2005@gmail.com">
    <img src="https://img.shields.io/badge/Email-334155?style=for-the-badge&logo=gmail&logoColor=white" alt="Contact by email" />
  </a>
</p>

</div>

---

## Portfolio Overview

This portfolio presents practical cybersecurity work completed in controlled lab environments. Each project documents the technical approach, tools used, and investigation findings, with a link to its dedicated repository for supporting evidence.

| Project | Focus | Primary Tools |
| --- | --- | --- |
| **01. Microsoft Sentinel SOC Investigation Lab** | Security monitoring, SIEM detections, and incident investigation | Microsoft Sentinel, Azure, KQL, Sysmon |
| **02. Nmap Network Scan Analysis** | Network reconnaissance and TCP traffic analysis | Nmap, Wireshark, Kali Linux |
| **03. DNS Traffic Investigation** | DNS monitoring and packet-level investigation | Wireshark, DNS, TCP/IP |

---

## 01. Microsoft Sentinel SOC Investigation Lab

**Category:** SIEM / Security Operations / Incident Investigation  
**Project status:** In progress

A hands-on SOC laboratory using **Microsoft Sentinel** to collect and investigate Windows security telemetry. The project covers log ingestion, KQL analysis, detection logic, security alerts, and incident investigation workflows.

### Investigation Highlights

- Collected Windows security events through Azure Arc, Azure Monitor Agent, and Log Analytics.
- Analyzed failed and successful authentication events (`4625` and `4624`) to investigate sign-in activity.
- Investigated process execution and relationships using Windows Event ID `4688` and Sysmon Event ID `1`.
- Examined Sysmon network connections (`Event ID 3`) and file creation events (`Event ID 11`).
- Built and tested KQL queries and detection rules for suspicious activity, including repeated failed sign-ins and PowerShell behavior.
- Documented alerts, investigation steps, incident handling, and MITRE ATT&CK mappings.

**Technologies:** `Microsoft Sentinel` `Microsoft Azure` `KQL` `Log Analytics` `Windows Event Logs` `Sysmon` `MITRE ATT&CK`

<div align="center">

<a href="https://github.com/juancarranza-cyber/SOC-Sentinel-Lab">
  <img src="https://img.shields.io/badge/VIEW%20SOC%20LAB-1E40AF?style=for-the-badge&logo=github&logoColor=white" alt="Open Microsoft Sentinel SOC Investigation Lab repository" />
</a>

</div>

---

## 02. Nmap Network Scan Analysis

**Category:** Network Security / Reconnaissance Detection

A network security investigation using **Nmap and Wireshark** in an isolated virtual lab. The analysis examines network reconnaissance activity and the packet-level indicators that help defenders recognize scanning behavior.

### Investigation Highlights

- Generated and observed network scanning traffic in a controlled environment.
- Analyzed TCP connection attempts and port-scanning behavior.
- Inspected TCP flags and packet sequences using Wireshark.
- Examined reconnaissance patterns from a defensive security perspective.
- Documented packet observations and technical investigation findings.

**Technologies:** `Nmap` `Wireshark` `Kali Linux` `Windows` `TCP/IP` `VirtualBox`

<div align="center">

<a href="https://github.com/juancarranza-cyber/nmap-network-scan-analysis">
  <img src="https://img.shields.io/badge/VIEW%20INVESTIGATION-1E40AF?style=for-the-badge&logo=github&logoColor=white" alt="Open Nmap Network Scan Analysis repository" />
</a>

</div>

---

## 03. DNS Traffic Investigation with Wireshark

**Category:** Network Traffic Analysis / Defensive Investigation

An investigation of **DNS queries and responses** using Wireshark. The project explores how domain resolution traffic can support security monitoring, network visibility, and incident investigations.

### Investigation Highlights

- Captured and examined DNS communications in Wireshark.
- Analyzed DNS queries, responses, and domain resolution activity.
- Inspected source and destination information in network packets.
- Interpreted DNS activity in the context of defensive security monitoring.
- Documented observations and supporting evidence.

**Technologies:** `Wireshark` `DNS` `Windows 10` `TCP/IP` `Packet Analysis`

<div align="center">

<a href="https://github.com/juancarranza-cyber/DNS-Traffic-Investigation-Wireshark">
  <img src="https://img.shields.io/badge/VIEW%20INVESTIGATION-1E40AF?style=for-the-badge&logo=github&logoColor=white" alt="Open DNS Traffic Investigation repository" />
</a>

</div>

---

## About This Portfolio

The projects emphasize a repeatable defensive workflow: **collect evidence, analyze activity, identify relevant indicators, and document technical findings**. Detailed procedures, queries, screenshots, and investigation notes are maintained in the individual project repositories.

<div align="center">

<a href="https://github.com/juancarranza-cyber">
  <img src="https://img.shields.io/badge/BACK%20TO%20GITHUB%20PROFILE-334155?style=for-the-badge&logo=github&logoColor=white" alt="Return to GitHub profile" />
</a>

</div>
