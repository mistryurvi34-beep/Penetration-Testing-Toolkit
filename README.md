# Penetration-Testing-Toolkit
🧪 Task-3: Penetration Testing Toolkit

📌 What is Penetration Testing?
Penetration Testing (Pentesting) means testing the security of a system or network by trying to find vulnerabilities.
Security professionals behave like ethical hackers to find weaknesses before real hackers exploit them.
Example:
A company website may have:
open ports
weak passwords
vulnerable services
Pentesting tools help detect these problems.

🎯 Objective of Task-3
Build a Python toolkit that contains multiple security testing tools (modules).
Example modules:
Port Scanner
Brute Force Tool
Banner Grabber
All tools should work from one program (main menu).

⚙️ Module 1: Port Scanner
What it does
A port scanner checks which network ports are open on a system.
Example ports:
Port Service
80 HTTP (Website)
443 HTTPS
21 FTP
22 SSH
If a port is open → a service is running there.
Example
If port 22 is open → SSH service is running.
Hackers often attack open ports.
Why it is important
Security engineers use port scanning to:
find exposed services
detect vulnerabilities
secure networks
Real tool example:
Nmap

⚙️ Module 2: Brute Force Tool
What it does
A brute force attack tries many passwords automatically until the correct one is found.
Example password attempts:

admin
123456
password
admin123
The program tries each password until login succeeds.
Why it is important
Companies test their systems to check:
Are passwords strong?
Can attackers guess passwords easily?
Security engineers run controlled brute force tests.

⚙️ Module 3: Banner Grabber
What it does
Banner grabbing collects information from a server.
Example information:

Apache Web Server
OpenSSH 7.6
FTP Server
This helps identify:
server software
server version
Why it is important
If hackers know the server version, they can search for known vulnerabilities.
Security testers use this to detect outdated software.

🧠 Why Task-3 is Important in Computer Science
This task teaches:
✔ Networking concepts
✔ Socket programming
✔ Cybersecurity basics
✔ Ethical hacking techniques
These skills are used in jobs like:
Security Analyst
Ethical Hacker
Network Security Engineer
