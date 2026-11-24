# Lab 05 - Nmap service discovery on a local lab

**Date:** TBD | **Course:** CYCP5103 | **Status:** not started

## Objective
Interpret open/closed ports and service versions without assuming vulnerabilities.

## Environment
- OS / version:
- Tools and versions:
- Scope statement: 127.0.0.1 or my own VM only. Never scan third-party hosts.

## Steps performed
1. Start python3 -m http.server 8000 --bind 127.0.0.1
2. Verify with curl
3. nmap -sT -sV -p 8000 127.0.0.1
4. nmap -sT -p 8001 127.0.0.1 (closed port comparison)
5. Practise host discovery flags (-sn -PR/-PE/-PS/-PA) against my own VM
6. Save output (-oN / -oX)
7. Table: Service | Exposure | Potential risk | Evidence | Mitigation (no invented CVEs)
8. Stop the server and re-scan

## Evidence
_Add redacted screenshots to `evidence/`._

## Findings
_TBD_

## Defensive recommendations
1.
2.
3.

## Limitations
_TBD_

## Reflection
- What did I observe?
- Which control would reduce the risk?
- What limitations did the tool or method have?
