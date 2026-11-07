# Wazuh SIEM Home Lab

A hands-on home lab documenting the installation of Wazuh on an Ubuntu
virtual machine and the onboarding of a Windows endpoint for security
monitoring.

## Project overview

This project demonstrates a basic Wazuh SIEM deployment and endpoint
integration. The work documented in this repository includes:

-   Installing Wazuh on an Ubuntu virtual machine.
-   Accessing the Wazuh web dashboard.
-   Installing the Wazuh agent on a Windows endpoint.
-   Registering the Windows agent with the Wazuh manager.
-   Verifying that the endpoint is connected and running.
-   Viewing endpoint events in the Wazuh dashboard, including File
    Integrity Monitoring (FIM) events.

## Lab environment

  -----------------------------------------------------------------------
  Component                           Role
  ----------------------------------- -----------------------------------
  Ubuntu virtual machine              Hosts the Wazuh manager and
                                      dashboard

  Windows virtual machine/device      Endpoint monitored by the Wazuh
                                      agent

  Wazuh                               SIEM and endpoint monitoring
                                      platform
  -----------------------------------------------------------------------

> The accompanying installation document contains the screenshots and
> walkthrough captured during this lab.

## Implementation walkthrough

### 1. Install Wazuh on Ubuntu

Wazuh was installed on the Ubuntu virtual machine using the Wazuh
installation assistant. The installation process deployed the components
required for the dashboard-based lab.

### 2. Access the Wazuh dashboard

After installation, the Wazuh dashboard was opened in a web browser and
a successful login was verified.

### 3. Install the Windows agent

The Wazuh agent was installed on the Windows endpoint.

### 4. Register the endpoint

The Ubuntu Wazuh manager address and the agent
registration/authentication information were configured on the Windows
agent so that it could communicate with the manager.

### 5. Verify agent connectivity

The Windows endpoint appeared in the Wazuh dashboard as an enrolled,
active agent.

### 6. Review endpoint events

The lab documentation includes a view of events from the Windows
endpoint in the Wazuh dashboard, including file integrity monitoring
activity.

## Repository contents

``` text
wazuh-siem-home-lab/
├── README.md
├── Documentation/
│   ├── Installation-of-Wazuh-in-Ubuntu-VM.docx
│   └── Installation-of-Wazuh-in-Ubuntu-VM.pdf
└── Screenshots/
```

Add the `Documentation/` and `Screenshots/` folders and their files as
you upload them. If you use different filenames, update the links and
folder tree in this README.

## Skills demonstrated

-   SIEM deployment fundamentals
-   Ubuntu/Linux administration
-   Windows endpoint onboarding
-   Wazuh agent registration and connectivity verification
-   Security event monitoring
-   File Integrity Monitoring (FIM)
-   Technical documentation and troubleshooting

## Documentation

-   [Wazuh installation and Windows agent onboarding guide
    (PDF)](Documentation/Installation-of-Wazuh-in-Ubuntu-VM.pdf)
-   [Wazuh installation and Windows agent onboarding guide
    (Word)](Documentation/Installation-of-Wazuh-in-Ubuntu-VM.docx)

## Security and privacy

Before making this repository public, review every document and
screenshot. Remove or permanently redact:

-   Passwords, installation credentials, authentication keys and tokens.
-   Private or public IP addresses, hostnames, usernames or other
    environment details that you do not intend to disclose.
-   Any personal or organisation-sensitive information.

Do not publish agent authentication keys or installation passwords.
Redactions should be applied to the source document and screenshots, not
merely covered with shapes that can be removed.

## Project status

The documented lab covers Wazuh installation, dashboard access, Windows
agent onboarding and endpoint event visibility. Additional detections,
alert testing and response workflows can be added as the lab develops.

------------------------------------------------------------------------

**Author:** Kagiso Lebambo\
**Project:** Wazuh SIEM Home Lab

## Skills and Associated Projects

| Skill | Associated Project |
|---|---|
| SIEM Implementation | [Wazuh SIEM Home Lab](Documentation/Wazuh-SIEM-Home-Lab-Installation-Guide.docx) |
| Linux Administration | [Ubuntu Wazuh Installation](Documentation/Wazuh-SIEM-Home-Lab-Installation-Guide.docx) |
| Endpoint Monitoring | [Windows Agent Integration](Documentation/Wazuh-SIEM-Home-Lab-Installation-Guide.docx) |
| Security Event Analysis | [Wazuh Event Monitoring](Documentation/Wazuh-SIEM-Home-Lab-Installation-Guide.docx) |

## Project Repository

[View my Wazuh SIEM Home Lab on GitHub](https://github.com/kagis-gif/kagis-gif)
