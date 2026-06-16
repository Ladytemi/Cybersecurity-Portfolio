# Amazon Delivery Phishing Email

## Scenario Overview

This SOC Simulator investigation focused on a phishing email impersonating Amazon. The email claimed that a package delivery failed and instructed the recipient to click a link to update shipping information.

## Investigation Process

The email was reviewed to determine whether it was legitimate or malicious.

Key findings included:

- Sender domain was amazon.biz instead of amazon.com
- Use of a shortened bit.ly URL
- Urgent language pressuring the recipient to act
- Brand impersonation of Amazon
- Request for user interaction through an external link

## Findings

The email was confirmed as a phishing attempt designed to trick users into visiting a malicious website and potentially disclose sensitive information.

## Classification

True Positive

## Escalation

Yes

## Outcome

The alert was escalated for further investigation and containment. Recommended actions include blocking the sender domain, reviewing user activity, and monitoring for additional phishing attempts.

## Skills Demonstrated

- Email Analysis
- Phishing Detection
- IOC Identification
- Alert Triage
- Incident Reporting
- Escalation Procedures
