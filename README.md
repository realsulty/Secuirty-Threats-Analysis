## Secuirty Report

Your data center has experienced a denial of service (DoS) attack from an unknown attacker. 
Data network connectivity to the production logistics database is down, and voice communications are being disrupted intermittently.

 Someone who is taking responsibility for the attack has contacted management and is demanding payment to end the attack.
 
 You are an IT security leader who must interface with the correct internal resources to identify any damage to critical assets.You are tasked with coordinating measures to stop the attack, identify affected assets, and minimize further damage. You also must recommend controls to prevent this kind of attack from happening again.


### 1. Identify an incident:

- Has an event occurred that will affect the company?
> Yes, an event has occurred that will affect the company. the data center has experienced a denial of service (DoS) attack, disrupting critical services such as data network connectivity to the production logistics database and intermittent disruptions in voice communications. 

- Will the event disrupt the confidentiality, availability, or integrity of the company's assets?
> The event will disrupt the availability of the company's assets as data network connectivity to the production logistics database is down and this will affect the availability of important data for operational tasks

- Which type of incident might have occurred (for example, DoS, data loss, equipment, or physical)?
> The incident is likely a Ransomware or denial of service attack, bearing in mind the symptoms of disrupted network connectivity and intermittent disruptions in voice communications.
- what is the level of impact low, medium, or high?
> the level of impact is high due to the disruption to critical services and potential financial result due to the demand for payment from the attacker.

- Do you believe that this company is experiencing an incident?
> The comapny is experiencing the incident based on the disruption to critical services and the characteristics of a denial of service attack, it is clear that the company is experiencing a an incident.

 - For the DoS attack described, what groups or managers would be appropriate to contact?
 > Database Admins group

### 2. Key Assets:

- Determine how the incident was detected :
> failure in accessing the database by the Database administrator, and a report from the managment after reciving the ransome call to collect a payment


- Provide an initial incident description.
> database admin could not reach to the databse, when a security alert is activated, the alert must be verified because false positives can happen, especially with a system such as an automated intrusion detection system (IDS)

- Provide any additional information: IP address, MAC address, server name, system name, and any other information.
> 192.68.0.0 
Linux 2 

- Classify the affected system: mission-critical, sensitive, or departmental
> the affected systems are sensitive and need an urgent eradication

### 3. incident response plan 
Incident Summary
Date of Report: 30/05/2024 12:30PM
Individual Completing Report: Group number 1
Manager Contact Information:
Name: Sultan
Phone: xxxxxxxxx
Email: linux@netcom.com


Incident Description 
: A denial of service (DoS) attack has targeted our data center, causing disruptions to data network connectivity and intermittent voice communications issues. An unknown attacker has claimed responsibility and demanded payment to stop the attack.

Incident Detection 
: The attack was detected through monitoring systems that flagged unusual access to ourdatabase and through reports of disrupted services from IT team members.

Root Cause 
: Initial investigation suggests the attack was facilitated by vulnerabilities in our database infrastructure, resulting in service disruptions.

Vulnerability Exploited 
: Possible unpatched security flaws in the network devices.
Insufficient network traffic monitoring and filtering capabilities.
Lack of redundancy and failover mechanisms.
 
 ### 4. Eradication solutions
 Affected System | Eradication Solution | Actions to Prevent Reoccurrence|
| ----------- | ----------- | ----------- |
| Network Infrastructure | Implement network segmentation and update firewall rules | Regularly update and patch network devices, implement advanced intrusion detection systems (IDS), and conduct frequent vulnerability assessments |
| Web Servers| Block malicious IP addresses, update web server software, and apply patches| Regularly update web server software, use Web Application Firewalls (WAF), and conduct regular security assessments 
| DataBases| Contain infected elements if there are any, such as hosts infected by a virus. Then, block access to network addresses |Identity Management, Symmetric encryption, Regular Backups
| Backup Systems | Verify integrity of backups and replace compromised systems | Implement redundant backup solutions, regularly test backup restoration processes, and encrypt backups |
| Security Monitoring Systems | Reconfigure and update security monitoring tools | Regularly review and update security policies, conduct penetration testing, and enhance logging and alerting mechanisms |
| Application Servers |Patch vulnerabilities and apply configuration change | Conduct regular application security reviews, use secure coding practices, and perform regular security updates|
