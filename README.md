# **Daily Duties of a Firewall Analyst**  
By Jacob Vasquez  

Your daily routine will be a blend of proactive monitoring, reactive response,   
and administrative maintenance. The specific tasks can vary, but generally, they will include:  

<img width="400" height="400" alt="LogAnalysisAndAlet_Infographic" src="https://github.com/user-attachments/assets/2e52c50b-78ca-4c44-b63b-53b5fc3d0d4c" />
<img width="400" height="400" alt="IncidentResponse_Infographic" src="https://github.com/user-attachments/assets/10492889-877c-4117-b77e-97062118c3c8" /> 
  
1. **Log Analysis and Alert Triage:** This is the most critical daily task. You will be responsible   for reviewing logs from the firewall and a central Security Information and Event Management (SIEM) system.     

2. **Incident Response:** When an alert is escalated to a high-priority incident, you will be a first responder, investigating the event and initiating the proper response protocol.  
 

    
<img width="400" height="400" alt="FirewallRUleMgmt_Infographic" src="https://github.com/user-attachments/assets/2cc0dcb6-7d16-4f80-a37c-8a19943e8016" />
<img width="400" height="400" alt="PerformanceAndHealth_Infographic" src="https://github.com/user-attachments/assets/eb82b22f-0d33-4910-8c80-a3691c6b43b2" />


3. **Firewall Rule Management:** You will handle change requests for firewall rules, which requires careful review, testing, and documentation to avoid security gaps.  

4. **Performance and Health Monitoring:** You will check the operational status of the firewalls to ensure they are not experiencing performance issues like high CPU usage or packet loss, which could affect network stability.  

  
5. **Documentation and Reporting:** Keeping detailed records of your activities, incidents, and changes is essential for audits and future reference.
<img width="400" height="400" alt="DocsAndReporting_Infographic" src="https://github.com/user-attachments/assets/fd47754e-6761-448b-bea6-51f34defc7d2" />

---

## **How to Accomplish These Tasks**

Here are the practical steps for each daily duty:

#### **1\. Log Analysis and Alert Triage**

* **Use a SIEM/Centralized Logging System:** Manually sifting through firewall logs is inefficient and prone to error. Your company will likely use a SIEM (e.g., Splunk, LogRhythm, or a similar tool) to aggregate and analyze logs from all firewalls and other security devices.  
* **Prioritize Alerts:** The SIEM will flag suspicious activity. Start with the highest-priority alerts, such as "brute-force login attempts," "blocked malware," or "failed connection attempts from a blacklisted IP address."  
* **Investigate Context:** For each alert, don't just close it. Investigate it to determine if it is a true positive or a false positive. Check the source and destination IP addresses, the ports involved, and the time of the event. Correlate this information with data from other systems (e.g., DNS logs, user login records) to build a complete picture.

#### **2\. Incident Response**

* **Follow Established Playbooks:** Your team will have pre-defined procedures (often called "playbooks") for responding to different types of incidents. Follow these steps meticulously.  
* **Containment and Mitigation:** If a legitimate threat is identified, your role may involve blocking the malicious IP address, isolating a compromised host, or updating a rule to block a specific type of traffic.  
* **Escalate When Necessary:** You are the first line of defense. If an incident is too complex or severe for you to handle, you must know when and how to escalate it to a senior analyst, a security engineer, or an incident response team.

#### **3\. Firewall Rule Management**

* **Follow Change Management Protocols:** Never make a rule change without a formal request and approval process. This prevents misconfigurations and maintains an audit trail.  
* **Review and Validate Requests:** A request for a new rule should specify the exact source and destination IP addresses, services, and the business justification for the change. Your job is to scrutinize this request to ensure it aligns with the principle of **least privilege** (only allowing the minimum amount of traffic necessary).  
* **Test Changes:** If possible, test new rules in a pre-production or sandbox environment to ensure they work as intended without causing unintended disruptions or creating new vulnerabilities.  
* **Document Everything:** Record who requested the change, the business reason, the exact rules implemented, and the date of implementation.

#### **4\. Performance and Health Monitoring**

* **Use Dashboards:** Use your SIEM or the firewall's native management interface to check daily performance metrics, such as CPU and memory utilization, network throughput, and the number of active sessions.  
* **Look for Anomalies:** A sudden spike in CPU usage could indicate a potential Denial-of-Service (DoS) attack, while a consistent increase in session counts might signal an unmanaged application or a new network service.

---



