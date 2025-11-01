# Web-Security-works


## Content of this repo

Each folder contains a short `README.md` file that summarizes the lab’s objectives and main procedures.
A `screenshots` directory provides visual evidence and slide captures, while the `scripts` directory stores any custom or automation code used in the exercises.


---

## Lab Summaries

| Lab | Title | Focus |
|-----|--------|--------|
| 01 | Client-Side Attacks: Stored XSS, CSRF & BeEF Browser Hooking | Exploiting cross-site scripting, cross-site request forgery, and browser-based control using BeEF. |
| 02 | Burp Proxy Setup, IIS + Juice Shop Deployment, Directory Traversal & XXE | Setting up Burp Suite for interception, hosting Juice Shop on IIS, and testing directory traversal and XML External Entity injection. |
| 03 | HTTP Enumeration & Session Hijacking | Capturing and manipulating HTTP headers, hijacking cookies, altering user-agents, and performing brute-force logins with Burp Intruder. |
| 04 | PHP Includes & MySQL Privileges | Writing basic PHP scripts, performing file inclusions, and managing database permissions securely. |
| 05 | SQL Injection – Manual and Automated | Demonstrating SQL Injection exploitation using manual payloads and sqlmap against Mutillidae and Juice Shop. |
| 06 | Session Attacks & Cookie Exfiltration | Capturing credentials via injected HTML, sniffing with Cain & Abel, analyzing session token entropy, and exfiltrating cookies. |
| 07 | Web Pentest Toolchain – Skipfish, Nikto, HTTrack & DVWA | Performing automated scanning, mirroring web apps, and exploiting command injection in DVWA. |


---

## Tools and Technologies

- Operating Systems: Kali Linux 2023, Ubuntu Server 20.04, Windows 10 Pro, Windows Server 2016  
- Frameworks and Tools: Burp Suite, OWASP Juice Shop, Mutillidae, DVWA, BeEF, Nikto, Skipfish, HTTrack, ClamAV, Sendmail, sqlmap  
- Languages: PHP, SQL, Bash, HTML, JavaScript  

---

## Environment Summary

All labs were executed in a virtualized network topology using VMware Workstation 16, isolated lab subnets, and controlled service interactions between attacker and victim hosts.  
See resources/vm_network_topology.png for the full layout.

---

## License and Academic Integrity

All tests were conducted within a sandbox environment.
This repository is for educational and demonstration purposes only.  

