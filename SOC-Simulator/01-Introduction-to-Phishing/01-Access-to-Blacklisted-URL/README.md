# Access to Blacklisted External URL Blocked by Firewall

## Scenario Overview
A firewall alert was triggered after a user attempted to access an external URL that was listed in the organisation's threat intelligence blacklist.

The firewall successfully blocked the connection attempt, preventing communication with the potentially malicious destination.

## Investigation Summary
The alert was reviewed to determine whether the event represented a legitimate security concern.

Key findings included:

- Source IP: 10.20.2.17
- Destination IP: 67.199.248.11
- URL: http://bit.ly/3sHkX3da12340
- Protocol: TCP
- Application: Web Browsing
- Firewall Action: Blocked

The destination URL used a shortened link and matched an entry within the organisation's threat intelligence blacklist.

## Classification
True Positive

## Escalation
Yes

## Outcome
The connection was successfully blocked by the firewall. The alert was escalated for further investigation to determine whether the user endpoint had been exposed to phishing activity, malware, or unauthorised web activity.

## Skills Demonstrated
- Alert Triage
- Firewall Log Analysis
- Threat Intelligence Validation
- Incident Reporting
- Escalation Procedures
