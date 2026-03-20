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
Everything I do is in controlled lab environments, never on unauthorized systems.

Feel free to check my:

<a href="https://www.linkedin.com/in/mohammed-rashad-abdallah-428702336/"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://www.credly.com/users/mohammed-rashad-abdallah/badges#credly">
  <img src="https://img.shields.io/badge/-Credly%20Badges-orange?&style=for-the-badge&logo=credly&logoColor=white" />
</a> 

Open to connect, feedback, or collaboration! 

## Skills

## Current Skills & Hands-On Projects (March 2026)

As a beginner building toward junior SOC analyst roles in Ajman, here are the skills I've developed so far through courses and personal labs:

| Skill                                      | Associated Project / Lab                                      | Status / Notes (March 2026)                          |
|--------------------------------------------|---------------------------------------------------------------|------------------------------------------------------|
| Basic IT & Networking Fundamentals         | Cisco Networking Academy – Introduction to Cybersecurity      | Completed – My first certificate!                    |
| Wireless Security Concepts & Defense       | Cisco Junior Cybersecurity Analyst – Network Defence module   | In progress – Learning protection against wireless attacks |
| Wi-Fi Deauthentication Attack Execution    | Udemy Ethical Hacking Course – Deauth section + Wireshark     | Completed – Captured & analyzed on test network      |
| WPA/WPA2 Handshake Capture & Dictionary Crack | Kali Aircrack-ng lab (4-way handshake + rockyou.txt)         | Successfully done on my own router |
| Packet Capture & Analysis (EAPOL / 802.11) | Wireshark analysis of captured 4-way handshake                | Done – Verified 4 messages, screenshots in repo      |                 |
| Basic Recon & OSINT Awareness              | Intro to tools (HIBP, VirusTotal, Shodan, Censys)             | Learning – Created Anki flashcards                   |
| Home Lab Setup & Kali Usage                | Kali Linux VM + wireless adapter in monitor mode              | Active – Used for all wireless labs so far           |
| Future: SIEM & Log Analysis                | Planned: TryHackMe SOC Level 1 + Wazuh/Elastic home SIEM      | Next phase after Security+                           |
| Future: Incident Response Basics           | Planned: TryHackMe SOC Level 1 practical exercises            | Starting soon                                        |

## Tools I Use in My Cybersecurity Journey

Below are the main tools I've been working with so far (March 2026).  
I'm still a beginner, so this list focuses on what I've already used in labs (Kali wireless tools, Wireshark, etc.) and the basic recon tools from my Intro to Cybersecurity course.

### 1. Operating System & Lab Environment

| Tool              | Description                              | Why I Use It                                 | Official Link                |
|-------------------|---------------------------------------------------|----------------------------------------------|---------------------------------------------------|
| Kali Linux        | Security-focused Linux for hacking & testing labs | My main machine for labs & analysis | https://www.kali.org/get-kali/                    |
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

| Tool              | What It Does                            | My Status                                    | Official Link                                     |
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
    <img src="https://img.shields.io/badge/-VirtualBox-183A61?&style=for-the-badge&logo=virtualbox&logoColor=white" />
    <img src="https://img.shields.io/badge/-Kali_Linux-557C94?&style=for-the-badge&logo=kalilinux&logoColor=white" />
    <img src="https://img.shields.io/badge/-Windows_Target_VM-0078D6?&style=for-the-badge&logo=windows&logoColor=white" />
    <img src="https://img.shields.io/badge/-TryHackMe_Endpoint_Labs-000000?&style=for-the-badge&logo=tryhackme&logoColor=#00FF9F" />
</div>

### SIEM
<div>
    <img src="https://img.shields.io/badge/-Wazuh-00A4EF?&style=for-the-badge&logo=wazuh&logoColor=white" />
    <img src="https://img.shields.io/badge/-Elastic-005571?&style=for-the-badge&logo=elastic&logoColor=white" />
    <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-TryHackMe_SOC_Level_1-000000?&style=for-the-badge&logo=tryhackme&logoColor=#00FF9F" />
</div>

## Certifications & Badges

All my Cisco Networking Academy badges and other achievements are verified on Credly:

<div style="margin: 20px 0;">
    <a href="https://www.credly.com/users/mohammed-rashad-abdallah/badges#credly" target="_blank">
        <img src="https://img.shields.io/badge/View_All_My_Badges_on_Credly-007ACC?style=for-the-badge&logo=credly&logoColor=white" alt="Credly Profile" />
    </a>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 10px; margin: 15px 0;">
    <!-- Diploma -->
    <a href="https://www.credly.com/users/mohammed-rashad-abdallah/badges#credly" target="_blank">
        <img src="https://img.shields.io/badge/-Diploma_in_Computer_Science-4CAF50?style=for-the-badge&logo=book&logoColor=white" />
    </a>
</div>

**My Current Achievements (March 2026):**
- **Diploma in Computer Science** – New Life College, Ghana  
- **Cisco Networking Academy Badges** (all completed & verified on Credly):  
  - Introduction to Cybersecurity  
  - Endpoint Security  
  - Networking Basics  
  - Networking Devices and Initial Configuration  

Full verification and details:  
🔗 [View my complete Credly profile →](https://www.credly.com/users/mohammed-rashad-abdallah/badges#credly)

These are the foundations I'm building on as I prepare for CompTIA Security+ and more advanced certifications.

## Projects
- Lab
- Project
