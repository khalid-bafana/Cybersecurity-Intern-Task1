# Cybersecurity Internship – Task 1: Network Port Scanning with Nmap

# Objective
The goal of this task was to discover devices and open ports on my local network using Nmap, and analyze the services running to understand potential network exposure and security risks.

# Tools Used
Nmap - Used for network port scanning
Command Prompt (Windows) – For getting local IP

# Task Performed
1. Open CMD and type "IPCONFIG" to get the Local IP
2. Used that IP in Nmap command nmap -sS 192.168.1.0/24 to scan the network
3. Got the output which shows Port#53 is open in my network
3. Once got the scan output. Saved that output in .txt format to save it in GitHub

# Scan Summary
Total 9 devices detected in the scan
IP Address      Open Ports	Services	Notes
192.168.1.248	53		DNS (domain)	Open and active
All others	113 (closed)			Closed

# Lesson Learned
Learned how to scan a local network using Nmap.
Gained basic understanding of identifying open ports.
Understood how to analyze scan results.
Learned to document and save results on GitHub.

# Files Included
Nmap_Ports_Scan.txt – Raw scan output
README.md – Task explanation (this file)


