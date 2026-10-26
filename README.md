# Detecting "Disable Windows Event Logging" (MITRE ATT&CK T1562.002)

A threat-hunting and detection project implementing **MITRE CAR-2022-03-001**, which addresses the defense-evasion technique **T1562.002 – Impair Defenses: Disable Windows Event Logging**.

## Objective
Understand how attackers disable Windows event logging to evade detection, emulate the technique in a controlled lab, and build detection logic to catch it.

## Environment & Tools
- Windows VM (isolated lab)
- Sysmon (System Monitor) for enhanced logging
- MITRE ATT&CK framework & CAR analytics
- Windows Event Viewer / log analysis

## What I Did
1. **Analysis** — Researched and documented the main methods attackers use to disable or tamper with Windows Event Logging, mapping each to the ATT&CK technique.
2. **Emulation** — Safely emulated the logging-evasion activity on an isolated Windows VM.
3. **Detection** — Configured Sysmon and monitored for the indicators of the technique, developing detection logic to flag the defense-evasion behavior.
4. **Documentation** — Recorded the attacker methods, detection approach, and results.

## Detection Logic (summary)
[Add a short description of the Sysmon events / indicators you monitored — e.g., service state changes, registry modifications, or event-log clearing signals.]

## Key Findings / What I Learned
- [Add 2–3 concrete takeaways — e.g., which signals reliably indicated the technique, blind spots, how Sysmon complements native logging.]

## Screenshots
[Add screenshots of your Sysmon config, the emulation, and the detection — redact anything sensitive.]

---
*Educational lab project completed as part of Seneca Polytechnic's Cybersecurity & Threat Management program. No malware samples or sensitive data included.*
