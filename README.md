# Introduction


Vulnerability assessment is a fundamental component of cybersecurity operations. It involves
identifying weaknesses in systems, applications, and networks that could be exploited by
attackers.

Nessus, developed by Tenable, is one of the most powerful tools used by security professionals
to perform automated vulnerability scans and compliance checks.


# Objective


1. To set up Nessus Essentials in a secure lab environment.
2. To perform authenticated and unauthenticated vulnerability scans.
3. To identify, analyze, and prioritize vulnerabilities based on severity.
4. To understand how plugin data maps to potential exploits and mitigation strategies.
5. To generate professional vulnerability reports suitable for audit or portfolio presentation



# Step-by-Step Guide

# Task 1: Understand the Objective
<summary><b>The primary objective of this project is to perform a comprehensive vulnerability assessment
using Nessus. The aim is to detect vulnerabilities, misconfigurations, and compliance
gaps within the target systems. This step focuses on understanding the overall purpose of the
assessment — to identify, analyze, and prioritize security risks that could potentially
compromise the system’s integrity, availability, or confidentiality.  




# Task 2: Set Up Your Lab Environment 
<summary><b>Prepare test environment using VMware. Set up one VM for Nessus (Kali) and another as a target
(Windows 10 and Metasploitable2).</b></summary>


![image alt](https://github.com/hostzubair/Wireshark/blob/213a3e5936798dd16bdc4f08151dafd860289e12/Images/Screenshot%20(57).png)
![image alt]()


# Task 3: Configure Nessus Scan 
<summary><b>Create a new scan (Basic Network Scan), enter the target IP, and launch the scan</b></summary>

![image alt](https://github.com/hostzubair/Wireshark/blob/213a3e5936798dd16bdc4f08151dafd860289e12/Images/Screenshot%20(58).png)

# Task 4: Analyze Scan Results
<summary><b>After the scans completed, vulnerabilities were categorized by severity: Critical, High,
Medium, Low, and Informational.
Key findings included:      
   


 Windows 10: Minor configuration and patch management warnings.   


 Metasploitable2: Multiple critical vulnerabilities, including open services (FTP, Telnet,
SSH), outdated software, and known CVEs exploitable via Metasploit.   




 testphp.vulnweb: Web application issues such as XSS, outdated PHP versions, and insecure
cookie handling.


Each vulnerability included detailed plugin output, description, impact, and recommended
mitigation</b></summary>
![image alt]()


# Task 3: Analyze Scan Results
<summary><b></b></summary>
![image alt]()

# Task 3: 
<summary><b></b></summary>
![image alt]()

# Task 3: 
<summary><b></b></summary>
![image alt]()




