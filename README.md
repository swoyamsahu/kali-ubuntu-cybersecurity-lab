# Kali–Ubuntu Cybersecurity Lab

## Overview
This project documents a hands-on cybersecurity lab built using Kali Linux (attacker) and Ubuntu (target) inside VirtualBox.  
The goal was to move beyond theory and understand real-world fundamentals like networking, reconnaissance, and password security in a safe, isolated environment.

---

## Lab Setup
- VirtualBox virtual environment
- Kali Linux (attacker machine)
- Ubuntu Linux (target machine)
- Internal virtual network (isolated from host and internet)

---

## What I Practiced
- Manual static IP configuration
- Troubleshooting connectivity between virtual machines
- Network verification using ping and routing checks
- Host discovery and service enumeration using Nmap
- Identifying exposed services like SSH
- Exploring how Linux stores password hashes (`/etc/shadow`)
- Offline hash analysis using John the Ripper

---

## Key Learnings
- Strong understanding of basic networking is essential in cybersecurity
- Modern Linux uses secure hashing algorithms (yescrypt / SHA-512)
- Tool compatibility matters in practical security testing
- Small configuration mistakes can break entire environments
- Troubleshooting is a major part of hands-on cybersecurity learning

---

## Screenshots
Example lab stages included:
- Lab architecture setup
- Internal network connectivity
- Nmap scanning results
- Linux password hash inspection
- Hash loading using John the Ripper

(Screenshots available in the `/screenshots` folder)

---

## Disclaimer
All activities were performed in a controlled lab environment for educational purposes only.  
This project is focused on learning and understanding cybersecurity fundamentals.

---

## Next Steps
- Build more advanced offensive and defensive labs
- Explore web security and privilege escalation concepts
- Continue documenting hands-on learning

