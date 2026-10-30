# n8n Threat Intelligence Automation

## Overview

This project demonstrates a cybersecurity threat intelligence workflow built with n8n.

## Architecture

```text
Schedule Trigger
      ↓
HTTP Request (VirusTotal)
      ↓
AI Agent
      ↓
Email Notification
```

## Features

- Automated scheduling
- VirusTotal reputation lookup
- AI-powered threat analysis
- Email alerting

## Requirements

- n8n
- VirusTotal API Key
- Email credentials

## Configuration

Replace the following placeholders:

```text
YOUR_VIRUSTOTAL_API_KEY
YOUR_EMAIL_CREDENTIAL
recipient@example.com
```

## Workflow Import

1. Download the JSON workflow file.
2. Open n8n.
3. Import from JSON.
4. Configure credentials.
5. Activate workflow.

## Sample Output

```text
Threat Intelligence Report

Domain Name: example.com
Risk Level: Low

Summary:
No malicious or suspicious detections identified.

Recommended Action:
Continue monitoring.
```
