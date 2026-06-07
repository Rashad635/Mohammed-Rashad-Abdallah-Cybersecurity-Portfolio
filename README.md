## Hi, I'm Mohammed Rashad Abdallah

**Aspiring Cybersecurity Analyst**, UAE

IT support personnel transitioning into cybersecurity with a focus on understanding how systems are attacked, detected, and secured in real environments. I am building practical skills across defensive and offensive areas through consistent hands on work and structured learning.

My goal is to grow into a SOC analyst role, contribute to strengthening security, improving detection, and supporting resilient systems, and later expand into offensive security.

## What I've achieved so far
- **Diploma in Computer Science** – New Life College, Ghana
- **Full Cybersecurity course From 0. Ethical Hacking & Defense** - Udemy 
- **Cisco Networking Academy Badges** (verified on [Credly](https://www.credly.com/users/mohammed-rashad-abdallah/badges#credly)):  
  - Introduction to Cybersecurity  
  - Endpoint Security
  - Security and Connectivity Support
  - Networking Basics  
  - Networking Devices and Initial Configuration
  - Network Addressing and Basic Troubleshooting
  - Network Defense
  - Network Network Support and Security
  - Nerwork Technician Career Path
  - Cyber Threat Management
  - Junior Cybersecurity Analyst Career Path Exam
  

## Current focus & hands-on labs
- Actively using **Kali Linux** in VMware for labs:  
- TryHackMe (Pre Security path → SOC)
- Cisco Certified Network Associate (CCNA) Course
- CompTIA Security+ Course
- MYDFIR Forge (90 days SOC Accelerator Course)
- Wireshark Master Class (Chris Greer)
- Building a public portfolio on GitHub with weekly write-ups, screenshots, and Anki flashcards for retention  

## My Goals
- Pass **CompTIA Security+** (SY0-701)
- Pass **Cisco Certified Network Associate** (CCNA)
- Set up first home **SIEM** lab (Wazuh, Microsoft Sentinel and Splunk)  
- Gain practical **SOC** analyst skills (log analysis, incident response & documentation, threat detection)  
- Eventually contribute to **blue-team** projects in the cybersecurity community  

I believe in **SOC**, **continuous documentation**, and **strong defense-in-depth**.  
Everything I do is in controlled lab environments, never on unauthorized systems.

Feel free to check my:

<a href="https://www.linkedin.com/in/mohammed-rashad-abdallah-428702336/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://www.credly.com/users/mohammed-rashad-abdallah/badges#credly">
  <img src="https://img.shields.io/badge/-Credly%20Badges-orange?&style=for-the-badge&logo=credly&logoColor=white" />
</a> 

Open to connect, feedback, or collaboration! 


## Current Skills and Hands-On Projects

I am building toward a junior SOC analyst role through structured courses and hands-on labs.  
The table below shows what I have completed, what I am actively working on, and what I plan to learn next.

### Core skills and completed labs

| Skill | Project or Lab | Status |
|------|---------------|---------------------|
| Home Lab Setup and Kali Linux Usage | Kali Linux VM | Active. Use for labs |
| Wi-Fi Deauthentication Attack | WiFi attack lab | Completed on personal test network |
| WPA and WPA2 Handshake Capture and Crack | Aircrack-ng lab using 4-way handshake and rockyou.txt | Completed successfully on personal router |
| Packet Capture and Analysis | Wireshark analysis of EAPOL 4-way handshake | Verified all handshake messages |
| Nmap reconnaissance and basic vulnerability discovery lab | Nmap scanning with service version detection and vulnerability lookup using searchsploit | Completed. Performed host discovery, port scanning, service enumeration, version detection, and mapped services to known vulnerabilities |
| Bash Scripting | Bash Authentication System Lab | Completed successfully using Nano text editor kali linux |
| Phishing attack | Phishing attack lab | Completed successfully using zphisher on kali linux |
| Incident Investigation Report | Microsoft XDR lab | Completed successfully using Microsoft sentinel |


## Tools I Use in My Cybersecurity Journey  

Below are the main tools I have been working with as of April 2026.  
This list reflects hands-on lab experience, including wireless security testing, packet analysis, phishing simulation, and basic reconnaissance from foundational cybersecurity training.


### 1. Operating System and Lab Environment  

| Tool                         | Description                                                                                                                           | Why I Use It                                                                                          | Official Link                                                                   |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| Kali Linux                   | Security-focused Linux distribution with hundreds of built-in penetration testing and forensic tools.                                 | Primary lab environment for cybersecurity training, threat hunting, and security testing.             | https://www.kali.org                                                            |
| VirtualBox                   | Open-source virtualization platform for running multiple operating systems on a single machine.                                       | Creates isolated lab environments while keeping the host system separate and protected.               | https://www.virtualbox.org                                                      |
| VMware Workstation           | Enterprise-grade virtualization platform for creating and managing virtual machines.                                                  | Used for building realistic lab environments and testing Windows and Linux systems.                   | https://www.vmware.com                                                          |
| Microsoft Sentinel           | Cloud-native SIEM and SOAR platform for security monitoring, threat detection, investigation, and automated response.                 | Used to analyze security events, investigate incidents, and develop detection and response workflows. | https://azure.microsoft.com/products/microsoft-sentinel                         |
| Splunk Enterprise            | Data analytics and SIEM platform that collects, searches, analyzes, and visualizes machine data from multiple sources.                | Used for log analysis, threat hunting, security monitoring, and incident investigations.              | https://www.splunk.com                                                          |
| Microsoft Defender XDR       | Extended Detection and Response platform providing visibility across endpoints, identities, email, applications, and cloud resources. | Used to investigate alerts, analyze attack chains, and perform threat hunting activities.             | https://www.microsoft.com/security/business/siem-and-xdr/microsoft-defender-xdr |
| Wireshark                    | Network protocol analyzer used to capture and inspect network traffic in real time.                                                   | Used to analyze network communications, investigate suspicious traffic, and study protocols.          | https://www.wireshark.org                                                       |
| Sysmon                       | Windows system monitoring utility that provides detailed process, network, and file activity logging.                                 | Used to generate high-fidelity telemetry for threat hunting and forensic investigations.              | https://learn.microsoft.com/sysinternals/downloads/sysmon                       |
| Sysinternals Suite           | Collection of advanced Windows utilities for troubleshooting, monitoring, and system analysis.                                        | Used to investigate processes, services, autoruns, registry activity, and system behavior.            | https://learn.microsoft.com/sysinternals                                        |
| Nmap                         | Network discovery and security auditing tool.                                                                                         | Used for host discovery, service enumeration, and network reconnaissance in lab environments.         | https://nmap.org                                                                |
| Git & GitHub                 | Version control system and collaborative development platform.                                                                        | Used to document projects, manage code, and maintain a cybersecurity learning portfolio.              | https://github.com                                                              |


### 2. Wireless Security and Packet Capture  

| Tool        | What It Does                                      | My Current Use                                      | Link or Command                              |
|-------------|---------------------------------------------------|-----------------------------------------------------|----------------------------------------------|
| airmon-ng   | Enables monitor mode on wireless interfaces       | Preparing adapter for packet capture                | Built-in: sudo airmon-ng start wlan0         |
| airodump-ng | Scans networks and captures wireless traffic      | Identifying access points and capturing handshakes  | Built-in: sudo airodump-ng wlan0             |
| aireplay-ng | Performs packet injection such as deauthentication | Forcing client reconnection to capture handshake    | Built-in: sudo aireplay-ng                   |
| aircrack-ng | Performs password cracking on captured handshakes | Running dictionary attacks using wordlists          | Built-in: aircrack-ng -w rockyou.txt         |
| Wireshark   | Packet analysis tool for deep inspection          | Analyzing EAPOL handshake and traffic               | https://www.wireshark.org/download.html      |
| Mdk4        | Wireless testing tool for stress and simulation   | Testing wireless behavior in controlled lab         | Built-in Kali                                |

### 3. Wordlists for Cracking  

| Tool or File | Description                                   | My Use                                | Location or Link                |
|--------------|-----------------------------------------------|--------------------------------------|---------------------------------|
| rockyou.txt  | Common password list with millions of entries | Testing weak passwords in lab setups | /usr/share/wordlists/rockyou.txt |

### 4. Recon and OSINT Tools  

| Tool                     | What It Does                                                                                           | My Status                                                                           | Official Link                                                                                                                                                              |
| ------------------------ | ------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Have I Been Pwned        | Checks whether email addresses or passwords have appeared in known data breaches.                      | Used for breach awareness and account exposure assessments.                         | [https://haveibeenpwned.com/](https://haveibeenpwned.com/)                                                                                                                 |
| VirusTotal               | Aggregates results from multiple security vendors to analyze files, URLs, IP addresses, and domains.   | Learning threat intelligence, malware analysis, and IOC enrichment.                 | [https://www.virustotal.com/](https://www.virustotal.com/)                                                                                                                 |
| AbuseIPDB                | Community-driven threat intelligence platform for checking and reporting malicious IP addresses.       | Used for IP reputation analysis and incident investigations.                        | [https://www.abuseipdb.com/](https://www.abuseipdb.com/)                                                                                                                   |
| ZoomEye                  | Cyber asset search engine used to discover internet-facing devices, services, and exposed systems.     | Learning external attack surface analysis and reconnaissance techniques.            | [https://www.zoomeye.org/](https://www.zoomeye.org/)                                                                                                                       |
| MITRE ATT&CK             | Knowledge base of adversary tactics, techniques, and procedures (TTPs) observed in real-world attacks. | Used to map threats, analyze attacker behavior, and improve detection capabilities. | [https://attack.mitre.org/](https://attack.mitre.org/)                                                                                                                     |
| nslookup                 | Command-line tool used to query DNS records and troubleshoot name resolution issues.                   | Used for DNS investigations and network troubleshooting.                            | [https://learn.microsoft.com/windows-server/administration/windows-commands/nslookup](https://learn.microsoft.com/windows-server/administration/windows-commands/nslookup) |
| Shodan                   | Search engine for internet-connected devices, services, and exposed infrastructure.                    | Learning asset discovery and security exposure analysis.                            | [https://www.shodan.io/](https://www.shodan.io/)                                                                                                                           |
| Censys                   | Internet intelligence platform that indexes hosts, services, certificates, and exposed assets.         | Exploring host discovery, certificate analysis, and attack surface visibility.      | [https://search.censys.io/](https://search.censys.io/)                                                                                                                     |
| Exploit Database         | Public repository of exploits, proof-of-concept code, and vulnerability references.                    | Studying vulnerabilities and understanding exploit techniques.                      | [https://www.exploit-db.com/](https://www.exploit-db.com/)                                                                                                                 |
| WHOIS                    | Provides domain registration and ownership information.                                                | Used for domain investigations and threat intelligence enrichment.                  | [https://whois.icann.org/](https://whois.icann.org/)                                                                                                                       |
| URLScan.io               | Analyzes websites and captures information about page content, requests, and infrastructure.           | Used for phishing investigations and web reputation analysis.                       | [https://urlscan.io/](https://urlscan.io/)                                                                                                                                 |
| Cisco Talos Intelligence | Threat intelligence platform providing domain, IP, and reputation information.                         | Used for IOC validation and infrastructure analysis.                                | [https://talosintelligence.com/](https://talosintelligence.com/)                                                                                                           |
| Any.Run                  | Interactive malware sandbox for dynamic analysis of suspicious files and URLs.                         | Learning malware behavior analysis and threat investigation workflows.              | [https://any.run/](https://any.run/)                                                                                                                                       |

### 5. Learning and Documentation Tools  

| Tool      | What It Is                                   | My Use                                                     | Link                                 |
|-----------|----------------------------------------------|------------------------------------------------------------|--------------------------------------|
| GitHub    | Platform for code and documentation          | Publishing labs and maintaining portfolio                  | https://github.com/                  |
| Notion    | Note-taking and organization tool            | Tracking progress and documenting learning                 | https://www.notion.so/               |
| Anki      | Flashcard application for memory retention   | Practicing commands, ports, and concepts                   | https://apps.ankiweb.net/            |

## Network
<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
    <img src="https://img.shields.io/badge/-Aircrack--ng-557C94?&style=for-the-badge&logo=linux&logoColor=white" />
    <img src="https://img.shields.io/badge/-TryHackMe-000000?&style=for-the-badge&logo=tryhackme&logoColor=#00FF9F" />
</div>

## Endpoint
<div>
    <img src="https://img.shields.io/badge/-VirtualBox-183A61?&style=for-the-badge&logo=virtualbox&logoColor=white" />
    <img src="https://img.shields.io/badge/-VMware-607078?&style=for-the-badge&logo=vmware&logoColor=white" />
    <img src="https://img.shields.io/badge/-Kali_Linux-557C94?&style=for-the-badge&logo=kalilinux&logoColor=white" />
    <img src="https://img.shields.io/badge/-Windows_Target_VM-0078D6?&style=for-the-badge&logo=windows&logoColor=white" />
    <img src="https://img.shields.io/badge/-TryHackMe_Endpoint_Labs-000000?&style=for-the-badge&logo=tryhackme&logoColor=#00FF9F" />
</div>

## SIEM
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Splunk-FFD700?&style=for-the-badge&logo=tryhackme&logoColor=#00FF9F" />
    <img src="https://img.shields.io/badge/-TryHackMe_SOC_Level_1-000000?&style=for-the-badge&logo=tryhackme&logoColor=#00FF9F" />
</div>

#

## Projects
-  <a href="https://github.com/Rashad635/WiFi-Attack-Lab/blob/main/README.md">WiFi attack lab</a>
-  <a href="https://github.com/Rashad635/nmap-reconnaissance-and-basic-vulnerability-discovery-lab/tree/main/README.md">Nmap reconnaissance and basic vulnerability discovery lab</a>
-  <a href="https://github.com/Rashad635/Phishing-attack-using-Zphisher/blob/main/README.md">Phishing attack lab</a>
-  <a href="https://github.com/Rashad635/Bash-Authentication-System-Lab/blob/main/README.md">Bash Authentication System Lab</a>
-  <a href="https://github.com/Rashad635/Incident-Investigation-Report/blob/main/README.md">Incident Investigation Report</a>
