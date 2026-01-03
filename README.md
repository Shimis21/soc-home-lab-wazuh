# soc-home-lab-wazuh
SOC home lab using Wazuh SIEM with Windows &amp; Linux endpoints.
# 🛡️ SOC Home Lab – Wazuh SIEM

## 📌 Project Overview
This project demonstrates a self-built Security Operations Center (SOC) home lab
using open-source tools to simulate real-world SOC analyst workflows.

The lab focuses on centralized log collection, attack detection, alerting,
and basic incident response.

---

## 🧰 Tools Used
- Wazuh (SIEM & XDR)
- VirtualBox
- Ubuntu Server 22.04 (Wazuh Manager)
- Windows 10 (Endpoint)
- Sysmon (Windows telemetry)

---

## 🏗️ Architecture
Windows and Linux endpoints send security logs to a centralized Wazuh SIEM
for detection, correlation, and alerting.

---

## 🔍 Implemented Use Cases
- Centralized log collection (Windows & Linux)
- Brute-force attack detection
- Suspicious PowerShell activity detection
- File Integrity Monitoring (FIM)
- SOC dashboards & alerts
- MITRE ATT&CK mapping

---

## 🧪 Attack Simulations
- Multiple failed login attempts (Event ID 4625)
- PowerShell execution bypass techniques
- Unauthorized file modification

---

## 📊 SOC Analyst Workflow
For each alert:
1. Identify alert source
2. Analyze logs
3. Determine false positive vs incident
4. Document findings
5. Recommend response

---

## 📁 Repository Structure
See folders for setup guides, configurations, attack simulations, and incident reports.

---

## 🚀 Learning Outcomes
- SIEM fundamentals
- Log analysis
- Incident detection & response
- SOC operational thinking
