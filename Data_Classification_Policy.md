<p align="center">
  <img src="https://hack23.com/icon-192.png" alt="Hack23 Logo" width="192" height="192">
</p>

<h1 align="center">🏷️ Hack23 AB — Data Classification Policy</h1>

<p align="center">
  <strong>🛡️ Systematic Information Handling Through Classification-Driven Protection</strong><br>
  <em>🎯 Enterprise-Grade Data Security Demonstrating Cybersecurity Excellence</em>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Owner-CEO-0A66C2?style=for-the-badge" alt="Owner"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-2.3-555?style=for-the-badge" alt="Version"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Effective-2026--01--25-success?style=for-the-badge" alt="Effective Date"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Review-Annual-orange?style=for-the-badge" alt="Review Cycle"/></a>
</p>

**📋 Document Owner:** CEO | **📄 Version:** 2.3 | **📅 Last Updated:** 2026-01-25 (UTC)  
**🔄 Review Cycle:** Annual | **⏰ Next Review:** 2027-01-25

---

## 🎯 **Purpose Statement**

**🏢 Hack23 AB's** data classification policy demonstrates how **🔧 systematic information handling directly enables both security excellence and operational transparency.** Our 📊 classification-driven data protection serves as both operational necessity and 👥 client demonstration of our cybersecurity consulting methodologies.

This policy establishes comprehensive data classification and handling requirements based on our [🏷️ Classification Framework](./CLASSIFICATION.md), ensuring information protection aligns with business value, regulatory obligations, and security objectives. Our 🌟 transparent approach to data classification showcases how methodical information management creates **🏆 competitive advantage** through protected innovations and **🤝 customer trust** via demonstrable privacy controls.

*— 👨‍💼 James Pether Sörling, CEO/Founder*

---

## 🔍 **Purpose & Scope**

### Purpose
This policy establishes the framework for classifying, labeling, handling, and protecting all information assets at Hack23 AB, ensuring appropriate security controls are applied based on business impact, regulatory requirements, and organizational risk appetite.

### Scope
This policy applies to:
- All information in any format (digital, physical, verbal)
- All systems documented in [💻 Asset Register](./Asset_Register.md)
- All data processed by applications and services
- All information shared with third parties per [🤝 Third Party Management](./Third_Party_Management.md)
- All employees, contractors, and authorized users

### Framework Integration
This policy implements the comprehensive classification methodology defined in [🏷️ Classification Framework](./CLASSIFICATION.md), covering:
- **CIA Triad Assessment:** Confidentiality, Integrity, and Availability requirements
- **Business Impact Analysis:** Financial, operational, reputational, and regulatory impact
- **RTO/RPO Classifications:** Recovery time and recovery point objectives
- **Risk Classifications:** Systematic risk level determination

---

## 🏗️ **Data Classification Framework Architecture**

### 📊 **Classification Methodology Integration**

Our data classification directly implements the [🏷️ Classification Framework](./CLASSIFICATION.md) methodology:

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#1565C0',
      'primaryTextColor': '#0D47A1',
      'lineColor': '#1565C0',
      'secondaryColor': '#4CAF50',
      'tertiaryColor': '#FF9800'
    }
  }
}%%
flowchart TD
    subgraph CIA["🔐 CIA Triad Assessment"]
        CONF["🔒 Confidentiality<br/>Public to Extreme"]
        INTEG["✅ Integrity<br/>Low to Critical"]
        AVAIL["⚡ Availability<br/>Standard to Mission Critical"]
    end
    
    subgraph IMPACT["📊 Business Impact Analysis"]
        FIN["💰 Financial Impact<br/>Negligible to Very High"]
        OPS["⚙️ Operational Impact<br/>No Impact to Critical"]
        REP["🤝 Reputational Impact<br/>No Impact to Critical"]
        REG["⚖️ Regulatory Impact<br/>No Impact to Critical"]
    end
    
    subgraph RECOVERY["🔄 Recovery Requirements"]
        RTO["⏰ Recovery Time<br/>Instant to Standard"]
        RPO["💾 Recovery Point<br/>Zero Loss to Extended"]
    end
    
    subgraph CONTROLS["🛡️ Security Controls"]
        ENCRYPTION["🔒 Encryption Level"]
        ACCESS["🔑 Access Control"]
        MONITORING["📊 Monitoring Level"]
        BACKUP["💾 Backup Strategy"]
    end
    
    CONF --> ENCRYPTION
    INTEG --> MONITORING
    AVAIL --> BACKUP
    FIN --> ACCESS
    OPS --> BACKUP
    REP --> MONITORING
    REG --> ACCESS
    RTO --> BACKUP
    RPO --> BACKUP
    
    style CIA fill:#1565C0
    style IMPACT fill:#4CAF50
    style RECOVERY fill:#FF9800
    style CONTROLS fill:#7B1FA2
```

### 🎯 **Data Classification Levels**

Based on [🏷️ Classification Framework](./CLASSIFICATION.md) confidentiality levels:

| Classification Level | Business Justification | Example Data Types | Handling Requirements |
|---------------------|------------------------|-------------------|----------------------|
| [![Extreme](https://img.shields.io/badge/Confidentiality-Extreme-black?style=for-the-badge&logo=shield&logoColor=white)](./CLASSIFICATION.md#confidentiality-levels) | Catastrophic damage if disclosed | HSM keys, critical authentication tokens | Hardware security modules, air-gapped systems |
| [![Very High](https://img.shields.io/badge/Confidentiality-Very_High-darkblue?style=for-the-badge&logo=shield&logoColor=white)](./CLASSIFICATION.md#confidentiality-levels) | Severe business impact | Financial data, customer PII, security configurations | AES-256 + CMK, strict access control, audit logging |
| [![High](https://img.shields.io/badge/Confidentiality-High-blue?style=for-the-badge&logo=shield&logoColor=white)](./CLASSIFICATION.md#confidentiality-levels) | Significant business impact | Source code, business plans, internal communications | AES-256 encryption, role-based access, monitoring |
| [![Moderate](https://img.shields.io/badge/Confidentiality-Moderate-orange?style=for-the-badge&logo=shield&logoColor=white)](./CLASSIFICATION.md#confidentiality-levels) | Moderate business impact | System logs, operational metrics, vendor agreements | Standard encryption, basic access control |
| [![Low](https://img.shields.io/badge/Confidentiality-Low-yellow?style=for-the-badge&logo=shield&logoColor=black)](./CLASSIFICATION.md#confidentiality-levels) | Minor business impact | Public documentation drafts, general communications | Basic protection, standard access |
| [![Public](https://img.shields.io/badge/Confidentiality-Public-lightgrey?style=for-the-badge&logo=shield&logoColor=black)](./CLASSIFICATION.md#confidentiality-levels) | No confidentiality requirement | Marketing materials, public policies, open source code | Public disclosure appropriate, integrity protection |

---

## 🔐 **CIA Triad Implementation**

### 🔒 **Confidentiality Requirements**

Implementation of confidentiality controls per [🏷️ Classification Framework](./CLASSIFICATION.md):

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#7B1FA2',
      'primaryTextColor': '#4A148C',
      'lineColor': '#7B1FA2',
      'secondaryColor': '#4CAF50',
      'tertiaryColor': '#FFC107'
    }
  }
}%%
graph TD
    subgraph EXTREME["🔴 Extreme Classification"]
        HSM["🔐 Hardware Security Modules"]
        AIRGAP["🏝️ Air-Gapped Systems"]
        BIOMETRIC["👁️ Biometric Authentication"]
    end
    
    subgraph VERYHIGH["🔵 Very High Classification"]
        CMK["🔑 Customer Managed Keys"]
        MFA["🛡️ Multi-Factor Authentication"]
        AUDIT["📋 Comprehensive Audit Logging"]
    end
    
    subgraph HIGH["🟡 High Classification"]
        AES256["🔒 AES-256 Encryption"]
        RBAC["👥 Role-Based Access Control"]
        MONITORING["📊 Activity Monitoring"]
    end
    
    subgraph MODERATE["🟠 Moderate Classification"]
        STANDARD["🔐 Standard Encryption"]
        BASIC["🔑 Basic Access Control"]
        LOGGING["📝 Standard Logging"]
    end
    
    subgraph LOW["🟢 Low/Public Classification"]
        MINIMAL["🔓 Minimal Protection"]
        INTEGRITY["✅ Integrity Verification"]
        PUBLIC["🌟 Public Disclosure Ready"]
    end
    
    style EXTREME fill:#D32F2F
    style VERYHIGH fill:#1565C0
    style HIGH fill:#FF9800
    style MODERATE fill:#FFC107
    style LOW fill:#4CAF50
```

#### **Confidentiality Control Matrix**

| Classification | Access Control | Encryption | Authentication | Monitoring | Retention |
|---------------|---------------|------------|----------------|------------|-----------|
| **Extreme** | Need-to-know only, hardware tokens | HSM-based, quantum-resistant prep | Hardware MFA + biometrics | Real-time alerts, tamper detection | Secure destruction, legal hold |
| **Very High** | Strict RBAC, manager approval | AES-256 + CMK, key rotation | Hardware MFA required | Comprehensive logging, SIEM alerts | Encrypted archives, compliance retention |
| **High** | Role-based, documented justification | AES-256, managed keys | MFA required | Activity monitoring, periodic review | Standard retention, secure deletion |
| **Moderate** | Group-based, supervisor approval | Standard encryption | Platform authentication | Basic monitoring, log retention | Business retention, standard deletion |
| **Low** | General access, self-service | Minimal encryption | Standard authentication | Minimal monitoring | Standard retention |
| **Public** | Open access appropriate | Integrity protection only | No authentication required | Optional logging |

### ✅ **Integrity Requirements**

Data integrity controls aligned with [🏷️ Classification Framework](./CLASSIFICATION.md):

#### **Integrity Level Matrix**

| Integrity Level | Control Requirements | Implementation | Validation Frequency |
|-----------------|---------------------|----------------|---------------------|
| [![Critical](https://img.shields.io/badge/Integrity-Critical-red?style=flat-square)](./CLASSIFICATION.md) | Immutable storage, digital signatures, real-time validation | Blockchain/tamper-evident systems | Continuous |
| [![High](https://img.shields.io/badge/Integrity-High-orange?style=flat-square)](./CLASSIFICATION.md) | Checksums, version control, audit trails | Database constraints, change logging | Daily |
| [![Moderate](https://img.shields.io/badge/Integrity-Moderate-yellow?style=flat-square)](./CLASSIFICATION.md) | Basic validation, backup verification | File integrity monitoring | Weekly |
| [![Low](https://img.shields.io/badge/Integrity-Low-lightgreen?style=flat-square)](./CLASSIFICATION.md) | Standard backup, basic validation | Standard file systems | Monthly |

### ⚡ **Availability Requirements**

Availability controls per [🏷️ Classification Framework](./CLASSIFICATION.md):

#### **Availability Level Implementation**

| Availability Level | Uptime Target | Architecture | Backup Strategy | Recovery Testing |
|-------------------|---------------|--------------|----------------|------------------|
| [![Mission Critical](https://img.shields.io/badge/Availability-Mission_Critical-red?style=flat-square)](./CLASSIFICATION.md) | 99.99%+ | Multi-region, active-active | Real-time replication | Monthly |
| [![High](https://img.shields.io/badge/Availability-High-orange?style=flat-square)](./CLASSIFICATION.md) | 99.9% | Multi-AZ, load balanced | Hourly backups | Quarterly |
| [![Moderate](https://img.shields.io/badge/Availability-Moderate-yellow?style=flat-square)](./CLASSIFICATION.md) | 99.5% | Standard redundancy | Daily backups | Semi-annual |
| [![Low](https://img.shields.io/badge/Availability-Low-lightgreen?style=flat-square)](./CLASSIFICATION.md) | 99% | Basic deployment | Weekly backups | Annual |
| [![Standard](https://img.shields.io/badge/Availability-Standard-lightgrey?style=flat-square)](./CLASSIFICATION.md) | Best effort | Single instance | Manual backups | As needed |

---

## 📊 **Business Impact-Driven Classification**

### 💰 **Financial Impact Classifications**

Based on [🏷️ Classification Framework](./CLASSIFICATION.md#financial-impact-levels):

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#4CAF50',
      'primaryTextColor': '#2E7D32',
      'lineColor': '#4CAF50',
      'secondaryColor': '#1565C0',
      'tertiaryColor': '#FF9800'
    }
  }
}%%
pie title 💰 Financial Impact Distribution by Data Category
    "Very High (>$10K/day)" : 15
    "High ($1K-5K/day)" : 25
    "Moderate ($500-1K/day)" : 30
    "Low (<$500/day)" : 20
    "Negligible" : 10
```

#### **Financial Impact Control Requirements**

| Impact Level | Example Data Types | Protection Requirements | Incident Response |
|-------------|-------------------|------------------------|-------------------|
| [![Very High](https://img.shields.io/badge/Financial-Very_High_(>$10K/day)-darkred?style=flat-square)](./CLASSIFICATION.md#financial-impact-levels) | Banking credentials, payment processing data | HSM encryption, real-time monitoring | Immediate escalation, executive notification |
| [![High](https://img.shields.io/badge/Financial-High_($1K--5K/day)-orange?style=flat-square)](./CLASSIFICATION.md#financial-impact-levels) | Customer financial data, accounting records | Strong encryption, audit logging | <15 min response, stakeholder notification |
| [![Moderate](https://img.shields.io/badge/Financial-Moderate_($500--1K/day)-yellow?style=flat-square)](./CLASSIFICATION.md#financial-impact-levels) | Vendor contracts, pricing information | Standard encryption, access control | <1 hour response, management notification |
| [![Low](https://img.shields.io/badge/Financial-Low_(<$500/day)-lightgreen?style=flat-square)](./CLASSIFICATION.md#financial-impact-levels) | General business correspondence | Basic protection | <4 hour response |
| [![Negligible](https://img.shields.io/badge/Financial-Negligible-lightgrey?style=flat-square)](./CLASSIFICATION.md#financial-impact-levels) | Public information, marketing materials | Integrity protection only | Standard process |

### ⚙️ **Operational Impact Classifications**

Implementation per [🏷️ Classification Framework](./CLASSIFICATION.md#operational-impact-levels):

#### **Operational Impact Control Matrix**

| Impact Level | Service Disruption | Data Requirements | Recovery Priority |
|-------------|-------------------|-------------------|-------------------|
| [![Critical](https://img.shields.io/badge/Operational-Critical_(Complete_outage)-red?style=flat-square)](./CLASSIFICATION.md#operational-impact-levels) | Complete service failure | Mission-critical systems data | Immediate recovery, all resources |
| [![High](https://img.shields.io/badge/Operational-High_(Major_degradation)-orange?style=flat-square)](./CLASSIFICATION.md#operational-impact-levels) | Significant functionality loss | Core business process data | High priority, dedicated resources |
| [![Moderate](https://img.shields.io/badge/Operational-Moderate_(Partial_impact)-yellow?style=flat-square)](./CLASSIFICATION.md#operational-impact-levels) | Limited functionality impact | Supporting system data | Standard priority, available resources |
| [![Low](https://img.shields.io/badge/Operational-Low_(Minor_inconvenience)-lightgreen?style=flat-square)](./CLASSIFICATION.md#operational-impact-levels) | Minor inconvenience | Non-essential system data | Low priority, scheduled recovery |
| [![No Impact](https://img.shields.io/badge/Operational-No_Impact-lightgrey?style=flat-square)](./CLASSIFICATION.md#operational-impact-levels) | No operational effect | Archive/reference data | Best effort recovery |

### 🤝 **Reputational Impact Classifications**

Reputational protection per [🏷️ Classification Framework](./CLASSIFICATION.md#reputational-impact-levels):

#### **Reputational Impact Response Matrix**

| Impact Level | Exposure Risk | Communication Requirements | Media Response |
|-------------|---------------|---------------------------|----------------|
| [![Critical](https://img.shields.io/badge/Reputational-Critical_(International_media)-red?style=flat-square)](./CLASSIFICATION.md#reputational-impact-levels) | Global media attention | Executive spokesperson, PR firm | Proactive media strategy |
| [![High](https://img.shields.io/badge/Reputational-High_(National_coverage)-orange?style=flat-square)](./CLASSIFICATION.md#reputational-impact-levels) | National news coverage | Official statement, customer notification | Reactive media response |
| [![Moderate](https://img.shields.io/badge/Reputational-Moderate_(Industry_attention)-yellow?style=flat-square)](./CLASSIFICATION.md#reputational-impact-levels) | Industry publication coverage | Stakeholder communication | Industry engagement |
| [![Low](https://img.shields.io/badge/Reputational-Low_(Limited_visibility)-lightgreen?style=flat-square)](./CLASSIFICATION.md#reputational-impact-levels) | Limited public awareness | Internal communication | Monitor discussion |
| [![No Impact](https://img.shields.io/badge/Reputational-No_Impact-lightgrey?style=flat-square)](./CLASSIFICATION.md#reputational-impact-levels) | No reputational risk | Standard processes | No special action |

### ⚖️ **Regulatory Impact Classifications**

Compliance requirements per [🏷️ Classification Framework](./CLASSIFICATION.md#regulatory-impact-levels):

#### **Regulatory Impact Compliance Matrix**

| Impact Level | Legal Consequences | Compliance Actions | Reporting Requirements |
|-------------|-------------------|-------------------|----------------------|
| [![Critical](https://img.shields.io/badge/Regulatory-Critical_(Criminal_charges)-red?style=flat-square)](./CLASSIFICATION.md#regulatory-impact-levels) | Criminal prosecution risk | Legal counsel, immediate remediation | Mandatory breach notification, regulatory reporting |
| [![High](https://img.shields.io/badge/Regulatory-High_(Significant_fines)-orange?style=flat-square)](./CLASSIFICATION.md#regulatory-impact-levels) | Significant financial penalties | Compliance review, process improvement | Formal reporting, corrective action plans |
| [![Moderate](https://img.shields.io/badge/Regulatory-Moderate_(Minor_penalties)-yellow?style=flat-square)](./CLASSIFICATION.md#regulatory-impact-levels) | Administrative penalties | Policy review, staff training | Standard reporting, documentation |
| [![Low](https://img.shields.io/badge/Regulatory-Low_(Warnings)-lightgreen?style=flat-square)](./CLASSIFICATION.md#regulatory-impact-levels) | Warning notices | Process documentation | Routine compliance checks |
| [![No Impact](https://img.shields.io/badge/Regulatory-No_Impact-lightgrey?style=flat-square)](./CLASSIFICATION.md#regulatory-impact-levels) | No regulatory implications | Standard processes | No special requirements |

---

## 🔄 **Recovery Time and Point Objectives**

### ⏰ **RTO Classifications Implementation**

Based on [🏷️ Classification Framework](./CLASSIFICATION.md#rto-classifications):

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#FF9800',
      'primaryTextColor': '#F57C00',
      'lineColor': '#FF9800',
      'secondaryColor': '#4CAF50',
      'tertiaryColor': '#1565C0'
    }
  }
}%%
gantt
    title ⏰ RTO Classification Timeline
    dateFormat X
    axisFormat %s
    
    section Critical
    Instant (0-5min)    :done, instant, 0, 5
    Critical (5-60min)  :done, critical, 0, 60
    
    section High Priority
    High (1-4hrs)       :active, high, 0, 240
    
    section Standard
    Medium (4-24hrs)    :medium, 0, 1440
    Low (24-72hrs)      :low, 0, 4320
    Standard (>72hrs)   :standard, 0, 10080
```

#### **RTO Implementation Requirements**

| RTO Classification | Technical Architecture | Staffing | Testing Frequency |
|-------------------|------------------------|----------|-------------------|
| [![Instant](https://img.shields.io/badge/RTO-Instant-red?style=flat-square)](./CLASSIFICATION.md#rto-classifications) | Active-active, automatic failover | 24/7 on-call | Weekly |
| [![Critical](https://img.shields.io/badge/RTO-Critical-orange?style=flat-square)](./CLASSIFICATION.md#rto-classifications) | Hot standby, rapid activation | On-call response | Monthly |
| [![High](https://img.shields.io/badge/RTO-High-yellow?style=flat-square)](./CLASSIFICATION.md#rto-classifications) | Warm standby, documented procedures | Business hours response | Quarterly |
| [![Medium](https://img.shields.io/badge/RTO-Medium-lightgreen?style=flat-square)](./CLASSIFICATION.md#rto-classifications) | Cold backup, standard recovery | Standard business processes | Semi-annual |
| [![Low](https://img.shields.io/badge/RTO-Low-lightblue?style=flat-square)](./CLASSIFICATION.md#rto-classifications) | Backup restoration, planned recovery | Scheduled maintenance | Annual |
| [![Standard](https://img.shields.io/badge/RTO-Standard-lightgrey?style=flat-square)](./CLASSIFICATION.md#rto-classifications) | Best effort recovery | As resources available | As needed |

### 💾 **RPO Classifications Implementation**

Based on [🏷️ Classification Framework](./CLASSIFICATION.md#rpo-classifications):

#### **RPO Data Protection Matrix**

| RPO Classification | Backup Frequency | Replication Method | Validation |
|-------------------|-----------------|-------------------|------------|
| [![Zero Loss](https://img.shields.io/badge/RPO-Zero_Loss-red?style=flat-square)](./CLASSIFICATION.md#rpo-classifications) | Synchronous replication | Real-time mirroring | Continuous |
| [![Near Real-time](https://img.shields.io/badge/RPO-Near_Real--time-orange?style=flat-square)](./CLASSIFICATION.md#rpo-classifications) | Every 15 minutes | Asynchronous replication | Real-time monitoring |
| [![Hourly](https://img.shields.io/badge/RPO-Hourly-lightgreen?style=flat-square)](./CLASSIFICATION.md#rpo-classifications) | Every hour | Log shipping | Hourly validation |
| [![Daily](https://img.shields.io/badge/RPO-Daily-lightblue?style=flat-square)](./CLASSIFICATION.md#rpo-classifications) | Daily snapshots | Scheduled backups | Daily verification |
| [![Extended](https://img.shields.io/badge/RPO-Extended-lightgrey?style=flat-square)](./CLASSIFICATION.md#rpo-classifications) | Weekly/monthly | Archive backups | Periodic testing |

---

## 🛡️ **Data Handling Procedures**

### 📋 **Classification Process Workflow**

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#1565C0',
      'primaryTextColor': '#1565C0',
      'lineColor': '#1565C0',
      'secondaryColor': '#4CAF50',
      'tertiaryColor': '#FFC107'
    }
  }
}%%
flowchart TD
    START["📝 Data Creation/Receipt"] --> IDENTIFY["🔍 Data Identification"]
    IDENTIFY --> CIA_ASSESS["🔐 CIA Assessment"]
    CIA_ASSESS --> IMPACT_ASSESS["📊 Business Impact Assessment"]
    IMPACT_ASSESS --> RECOVERY_ASSESS["🔄 Recovery Assessment"]
    RECOVERY_ASSESS --> CLASSIFY{"🏷️ Classification Decision"}
    
    CLASSIFY -->|Extreme/Very High| CRITICAL_HANDLE["🔴 Critical Handling"]
    CLASSIFY -->|High/Moderate| STANDARD_HANDLE["🟡 Standard Handling"]
    CLASSIFY -->|Low/Public| BASIC_HANDLE["🟢 Basic Handling"]
    
    CRITICAL_HANDLE --> LABEL["🏷️ Apply Labels"]
    STANDARD_HANDLE --> LABEL
    BASIC_HANDLE --> LABEL
    
    LABEL --> CONTROLS["🛡️ Apply Controls"]
    CONTROLS --> MONITOR["📊 Monitor & Review"]
    MONITOR --> REVIEW{"🔍 Periodic Review"}
    
    REVIEW -->|Changes Required| IDENTIFY
    REVIEW -->|No Changes| CONTINUE["✅ Continue Current Classification"]
    
    style START fill:#1565C0
    style CLASSIFY fill:#FFC107
    style CRITICAL_HANDLE fill:#D32F2F
    style STANDARD_HANDLE fill:#FF9800
    style BASIC_HANDLE fill:#4CAF50
```

### 🏷️ **Labeling Standards**

#### **Digital Data Labeling**
All digital files and databases must include classification metadata:

```yaml
Classification_Metadata:
  confidentiality: "Very High"
  integrity: "High" 
  availability: "Mission Critical"
  financial_impact: "High"
  operational_impact: "Critical"
  reputational_impact: "Moderate"
  regulatory_impact: "High"
  rto: "Critical"
  rpo: "Near Real-time"
  owner: "James Pether Sörling"
  classification_date: "2025-08-31"
  review_date: "2026-08-31"
  retention_period: "7 years"
  legal_hold: false
```

#### **Physical Document Labeling**
Physical documents require clear classification markings:

| Classification | Header/Footer Marking | Color Code | Handling Instructions |
|---------------|----------------------|------------|----------------------|
| **Extreme** | `EXTREME - HSM ONLY` | Black | Hardware security required |
| **Very High** | `VERY HIGH CONFIDENTIAL` | Dark Blue | Restricted access, MFA required |
| **High** | `HIGH CONFIDENTIAL` | Blue | Controlled access, authorization required |
| **Moderate** | `MODERATE CONFIDENTIAL` | Orange | Standard business controls |
| **Low** | `LOW CONFIDENTIAL` | Yellow | Basic protection required |
| **Public** | `PUBLIC` or no marking | Green | Public disclosure appropriate |

### 📦 **Data Storage Requirements**

#### **Storage Controls by Classification**

| Classification | Storage Location | Encryption | Access Control | Backup Requirements |
|---------------|-----------------|------------|---------------|-------------------|
| **Extreme** | Air-gapped systems, HSM | Hardware encryption | Biometric + token | Real-time mirroring |
| **Very High** | Encrypted cloud storage | AES-256 + CMK | MFA + approval | Cross-region replication |
| **High** | Secure cloud storage | AES-256 | MFA required | Daily encrypted backups |
| **Moderate** | Standard cloud storage | Service encryption | RBAC | Standard backups |
| **Low** | Standard storage | Basic encryption | Group access | Weekly backups |
| **Public** | Public repositories | Integrity protection | Open access | Version control |

### 🔄 **Data Transmission Security**

#### **Transmission Controls Matrix**

| Classification | Transport Method | Encryption | Authentication | Logging |
|---------------|-----------------|------------|----------------|---------|
| **Extreme** | Secure courier, air-gapped transfer | Physical security | Chain of custody | Complete audit trail |
| **Very High** | TLS 1.3, secure channels | End-to-end encryption | Certificate + MFA | Comprehensive logging |
| **High** | TLS 1.2+, VPN | Transport encryption | Certificate authentication | Standard logging |
| **Moderate** | TLS, secure protocols | Standard encryption | Platform authentication | Basic logging |
| **Low** | Standard protocols | Basic encryption | Standard authentication | Minimal logging |
| **Public** | Any method | Integrity protection | No authentication required | Optional logging |

### 🗑️ **Data Retention and Disposal**

#### **Retention Schedule by Data Type**

| Data Category | Legal Requirement | Business Need | Total Retention | Disposal Method |
|---------------|------------------|---------------|----------------|----------------|
| **Financial Records** | 7 years (Swedish law) | 7 years | 7 years | Secure deletion, certificate |
| **Customer Data** | GDPR retention limits | Business relationship + 2 years | Per GDPR | GDPR-compliant deletion |
| **Employee Records** | 3 years post-employment | 5 years | 5 years | Secure deletion |
| **Contracts** | Contract term + 7 years | Contract term + 7 years | Statute of limitations | Secure archiving |
| **Security Logs** | 1 year minimum | 3 years | 3 years | Automated purging |
| **Operational Data** | No requirement | 2 years | 2 years | Standard deletion |
| **Public Information** | No requirement | Indefinite | Indefinite | No special disposal |

#### **Secure Disposal Procedures**

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#7B1FA2',
      'primaryTextColor': '#4A148C',
      'lineColor': '#7B1FA2',
      'secondaryColor': '#4CAF50',
      'tertiaryColor': '#FFC107'
    }
  }
}%%
flowchart LR
    subgraph DIGITAL["💾 Digital Data Disposal"]
        CRYPTO["🔒 Cryptographic Erasure"]
        OVERWRITE["📝 Multi-Pass Overwrite"]
        PHYSICAL["🔨 Physical Destruction"]
    end
    
    subgraph PHYSICAL_DOC["📄 Physical Document Disposal"]
        SHRED["🗃️ Cross-Cut Shredding"]
        INCINERATE["🔥 Incineration"]
        PULP["♻️ Pulping"]
    end
    
    subgraph VERIFICATION["✅ Disposal Verification"]
        CERTIFICATE["📜 Disposal Certificate"]
        AUDIT["📋 Audit Trail"]
        COMPLIANCE["⚖️ Compliance Check"]
    end
    
    CRYPTO --> CERTIFICATE
    OVERWRITE --> CERTIFICATE
    PHYSICAL --> CERTIFICATE
    SHRED --> AUDIT
    INCINERATE --> AUDIT
    PULP --> AUDIT
    
    CERTIFICATE --> COMPLIANCE
    AUDIT --> COMPLIANCE
    
    style DIGITAL fill:#1565C0
    style PHYSICAL_DOC fill:#4CAF50
    style VERIFICATION fill:#FF9800
```

### 📋 **Comprehensive Records Retention Matrix**

Implementation of ISO 27001 A.5.33 (Protection of records) with systematic retention management:

#### **Business Records Retention Schedule**

| Record Type | Category | Legal Basis | Business Retention | Total Retention | Storage Location | Disposal Method |
|-------------|----------|-------------|-------------------|-----------------|------------------|----------------|
| **📊 Financial Statements** | Financial | Swedish Bookkeeping Act | 7 years | 7 years | Bokio + AWS Backup | Secure deletion + certificate |
| **💰 Invoices & Receipts** | Financial | Swedish Bookkeeping Act | 7 years | 7 years | Bokio + AWS Backup | Secure deletion + certificate |
| **🏦 Bank Statements** | Financial | Swedish Bookkeeping Act | 7 years | 7 years | SEB + AWS Backup | Secure deletion |
| **📜 Tax Returns** | Tax | Swedish Tax Agency requirements | 7 years | 10 years | Bokio + AWS Backup | Secure deletion + certificate |
| **💳 Payment Records** | Financial | PCI DSS + Swedish law | 7 years | 7 years | Stripe + AWS Backup | Secure deletion |
| **📑 Contracts** | Legal | Contract terms + Swedish law | Term + 7 years | As specified | AWS S3 encrypted | Secure deletion |
| **👥 Employee Records** | HR | Swedish labor law | 3 years post-employment | 5 years | Internal systems | Secure deletion |
| **🔐 Access Logs** | Security | ISO 27001 + NIS2 | 1 year minimum | 3 years | AWS CloudTrail | Automated purging |
| **🚨 Incident Reports** | Security | ISO 27001 + NIS2 | 3 years | 5 years | Incident response system | Secure archiving |
| **📧 Email (Business)** | Communication | GDPR + business need | 2 years | 3 years | AWS WorkMail | Standard deletion |
| **📧 Email (Legal)** | Legal | Statute of limitations | 7 years | 7 years | AWS WorkMail archive | Secure deletion |
| **🔑 Credentials/Secrets** | Security | Immediate rotation policy | 90 days | 1 year (audit) | AWS Secrets Manager | Cryptographic erasure |
| **📝 Meeting Minutes** | Governance | Companies Act | Permanent | Permanent | Internal systems | N/A - permanent record |
| **🎫 Support Tickets** | Operations | Business need | 3 years | 3 years | Support system | Standard deletion |
| **📊 Compliance Evidence** | Compliance | ISO 27001 + regulatory | 3 years | 7 years | Compliance management system | Secure archiving |
| **🏗️ Architecture Docs** | Technical | Business need | Active + 2 years | 5 years | GitHub + AWS S3 | Standard deletion |
| **📚 Public Documentation** | Public | No requirement | Indefinite | Indefinite | GitHub Pages | Version control only |

#### **Privacy & GDPR-Specific Retention**

| Data Subject Category | Data Types | Legal Basis | Retention Period | Review Trigger | Disposal Action |
|----------------------|------------|-------------|------------------|---------------|----------------|
| [![Personal](https://img.shields.io/badge/Privacy-Personal-orange?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Contact info, usage data | Art. 6(1)(f) Legitimate Interest | 12-24 months after last activity | Inactivity + annual review | Standard secure deletion |
| [![Sensitive](https://img.shields.io/badge/Privacy-Sensitive-red?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Employee personal data | Art. 6(1)(b) Contract | 3 years post-employment | Termination + period end | GDPR-compliant deletion + certificate |
| [![Confidential](https://img.shields.io/badge/Privacy-Confidential-black?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Financial data with PII | Art. 6(1)(c) Legal Obligation | 7 years (Swedish law) | Legal retention expiry | Secure deletion + audit trail |
| [![Public](https://img.shields.io/badge/Privacy-Public-lightgrey?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Publicly shared info | Art. 6(1)(a) Consent | Until consent withdrawn | Withdrawal request | Standard deletion |

#### **Retention Implementation Procedures**

**Automated Retention Management:**
- **AWS Backup Lifecycle Policies:** Automatic transition to cold storage and deletion
- **S3 Lifecycle Rules:** Automated expiration of temporary data
- **CloudWatch Logs Retention:** Configured per log group based on retention matrix
- **Database Backups:** Automated expiration per AWS Backup vault policies

**Manual Review Triggers:**
- **Annual Review:** Q1 review of all retention policies against legal changes
- **Regulatory Updates:** Ad-hoc review when laws change (GDPR, NIS2, CRA)
- **Incident-Driven:** Review after data breaches or audit findings
- **Business Changes:** Review when asset ownership or classification changes

**Disposal Verification:**
- **Deletion Certificates:** Generated for High+ classified data disposal
- **Audit Trail:** CloudTrail logs retain disposal actions for 3 years
- **Compliance Review:** Quarterly verification of disposal procedures

---

### 🎭 **Data Masking and Tokenization**

Implementation of ISO 27001 A.8.11 (Data masking) for production data protection in non-production environments:

#### **Data Masking Strategy**

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#1565C0',
      'primaryTextColor': '#1565C0',
      'lineColor': '#1565C0',
      'secondaryColor': '#4CAF50',
      'tertiaryColor': '#FFC107'
    }
  }
}%%
flowchart TD
    PROD["🔒 Production Data<br/>Sensitive Information"]
    
    subgraph MASKING["🎭 Masking Techniques"]
        STATIC["📝 Static Masking<br/>Permanent replacement"]
        DYNAMIC["⚡ Dynamic Masking<br/>Runtime obfuscation"]
        TOKENIZE["🔑 Tokenization<br/>Reversible substitution"]
    end
    
    subgraph ENVIRONMENTS["🧪 Target Environments"]
        DEV["💻 Development<br/>Fully masked"]
        TEST["🧪 Testing<br/>Format-preserved"]
        STAGE["📊 Staging<br/>Realistic but fake"]
        ANALYTICS["📈 Analytics<br/>Anonymized"]
    end
    
    PROD --> STATIC
    PROD --> DYNAMIC
    PROD --> TOKENIZE
    
    STATIC --> DEV
    DYNAMIC --> TEST
    TOKENIZE --> STAGE
    STATIC --> ANALYTICS
    
    style PROD fill:#D32F2F
    style MASKING fill:#1565C0
    style ENVIRONMENTS fill:#4CAF50
```

#### **Masking Rules by Data Type**

| Data Type | Masking Method | Format Preservation | Example Transformation | Use Case |
|-----------|---------------|--------------------|-----------------------|----------|
| **Email Addresses** | Static + Format | Yes | user@example.com → test123@example.com | Development/Testing |
| **Names** | Dictionary Replacement | No | "John Smith" → "Jane Wilson" | Realistic test data |
| **Phone Numbers** | Randomization + Format | Yes | +46701234567 → +46709876543 | Format validation testing |
| **Credit Cards** | Tokenization | Yes (Luhn-valid) | 4532-1234-5678-9010 → 4532-****-****-TEST | Payment testing |
| **Swedish Personal Numbers** | Format-preserved random | Yes | 19850315-1234 → 19900101-0000 | Identity validation |
| **IP Addresses** | Subnet preservation | Partial | 192.168.1.100 → 192.168.255.XXX | Network testing |
| **Financial Amounts** | Range-preserved random | Yes | 12,345.67 SEK → Random 1,000-99,999 | Financial calculations |
| **Addresses** | Dictionary replacement | No | Real address → Fake but valid address | Shipping logic testing |
| **Passwords/Secrets** | Never copied | N/A | Excluded from non-prod | Security compliance |

#### **Data Masking Implementation Matrix**

| Environment | Classification Allowed | Masking Required | Tokenization Allowed | Real Data Prohibition |
|-------------|----------------------|------------------|---------------------|----------------------|
| **🔒 Production** | All levels | No (real data) | Yes (for PCI DSS) | N/A - real data |
| **📊 Staging** | Up to Moderate | Yes for High+ | Yes | Prohibited: Very High, Extreme |
| **🧪 Testing** | Up to Low | Yes for Moderate+ | No | Prohibited: High, Very High, Extreme |
| **💻 Development** | Public only | Yes for all | No | Prohibited: All classified data |
| **📈 Analytics** | Anonymized only | Yes (irreversible) | No | Prohibited: All PII |

#### **Masking Techniques Standards**

**🔐 Static Data Masking (SDM):**
- **Purpose:** Create realistic but non-sensitive test datasets
- **Implementation:** Pre-processing before environment deployment
- **Tools:** Custom masking scripts + AWS Data Pipeline
- **Verification:** Automated scanning for PII patterns post-masking
- **Use Cases:** Development environments, training databases

**⚡ Dynamic Data Masking (DDM):**
- **Purpose:** Real-time data obfuscation based on user role
- **Implementation:** Database view-layer masking
- **Tools:** RDS row-level security + application middleware
- **Verification:** Access control testing + role validation
- **Use Cases:** Production data access for non-privileged users

**🔑 Tokenization:**
- **Purpose:** Reversible data protection for operational needs
- **Implementation:** AWS Secrets Manager for token vault
- **Tools:** Custom tokenization service + audit logging
- **Verification:** Token-to-data mapping validation
- **Use Cases:** Payment processing, temporary data sharing

#### **Test Data Generation Standards**

Per ISO 27001 A.8.33 (Test information), production data MUST NOT be used in non-production environments:

| Test Data Type | Generation Method | Characteristics | Compliance |
|----------------|------------------|----------------|------------|
| **Synthetic Data** | Algorithmically generated | Statistically similar, no real PII | ✅ Preferred |
| **Anonymized Data** | Irreversible PII removal | Real patterns, no identifiable info | ✅ Acceptable |
| **Masked Data** | Substitution with fake values | Format-preserved, fake content | ✅ Acceptable |
| **Scrambled Data** | Randomized real data | Real patterns, shuffled relationships | ⚠️ Risk assessment required |
| **Production Copy** | Direct copy of real data | Real PII and sensitive data | ❌ Prohibited |

#### **Data Masking Governance**

**Review and Approval:**
- **Masking Rule Changes:** Security team approval required
- **New Data Types:** Classification assessment before masking rules created
- **Tokenization Keys:** CEO approval for token vault access
- **Test Data Refresh:** Quarterly review of test dataset currency

**Monitoring and Compliance:**
- **PII Scanning:** Weekly automated scans of non-production environments
- **Access Auditing:** Quarterly review of data access patterns
- **Breach Detection:** Real-time alerts for unmasked PII in non-production
- **Training:** Annual data masking training for developers

**Integration with Other Controls:**
- **Secure Development Policy:** Test data handling requirements (§ Protection of Test Data)
- **Access Control Policy:** Role-based data access including masked views
- **Change Management:** Masking rule changes via standard change process
- **Incident Response:** Unmasked PII in non-production triggers security incident

---

## 🔍 **Data Loss Prevention (DLP)**

### 🛡️ **DLP Strategy Implementation**

#### **Content Discovery and Classification**
Automated tools and processes for identifying and classifying sensitive data:

| Detection Method | Scope | Classification Trigger | Response |
|-----------------|-------|----------------------|----------|
| **Pattern Matching** | Email, documents, databases | PII, financial data, credentials | Auto-classification, alert |
| **ML Classification** | Unstructured content | Sensitive context | Risk scoring, review |
| **Database Scanning** | Structured data | Column patterns, data types | Schema classification |
| **Network Monitoring** | Data in transit | Transmission patterns | Real-time blocking |

#### **DLP Control Matrix**

| Data Type | Detection Method | Prevention Action | Notification |
|-----------|-----------------|-------------------|--------------|
| **Credit Cards** | Luhn algorithm + patterns | Block transmission | Immediate alert |
| **Personal Data** | PII patterns + context | Encrypt/quarantine | Compliance team |
| **Financial Data** | Account patterns + context | Access control | Security team |
| **Source Code** | Syntax detection | Repository control | Development team |
| **Credentials** | Secret scanning | Immediate revocation | Security incident |

### 📊 **DLP Monitoring and Metrics**

#### **Key Performance Indicators**

| Metric | Target | Measurement | Review Frequency |
|--------|--------|-------------|------------------|
| **False Positive Rate** | <5% | DLP alerts vs. confirmed incidents | Weekly |
| **Detection Coverage** | 95% | Sensitive data identified | Monthly |
| **Response Time** | <15 minutes | Alert to action | Daily |
| **Policy Compliance** | 98% | Successful policy enforcement | Monthly |
| **User Training Effectiveness** | <2% repeat violations | Incident recurrence rate | Quarterly |

---

## 🤝 **Third-Party Data Sharing**

### 📋 **Data Sharing Framework**

Based on [🤝 Third Party Management](./Third_Party_Management.md) classifications:

#### **Supplier Data Sharing Matrix**

| Supplier Risk Tier | Data Classification Allowed | Contract Requirements | Monitoring Level |
|--------------------|---------------------------|----------------------|------------------|
| **🔴 Critical Suppliers** | Up to Very High | Comprehensive DPA, audit rights | Real-time monitoring |
| **🟠 High Risk Suppliers** | Up to High | Standard DPA, compliance verification | Daily monitoring |
| **🟡 Medium Risk Suppliers** | Up to Moderate | Basic agreement, attestation | Weekly monitoring |
| **🟢 Low Risk Suppliers** | Public + Low only | Standard terms | Monthly review |

#### **Data Processing Agreement (DPA) Requirements**

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#4CAF50',
      'primaryTextColor': '#2E7D32',
      'lineColor': '#4CAF50',
      'secondaryColor': '#1565C0',
      'tertiaryColor': '#FF9800'
    }
  }
}%%
flowchart TD
    subgraph ASSESSMENT["📊 Risk Assessment"]
        CLASSIFY["🏷️ Data Classification"]
        SUPPLIER["🤝 Supplier Risk Rating"]
        LEGAL["⚖️ Legal Requirements"]
    end
    
    subgraph CONTRACT["📝 Contract Terms"]
        PURPOSE["🎯 Processing Purpose"]
        CONTROLS["🛡️ Security Controls"]
        RETENTION["📅 Retention Limits"]
        AUDIT["🔍 Audit Rights"]
    end
    
    subgraph MONITORING["📊 Ongoing Monitoring"]
        COMPLIANCE["✅ Compliance Checks"]
        INCIDENTS["🚨 Incident Reporting"]
        REVIEWS["🔄 Regular Reviews"]
    end
    
    CLASSIFY --> PURPOSE
    SUPPLIER --> CONTROLS
    LEGAL --> RETENTION
    PURPOSE --> COMPLIANCE
    CONTROLS --> INCIDENTS
    RETENTION --> REVIEWS
    AUDIT --> REVIEWS
    
    style ASSESSMENT fill:#1565C0
    style CONTRACT fill:#4CAF50
    style MONITORING fill:#FF9800
```

### 🌍 **Cross-Border Data Transfers**

#### **International Transfer Framework**

| Destination | Legal Basis | Additional Safeguards | Approval Required |
|-------------|-------------|---------------------|-------------------|
| **🇪🇺 EU/EEA** | Adequacy decision | Standard contractual clauses | Standard process |
| **🇺🇸 USA** | Adequacy framework | Data Privacy Framework compliance | Enhanced due diligence |
| **🇨🇦 Canada** | Adequacy decision | Standard contractual clauses | Standard process |
| **Other Countries** | Standard contractual clauses | Additional security measures | Executive approval |

---

## 🏷️ **Privacy & GDPR Compliance**

### 🔒 **Privacy Data Classification**

All personal data is classified using the comprehensive [🏷️ Privacy Levels](./CLASSIFICATION.md#privacy-levels) framework, ensuring appropriate protection measures and GDPR compliance.

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#D32F2F',
      'primaryTextColor': '#C62828',
      'lineColor': '#D32F2F',
      'secondaryColor': '#4CAF50',
      'tertiaryColor': '#FF9800'
    }
  }
}%%
flowchart TD
    START["📊 Data Received/Created"] --> IDENTIFY["🔍 Identify Data Type"]
    
    IDENTIFY --> GDPR_CHECK{"🇪🇺 Contains Personal Data?"}
    
    GDPR_CHECK -->|❌ No| NON_PERSONAL["🟢 Non-Personal Data<br/>Privacy: NA"]
    GDPR_CHECK -->|✅ Yes| PERSONAL_CHECK{"👤 Type of Personal Data?"}
    
    PERSONAL_CHECK --> SPECIAL{"🚨 Art. 9 Special Category?"}
    PERSONAL_CHECK --> IDENTIFIER{"🆔 Direct Identifier?"}
    PERSONAL_CHECK --> BEHAVIORAL{"📊 Behavioral/Preference?"}
    
    SPECIAL -->|✅ Yes| SPECIAL_CAT["🔴 Special Category Data<br/>Health, Biometric, etc."]
    IDENTIFIER -->|✅ Yes| PERS_ID["🔴 Personal Identifier<br/>Name, Email, SSN, IP"]
    BEHAVIORAL -->|✅ Yes| PERSONAL["🟠 Personal Data<br/>Activity, Preferences"]
    
    SPECIAL_CAT --> PROTECT_SPECIAL["🛡️ Highest Protection<br/>Explicit Consent + Legal Basis"]
    PERS_ID --> PROTECT_HIGH["🛡️ High Protection<br/>Encryption, Access Control"]
    PERSONAL --> PROTECT_STANDARD["🛡️ Standard Protection<br/>GDPR Compliance"]
    
    IDENTIFY --> PSEUDO_CHECK{"🎭 Can Pseudonymize?"}
    PSEUDO_CHECK -->|✅ Yes| PSEUDO["🟡 Pseudonymized Data<br/>Key Separation"]
    PSEUDO_CHECK -->|❌ Keep Anonymous| ANON["🟢 Anonymized Data<br/>Aggregated/Statistical"]
    
    classDef startStyle fill:#1565C0,stroke:#0D47A1,color:#fff
    classDef decisionStyle fill:#FF9800,stroke:#F57C00,color:#fff
    classDef criticalStyle fill:#D32F2F,stroke:#B71C1C,color:#fff
    classDef highStyle fill:#FF9800,stroke:#F57C00,color:#fff
    classDef standardStyle fill:#FF9800,stroke:#F57C00,color:#fff
    classDef lowStyle fill:#FFC107,stroke:#FFA000,color:#000
    classDef safeStyle fill:#4CAF50,stroke:#388E3C,color:#fff
    
    class START startStyle
    class GDPR_CHECK,PERSONAL_CHECK,SPECIAL,IDENTIFIER,BEHAVIORAL,PSEUDO_CHECK decisionStyle
    class SPECIAL_CAT criticalStyle
    class PERS_ID highStyle
    class PERSONAL standardStyle
    class PSEUDO lowStyle
    class ANON,NON_PERSONAL safeStyle
```

### 📋 **Privacy Classification Matrix**

| Privacy Level | GDPR Article | Data Examples | Protection Requirements | Data Subject Rights |
|---------------|-------------|---------------|------------------------|-------------------|
| [![Special Category](https://img.shields.io/badge/Privacy-Special_Category-darkred?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Art. 9 | Health data, biometric, genetic, racial origin, political opinions, religious beliefs | Explicit consent + Art. 9(2) legal basis, enhanced encryption, audit all access | Full rights + special protections |
| [![Personal Identifier](https://img.shields.io/badge/Privacy-Personal_Identifier-red?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Art. 4(1) | Name, email, SSN, IP address, device ID, biometric identifiers | AES-256 encryption, MFA access, comprehensive audit logging | Full GDPR rights (Art. 15-22) |
| [![Personal](https://img.shields.io/badge/Privacy-Personal-orange?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Art. 4(1) | User preferences, activity logs, location history, contacts | Standard encryption, RBAC, access logging | Full GDPR rights (Art. 15-22) |
| [![Pseudonymized](https://img.shields.io/badge/Privacy-Pseudonymized-yellow?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Art. 4(5) | Hashed user IDs, tokenized data with key separation | Key isolation, standard encryption | Limited rights (re-identification possible) |
| [![Anonymized](https://img.shields.io/badge/Privacy-Anonymized-lightgreen?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Outside GDPR | Aggregated statistics, anonymized analytics | Integrity protection, access control | No GDPR rights (not personal data) |
| [![NA](https://img.shields.io/badge/Privacy-NA-lightgrey?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | N/A | Public information, system configuration, non-personal metadata | Standard information security controls | No GDPR rights (not personal data) |

### 🇪🇺 **GDPR Principles Integration**

Implementation of GDPR Article 5 principles through data classification:

| GDPR Principle (Art. 5) | Classification Implementation | Validation Method |
|------------------------|------------------------------|------------------|
| **Lawfulness, Fairness, Transparency** | Legal basis documented in [🔐 Privacy Policy](./Privacy_Policy.md) | Privacy notices, consent records |
| **Purpose Limitation** | Processing purposes defined per classification | Purpose-to-classification mapping |
| **Data Minimization** | Only collect data matching classification requirements | Regular data audits |
| **Accuracy** | Rectification procedures per privacy level | Data quality metrics |
| **Storage Limitation** | Retention periods per classification level (see below) | Automated deletion workflows |
| **Integrity & Confidentiality** | Security controls per privacy classification | Security assessments, penetration testing |
| **Accountability** | Classification audit trail, DPIA for High+ | Compliance audits, documentation reviews |

### ⏱️ **Privacy-Based Retention Schedule**

| Privacy Level | Retention Period | Legal Basis | Deletion Method |
|---------------|-----------------|-------------|-----------------|
| [![Special Category](https://img.shields.io/badge/Privacy-Special_Category-darkred?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Purpose limited + 0 days | Art. 9(2) specific basis | Cryptographic erasure + secure wipe |
| [![Personal Identifier](https://img.shields.io/badge/Privacy-Personal_Identifier-red?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Contract + 2 years OR Legal obligation (7 years for financial) | Art. 6(1)(b) or 6(1)(c) | Cryptographic erasure + backup purge |
| [![Personal](https://img.shields.io/badge/Privacy-Personal-orange?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | 12-24 months after last activity | Art. 6(1)(f) Legitimate Interest | Standard secure deletion |
| [![Pseudonymized](https://img.shields.io/badge/Privacy-Pseudonymized-yellow?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | 12-14 months (analytics) | Art. 6(1)(f) Legitimate Interest | Key deletion + data retention |
| [![Anonymized](https://img.shields.io/badge/Privacy-Anonymized-lightgreen?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | Indefinite (no longer personal data) | N/A (outside GDPR) | Standard deletion when no longer needed |

### 🛡️ **Data Subject Rights Implementation**

Rights enforcement procedures per privacy classification:

```mermaid
%%{
  init: {
    'theme': 'base',
    'themeVariables': {
      'primaryColor': '#1565C0',
      'primaryTextColor': '#1565C0',
      'lineColor': '#1565C0'
    }
  }
}%%
flowchart LR
    REQUEST["📧 Data Subject Request"] --> VERIFY["🔍 Identity Verification"]
    
    VERIFY --> CLASSIFY{"🏷️ Data Classification?"}
    
    CLASSIFY -->|🔴 Special/Identifier| PRIORITY["⚡ High Priority<br/>15 day target"]
    CLASSIFY -->|🟠 Personal| STANDARD["📅 Standard Process<br/>30 day target"]
    CLASSIFY -->|🟡 Pseudonymized| COMPLEX["🔍 Re-identification Check<br/>30-60 day target"]
    
    PRIORITY --> FULFILL["✅ Fulfill Request"]
    STANDARD --> FULFILL
    COMPLEX --> FULFILL
    
    FULFILL --> ACCESS{"📋 Request Type?"}
    
    ACCESS -->|📥 Access| EXPORT["📦 Data Export"]
    ACCESS -->|✏️ Rectification| UPDATE["🔄 Data Update"]
    ACCESS -->|🗑️ Erasure| DELETE["❌ Data Deletion"]
    ACCESS -->|⏸️ Restriction| RESTRICT["🔒 Processing Restriction"]
    ACCESS -->|📤 Portability| PORT["📊 Machine-Readable Export"]
    ACCESS -->|❌ Object| STOP["🛑 Stop Processing"]
    
    EXPORT --> RESPOND["📧 Response to Data Subject"]
    UPDATE --> RESPOND
    DELETE --> RESPOND
    RESTRICT --> RESPOND
    PORT --> RESPOND
    STOP --> RESPOND
    
    classDef requestStyle fill:#1565C0,stroke:#0D47A1,color:#fff
    classDef verifyStyle fill:#FF9800,stroke:#F57C00,color:#fff
    classDef priorityStyle fill:#D32F2F,stroke:#B71C1C,color:#fff
    classDef standardStyle fill:#FFC107,stroke:#FFA000,color:#000
    classDef actionStyle fill:#4CAF50,stroke:#388E3C,color:#fff
    classDef respondStyle fill:#1565C0,stroke:#1565C0,color:#fff
    
    class REQUEST requestStyle
    class VERIFY,CLASSIFY,ACCESS verifyStyle
    class PRIORITY priorityStyle
    class STANDARD,COMPLEX standardStyle
    class FULFILL actionStyle
    class EXPORT,UPDATE,DELETE,RESTRICT,PORT,STOP,RESPOND respondStyle
```

| GDPR Right | Privacy Levels Applicable | Response Time | Implementation |
|-----------|-------------------------|---------------|----------------|
| **Right to Access (Art. 15)** | All (except NA) | 30 days | Automated data export, manual compilation for complex requests |
| **Right to Rectification (Art. 16)** | Personal Identifier, Personal | 30 days | Self-service updates + admin verification for identifiers |
| **Right to Erasure (Art. 17)** | All (except legal obligation) | 30 days | Cryptographic erasure, cascade deletion, backup purge |
| **Right to Restriction (Art. 18)** | All | 30 days | Processing flag, access restriction, retention-only mode |
| **Right to Data Portability (Art. 20)** | Personal Identifier, Personal | 30 days | JSON/CSV export, structured format, machine-readable |
| **Right to Object (Art. 21)** | Legitimate Interest basis | Immediate for marketing | Opt-out mechanism, processing cessation |

### 🔍 **Data Protection Impact Assessment (DPIA)**

DPIA required per GDPR Article 35 for:

| Trigger Condition | Privacy Classification | When Required | Review Frequency |
|------------------|----------------------|---------------|------------------|
| **High risk to rights and freedoms** | Special Category data processing | Before deployment | Annual |
| **Large-scale systematic monitoring** | Personal Identifier tracking at scale | New feature/service | Annual |
| **Automated decision-making with legal effect** | Any with automated profiling | Before implementation | Per change |
| **Sensitive data processing** | Special Category + Personal Identifier combined | New processing activity | Annual |
| **Cross-border data transfers outside EU** | Personal+ outside adequate countries | Before transfer | Per transfer assessment |

**DPIA Process:**
1. 📋 Identify necessity and proportionality
2. 🔍 Assess risks to data subjects
3. 🛡️ Identify mitigation measures
4. 📊 Document findings and decisions
5. ✅ DPO review and approval
6. 📅 Ongoing monitoring and review

### 📊 **Privacy Classification Examples from Hack23 Projects**

Based on the SQL comment classification system used in CIA project:

| Data Element | Classification | SQL Comment Example | Rationale |
|--------------|----------------|---------------------|-----------|
| **Public parliamentary data** | [![NA](https://img.shields.io/badge/Privacy-NA-lightgrey?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | `COMMENT ON COLUMN document_data.title IS 'DATA.Public GDPR.NA'` | Public government information, not personal data |
| **Politician assignments** | [![Personal](https://img.shields.io/badge/Privacy-Personal-orange?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | `COMMENT ON COLUMN assignment_data.intressent_id IS 'DATA.Public GDPR.Personal_Identifier'` | Public official information, identifiable natural person |
| **User session data** | [![Personal](https://img.shields.io/badge/Privacy-Personal-orange?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | `COMMENT ON COLUMN application_session.ip_information IS 'DATA.Sensitive GDPR.Personal'` | User activity tracking, identifiable |
| **Application user ID** | [![Personal Identifier](https://img.shields.io/badge/Privacy-Personal_Identifier-red?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | `COMMENT ON COLUMN application_action_event.user_id IS 'DATA.Sensitive GDPR.Personal_Identifier'` | Direct user identifier |
| **System configuration** | [![NA](https://img.shields.io/badge/Privacy-NA-lightgrey?style=flat-square)](./CLASSIFICATION.md#privacy-levels) | `COMMENT ON COLUMN application_configuration.property_value IS 'DATA.Sensitive GDPR.NA'` | System metadata, not personal |

**Column Comment Format Standard:**
```sql
COMMENT ON COLUMN schema.table.column IS 'DATA.[Confidentiality] GDPR.[Privacy_Level]';

-- Examples:
-- 'DATA.Public GDPR.NA' - Public, non-personal
-- 'DATA.Sensitive GDPR.Personal' - Sensitive, personal data
-- 'DATA.Sensitive GDPR.Personal_Identifier' - Sensitive, direct identifier
```

---

## ✅ **Compliance Integration**

### ⚖️ **Regulatory Framework Alignment**

Integration with [✅ Compliance Checklist](./Compliance_Checklist.md):

#### **GDPR Compliance Matrix**

| GDPR Article | Data Classification Impact | Implementation | Validation |
|-------------|---------------------------|----------------|------------|
| **Article 5 (Principles)** | All classifications | Data minimization, purpose limitation | Quarterly review |
| **Article 25 (Data Protection by Design)** | High+ classifications | Technical/organizational measures | Architecture review |
| **Article 32 (Security)** | All classifications | Appropriate technical measures | Security assessment |
| **Article 33 (Breach Notification)** | Moderate+ classifications | 72-hour notification | Incident procedures |
| **Article 35 (DPIA)** | High risk processing | Impact assessment | Legal review |

#### **NIS2 Alignment**

| NIS2 Requirement | Data Category | Classification Threshold | Implementation |
|------------------|---------------|------------------------|----------------|
| **Risk Management** | Operational data | Moderate+ | Risk register integration |
| **Incident Reporting** | Security events | High+ | Incident response procedures |
| **Business Continuity** | Critical systems | Mission Critical availability | BCP integration |
| **Supply Chain Security** | Supplier data | Supplier risk assessment | Third-party management |

### 📋 **Audit and Evidence Management**

#### **Classification Audit Trail**

| Audit Event | Data Captured | Retention Period | Review Frequency |
|-------------|---------------|----------------|------------------|
| **Classification Assignment** | Data type, rationale, approver | 7 years | Annual |
| **Access Events** | User, timestamp, data accessed | 3 years | Monthly |
| **Reclassification** | Old/new classification, justification | 7 years | Quarterly |
| **Disposal Actions** | Date, method, verification | Permanent | Annual |
| **Incident Events** | Classification impact, response | 7 years | Per incident |

---

## 📚 **Related Documents**

### 🎯 Strategic & Governance
- [📈 Information Security Strategy](./Information_Security_Strategy.md) — AI-first operations, Pentagon framework, and strategic data classification direction
- [🏷️ Classification Framework](./CLASSIFICATION.md) — Comprehensive classification methodology and business impact analysis
- [🔐 Information Security Policy](./Information_Security_Policy.md) — Overall security governance with AI-First Operations Governance
- [🤖 AI Policy](./AI_Policy.md) — AI-assisted data classification and handling automation
- [📉 Risk Register](./Risk_Register.md) — Data-related risk identification and treatment tracking
- [✅ Compliance Checklist](./Compliance_Checklist.md) — Regulatory compliance tracking including data protection laws

### 🔐 Security Policies & Controls
- [🔐 Privacy Policy](./Privacy_Policy.md) — User-facing privacy notices and GDPR compliance for products
- [🔒 Cryptography Policy](./Cryptography_Policy.md) — Encryption standards and key management for classified data
- [🔑 Access Control Policy](./Access_Control_Policy.md) — Identity management and authorization controls for data access
- [🛠️ Secure Development Policy](./Secure_Development_Policy.md) — Application security with data protection requirements

### ⚙️ Operational Integration
- [💾 Backup Recovery Policy](./Backup_Recovery_Policy.md) — Data protection and recovery procedures based on classification
- [🤝 Third Party Management](./Third_Party_Management.md) — Supplier risk management and data sharing governance
- [💻 Asset Register](./Asset_Register.md) — Information asset inventory with classification assignments
- [🚨 Incident Response Plan](./Incident_Response_Plan.md) — Data breach and security incident response procedures
- [🔄 Business Continuity Plan](./Business_Continuity_Plan.md) — Business resilience with classification-based recovery priorities

---

**📋 Document Control:**  
**✅ Approved by:** James Pether Sörling, CEO  
**📤 Distribution:** Public  
**🏷️ Classification:** [![Confidentiality: Public](https://img.shields.io/badge/C-Public-lightgrey?style=flat-square)](./CLASSIFICATION.md#confidentiality-levels)  
**📅 Effective Date:** 2026-01-25  
**⏰ Next Review:** 2027-01-25  
**🎯 Framework Compliance:** [![ISO 27001](https://img.shields.io/badge/ISO_27001-2022_Aligned-blue?style=flat-square&logo=iso&logoColor=white)](./CLASSIFICATION.md) [![NIST CSF 2.0](https://img.shields.io/badge/NIST_CSF-2.0_Aligned-green?style=flat-square&logo=nist&logoColor=white)](./CLASSIFICATION.md) [![CIS Controls](https://img.shields.io/badge/CIS_Controls-v8.1_Aligned-orange?style=flat-square&logo=cisecurity&logoColor=white)](./CLASSIFICATION.md)

