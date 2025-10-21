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


![image alt](https://github.com/hostzubair/Nessus/blob/d91e2fc93cd9f6d68351f97dd2f0c3f1cc9c5288/Image/Screenshot%20(71).png)

<summary><b>NESSUS IN KALI</b></summary>   

![image alt](https://github.com/hostzubair/Nessus/blob/d91e2fc93cd9f6d68351f97dd2f0c3f1cc9c5288/Image/Screenshot%20(47).png)

<summary><b>TARGET MACHINE 1 - WINDOWS 10</b></summary>   

![image alt](https://github.com/hostzubair/Nessus/blob/d91e2fc93cd9f6d68351f97dd2f0c3f1cc9c5288/Image/Screenshot%20(45).png)

<summary><b>TARGET MACHINE 2 – METASPLOITABLE</b></summary>   

![image alt](https://github.com/hostzubair/Nessus/blob/d91e2fc93cd9f6d68351f97dd2f0c3f1cc9c5288/Image/Screenshot%20(46).png)


# Task 3: Configure Nessus Scan 
<summary><b>Create a new scan (Basic Network Scan), enter the target IP, and launch the scan</b></summary>

<summary><b>SCANNED WINDOWS 10 MACHINE</b></summary>


![image alt](https://github.com/hostzubair/Nessus/blob/d91e2fc93cd9f6d68351f97dd2f0c3f1cc9c5288/Image/Screenshot%20(48).png)

<summary><b>RESULT</b></summary>


![image alt](https://github.com/hostzubair/Nessus/blob/d91e2fc93cd9f6d68351f97dd2f0c3f1cc9c5288/Image/Screenshot%20(51).png)

<summary><b>SCANNED METASPLOITABLE MACHINE</b></summary>


![image alt](https://github.com/hostzubair/Nessus/blob/d91e2fc93cd9f6d68351f97dd2f0c3f1cc9c5288/Image/Screenshot%20(49).png)

<summary><b>RESULT</b></summary>


![image alt](https://github.com/hostzubair/Nessus/blob/d91e2fc93cd9f6d68351f97dd2f0c3f1cc9c5288/Image/Screenshot%20(52).png)


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



# Task 5: Generate Reports 


<summary><b>Results were exported as PDF and CSV for further analysis and documentation. Nessus provided
detailed summaries including CVE IDs, CVSS scores, and risk ratings, useful for reporting and
remediation tracking</b></summary>    

 


![image alt](https://github.com/hostzubair/Nessus/blob/d91e2fc93cd9f6d68351f97dd2f0c3f1cc9c5288/Image/Screenshot%20(54).png)

# Conclusion 


The Nessus vulnerability assessment project successfully demonstrated how to perform
vulnerability scanning, interpret findings, and propose remediation strategies.
Through systematic analysis, vulnerabilities were effectively categorized and documented,
reinforcing the importance of continuous vulnerability management in cybersecurity.


Nessus proved to be a reliable and versatile tool for identifying security weaknesses across
diverse environments.
This project enhanced understanding of:


 Network and host-based vulnerability detection,
 CVE and CVSS scoring interpretation,
 Patch management and remediation validation




