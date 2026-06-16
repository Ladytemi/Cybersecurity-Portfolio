# Microsoft Account Phishing Email

## Scenario Overview

This SOC Simulator investigation focused on an inbound phishing email impersonating Microsoft account security.

The email claimed that unusual sign-in activity had been detected on the recipient's Microsoft account and urged the user to review the activity through an external link.

## Investigation Process

The email was reviewed to determine whether it was legitimate or malicious.

Key findings included:

- Sender domain impersonated Microsoft
- The domain used character substitution: m1crosoftsupport.co
- The email used urgency and fear-based language
- The message contained an external login/review link
- The content attempted to trick the recipient into taking immediate action

## Findings

The email was confirmed as a phishing attempt designed to harvest user credentials through Microsoft brand impersonation.

## Classification

True Positive

## Escalation

Yes

## Outcome

The alert was escalated for further investigation and containment. Recommended actions included blocking the sender domain, searching for similar phishing emails, checking user interaction, and enforcing credential protection measures.

## Skills Demonstrated

- Email Analysis
- Phishing Detection
- IOC Identification
- Alert Triage
- Incident Reporting
- Escalation Procedures
