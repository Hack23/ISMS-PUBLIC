<p align="center">
  <img src="https://hack23.github.io/cia-compliance-manager/icon-192.png" alt="Hack23 Logo" width="192" height="192">
</p>

<h1 align="center">🌐 Hack23 AB — ISMS Transparency Plan</h1>

<p align="center">
  <strong>Security Through Radical Transparency</strong><br>
  <em>Defining the Boundaries Between Public Demonstration and Confidential Information</em>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Owner-CEO-0A66C2?style=for-the-badge" alt="Owner"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-1.0-555?style=for-the-badge" alt="Version"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Effective-2025--08--14-success?style=for-the-badge" alt="Effective Date"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Review-Annual-orange?style=for-the-badge" alt="Review Cycle"/></a>
</p>

**Document Owner:** CEO | **Version:** 1.0 | **Last Updated:** 2025-08-14 (UTC)  
**Review Cycle:** Annual | **Next Review:** 2026-08-14

---

## 🎯 **Purpose Statement**

Hack23 AB's core philosophy is that **transparency enhances security rather than diminishing it.** This document outlines our strategy for making our Information Security Management System (ISMS) public, demonstrating our expertise and building trust, while carefully protecting sensitive information that could introduce risk.

This plan defines what is considered public, what is confidential, and the rationale for each decision.

---

## 📜 **Guiding Principles**

1.  **Default to Public:** Policies, frameworks, and high-level procedures will be public unless a specific, documented risk is identified.
2.  **Demonstrate, Don't Expose:** The goal is to showcase our security maturity and processes, not to reveal secrets that could be exploited.
3.  **Redact, Don't Hide:** When a document contains a mix of public and sensitive information, we will redact the sensitive parts and publish the rest.
4.  **Clarity and Rationale:** The reason for keeping any information confidential will be clearly documented internally.

---

## 📊 **Information Classification for Publication**

This table defines the publication status of ISMS documents and the rationale.

| Document / Information Type | Publication Status | Rationale & Redaction Rules |
|-----------------------------|--------------------|-----------------------------|
| **Core Policies & Frameworks** | | |
| Information Security Policy | ✅ **Public** | Demonstrates overall security posture. No sensitive details. |
| Classification Framework | ✅ **Public** | Core to our methodology; showcases our approach to risk. |
| Open Source Policy | ✅ **Public** | Aligns with our open-source philosophy. |
| Style Guide | ✅ **Public** | Shows our commitment to quality and consistency. |
| **Operational Policies** | | |
| Access Control Policy | ✅ **Public** | High-level policy is public. Specific roles and access lists are confidential. |
| Cryptography Policy | ✅ **Public** | Approved algorithms and standards are public. Key management procedures are confidential. |
| Secure Development Policy | ✅ **Public** | The framework is public. Specific tool configurations are confidential. |
| **Management & Governance** | | |
| Asset Register | ⚠️ **Redacted** | Public version will list asset categories (e.g., "SaaS Platforms," "AWS Accounts"). Specific account IDs, emails, and internal hostnames are **CONFIDENTIAL**. |
| Risk Register | ⚠️ **Redacted** | The framework and risk categories are public. Specific risk details, financial impacts, and vulnerabilities are **CONFIDENTIAL**. |
| Supplier Management / `SUPPLIER.md` | ⚠️ **Redacted** | The list of suppliers is public. Contract details, costs, and specific security posture findings are **CONFIDENTIAL**. |
| **Response & Recovery Plans** | | |
| Incident Response Plan | ⚠️ **Redacted** | The process (PICERL) is public. Specific contact details, technical playbooks, and internal communication plans are **CONFIDENTIAL**. |
| Business Continuity Plan | ⚠️ **Redacted** | High-level strategies are public. Specific recovery steps, contact lists, and financial details are **CONFIDENTIAL**. |
| Disaster Recovery Plan | ⚠️ **Redacted** | The architecture overview is public. Detailed recovery scripts, credentials, and internal IP addresses are **CONFIDENTIAL**. |
| **Compliance & Legal** | | |
| Compliance Checklist | ⚠️ **Redacted** | The frameworks we align with are public. The detailed status of compliance gaps is **CONFIDENTIAL** to prevent targeted attacks. |
| Data Classification Policy | ✅ **Public** | The classification levels and handling rules are public. The classification of specific, sensitive datasets is confidential. |
| **Sensitive Information** | | |
| Personal Data (CEO, future employees) | ❌ **Confidential** | Per GDPR and privacy best practices. |
| Financial Records & Bank Details | ❌ **Confidential** | Per Swedish Bookkeeping Act and security best practices. |
| Customer Data | ❌ **Confidential** | Absolute confidentiality is paramount for client trust and GDPR. |
| Active Security Vulnerabilities | ❌ **Confidential** | Public disclosure would be irresponsible. |
| Credentials, API Keys, Tokens | ❌ **Confidential** | Extreme-level confidential data. |

---

## 🔧 **Redaction and Publication Process**

1.  **Create Internal Version:** The complete, unredacted document is created and stored in a secure, internal repository. This is the "source of truth."
2.  **Create Public Version:** A copy of the document is made for public release.
3.  **Apply Redactions:** Based on the table above, sensitive information is removed or replaced with generic descriptions (e.g., `[REDACTED]`, `[Internal Procedure]`).
4.  **Review:** The public version is reviewed by the CEO to ensure no sensitive information remains.
5.  **Publish:** The sanitized version is published to the public GitHub repository.

---

**Document Control:**  
**Approved by:** James Pether Sörling, CEO  
**Distribution:** All Personnel
**Classification:** [![Confidentiality: Moderate](https://img.shields.io/badge/C-Moderate-orange?style=flat-square)](./CLASSIFICATION.md#confidentiality-levels)  
**Effective Date:** 2025-08-14  
**Next Review:** 2026-08-14
