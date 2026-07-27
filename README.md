# Azure Order Management Security Reference Architecture

## Overview

This repository presents a reference security architecture for a cloud-native Order Management Solution hosted on Microsoft Azure.

The solution demonstrates how enterprise security controls can be integrated across the identity, network, application, data, monitoring, and governance layers to protect business-critical applications processing sensitive information.

The architecture follows a defense-in-depth approach and incorporates Zero Trust principles, modern identity management, secure API design, DevSecOps practices, cloud-native security services, and centralized monitoring.

> **Disclaimer**
>
> This repository is intended for educational and portfolio purposes only. It is a reference architecture and does not represent any production environment or disclose confidential client information.

---

# Architecture Diagram

![Azure Order Management Security Architecture](images/architecture.png)

---

# Architecture Highlights

- Secure customer and administrator authentication
- Microsoft Entra ID and Microsoft Entra External ID (B2C)
- Conditional Access and Multi-Factor Authentication (MFA)
- Privileged Identity Management (PIM)
- Azure Front Door with Web Application Firewall (WAF)
- Azure DDoS Protection
- Azure API Management
- Azure Kubernetes Service (AKS)
- Azure Key Vault with Managed Identities
- Azure SQL Database with Transparent Data Encryption (TDE)
- Always Encrypted for highly sensitive data
- Azure Cosmos DB
- Azure Blob Storage
- SAP Integration Layer
- Microsoft Defender for Cloud
- Microsoft Sentinel
- Azure Monitor & Application Insights
- Microsoft Purview
- Azure DevOps with integrated DevSecOps security scanning

---

# Security Principles

This reference architecture is designed around the following principles:

- Zero Trust
- Defense in Depth
- Least Privilege Access
- Secure by Design
- Identity First Security
- Secure API Integration
- Data Protection
- Continuous Monitoring
- DevSecOps

---

# Technologies

| Category | Technologies |
|-----------|-------------|
| Identity | Microsoft Entra ID, Microsoft Entra External ID (B2C), MFA, Conditional Access, PIM |
| Network | Azure Front Door, WAF, Azure DDoS Protection, NSGs, Azure Firewall |
| Application | Azure API Management, AKS |
| Secrets | Azure Key Vault, Managed Identity |
| Data | Azure SQL, Cosmos DB, Blob Storage |
| Integration | SAP Integration Layer, Azure Functions |
| Monitoring | Microsoft Sentinel, Azure Monitor, Application Insights |
| Governance | Microsoft Purview |
| DevSecOps | Azure DevOps, Git, SAST, DAST, Secret Scanning, Image Scanning |


```

---

# Documentation

- [Architecture Overview](docs/Architecture-Overview.md)
- [Security Controls](docs/Security-Controls.md)

---

# License

This project is released under the MIT License.
