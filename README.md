<h1>Azure Sentinel Home SIEM Lab</h1>



# Azure Sentinel Home SIEM Lab

## 📌 Description
This project demonstrates the creation of a cloud-based **Azure Sentinel SIEM** environment paired with a Windows 10 **honeypot virtual machine** used to collect, analyze, and visualize real-world security events.  
This lab focuses on building hands-on experience in SIEM operations, log analysis, threat detection, and cloud-based monitoring.

---

## 🔥 Key Features

- **Windows 10 Honeypot:** Deployed a publicly exposed VM to intentionally attract failed login attempts and suspicious activity.
- **Centralized Log Collection:** Configured Azure Log Analytics Workspace to ingest Windows Security Events.
- **Microsoft Sentinel SIEM:** Set up for live monitoring, alerting, and security event analysis.
- **KQL Threat Hunting:** Queried failed login attempts (Event ID 4625) and analyzed attacker behavior.
- **Geo-IP Log Enrichment:** Imported a custom IP geolocation watchlist to correlate attacker IPs with their geographic origin.
- **Interactive Attack Map:** Built a real-time map that visualizes where global login attempts are coming from.

---

## 🛠️ Technology Used

- **Azure Virtual Machine (Windows 10)**
- **Azure Log Analytics Workspace**
- **Microsoft Sentinel**
- **Azure Data Collection Rules (AMA)**
- **Kusto Query Language (KQL)**
- **Azure Watchlists**
- **Sentinel Workbooks**

---

## 📂 Lab Architecture

