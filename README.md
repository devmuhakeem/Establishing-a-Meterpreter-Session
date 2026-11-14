# Establishing a Meterpreter Session

Completed a hands-on lab on the Meterpreter payload and post-exploitation workflow in Metasploit, run in an isolated Kali Linux environment.

## What it covered
- How reverse Meterpreter payloads establish a callback connection
- Simulated remote code execution against a local, unprivileged victim account
- Interacting with an active Meterpreter session and running post-exploitation commands to confirm identity, system info, and working directory
- A blue-team challenge: detecting evidence of a compromise using standard Linux investigation commands (process listing, file search, scheduled-task review, login history)
- Full cleanup afterward, removing test artifacts and accounts to restore the environment

## Why this matters
Understanding the mechanics of how a session gets established and used is what makes the defensive side meaningful — you can't reliably spot or investigate a compromise without knowing what one actually looks like on a system. This connects directly to the detection and incident response work I've done in other labs: SIEM-based threat hunting, HIDS/NIDS detection, and memory forensics all depend on recognizing the same kinds of artifacts this lab's blue-team exercise focused on.

---
*Completed in an isolated training lab environment. Payload build/deploy specifics intentionally omitted from this write-up.*
