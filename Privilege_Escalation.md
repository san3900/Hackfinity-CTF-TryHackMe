# Privilege Escalation – Hackfinity CTF

## 🧱 Scenario:
Gained initial access to a Linux shell through weak web credentials.

## 🔎 Enumeration:
- Used `linpeas.sh` to scan for misconfigurations
- Found SUID binary with root permissions
- Searched on GTFOBins for exploit method

## 🚀 Exploitation:
- Leveraged `/usr/bin/python3` SUID to get a root shell
- Confirmed access using `whoami` and `id`

## 🎯 Outcome:
Root shell achieved, flag captured from `/root/flag.txt`

*Tools Used: LinPEAS, GTFOBins, Python, SSH*
