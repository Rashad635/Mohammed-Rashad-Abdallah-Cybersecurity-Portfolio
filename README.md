## Hi, I'm Mohammed Rashad Abdallah

**Aspiring Cybersecurity Analyst**, UAE

I’m a beginner in cybersecurity who is passionate about learning both defensive (blue team) and offensive (red team) skills to protect systems and understand real-world threats.  

### What I've achieved so far (March 2026)
- **Diploma in Computer Science** – New Life College, Ghana  
- **Cisco Networking Academy Badges** (verified on [Credly](https://www.credly.com/users/mohammed-rashad-abdallah/badges#credly)):  
  - Introduction to Cybersecurity  
  - Endpoint Security  
  - Networking Basics  
  - Networking Devices and Initial Configuration  

### Current focus & hands-on labs
- Completing **Udemy Full Cybersecurity Course From 0: Ethical Hacking & Defense** (wireless attacks, phishing simulation with Zphisher, etc.)  
- Actively using **Kali Linux** in VirtualBox for labs:  
  - Wi-Fi deauthentication attacks  
  - WPA/WPA2 handshake capture & dictionary cracking (Aircrack-ng)  
  - Phishing page simulation (Zphisher – local testing only)  
  - Packet capture & analysis with **Wireshark** (EAPOL 4-way handshake)  
- Just started **TryHackMe** (Pre Security path → SOC Level 1 next)  
- Building a public portfolio on GitHub with daily/weekly write-ups, screenshots, and Anki flashcards for retention  

### My Goals
- Pass **CompTIA Security+** (SY0-701) soon  
- Set up first home SIEM lab (Wazuh + Elastic)  
- Gain practical SOC analyst skills (log analysis, incident response, threat detection)  
- Eventually contribute to blue-team / purple-team projects in the UAE cybersecurity community  

I believe in **ethical hacking**, **continuous documentation**, and **strong defense-in-depth**.  
Everything I do is in controlled lab environments — never on unauthorized systems.

Feel free to check my:
- <a href="https://www.linkedin.com/in/mohammed-rashad-abdallah-428702336/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
- [Credly Badges](https://www.credly.com/users/mohammed-rashad-abdallah/badges#credly)  

Open to connect, feedback, or collaboration! 

## Skills

## Current Skills & Hands-On Projects (March 2026)

As a beginner building toward junior SOC analyst roles in Ajman, here are the skills I've developed so far through courses and personal labs:

| Skill                                      | Associated Project / Lab                                      | Status / Notes (March 2026)                          |
|--------------------------------------------|---------------------------------------------------------------|------------------------------------------------------|
| Basic IT & Networking Fundamentals         | Cisco Networking Academy – Introduction to Cybersecurity      | Completed – My first certificate!                    |
| Wireless Security Concepts & Defense       | Cisco Junior Cybersecurity Analyst – Network Defence module   | In progress – Learning protection against wireless attacks |
| Wi-Fi Deauthentication Attack Execution    | Udemy Ethical Hacking Course – Deauth section + Wireshark     | Completed – Captured & analyzed on test network      |
| WPA/WPA2 Handshake Capture & Dictionary Crack | Kali Aircrack-ng lab (4-way handshake + rockyou.txt)         | Successfully done on my own router – GitHub write-up |
| Packet Capture & Analysis (EAPOL / 802.11) | Wireshark analysis of captured 4-way handshake                | Done – Verified 4 messages, screenshots in repo      |
| Ethical Hacking Lab Documentation          | Personal GitHub portfolio (cyber-journey-2026 repo)           | Ongoing – Daily/weekly lab write-ups                 |
| Basic Recon & OSINT Awareness              | Intro to tools (HIBP, VirusTotal, Shodan, Censys)             | Learning – Created Anki flashcards                   |
| Home Lab Setup & Kali Usage                | Kali Linux VM + wireless adapter in monitor mode              | Active – Used for all wireless labs so far           |
| Future: SIEM & Log Analysis                | Planned: TryHackMe SOC Level 1 + Wazuh/Elastic home SIEM      | Next phase after Security+                           |
| Future: Incident Response Basics           | Planned: TryHackMe SOC Level 1 practical exercises            | Starting soon                                        |

## Tools I Use in My Cybersecurity Journey

Below are the main tools I've been working with so far (March 2026).  
I'm still a beginner, so this list focuses on what I've already used in labs (Kali wireless tools, Wireshark, etc.) and the basic recon tools from my Intro to Cybersecurity course.

### 1. Operating System & Lab Environment

| Tool              | Description (Simple)                              | Why I Use It                                 | Official Link / How to Get It                     |
|-------------------|---------------------------------------------------|----------------------------------------------|---------------------------------------------------|
| Kali Linux        | Security-focused Linux for hacking & testing labs | My main machine for wireless attacks & analysis | https://www.kali.org/get-kali/                    |
| VirtualBox        | Free software to run Kali safely in a virtual machine | Keeps my laptop clean and safe               | https://www.virtualbox.org/                       |

### 2. Wireless Security & Packet Capture (Aircrack-ng Suite)

| Tool              | What It Does                                      | My Current Use                               | Link / Command                                    |
|-------------------|---------------------------------------------------|----------------------------------------------|---------------------------------------------------|
| airmon-ng         | Enables monitor mode on Wi-Fi card                | Put card in monitor mode before scanning     | Built-in Kali: `sudo airmon-ng start wlan0`       |
| airodump-ng       | Scans Wi-Fi networks & captures packets           | Find APs, clients, and capture handshakes    | Built-in: `sudo airodump-ng wlan0`                |
| aireplay-ng       | Sends deauth packets or other injections          | Force clients to reconnect for handshake     | Built-in: `sudo aireplay-ng ...`                  |
| aircrack-ng       | Cracks WPA/WPA2 passwords from captured handshake | Dictionary attack with rockyou.txt           | Built-in: `aircrack-ng -w rockyou.txt ...`        |
| Wireshark         | Captures and views network packets in detail      | Analyzed EAPOL 4-way handshake messages      | https://www.wireshark.org/download.html           |

### 3. Wordlists for Cracking

| Tool/File         | Description                                       | My Use                                       | Location / Link                                   |
|-------------------|---------------------------------------------------|----------------------------------------------|---------------------------------------------------|
| rockyou.txt       | Popular password wordlist (~14 million entries)   | Used to crack weak test passwords            | Kali default: `/usr/share/wordlists/rockyou.txt`  |

### 4. Recon & OSINT Tools (From Intro to Cybersecurity)

| Tool              | What It Does (Simple)                             | My Status                                    | Official Link                                     |
|-------------------|---------------------------------------------------|----------------------------------------------|---------------------------------------------------|
| Have I Been Pwned | Checks if your email was leaked in breaches       | Checked my email safely + Anki cards         | https://haveibeenpwned.com/                       |
| VirusTotal        | Scans files/URLs with 70+ antivirus engines       | Learning to check suspicious files           | https://www.virustotal.com/gui/home/upload        |
| Shodan            | Search engine for internet-connected devices      | Learning basics + Anki cards                 | https://www.shodan.io/                            |
| Censys            | Searches hosts, websites, certificates            | Learning basics + Anki cards                 | https://platform.censys.io/                       |
| Exploit Database  | Collection of exploit codes (use ethically only)  | Understanding red team side                  | https://www.exploit-db.com/                       |

### 5. Learning & Documentation Tools

| Tool              | What It Is                                        | My Use                                       | Link                                              |
|-------------------|---------------------------------------------------|----------------------------------------------|---------------------------------------------------|
| GitHub            | Free place to store write-ups & portfolio         | Daily lab write-ups & screenshots            | https://github.com/ (my repo: cyber-journey-2026) |
| Notion            | Note-taking & progress tracker                    | Daily checklists & planning                  | https://www.notion.so/                            |
| Anki              | Flashcard app for memorizing terms & commands     | Practicing tools, ports, reason codes        | https://apps.ankiweb.net/                         |

### 6. Tools I'm Starting to Use Now / Soon

| Tool       | What It Is                                      | My Current / Planned Use                              | Link                          |
|------------|-------------------------------------------------|-------------------------------------------------------|-------------------------------|
| TryHackMe  | Online platform with guided cybersecurity labs  | Already started – Beginning with Pre Security / SOC Level 1 paths for blue-team skills | https://tryhackme.com/        |
| Wazuh      | Free open-source SIEM for log monitoring        | Planned next – Home SIEM lab after Security+          | https://wazuh.com/            |

### Network

<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
    <img src="https://img.shields.io/badge/-Aircrack--ng-000000?&style=for-the-badge&logo=linux&logoColor=white" />
    <img src="https://img.shields.io/badge/-TryHackMe-000000?&style=for-the-badge&logo=tryhackme&logoColor=#00FF9F" />
</div>

### Endpoint
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=Microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Velociraptor-4B275F?&style=for-the-badge&logo=Velociraptor&logoColor=white" />
</div>

### SIEM
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=Microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
    <img src="https://img.shields.io/badge/-Elastic-005571?&style=for-the-badge&logo=Elastic&logoColor=white" />
</div>

## Certifications
[Provide certifications that you have obtained. Use ChatGPT to help create the link - Remove this afterwards]]
<div>
<img src="https://img.shields.io/badge/-Security%2B-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-Network%2B-007ACC?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-A%2B-4D4D4D?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-CDSA-006400?&style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/-CCD-000080?&style=for-the-badge&logoColor=white" />
</div>

## Projects
- Detection Lab
- SOC Automation Project
