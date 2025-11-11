🧱 Cybersecurity Homelab – Offensive & Defensive Simulation Environment

📖 Overview

This project showcases my personal Cybersecurity Homelab — a fully virtualized environment built to safely simulate offensive, defensive, and monitoring scenarios.
It integrates an Active Directory network, firewall segmentation, attacker and victim machines, and a centralized SIEM (Splunk) for end-to-end visibility.

Through this lab, I gained a practical, real-world understanding of:
Network segmentation and firewalling with pfSense
Windows Server Active Directory setup and management
Attack simulation using Kali Linux and Metasploitable 2
Security log collection and correlation using Splunk
Blue Team analysis workflows for detection and defense

⚙️ Components
| Role                              | OS / Tool            | Purpose                                    |
| --------------------------------- | -------------------- | ------------------------------------------ |
| 🧠 **Kali Linux**                 | Debian-based         | Offensive testing & vulnerability scanning |
| 🔥 **pfSense**                    | FreeBSD              | Firewall, router, VLAN segmentation, NAT   |
| 🧱 **Metasploitable 2**           | Ubuntu Server        | Vulnerable target machine for exploitation |
| 🧾 **Windows Server 2019**        | AD Domain Controller | Active Directory, DNS, authentication      |
| 💻 **Windows 10 Enterprise**      | Client Machine       | Domain-joined user workstation             |
| 📊 **Ubuntu (Splunk Enterprise)** | SIEM                 | Log ingestion, correlation, dashboards     |

🧠 Learning Outcomes
| Area                        | Key Takeaway                                                                      |
| --------------------------- | --------------------------------------------------------------------------------- |
| 🔐 **Network Security**     | Configured pfSense for multi-LAN segmentation and routing.                        |
| ⚔️ **Attack Simulation**    | Used Kali Linux to scan and exploit Metasploitable 2 in a controlled environment. |
| 🧩 **Blue Team Monitoring** | Collected and analyzed system, DNS, and auth logs in Splunk.                      |
| 🪪 **Active Directory**     | Built domain controllers and managed group policies for lab users.                |
| 📈 **Incident Response**    | Created and investigated alerts inside Splunk dashboards.                         |

🧾 MITRE ATT&CK Mapping
| Technique         | ID    | Description                       |
| ----------------- | ----- | --------------------------------- |
| Credential Access | T1003 | OS Credential Dumping             |
| Discovery         | T1082 | System Information Discovery      |
| Execution         | T1059 | Command and Scripting Interpreter |
| Defense Evasion   | T1070 | Indicator Removal on Host         |

🚀 Why Build a Homelab?

1️⃣ Safe, isolated environment for hands-on learning.
2️⃣ Real-world exposure to enterprise-grade tools.
3️⃣ End-to-end view of offensive + defensive operations.
4️⃣ Opportunity to experiment, break, and fix — without risk.
5️⃣ Builds confidence for professional SOC and pentesting roles.


🧑‍💻 Author

Chirayu Paliwal
Cybersecurity Blue Team & SOC Automation Enthusiast
🔗 LinkedIn: www.linkedin.com/in/chirayu-paliwal-a726a925a
