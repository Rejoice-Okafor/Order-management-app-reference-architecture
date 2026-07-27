# Security Controls

## Identity Security

| Control | Purpose |
|----------|---------|
| Microsoft Entra ID | Workforce identity management |
| Microsoft Entra External ID (B2C) | Customer identity management |
| Multi-Factor Authentication | Strengthens authentication |
| Conditional Access | Enforces contextual access policies |
| Privileged Identity Management | Just-In-Time administrative access |

---

## Network Security

| Control | Purpose |
|----------|---------|
| Azure Front Door | Global application entry point |
| Web Application Firewall | Protects against OWASP Top 10 attacks |
| Azure DDoS Protection | Mitigates denial-of-service attacks |
| Network Security Groups | Network traffic filtering |
| Azure Firewall | Network traffic inspection and control |

---

## Application Security

| Control | Purpose |
|----------|---------|
| Azure API Management | API authentication, authorization, throttling and monitoring |
| Azure Kubernetes Service | Secure hosting for containerized workloads |
| Managed Identity | Passwordless authentication between Azure resources |
| Azure Key Vault | Secure storage of secrets, certificates and encryption keys |

---

## Data Security

| Control | Purpose |
|----------|---------|
| Transparent Data Encryption | Encrypts databases at rest |
| Always Encrypted | Protects highly sensitive database columns |
| Azure SQL Database | Secure relational data storage |
| Azure Cosmos DB | Secure NoSQL data storage |
| Azure Blob Storage | Secure object storage |

---

## Monitoring and Detection

| Control | Purpose |
|----------|---------|
| Microsoft Sentinel | Security Information and Event Management (SIEM) |
| Azure Monitor | Infrastructure monitoring |
| Application Insights | Application performance monitoring |
| Log Analytics | Centralized log collection and querying |

---

## Cloud Security

| Control | Purpose |
|----------|---------|
| Microsoft Defender for Containers | Container runtime protection |
| Microsoft Defender for Storage | Storage threat detection |
| Microsoft Defender for Cosmos DB | Database threat protection |
| Microsoft Defender for DevOps | DevSecOps security posture management |

---

## Governance and Compliance

| Control | Purpose |
|----------|---------|
| Microsoft Purview | Data governance and compliance |
| Data Classification | Identification of sensitive information |
| Information Protection | Protection of confidential data |

---

## DevSecOps Controls

| Control | Purpose |
|----------|---------|
| Azure DevOps | Source control and CI/CD |
| Git Repository | Version control |
| SAST | Static code security testing |
| DAST | Dynamic application security testing |
| Secret Scanning | Detects exposed credentials |
| Container Image Scanning | Detects vulnerabilities in container images |

---

# Security Design Principles

The architecture implements multiple layers of security using the following principles:

- Zero Trust
- Defense in Depth
- Least Privilege Access
- Identity-First Security
- Secure by Design
- Continuous Monitoring
- DevSecOps
