# Ben Pham

Cybersecurity student in Tampa, Florida, building a portfolio of home-lab investigations, detection tests, and clear case notes.

## About me

I’m working toward my first IT support, cybersecurity internship, or entry-level SOC role. I’m completing the University of Florida’s 18-week Certified Cybersecurity Associate Program while pursuing a B.S. in Exercise Science at the University of South Florida.

I like figuring out what actually happened: tracing an alert back to the source event, checking the timeline, and explaining why I would close a case or keep investigating. My customer-service experience taught me to stay calm under pressure, communicate clearly, and follow through.

## Selected investigations

- **[Windows authentication through Wazuh](https://github.com/Benpham3466-cyb/Cybersecurity-Portfolio/blob/main/projects/windows-authentication-through-wazuh.md)** — Checked five alerts against Windows Security events and documented why the controlled account and login activity was a benign true positive.
- **[Sysmon collection and Wazuh detection testing](https://github.com/Benpham3466-cyb/Cybersecurity-Portfolio/blob/main/projects/wazuh-sysmon-detection-investigation.md)** — Verified event receipt separately from alert generation, tested a scoped custom rule, and preserved exported evidence with SHA-256 checks.
- **[Personal-mailbox phishing investigation](https://github.com/Benpham3466-cyb/Cybersecurity-Portfolio/blob/main/projects/personal-mailbox-phishing-investigation.md)** — Examined sender headers and billing-link destinations, reported the message as phishing, and documented what the email could not prove.
- **[Microsoft Sentinel and KQL](https://github.com/Benpham3466-cyb/Cybersecurity-Portfolio/blob/main/projects/sentinel-tag-change-investigation.md)** — Correlated Azure tag-change events with alerts and distinguished authorized activity from duplicate detections.

**[View the full cybersecurity portfolio](https://github.com/Benpham3466-cyb/Cybersecurity-Portfolio)** for write-ups, evidence, detection logic, and limitations.

## Tools and skills I’ve used

- **SIEM and endpoint logs:** Wazuh, Sysmon, Windows Security events, Microsoft Sentinel, KQL
- **Network and email analysis:** Wireshark, TCP/IP fundamentals, email headers, phishing indicators
- **Detection and file triage:** YARA rules tested on harmless samples, VirusTotal, SHA-256 verification
- **Systems:** PowerShell, Linux command line, macOS/osquery, local accounts and permissions, virtual machines
- **Reporting:** UTC timelines, evidence handling, concise case notes, and documented investigation limits

## Current project

I’m investigating a LokiBot sample in a network-disconnected Windows VM. I verified its hash against the source reference, inspected it in Ghidra, and saved Sysmon and Process Monitor recordings from the first execution. Next, I’m checking the process tree and recorded behavior. Sample-specific YARA/Sigma detections and the final report are still ahead.

My goal is to understand the evidence well enough to explain my decisions in my own words.

## Goals

I’m passionate about cybersecurity and eager to keep learning. I’m open to opportunities where I can contribute, learn from experienced teammates, and grow my knowledge and understanding of technology and security.
