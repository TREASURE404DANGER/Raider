  <a>
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=EB+Garamond&weight=800&size=28&duration=4000&pause=1000&random=false&width=435&lines=+•★⃝ Raider★⃝•; Python-based+Penetration+Tool;BY+TREASUR404DANGER;RELEASED+DATE+18%2F10%2F2024." alt="Typing SVG" /></a>
 </p>
<p align="center">
<p align="center"><img src="https://profile-counter.glitch.me/{TREASURE404DANGER}/count.svg" alt="TREASURE404DANGER" :: Visitor's Count" /></p>
<p align="center">
<a href="https://github.com/TREASURE404DANGER/followers"><img title="Followers" src="https://img.shields.io/github/followers/TREASURE404DANGER?color=red&style=flat-square"></a>
<a href="https://github.com/TREASURE404DANGER/Raider/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/TREASURE404DANGER/Raider?color=blue&style=flat-square"></a>
<a href="https://github.com/TREASURE404DANGER/Raider/network/members"><img title="Forks" src="https://img.shields.io/github/forks/TREASURE404DANGER/Raider?color=red&style=flat-square"></a>
<a href="https://github.com/TREASURE404DANGER/Raider/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/TREASURE404DANGER/Raider?label=Watchers&color=blue&style=flat-square"></a>
<a href="https://github.com/TREASURE404DANGER/Raider/"><img title="Size" src="https://img.shields.io/github/repo-size/TREASURE404DANGER/Raider?style=flat-square&color=green"></a>
 Raider is a Python-based network penetration Here's the rewritten text with added sections, removed unnecessary parts, and improved readability:

*Raider: Network Penetration Testing Tool*

*Overview*

Raider is a Python-based network penetration testing tool designed to facilitate Capture The Flag (CTF) challenges and comprehensive network assessments.

*Key Features*

- TCP and UDP port scanning using Nmap
- Modular design with service-specific handlers
- Recommendations and potential actions for specific ports
- Multiprocessing capabilities for concurrent module execution

*System Requirements*

- Python 3.x
- Nmap
- Gobuster
- Dig
- Crackmapexec
- Metasploit
- Required Python libraries: subprocess, multiprocessing, sys, re, etc.

### FORK THIS REPO

<a href='https://github.com/TREASURE404DANGER/Raider/fork' target="_blank"><img alt='Fork repo' src='https://img.shields.io/badge/Fork This Repo-black?style=for-the-badge&logo=git&logoColor=white'/></a>

### *Installation*


```bash
curl https://raw.githubusercontent.com/TREASURE404DANGER/Raider/main/install.sh|bash
```

### *Usage*


```bash
python3 /application/path/raider.py <IP_ADDRESS>
```

If installed with install.sh:


```bash
raider <IP_ADDRESS>
````

### *Modules*

1. *NMAP Scan*

- Automatic port detection and scanning
- Scrapes DNS information

2. *FTP*

- Anonymous login checks
- Bruteforce attempts
- Directory listing

3. *SSH*

- Credential bruteforce suggestions

4. *HTTP*

- Server identification
- Technology detection
- Crawling and bruteforce location scanning
- Detects VHOSTS and adds them to /etc/hosts file
- Extracts comments from founded URLs
- Tests for Apache Server CVEs

5. *KERBEROS*

- Username enumeration
- Ticket extraction
- Automatic synchronization with DC
- Automatic ticket cracking (optional)

6. *SMB*

- RID cycling usernames enumeration
- Bruteforce attempts
- Share enumeration

*Reporting*

Raider generates a comprehensive report detailing:

- Open ports and services
- Potential vulnerabilities
- Recommended actions

### *Disclaimer*

Raider is intended for educational and ethical penetration testing purposes only. Ensure proper authorization before using it on any network or system.


#### *Contact*

[Insert contact information]

## 🙇 Special Thanks

- [Mr. Robot 🤖](https://github.com/Sphinxx404)
 
- [Ghost👻](https://github.com/ghostx313)
