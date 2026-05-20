#  Home SOC Lab — Threat Detection & Incident Response

![Status](https://img.shields.io/badge/Status-Complete-success)
![Platform](https://img.shields.io/badge/Platform-Splunk%20%7C%20Suricata%20%7C%20Sysmon-blue)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-5%20Techniques-orange)
![IR Reports](https://img.shields.io/badge/IR%20Reports-3%20Complete-green)


A fully operational Security Operations Center built from scratch to demonstrate end-to-end threat detection, investigation, and incident response capabilities.
Built by Sabelo Eugene Moyo 

---
 <h1>🎯 Project Overview</h1>
This project showcases practical SOC analyst skills through a complete security operations environment. I built a multi-platform SOC lab using industry-standard tools (Splunk, Suricata IDS, Sysmon) to detect, investigate, and document real-world attack scenarios mapped to the MITRE ATT&CK framework.

## Why This Project Matters:

- Demonstrates hands-on experience with SIEM platforms, not just theoretical knowledge
- Shows ability to write custom detection rules and investigate security incidents
- Proves capability to document findings in professional incident response reports
- Validates understanding of adversary tactics, techniques, and procedures (TTPs)

---
  <h1>🏗️ Architecture</h1>
<h2>Environment Overview</h2>


| Component          | Technology                     | Purpose                                         |
|--------------------|--------------------------------|-------------------------------------------------|
| **SIEM**           | Splunk Enterprise 9.2          | Central log aggregation, correlation, alerting  |
| **Network IDS**    | Suricata                       | Network traffic monitoring, signature detection |
| **Windows Telemetry** | Sysmon (SwiftOnSecurity config) | Process creation, network connections, file events |
| **Linux Telemetry** | auditd                        | System call auditing, security events           |
| **Attack Platform** | Kali Linux                    | Adversary simulation and penetration testing    |
| **Virtualization** | VirtualBox 7.0                 | Isolated lab environment                        |

