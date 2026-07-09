Title: ManageEngine PAM360

# ManageEngine PAM360

- ManageEngine PAM360 is a unified Privileged Access Management (PAM) solution that helps organizations secure, control, monitor, and automate privileged access across their entire IT infrastructure.
- PAM360 is to CyberArk what a different operating system is to the same computer.
- Both provide privileged account vaulting, password rotation, session management, auditing, RBAC, and integrations with AD/Entra ID.
- CyberArk is more modular and enterprise-centric, while PAM360 offers similar core PAM capabilities through a more unified platform and interface.

[Paste an image here]

> Key Features

- Enterprise Credential Vault
- Endpoint Privilege Management
- Privilege Elevation and Delegation Management
- Zero Trust Controls
- Secure Remote Access
- Universal Connectors
- Privileged Session Monitoring
- System Events and Keystroke Logging
- Context-Aware Event Correlation
- Privileged User Behavior Analytics
- Application Credential Security
- SSH Key Management
- SSL Certificate Management
- DevOps Protection
- Privileged Task Automation
- IT and Security Platform Integrations
- Business Continuity
- Audit and Compliance
- Comprehensive Reporting

> Modules in PAM360

- Primary Authentication

    - Local Authentication
    - Active Directory
    - Microsoft Entra ID
    - LDAP
    - RADIUS
    - Smart Card / PKI / Certificate

- Two-Factor Authentication

    - Google Authenticator
    - Microsoft Authenticator
    - RADIUS Authenticator
    - One-Time Password
    - RSA SecureID
    - Oracle Authenticator
    - DUO Security
    - Okta Verify
    - YuibiKey
    - Zoho OneAuth Authenticator

> Architecture

[Paste an image here]

> Components

- Interface and Access
- Databases
- Users
- Supported Resource Types

    - Operating System
    - Cisco Devices
    - Database Servers
    - Network Devices
    - Cloud Devices
    - File Stores
    - MQ Applications
    - Others

- Primary and Secondary Servers

    - Application Scaling
    - Secondary Server
    - Failover Service
    - Read-Only Server

> Ports and Protocols used

[Paste an image here]

## ManageEngine PAM360 — Explained Through a CyberArk Lens

```
Legend

PAM = Privileged Access Management
PSM = Privileged Session Management
JIT = Just-In-Time
RBAC = Role-Based Access Control
SSO = Single Sign-On

Check out more abbreviations at PAM360: Glossary of Terms and Abbreviations
```

| CyberArk | PAM360 |
| --- | --- |
| Digital Vault | Password Repository / Vault |
| Safe | Resource Groups / Resource Organization |
| CPM | Password Management & Rotation |
| PSM | Session Management & Recording |
| LDAP/AD | Integration	AD / Entra ID Integration |
| Vault Users | PAM360 Users & Roles |
| Platform | Resource Type / Password Policy |
| Account Onboarding | Resource Discovery & Onboarding |
| Dual Control | Approval Workflows |
| Session Recording | Session Audit & Playback |
| Central Policy | RBAC & Policy Configuration |

> Workflow Comparison

CyberArk

1. User authenticates.
2. CyberArk checks AD/LDAP.
3. User accesses a Safe.
4. CPM manages passwords.
5. PSM brokers and records sessions.
6. Audit logs are generated.

PAM360

1. User authenticates (often via Entra ID/AD).
2. PAM360 authorizes the user.
3. User accesses a vaulted resource.
4. PAM360 rotates passwords.
5. PAM360 brokers/records privileged sessions.
6. Audit logs are generated.

Key Difference

- CyberArk is a dedicated enterprise PAM suite with highly modular components (Vault, CPM, PSM, etc.).
- PAM360 provides the same core PAM capabilities—vaulting, password rotation, session management, JIT, integrations, and auditing—but packages them into a more unified platform with different terminology and workflows.

'Mindset: Don't learn PAM360 as a completely new discipline. Translate each CyberArk concept to its PAM360 equivalent. The vendor changes; the principles of privileged access management remain largely the same.'

---

# References

- ManageEngine PAM360 [>](https://www.manageengine.com/privileged-access-management/help/)
- Glossary of Terms and Abbreviations [>](https://www.manageengine.com/privileged-access-management/help/important_terms.html)
- Modules and Features in PAM360 [>](https://www.manageengine.com/privileged-access-management/help/checklist.html)
- PAM360 Architecture, Components, Ports and Protocols [>](https://www.manageengine.com/privileged-access-management/help/architecture.html)

---
