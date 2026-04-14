🛡️ CEH v13 Practical Lab Platform
A complete browser-based cybersecurity training environment for Certified Ethical Hacker (CEH) certification preparation. Covers all 20 modules with interactive terminals, simulated tools, CTF challenges, and self-assessment quizzes.

📖 Overview
This project provides a self-contained, web-based laboratory platform designed for instructors and students pursuing the EC-Council Certified Ethical Hacker (CEH) v13 certification. Each module is delivered as an interactive HTML/JavaScript application that simulates real-world ethical hacking tools and techniques in a safe, legal environment.

No virtual machines, complex installations, or cloud costs are required. Students can access the labs directly from a browser while still experiencing realistic terminal commands, tool outputs, and attack scenarios.

🎯 Key Features
20 Comprehensive Modules – Every CEH v13 domain is covered with dedicated labs.

Browser-Based Terminal – Execute simulated commands (nmap, sqlmap, hydra, etc.) and see realistic outputs.

Interactive Tool Simulations – Experience tools like Burp Suite, Wireshark, Metasploit, John the Ripper, and bettercap through guided simulations.

Capture The Flag (CTF) Challenges – Each module includes a hands-on CTF where students must apply learned techniques to find hidden flags.

Self-Assessment Quizzes – Validate knowledge with multiple-choice questions and instant feedback.

Progress Tracking – Visual progress bars encourage completion of theory, practicals, and challenges.

Isolated & Safe – All attacks are simulated; no actual network traffic or exploitation occurs.

Instructor Ready – Easy to deploy in a classroom or training environment via Flask or static hosting.

📚 Modules Included
Module	Topic	Key Simulations
01	Introduction to Ethical Hacking	CIA triad demos, hacking phases, security controls
02	Footprinting & Reconnaissance	WHOIS, DNS enumeration, Google Dorking, OSINT tools
03	Scanning Networks	Nmap scan types, ping sweeps, OS detection, evasion
04	Enumeration	NetBIOS, SMB, SNMP, LDAP, SMTP enumeration
05	Vulnerability Analysis	Nessus, OpenVAS, Nikto, CVE lookup, CVSS scoring
06	System Hacking	Password cracking, privilege escalation, maintaining access
07	Malware Threats	Trojan analysis, ransomware simulation, keylogger detection
08	Sniffing	Wireshark/tcpdump analysis, ARP spoofing, MAC flooding
09	Social Engineering	Phishing email analysis, SET toolkit, vishing, pretexting
10	Denial of Service	SYN flood, Slowloris, DNS amplification, botnet C2 simulation
11	Session Hijacking	Sidejacking, XSS cookie theft, session fixation, Burp replay
12	Evading IDS, Firewalls, Honeypots	Fragmentation, decoys, tunneling, honeypot detection
13	Cloud Computing	S3 bucket enumeration, metadata theft, container escape
14	Cryptography	OpenSSL (AES, RSA, hashing), GPG, classic cipher cracking
