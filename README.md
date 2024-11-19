# Active Directory Home Lab

## Overview
This project demonstrates the creation of a fully functional Active Directory environment designed to simulate a real-world IT domain. Through a series of configurations, integrations, and simulations, the project explores key aspects of domain management, security event monitoring, and threat analysis.

---

## What I Did & How I Did It

### **1. Configured an Active Directory Environment**
- **What I Did:** Set up an Active Directory Domain Controller to manage users, groups, and organizational policies.
- **How I Did It:**
  - Installed and configured **Windows Server** with Active Directory Domain Services (AD DS).
  - Created a domain with structured **Organizational Units (OUs)** for different user groups and departments.
  - Added **user accounts, groups**, and group policies to enforce access control and security measures.

---

### **2. Set Up Event Logging and Monitoring**
- **What I Did:** Enabled logging of domain events and set up a Security Information and Event Management (SIEM) system to ingest and analyze logs.
- **How I Did It:**
  - Configured **Windows Event Viewer** to track user activity, login attempts, and system events.
  - Deployed **Splunk** as a SIEM tool, connecting it to the domain to collect logs.
  - Set up Splunk dashboards and searches to identify anomalies in real time.

---

### **3. Simulated Attack Scenarios**
- **What I Did:** Simulated real-world attacks to generate security events and test detection capabilities.
- **How I Did It:**
  - Used **Kali Linux** for ethical hacking and reconnaissance techniques.
  - Deployed **Atomic Red Team** to simulate specific attack behaviors such as brute force, privilege escalation, and lateral movement.
  - Monitored the logs generated by these activities in the SIEM tool.

---

### **4. Analyzed Security Telemetry**
- **What I Did:** Investigated generated telemetry to identify attacks and vulnerabilities.
- **How I Did It:**
  - Collected and filtered security logs for insights on suspicious activities.
  - Designed **custom Splunk dashboards and alerts** to visualize attack data and identify abnormal patterns.
  - Evaluated the system’s ability to detect, log, and respond to attack scenarios.

---

## Tools Used
- **Windows Server:** For setting up the domain environment and managing AD services.
- **Splunk:** As a SIEM tool for real-time log analysis and visualization.
- **Kali Linux:** For ethical hacking and attack simulation.
- **Atomic Red Team:** To automate and simulate specific attack techniques.
- **PowerShell & Event Viewer:** For system monitoring and administrative tasks.

---

## Key Takeaways
- Gained experience in **Active Directory domain management**, including account provisioning and policy enforcement.
- Learned to configure and use a **SIEM system** for security monitoring and event analysis.
- Developed skills in simulating and analyzing **real-world attack scenarios** using industry-standard tools.
- Improved proficiency in investigating and mitigating security threats within a controlled environment.

---

## How You Can Use This Project
1. **Recreate the Environment:**
   - Set up virtual machines for Active Directory, Splunk, and attack simulators like Kali Linux.
   - Configure the domain to mirror real-world organizational structures.
2. **Simulate Attacks:**
   - Use tools like Atomic Red Team or Kali Linux to test detection capabilities.
3. **Analyze Logs:**
   - Integrate a SIEM to capture events, create dashboards, and respond to incidents.

---

## Contact
Feel free to connect if you have questions about the project or want to discuss Active Directory and cybersecurity.  
**[Your Name]**  
[Your Email or LinkedIn Profile]
