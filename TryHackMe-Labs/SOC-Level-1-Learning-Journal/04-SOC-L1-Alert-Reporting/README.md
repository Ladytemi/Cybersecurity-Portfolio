# SOC L1 Alert Reporting

## Date Completed
June 2026

## Objective
Learn how Security Operations Center (SOC) analysts properly document investigations, escalate incidents to higher-tier analysts, and communicate findings during security events.

## Skills Demonstrated
- Alert Reporting
- Incident Documentation
- Escalation Procedures
- Security Communication
- Phishing Investigation
- Threat Analysis
- Incident Classification
- SIEM Alert Handling
- Security Case Management
- SOC Workflow Operations

## Scenario 1: Phishing Email Investigation

### Description
Investigated a phishing email that bypassed initial security controls and was later classified as malicious. The email spoofed Microsoft Support, contained a suspicious attachment, and failed SPF and DKIM validation checks.

### Findings
- Sender spoofing detected
- SPF validation failed
- DKIM validation failed
- Malicious attachment identified
- Social engineering indicators present

### Outcome
Classified as a True Positive phishing incident and documented findings using the Five Ws reporting methodology before escalation.

---

## Scenario 2: Active Directory Domain Discovery Activity

### Description
Investigated suspicious domain discovery commands executed on a Microsoft Exchange server.

### Findings
- Whois and domain enumeration commands executed
- Reverse shell activity detected
- Suspicious process chain identified
- IIS process linked to malicious execution
- Evidence of post-exploitation activity

### Outcome
Confirmed compromise and escalated to Level 2 analysts for incident response and containment.

---

## Key Lessons Learned
- Security investigations must be properly documented.
- Alert escalation is critical when additional expertise or remediation is required.
- Effective communication improves incident response efficiency.
- Reports should provide sufficient context for higher-tier analysts.
- Early identification and escalation reduce incident impact.

## Tools Used
- TryHackMe SOC Simulator
- SIEM Dashboard
- Incident Reporting Workflow
- Alert Escalation Process

## Outcome
Successfully completed multiple alert investigations, produced structured incident reports, and escalated confirmed security incidents according to SOC procedures.
