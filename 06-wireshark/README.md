# Lab 06 - Wireshark on local traffic

**Date:** TBD | **Course:** CYCP5103 | **Status:** not started

## Objective
Capture my own loopback HTTP traffic and discuss encryption and metadata.

## Environment
- OS / version:
- Tools and versions:
- Scope statement: Own loopback traffic only.

## Steps performed
1. Start local server on 127.0.0.1:8000
2. Capture on the loopback interface (or tcpdump -i lo)
3. curl the server
4. Apply display filter: tcp.port == 8000
5. Record source, destination, protocol, port, info from one packet
6. Write 3 monitoring recommendations

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
