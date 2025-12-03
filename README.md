
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

## 🧠 Skills Demonstrated
- Cloud SIEM configuration (Azure Sentinel)
- Log ingestion & data connectors
- Kusto Query Language (KQL)
- Threat hunting & failed login analysis (Event ID 4625)
- Windows Security Event monitoring
- Geo-IP log enrichment using Watchlists
- Building SIEM dashboards & attack map visualizations
- SOC investigation workflow & documentation

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
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/228f7220-63d5-44e4-83a0-76162f795c97" />




---

## 💻 Step-by-Step Summary

### **1. Azure Setup**
- Created Azure subscription  
- Configured Log Analytics Workspace  
- Enabled Microsoft Sentinel  

### **2. Honeypot Virtual Machine**
- Deployed Windows 10 VM
- Allowed all inbound traffic via Network Security Group  
- Disabled Windows Firewall for testing  
- Generated failed login attempts  

### **3. Log Collection Configuration**
- Installed AMA agent  
- Enabled **Windows Security Events (via AMA)** data connector  
- Confirmed logs flowing into Log Analytics Workspace  

### **4. KQL Threat Hunting Queries**


