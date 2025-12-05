
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

Below is the architecture diagram representing the Azure Sentinel SIEM Honeypot environment:

<p align="center">
  <img 
       src="https://github.com/user-attachments/assets/1808c23c-eb02-4346-8ac3-80b77a2a2022"
       alt="Azure Sentinel SIEM Honeypot Architecture"
       width="900">
</p>



---

## 💻 Step-by-Step Lab Guide 

### **1. Azure Setup**
- Created an Azure account to deploy the lab environment  
  👉 [Create your Azure account](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account)

<p align="center">
  <img 
       src="https://github.com/user-attachments/assets/5cffaa3b-f13a-43be-82b4-54e8482f6fe8"
       alt="Azure Sentinel Architecture Diagram"
       width="900">
</p>

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


