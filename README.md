# Wazuh SIEM Home Lab

A hands-on cybersecurity project demonstrating the deployment of Wazuh SIEM on Ubuntu and the integration of a Windows endpoint for security monitoring.

## Project Overview

This project demonstrates practical experience implementing a Security Information and Event Management (SIEM) solution using Wazuh.

The lab covers:

- Wazuh installation on Ubuntu.
- Wazuh dashboard deployment and access.
- Windows endpoint agent installation.
- Agent registration and authentication.
- Endpoint connectivity verification.
- Security event monitoring.
- File Integrity Monitoring (FIM).

## Lab Environment

| Component | Purpose |
|---|---|
| Ubuntu Virtual Machine | Hosts the Wazuh installation and manager services |
| Wazuh Dashboard | Centralised security monitoring interface |
| Windows Endpoint | Monitored device running the Wazuh agent |
| Wazuh Agent | Collects and forwards endpoint security events |

## Implementation Walkthrough

### 1. Wazuh Installation on Ubuntu

Installed Wazuh on an Ubuntu virtual machine using the Wazuh installation assistant.

### 2. Dashboard Deployment

Accessed the Wazuh web dashboard and verified successful authentication.

### 3. Windows Agent Installation

Installed the Wazuh agent on a Windows endpoint to enable security monitoring.

### 4. Agent Registration

Configured the Windows agent to communicate with the Ubuntu-based Wazuh manager.

### 5. Agent Connectivity Verification

Verified that the Windows endpoint was successfully enrolled and appeared as active in the Wazuh dashboard.

### 6. Security Event Monitoring

Accessed endpoint events through the Wazuh dashboard and reviewed available security telemetry, including File Integrity Monitoring activity.

## Skills Demonstrated

- SIEM Implementation
- Ubuntu/Linux Administration
- Windows Endpoint Management
- Wazuh Agent Deployment
- Security Event Monitoring
- File Integrity Monitoring (FIM)
- Log Analysis
- Technical Documentation
- Troubleshooting

## Technologies Used

- Wazuh SIEM
- Ubuntu Linux
- Microsoft Windows
- Virtual Machines
- Wazuh Agent
- File Integrity Monitoring

## Documentation

**Installation and Implementation Guide**

[View Wazuh SIEM Installation Guide (Word)](./Documentation/Wazuh-SIEM-Home-Lab-Installation-Guide%20%281%29.docx)

## Repository Structure

```text
kagis-gif/
│
├── README.md
│
└── Documentation/
    └── Wazuh-SIEM-Home-Lab-Installation-Guide (1).docx
```

## Security Considerations

Before publishing this project:

- Remove passwords and installation credentials.
- Redact agent authentication keys and tokens.
- Review screenshots for sensitive network information.
- Avoid publishing confidential organisational information.

## Project Outcome

Successfully documented the installation of Wazuh on Ubuntu, dashboard access, Windows endpoint onboarding and endpoint event visibility.

This project demonstrates practical SIEM deployment and endpoint monitoring experience in a virtualised lab environment.

---

**Author:** Kagiso Lebambo

**Project:** Wazuh SIEM Home Lab

**GitHub:** https://github.com/kagi-gif/kagis-gif
