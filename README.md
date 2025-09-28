Cyber-internship-task1

This is the task 1 of cyber security internship in apexplanet .

 Cyber Internship Task 1 ->

 Day 1 - Project Plan ->
- Set up GitHub repo and folder structure.
- Write basic notes on cybersecurity (CIA triad, threat types).
- I capture relevant screenshots.
- The notes of basics (CIA triad, threat types) and virtual boc installation in /notes folder .


Day 2 - Project plan ->
- I download the virtual box.
- i make kali lynax inside the virtual box .
- screenshots of those operations in /screenshot folder .


Day 3 - Project plan ->
- Run the kali linax .
- I open the kali terminal and do the operations.
- The screenshots are in /screenshots folder.
- The wireshark opening video is in the /video folder.

 Day 4 (Target VM) - Project plan ->

- Target VM : Metasploitable2 (imported OVA)
- Target VM name : Metasploitable2
- Target IP (example) : 192.168.56.102
- Kali IP (example) : 192.168.56.101
- VirtualBox Host-only adapter : vboxnet0
- Commands run on target:
  - `ifconfig -a` or `ip a` (to find IP)
- Commands run on Kali:
  - `ip a` (to find Kali IP)
  - `ping -c 4 192.168.56.102`
  - `sudo nmap -sn 192.168.56.0/24`
  - `sudo nmap -sV 192.168.56.102`
- Screenshots: list of file names saved in `/screenshots/`



 Day 6 — Package Management & Network Commands

Objective: Learn how to install essential tools and perform basic network checks in Kali Linux.

Tasks Completed:
- Updated package lists using `sudo apt update`.
- Installed key tools:
  - `nmap` — network scanning
  - `netcat` — connection testing
  - `wireshark` — packet capture
  - `traceroute` — network path tracing
- Explored Linux networking commands:
  - `ifconfig` / `ip a` — check IP addresses
  - `netstat -tulnp` — view active connections and open ports
  - `traceroute 8.8.8.8` — trace the path to a remote host

Key Learnings:
- Package management is crucial for keeping tools updated.
- Network commands help verify connectivity, open ports, and routing paths.
- Practicing these commands in an isolated lab ensures safe experimentation.

Evidence/Outputs:
- Screenshots of successful tool installation.
- Terminal output showing network commands and results.


Submitted by -
Rajarshi Raha
