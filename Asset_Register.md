<p align="center">
  <img src="https://hack23.github.io/cia-compliance-manager/icon-192.png" alt="Hack23 Logo" width="192" height="192">
</p>

<h1 align="center">💻 Hack23 AB — Asset Register</h1>

<p align="center">
  <strong>Comprehensive Asset Management Through Systematic Documentation</strong><br>
  <em>Enterprise-grade Asset Inventory Demonstrating Cybersecurity Excellence</em>
</p>

<div align="center" style="background-color: #fff3cd; border: 2px solid #ffc107; border-radius: 8px; padding: 16px; margin: 20px 0;">
  <h3>⚠️ REDACTED PUBLIC VERSION</h3>
  <p><strong>This is a redacted version for public transparency.</strong><br>
  Specific account details, identifiers, and sensitive configurations have been removed.<br>
  The framework and methodology remain intact to demonstrate our security practices.</p>
</div>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Owner-CEO-0A66C2?style=for-the-badge" alt="Owner"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-1.4-555?style=for-the-badge" alt="Version"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Effective-2025--11--05-success?style=for-the-badge" alt="Effective Date"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Review-Annual-orange?style=for-the-badge" alt="Review Cycle"/></a>
</p>

**Document Owner:** CEO | **Version:** 1.4 | **Last Updated:** 2025-11-05 (UTC)  
**Review Cycle:** Annual | **Next Review:** 2026-11-05

---

## 🎯 **Purpose Statement**

**Hack23 AB's** asset register demonstrates how **comprehensive asset management directly enables both security excellence and business transparency.** Our systematic asset documentation serves as both operational necessity and client demonstration of our cybersecurity consulting methodologies.

Scope: Company identities, SaaS/platform accounts, cloud accounts, domains, and intellectual property. Supplier posture and SLAs are authoritative in [SUPPLIER.md](./SUPPLIER.md). Open source transparency governance in [Open Source Policy](./Open_Source_Policy.md).

<p align="center">
  <a href="#-asset-landscape-overview">Overview</a> •
  <a href="#1-identities-and-accounts">Identities</a> •
  <a href="#2-saas-and-platforms-summary">SaaS</a> •
  <a href="#3-aws-organization-control-tower">AWS</a> •
  <a href="#4-domains">Domains</a> •
  <a href="#5-intellectual-property">IP</a> •
  <a href="#6-asset-risk-and-controls-high-level">Risk</a> •
  <a href="#7-change-log">Changelog</a>
</p>

## 🧭 Icon Legend
- 👤 Identity • 🔐 MFA • 🛠️ Platforms • 📝 Notes
- 🧩 Service • 🏢 Account/Org • 📦 Plan • ✅ Status
- ☁️ Cloud • 🐙 GitHub • 🏦 Banking • 🧾 Accounting • 💳 Payments
- 🔎 Search/SEO • ▶️ YouTube • 🦄 Product Hunt • 🎵 TikTok • ✖️ X
- 🌐 Domain • ©️ Intellectual Property • 💼 LinkedIn

---

## 🗺️ Asset Landscape (Overview)

```mermaid
%%{
  init: { 'theme': 'base', 'themeVariables': { 'primaryColor': '#bbdefb', 'lineColor': '#90caf9' } }
}%%
mindmap
  root((Company Assets))
    Identities
      Primary Identity Provider
      Development Platform Identity
      Cloud Platform Identity
    SaaS & Platforms
      Accounting Platform
      Banking Services
      Development Platform
      Payment Processing
      Marketing Channels
      Search Console Tools
    Cloud Organization
      Audit Account
      Log Archive Account
      Production Account
      Permission Management
    Domains
      Primary Domain
      Product Domain
    IP & Repositories
      Game Product
      Compliance Product
      Analytics Product
      Infrastructure Code
      Security Tools
```

## 1) Identities and Accounts

### 1.1 Human identities
| Category | Platforms | Security | Notes | Types |
|----------|-----------|----------|-------|--------|
| Executive Identity | Identity Provider • Development Platform • Cloud SSO | MFA Enabled | Centralized identity management | [![Executive](https://img.shields.io/badge/Process-Executive-gold?style=for-the-badge&logo=university&logoColor=black)](./CLASSIFICATION.md#business-process-types) |

### 1.2 Linked services (via Identity Provider)
| Service Category | Integration Type | Status | Security | Types |
|-----------------|------------------|---------|----------|--------|
| Accounting Platform | SSO Integration | Active ✅ | IdP Protected | [![Compliance](https://img.shields.io/badge/Type-Compliance_Platform-green?style=for-the-badge&logo=clipboard-check&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Finance](https://img.shields.io/badge/Process-Finance-darkblue?style=for-the-badge&logo=dollar-sign&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| Payment Processing | SSO Integration | Active ✅ | IdP Protected | [![API](https://img.shields.io/badge/Type-API_Services-purple?style=for-the-badge&logo=cloud&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Sales](https://img.shields.io/badge/Process-Sales-darkgreen?style=for-the-badge&logo=handshake&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| Search Analytics | Platform MFA | Active ✅ | MFA Required | [![Analytics](https://img.shields.io/badge/Type-Data_Analytics-orange?style=for-the-badge&logo=chart-line&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| Marketing Channels | SSO/Platform | Active ✅ | Various | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](./CLASSIFICATION.md#project-type-classifications) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| Professional Network | Platform Auth | Active ✅ | MFA Available | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=linkedin&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Executive](https://img.shields.io/badge/Process-Executive-gold?style=for-the-badge&logo=university&logoColor=black)](./CLASSIFICATION.md#business-process-types) |

### 1.3 Development platform account and integrations
| Category | Security | Integrations | Notes | Types |
|----------|----------|--------------|-------|--------|
| Development Platform | MFA Required | Multiple | Version control and CI/CD | [![DevTools](https://img.shields.io/badge/Type-Development_Tools-lightblue?style=for-the-badge&logo=wrench&logoColor=black)](./CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| Security Scanning | OAuth Integration | Active | SAST analysis | [![Security](https://img.shields.io/badge/Type-Security_Tools-darkblue?style=for-the-badge&logo=shield-alt&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| Compliance Scanning | OAuth Integration | Active | License and vulnerability scanning | [![Security](https://img.shields.io/badge/Type-Security_Tools-darkblue?style=for-the-badge&logo=shield-alt&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Legal](https://img.shields.io/badge/Process-Legal-darkred?style=for-the-badge&logo=balance-scale&logoColor=white)](./CLASSIFICATION.md#business-process-types) |

---

## 2) SaaS and Platforms (summary)
See SUPPLIER.md for detailed posture (costs, SLAs, risks).

| Service Category | Type | Security | Purpose | Classification |
|-----------------|------|----------|---------|----------------|
| Cloud Infrastructure | IaaS/PaaS | MFA + SSO | Mission critical infrastructure | [![Core](https://img.shields.io/badge/Type-Core_Infrastructure-red?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Availability Mission Critical](https://img.shields.io/badge/Availability-Mission_Critical-red?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#availability-levels) |
| Development Platform | SaaS | MFA Required | Version control, CI/CD | [![DevTools](https://img.shields.io/badge/Type-Development_Tools-lightblue?style=for-the-badge&logo=wrench&logoColor=black)](./CLASSIFICATION.md#project-type-classifications) [![Availability High](https://img.shields.io/badge/Availability-High-orange?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#availability-levels) |
| Banking Services | Financial | Bank MFA | Corporate banking | [![API](https://img.shields.io/badge/Type-API_Services-purple?style=for-the-badge&logo=cloud&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Availability High](https://img.shields.io/badge/Availability-High-orange?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#availability-levels) |
| Accounting Platform | SaaS | IdP (SSO) | Financial management | [![Compliance](https://img.shields.io/badge/Type-Compliance_Platform-green?style=for-the-badge&logo=clipboard-check&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Availability Moderate](https://img.shields.io/badge/Availability-Moderate-yellow?style=for-the-badge&logo=server&logoColor=black)](./CLASSIFICATION.md#availability-levels) |
| Content Creation | SaaS | Platform Auth | Marketing content generation | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](./CLASSIFICATION.md#project-type-classifications) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#availability-levels) |
| AI Services | API/SaaS | API Keys + MFA | Development assistance | [![API](https://img.shields.io/badge/Type-API_Services-purple?style=for-the-badge&logo=cloud&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Availability Moderate](https://img.shields.io/badge/Availability-Moderate-yellow?style=for-the-badge&logo=server&logoColor=black)](./CLASSIFICATION.md#availability-levels) |
| Payment Processing | SaaS | Platform MFA | Transaction processing | [![API](https://img.shields.io/badge/Type-API_Services-purple?style=for-the-badge&logo=cloud&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Availability Mission Critical](https://img.shields.io/badge/Availability-Mission_Critical-red?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#availability-levels) |
| Search Analytics | Free Tier | IdP MFA | SEO and analytics | [![Analytics](https://img.shields.io/badge/Type-Data_Analytics-orange?style=for-the-badge&logo=chart-line&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#availability-levels) |
| Marketing Channels | Free/Paid | Various | Social media presence | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](./CLASSIFICATION.md#project-type-classifications) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#availability-levels) |
| Security Tools | Free Tier | OAuth | Code analysis and compliance | [![Security](https://img.shields.io/badge/Type-Security_Tools-darkblue?style=for-the-badge&logo=shield-alt&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Availability High](https://img.shields.io/badge/Availability-High-orange?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#availability-levels) |

---

## 3) Cloud Organization

Cloud Provider: Enterprise multi-account organization with governance framework and SSO.

### 3.1 Account Structure
| Account Type | Purpose | Security Controls | Types |
|--------------|---------|-------------------|--------|
| Audit Account | Security and compliance logging | Immutable logs, restricted access | [![Core](https://img.shields.io/badge/Type-Core_Infrastructure-red?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| Log Archive | Centralized log storage | Write-only, retention policies | [![Core](https://img.shields.io/badge/Type-Core_Infrastructure-red?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| Production Account | Primary workloads | Full security stack | [![Core](https://img.shields.io/badge/Type-Core_Infrastructure-red?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](./CLASSIFICATION.md#business-process-types) |

### 3.2 Permission Management
| Permission Level | Scope | Controls |
|-----------------|-------|----------|
| Administrator Access | Limited accounts | MFA required, monitored |
| Power User Access | Development tasks | MFA required, audited |
| Read Only Access | Monitoring and review | MFA required |
| Service Catalog Admin | Service management | Restricted scope |
| Service Catalog User | Service consumption | Limited permissions |

### 3.3 Visual: Cloud Organization Structure
```mermaid
flowchart LR
  A["Organization Root"]
  AU["Audit Account"]
  LA["Log Archive"]
  PROD["Production Account"]

  A --> AU
  A --> LA
  A --> PROD

  subgraph "Permission Framework"
    PS1["Administrator"]
    PS2["Power User"]
    PS3["Read Only"]
    PS4["Service Admin"]
    PS5["Service User"]
  end

  AU --- PS1
  AU --- PS3
  PROD --- PS1
  PROD --- PS2
  PROD --- PS3
  PROD --- PS4
  PROD --- PS5

  classDef ct fill:#ffecb3,stroke:#ffa000,stroke-width:2px,color:#333;
  classDef acct fill:#e3f2fd,stroke:#42a5f5,color:#0d47a1;

  class A ct;
  class AU,LA,PROD acct;
```

### 3.4 DNS and Domain Security
- DNS provider: Enterprise DNS service with hosted zones
- DNSSEC: Enabled for all domains
- Security: Registrar locks, monitoring alerts configured

| Domain Category | Security | Status |
|----------------|----------|---------|
| Primary Domain | DNSSEC Enabled | Active ✅ |
| Product Domain | DNSSEC Enabled | Active ✅ |

### 3.5 Cloud Services Portfolio (27 Active Services)

#### Security & Compliance Services (8 Services)
| Service Type | Purpose | Classification | Status |
|-------------|---------|----------------|---------|
| Web Application Firewall | Application protection | [![Availability Mission Critical](https://img.shields.io/badge/A-Mission_Critical-red?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Security Posture Management | Centralized findings | [![Integrity Critical](https://img.shields.io/badge/I-Critical-red?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Threat Investigation | Security analysis | [![Confidentiality High](https://img.shields.io/badge/C-High-blue?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Vulnerability Assessment | Security scanning | [![Integrity Critical](https://img.shields.io/badge/I-Critical-red?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Threat Detection | Continuous monitoring | [![Confidentiality High](https://img.shields.io/badge/C-High-blue?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Compliance Monitoring | Policy enforcement | [![Integrity High](https://img.shields.io/badge/I-High-orange?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Data Discovery | Sensitive data scanning | [![Confidentiality Extreme](https://img.shields.io/badge/C-Extreme-black?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Audit Logging | Complete API tracking | [![Integrity Critical](https://img.shields.io/badge/I-Critical-red?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |

#### Core Infrastructure Services (11 Services)
| Service Type | Purpose | Classification | Status |
|-------------|---------|----------------|---------|
| Relational Database | Application data | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| DNS Management | Domain services | [![Availability Mission Critical](https://img.shields.io/badge/A-Mission_Critical-red?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Corporate Email | Business communication | [![Confidentiality High](https://img.shields.io/badge/C-High-blue?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Key Management | Encryption services | [![Confidentiality Extreme](https://img.shields.io/badge/C-Extreme-black?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Object Storage | Data and backups | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Network Isolation | Security boundaries | [![Integrity High](https://img.shields.io/badge/I-High-orange?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Archive Storage | Long-term retention | [![Availability Standard](https://img.shields.io/badge/A-Standard-lightgreen?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Content Delivery | Global distribution | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Serverless Compute | API functions | [![Integrity Critical](https://img.shields.io/badge/I-Critical-red?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Governance Framework | Multi-account management | [![Integrity Critical](https://img.shields.io/badge/I-Critical-red?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Identity Management | SSO and permissions | [![Confidentiality Extreme](https://img.shields.io/badge/C-Extreme-black?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |

#### Monitoring & Analytics Services (4 Services)
| Service Type | Purpose | Classification | Status |
|-------------|---------|----------------|---------|
| Cost Management | Financial analysis | [![Confidentiality Moderate](https://img.shields.io/badge/C-Moderate-yellow?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Event Monitoring | Automation triggers | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Log Monitoring | Metrics and alerts | [![Integrity High](https://img.shields.io/badge/I-High-orange?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Data Transfer | Network usage | N/A | ✅ Active |

#### Resilience & DR Services (4 Services)
| Service Type | Purpose | Classification | Status |
|-------------|---------|-----------------|--------|
| Resilience Management | Application resilience | [![Availability Mission Critical](https://img.shields.io/badge/A-Mission_Critical-red?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Fault Injection | Recovery testing | [![Integrity High](https://img.shields.io/badge/I-High-orange?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Backup Management | Centralized backups | [![Confidentiality High](https://img.shields.io/badge/C-High-blue?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |
| Backup Compliance | Backup reporting | [![Integrity High](https://img.shields.io/badge/I-High-orange?style=flat-square)](./CLASSIFICATION.md) | ✅ Active |

#### Planned Services (Q2-Q3 2025)
| Service Type | Purpose | Classification | Timeline |
|--------------|---------|----------------|----------|
| API Management | API development | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](./CLASSIFICATION.md) | Q2 2025 |
| NoSQL Database | User data storage | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](./CLASSIFICATION.md) | Q2 2025 |
| User Authentication | Product access | [![Confidentiality High](https://img.shields.io/badge/C-High-blue?style=flat-square)](./CLASSIFICATION.md) | Q3 2025 |
| Container Service | Microservices hosting | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](./CLASSIFICATION.md) | Q3 2025 |

### 3.6 Security Architecture

```mermaid
graph TB
    subgraph Detection["🔍 Detection Layer"]
        GD[Threat Detection]
        DT[Investigation]
        MC[Data Discovery]
    end
    
    subgraph Protection["🛡️ Protection Layer"]
        WAF[Web Protection]
        IN[Vulnerability Scan]
        KMS[Encryption]
    end
    
    subgraph Compliance["📋 Compliance Layer"]
        SH[Posture Management]
        CFG[Compliance Rules]
        CT[Audit Logs]
    end
    
    subgraph Infrastructure["🏗️ Infrastructure"]
        CT_ORG[Governance]
        IDC[SSO]
        VPC[Network Isolation]
    end
    
    GD --> SH
    DT --> SH
    MC --> SH
    IN --> SH
    CFG --> SH
    CT --> S3[Log Storage]
    CT --> GL[Archive]
    
    style Detection fill:#e8f5e9
    style Protection fill:#e3f2fd
    style Compliance fill:#fff3e0
    style Infrastructure fill:#fce4ec
```

---

## 4) Domains

| Domain Type | Owner | Status | Security | Types |
|------------|-------|---------|----------|--------|
| Primary Corporate | Company | Active ✅ | DNS Security Extensions | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](./CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](./CLASSIFICATION.md#business-process-types) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| Product Domain | Company | Active ✅ | DNS Security Extensions | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](./CLASSIFICATION.md#project-type-classifications) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](./CLASSIFICATION.md#business-process-types) [![Sales](https://img.shields.io/badge/Process-Sales-darkgreen?style=for-the-badge&logo=handshake&logoColor=white)](./CLASSIFICATION.md#business-process-types) |

---

## 5) Intellectual Property

Statement: All copyrights remain with the CEO and sole owner.

| Project Category | Type | Status | Project Classification | Process Types |
|-----------------|------|---------|------------------------|---------------|
| 🎮 Game Product | Open Source | Active | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](./CLASSIFICATION.md#project-type-classifications) | [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](./CLASSIFICATION.md#business-process-types) [![Sales](https://img.shields.io/badge/Process-Sales-darkgreen?style=for-the-badge&logo=handshake&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| 🛡️ Compliance Manager | Open Source | Active | [![Compliance](https://img.shields.io/badge/Type-Compliance_Platform-green?style=for-the-badge&logo=clipboard-check&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) | [![Legal](https://img.shields.io/badge/Process-Legal-darkred?style=for-the-badge&logo=balance-scale&logoColor=white)](./CLASSIFICATION.md#business-process-types) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| 🏛️ Analytics Platform | Open Source | Active | [![Analytics](https://img.shields.io/badge/Type-Data_Analytics-orange?style=for-the-badge&logo=chart-line&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) | [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| ☁️ Infrastructure Code | Open Source | Active | [![Core](https://img.shields.io/badge/Type-Core_Infrastructure-red?style=for-the-badge&logo=server&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) | [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](./CLASSIFICATION.md#business-process-types) |
| 🔍 Security Tools | Open Source | Active | [![Security](https://img.shields.io/badge/Type-Security_Tools-darkblue?style=for-the-badge&logo=shield-alt&logoColor=white)](./CLASSIFICATION.md#project-type-classifications) | [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](./CLASSIFICATION.md#business-process-types) |

---

## 5.1) Intellectual Property Rights (IPR) Handling

### 📋 IPR Framework

All intellectual property created by or for Hack23 AB is managed systematically to ensure legal protection, proper licensing, and secure disposal when necessary.

| IPR Category | Handling Requirements | Protection Measures | Disposal Method |
|--------------|----------------------|---------------------|-----------------|
| **Source Code** | Apache-2.0 license, copyright notices | GitHub private/public repos, code review, commit signing | Secure repository deletion with backup retention |
| **Documentation** | Creative Commons BY-SA 4.0 for public docs | Version control, review process | Standard file deletion after retention period |
| **Trademarks** | Brand guidelines, usage restrictions | Registered where applicable, monitoring | Transfer or abandonment per legal counsel |
| **Trade Secrets** | Need-to-know access, NDA requirements | Encryption, access controls, audit logging | Secure deletion per [Data Classification Policy](./Data_Classification_Policy.md) |
| **Patents** | Prior art documentation, invention disclosures | Legal filing if commercially valuable | Abandonment after evaluation |

### 🔒 IPR Protection Controls

- **Copyright Notices:** All source files include SPDX headers with copyright attribution
- **License Compliance:** FOSSA scanning ensures dependency license compatibility (see [Open Source Policy](./Open_Source_Policy.md))
- **Access Control:** IPR classified per [Classification Framework](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) with appropriate access restrictions
- **Secure Disposal:** High/Very High confidentiality IPR requires secure deletion with verification

### 📜 Third-Party IPR Management

| Third-Party IPR | Usage Rights | Compliance Verification | Review Frequency |
|----------------|--------------|------------------------|------------------|
| Open Source Dependencies | Per dependency license | FOSSA automated scanning | Every commit |
| Cloud Service IP | AWS Customer Agreement terms | Terms review during renewals | Annual |
| SaaS Platform Tools | Per service agreement | Terms acceptance documented | Semi-Annual |
| Stock Media | Royalty-free or licensed | License verification in Asset Register | Annual |

---

## 5.2) Asset Return and Termination Procedures

### 🎯 Purpose

This section implements ISO 27001 A.5.11 (Return of assets) and A.6.5 (Responsibilities after termination), ensuring systematic asset recovery and access revocation.

### 📋 Termination Checklist

#### **Immediate Actions (Within 24 Hours)**

| Asset Category | Return/Revocation Actions | Verification | Responsibility |
|----------------|--------------------------|--------------|----------------|
| **Physical Devices** | Mobile devices, laptops returned to CEO | Physical receipt + device wipe log | Departing individual + CEO |
| **Cloud Access** | AWS Identity Center access revoked | IAM logs reviewed | CEO |
| **Repository Access** | GitHub organization membership removed | Audit log confirmation | CEO |
| **Email Access** | WorkMail account disabled | Email forwarding configured if needed | CEO |
| **SaaS Access** | Google Workspace suspension | Admin console log | CEO |

#### **Within 7 Days**

| Asset Category | Return/Revocation Actions | Verification | Responsibility |
|----------------|--------------------------|--------------|----------------|
| **Credentials** | All passwords reset, MFA devices deregistered | Authentication logs reviewed | CEO |
| **VPN/Network** | VPN certificates revoked, firewall rules updated | Connection logs verified empty | CEO |
| **Documentation** | Company confidential documents returned/deleted | Confirmation statement signed | Departing individual |
| **IP/Trade Secrets** | Reminder of confidentiality obligations | Acknowledgment signed | Departing individual |

#### **Within 30 Days**

| Action | Completion Criteria | Documentation |
|--------|-------------------|---------------|
| Final backup verification | Confirm departing individual data archived per retention policy | Backup log entry |
| Security review | Review access logs for anomalous activity | Security review memo |
| NDA reminder | Send reminder of ongoing confidentiality obligations | Certified email |
| Exit interview | Document knowledge transfer and lessons learned | Exit interview notes |

### 🔐 Asset Classification and Return Priority

Based on [Classification Framework](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md):

| Asset Classification | Return Priority | Access Revocation SLA | Verification Method |
|---------------------|-----------------|----------------------|---------------------|
| [![Extreme](https://img.shields.io/badge/C-Extreme-black?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | 🔴 Critical - Immediate | 4 hours | Manual verification + automated scanning |
| [![Very High](https://img.shields.io/badge/C-Very_High-darkblue?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | 🟠 High - Same day | 24 hours | Automated log review |
| [![High](https://img.shields.io/badge/C-High-blue?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | 🟡 Medium - Within 3 days | 72 hours | Automated log review |
| [![Moderate](https://img.shields.io/badge/C-Moderate-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | 🟢 Standard - Within 7 days | 7 days | Quarterly access review |

### 📝 Termination Documentation

The following documentation is maintained for each termination:

- **Asset Return Receipt:** Physical confirmation of device returns
- **Access Revocation Log:** Timestamped log of all access removals
- **Data Archival Certificate:** Confirmation of data retention compliance
- **Confidentiality Reminder:** Acknowledgment of ongoing obligations
- **Final Security Review:** Post-termination security assessment

### 🔄 Integration with Other Policies

- **Access Control:** Immediate implementation of [Access Control Policy](./Access_Control_Policy.md) § Access Revocation procedures
- **Data Classification:** Secure handling per [Data Classification Policy](./Data_Classification_Policy.md) retention requirements
- **Mobile Devices:** Device wipe per [Mobile Device Management Policy](./Mobile_Device_Management_Policy.md) § Device Lifecycle

---


## 6) Asset Risk and Controls (high level)

### 6.1 Controls Overview (Mindmap)

```mermaid
%%{
  init: { 'theme': 'base', 'themeVariables': { 'primaryColor': '#c8e6c9', 'lineColor': '#66bb6a' } }
}%%
mindmap
  root((Controls))
    Identities
      MFA on all platforms
      Quarterly app reviews
      Passkeys where supported
      Single IdP strategy
    Cloud Security Services
      Security services active
      Threat detection
      Security posture management
      Data discovery
      Application protection
      Vulnerability scans
      Investigation tools
      Compliance rules
      Full audit trails
    Infrastructure Controls
      Governance framework
      SSO implementation
      Encryption everywhere
      Network isolation
      DNS security
      Versioning enabled
      Immutable backups
      Secure email
    SaaS Management
      Central IdP
      Integrated services
      Quarterly access audits
      Export procedures ready
      Alternative suppliers mapped
    Domains & DNS
      Hosted zones
      DNSSEC enabled
      Registrar locks active
      Auto-renewal configured
      Expiry alerts
    IP Protection
      Active repositories
      Open source licensing
      Copyright protection
      Compliance scanning
      Quality gates
```

### 6.2 SWOT — Comprehensive Asset Management

```mermaid
%%{
  init: { 'theme': 'base', 'themeVariables': { 'primaryColor': '#ffe0b2', 'lineColor': '#fb8c00' } }
}%%
mindmap
  root((SWOT Analysis))
    Strengths
      Cloud services deployed
      Dedicated security tools
      Multi-account architecture
      Full MFA coverage
      DNSSEC enabled
      Complete audit trails
      Encryption at rest
      Automated threat detection
      IP assets documented
    Weaknesses
      Single person dependency
      Legacy access methods
      No break glass procedure
      Limited DR testing
      Manual security reviews
      Multiple SaaS dependencies
      Single IdP dependency
    Opportunities
      Automation with APIs
      Implement policies
      Token rotation
      Serverless automation
      CI/CD pipelines
      API monetization
      NoSQL scaling
      User management systems
    Threats
      Supply chain attacks
      Zero day vulnerabilities
      Service outages
      Sophisticated phishing
      Compliance changes
      Third party breaches
      Domain hijacking
      IP theft attempts
```

### 6.3 Asset Coverage Matrix

```mermaid
%%{
  init: { 'theme': 'base', 'themeVariables': { 'primaryColor': '#e1f5fe', 'lineColor': '#0288d1' } }
}%%
mindmap
  root((Asset Coverage))
    Cloud Services
      Security Services
        Application Protection
        Threat Detection
        Investigation Tools
      Infrastructure Services
        Database Services
        DNS Management
        Email Services
      Monitoring Services
        Log Management
        Cost Management
        Event Monitoring
      Planned Services
        API Management
        Authentication
        Container Services
    SaaS Services
      Critical Services
        Development Platform
        Banking Services
        Payment Processing
      Marketing Services
        Social Media
        Search Tools
        Analytics
      Content Services
        Generation Tools
        Media Services
      Security Services
        Code Analysis
        Compliance Tools
    Domains
      Primary Domain
      Product Domains
    IP Assets
      Game Products
      Compliance Tools
      Analytics Platforms
      Infrastructure Code
      Security Tools
```

### 6.4 Risk-Based Control Priorities

```mermaid
%%{
  init: { 'theme': 'base', 'themeVariables': { 'primaryColor': '#fce4ec', 'lineColor': '#f48fb1' } }
}%%
mindmap
  root((Risk Priorities))
    Critical Risks
      Single point of failure
      Root account security
      Credential exposure
      Domain security
      IP protection
    High Risks  
      Supply chain security
      IdP dependency
      Data breach potential
      Compliance gaps
      Email security
    Medium Risks
      Cost management
      Service degradation
      Third party failures
      Documentation gaps
      Backup recovery
    Low Risks
      Content delays
      Social media issues
      Service limits
      Marketing tools
      Analytics disruption
```

### 6.5 Comprehensive Security Posture

```mermaid
graph LR
    subgraph "🔐 Identity & Access"
        ID1[Primary IdP with MFA]
        ID2[Dev Platform MFA]
        ID3[Cloud SSO MFA]
        ID4[Integrated Services]
    end
    
    subgraph "🛡️ Security Stack"
        SEC1[Security Services]
        SEC2[Audit Trails]
        SEC3[Governance]
        SEC4[Encryption]
    end
    
    subgraph "🌐 Web & Domains"
        WEB1[Primary Domain]
        WEB2[Product Domain]
        WEB3[DNS Security]
        WEB4[CDN Services]
    end
    
    subgraph "💼 Business Systems"
        BUS1[Banking Services]
        BUS2[Accounting Platform]
        BUS3[Payment Processing]
        BUS4[Corporate Email]
    end
    
    subgraph "🚀 Development"
        DEV1[Code Repositories]
        DEV2[IP Assets]
        DEV3[Serverless Functions]
        DEV4[CI/CD Pipeline]
    end
    
    ID1 --> ID4
    SEC1 --> SEC2
    SEC3 --> SEC4
    WEB3 --> WEB1
    WEB3 --> WEB2
    
    style ID1 fill:#c8e6c9
    style SEC1 fill:#bbdefb
    style WEB1 fill:#fff9c4
    style BUS1 fill:#ffccbc
    style DEV1 fill:#d1c4e9
```

---

**Document Control:**  
**Approved by:** James Pether Sörling, CEO  
**Distribution:** Public  
**Classification:** [![Confidentiality: Public](https://img.shields.io/badge/C-Public-lightgrey?style=flat-square)](./CLASSIFICATION.md#confidentiality-levels)  
**Effective Date:** 2025-11-05  
**Next Review:** 2026-11-05   
**Framework Compliance:** [![ISO 27001](https://img.shields.io/badge/ISO_27001-2022_Aligned-blue?style=flat-square&logo=iso&logoColor=white)](./CLASSIFICATION.md) [![NIST CSF 2.0](https://img.shields.io/badge/NIST_CSF-2.0_Aligned-green?style=flat-square&logo=nist&logoColor=white)](./CLASSIFICATION.md) [![CIS Controls](https://img.shields.io/badge/CIS_Controls-v8.1_Aligned-orange?style=flat-square&logo=cisecurity&logoColor=white)](./CLASSIFICATION.md)

