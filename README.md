Azure VM Honeypot Project
Overview:
Designed a Security Information and Event Management (SIEM) system using Microsoft Sentinel, focusing on architecture, security monitoring, and data analytics. The project aimed to detect and analyze real-world cyber threats using honeypot VMs in Azure, though full deployment was limited due to budget constraints.

Project Scope & Objectives
✅ Deploy a Honeypot Environment: Designed an architecture for multiple Windows 10 VMs in Azure to attract and log malicious activity.
✅ Implement Security Monitoring: Integrated Microsoft Sentinel & Log Analytics Workspace to collect and analyse security events.
✅ Enhance Threat Detection: Utilised Microsoft Defender for Cloud for advanced monitoring and detection.
✅ Develop KQL Queries for Threat Intelligence: Created Kusto Query Language (KQL) scripts to extract failed login attempts (Event ID 4625) and detect attack trends.
✅ Visualise Attack Data: Configured Sentinel dashboards & geolocation maps to monitor live threats.
✅ Incident Response & Mitigation: Set up alerts, automated responses, and documented findings.

Technical Implementation
🔹 Project Planning
Designed a honeypot architecture to attract malicious login attempts.
Conducted security assessments and identified monitoring requirements.
🔹 Security Configuration
Deployed Windows 10 VMs with intentionally exposed attack surfaces (disabled firewalls, open RDP).
Configured NSG rules to allow inbound traffic and simulate a vulnerable system.
Integrated Microsoft Defender for Cloud for threat detection.
🔹 Data Collection & Analytics
Created a Log Analytics Workspace (LAW) to collect security logs.
Ingested Windows Security Event logs (Event ID 4625 – Failed Logins).
Developed KQL queries to analyse attack trends and correlate attacker IPs.
🔹 Threat Visualisation & Monitoring
Built Microsoft Sentinel dashboards to track attack patterns.
Configured a real-time attack map using Sentinel Watchlists & GeoIP data.
🔹 Incident Response & Mitigation
Implemented Sentinel alerts for failed brute-force attempts.
Documented findings on attack behaviour, logging IP sources, timestamps, and attack frequency.
Secured the environment and observed changes in attack rates.

Project Outcomes
✅ Demonstrated the use of Microsoft Sentinel for real-time security monitoring.
✅ Developed hands-on experience in log analysis and SIEM security operations.
✅ Gained insights into cyber-attack behaviours and attacker geolocation tracking.
✅ Successfully configured a honeypot environment to attract and log attacks.

Documentation & Screenshots
Project Documentation: Detailed report covering planning, deployment, and results.
Screenshots: Stored in the Word document (attached in the repository).
Final Notes:
💡 Although full deployment was limited due to budget constraints, this project provided valuable insights into Azure security operations, Sentinel SIEM, and threat detection techniques.

Use Cases & Relevance
🚀 For Cybersecurity Analysts & SOC Teams → Shows how to use Sentinel for real-time monitoring.
📊 For Security Engineers → Demonstrates SIEM implementation, KQL query development, and attack visualization.
🔎 For Research & Learning → Provides a practical case study on honeypots and attack detection in Microsoft Azure.

![image](https://github.com/user-attachments/assets/f89e37f9-18c6-4ed3-9d01-36ea581ed89e)

