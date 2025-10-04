Cyber-internship-task1

 1. Cybersecurity Basics
- CIA Triad
  - Confidentiality → Protect information (e.g., encryption, passwords).
  - Integrity → Prevent unauthorized modification of data.
  - Availability → Ensure systems and data are accessible when needed.
- Threat Types → Phishing, Malware, DDoS, SQL Injection, Brute Force, Ransomware.
- Attack Vectors → Social engineering, insider threats, wireless attacks, network exploitation.

---

 2. Lab Environment Setup
- Installed VirtualBox.
- Created two VMs:
  - Kali Linux (Attacker)  
  - Metasploitable2 / DVWA (Target)
- Configured Host-only Network (isolated lab).
- Verified connectivity using `ping`.

---

 3. Linux Fundamentals
Practiced essential commands:
- Navigation & Files → `cd`, `ls`, `pwd`, `touch`, `mkdir`
- Permissions → `chmod`, `chown`, `ls -l`
- Processes & Packages → `ps`, `top`, `apt update`, `apt install`
- Networking → `ifconfig` / `ip a`, `netstat`, `ping`, `traceroute`

---

 4. Networking Basics
- Learned OSI Model (7 layers) & TCP/IP Model (4 layers).
- Practiced commands:
  - `ping <target>` — test connectivity
  - `traceroute 8.8.8.8` — show network hops
  - `nslookup / dig` — DNS lookup
- Performed Nmap scans to identify open ports and services.

---

5. Cryptography Basics
- Symmetric vs Asymmetric Encryption
  - Symmetric → One key (e.g., AES).
  - Asymmetric → Public/Private key pair (e.g., RSA).
- Hashing → MD5, SHA256 (one-way, integrity check).
- Hands-on with OpenSS:
  - Generated RSA keys
  - Encrypted & Decrypted messages
  - Verified SHA256 hashes

---

 6. Security Tools Familiarization
- Wireshark → Captured packets, applied filters (`ip.addr == target_ip`).
- Nmap → Port scanning, service detection, vulnerability scripts.
- Netcat → Listener & client connections.
- Burp Suite → Captured HTTP requests for web traffic testing.

---

 7. Deliverables
- 📂 GitHub Repo Structure


Submitted by -
Rajarshi Raha
