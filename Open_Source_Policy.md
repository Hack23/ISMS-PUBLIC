<p align="center">
  <img src="https://hack23.github.io/cia-compliance-manager/icon-192.png" alt="Hack23 Logo" width="192" height="192">
</p>

<h1 align="center">🔓 Hack23 AB — Open Source Policy</h1>

<p align="center">
  <strong>Governance for Transparent and Responsible Open Source</strong><br>
  <em>Security-by-default, compliance-first, community-aligned</em>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Owner-CEO-0A66C2?style=for-the-badge" alt="Owner"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-1.2-555?style=for-the-badge" alt="Version"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Effective-2025--08--18-success?style=for-the-badge" alt="Effective Date"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Review-Quarterly-orange?style=for-the-badge" alt="Review Cycle"/></a>
</p>

**Document Owner:** CEO | **Version:** 1.2 | **Last Updated:** 2025-08-18 (UTC)  
**Review Cycle:** Quarterly | **Next Review:** 2025-11-18

---

## 🎯 Purpose Statement

Hack23 AB uses open source to demonstrate security excellence through transparency, while respecting community norms and legal obligations. This policy establishes governance requirements for creating, maintaining, and contributing to open source projects.

---

## 🔍 Purpose & Scope

- Scope: All Hack23-owned repositories, forks under the Hack23 organization, and contributions made by Hack23 personnel.
- Out of scope: Internal-only repositories not intended for public distribution.

---

## 🧭 Principles

1) Transparency: Security posture and governance evidence shall be publicly visible.  
2) Security-by-default: Preventive controls and responsible disclosure are mandatory.  
3) Compliance-first: Licensing and data protection requirements are non-negotiable.  
4) Community respect: Follow upstream guidelines, attribution, and code-of-conduct.

---

## 👤 Roles & Responsibilities

- CEO: Policy owner, exception approver, and final arbiter on licensing/classification disputes.
- Maintainer (repo owner): Ensures policy compliance in their repository.
- Contributor: Adheres to this policy and repository-level CONTRIBUTING and CODE_OF_CONDUCT.

---

## 📜 Policy Requirements

### 1) Governance Artifacts (mandatory in each repo)
- LICENSE file reflecting the project’s chosen license.
- SECURITY.md detailing coordinated vulnerability disclosure.
- CODE_OF_CONDUCT.md and CONTRIBUTING.md.
- README must include a “Project Classification (Hack23)” section that references definitions in CLASSIFICATION.md without duplicating them.

### 2) Security Posture and Assurance
- All repositories must be enrolled in OpenSSF Scorecard and CII Best Practices.  
- Public, non-sensitive indicators of security posture must be available; implementation details and badge mechanics are governed by the Secure Development Policy.  
- Secrets must never be committed; use approved secret management per organizational standards.

### 3) Classification and Documentation
- Each project MUST declare its classification using the Hack23 framework and link to CLASSIFICATION.md for definitions.  
- Do not restate impact levels or definitions in project READMEs; reference the canonical framework only.

### 4) Vulnerability Disclosure and Remediation
- Security issues are reported via SECURITY.md channel and handled privately until remediation.  
- Remediation SLAs and severity definitions are governed by the Vulnerability_Management policy.

### 5) Licensing and Third-Party Code
- Use approved open source licenses appropriate to project goals.  
- Strong copyleft components (e.g., GPL family) require CEO approval before inclusion.  
- Maintain license notices and attribution as required; avoid mixing incompatible licenses.

### 6) Data Protection
- Do not store personal, confidential, or regulated data in repositories.  
- Use anonymized or synthetic examples only; comply with Data_Classification_Policy for any datasets.

### 7) Supply Chain Expectations
- Release integrity, provenance, and SBOM requirements are defined by the Secure_Development_Policy.  
- This policy sets expectations; implementation specifics are documented elsewhere and must not be embedded here.

### 8) Contributions to External Projects
- Follow upstream contribution guidelines and license terms.  
- Disclose conflicts of interest where applicable; respect project governance decisions.

---

## 🔎 Compliance, Verification, and Exceptions

- Verification: Compliance is reviewed quarterly. Live posture is referenced via the Security_Metrics hub.  
- Exceptions: Time-bound exceptions may be granted by the CEO with documented rationale and end-date.  
- Non-compliance: Maintainers must remediate gaps within agreed timelines or risk archival of the repository.

---

## 📚 Related Documents
- [🔐 Information Security Policy](./Information_Security_Policy.md)
- [🛠️ Secure Development Policy](./Secure_Development_Policy.md)
- [🏷️ Classification Framework](./CLASSIFICATION.md)
- [🔍 Vulnerability Management](./Vulnerability_Management.md)
- [📝 Change Management](./Change_Management.md)
- [🏷️ Data Classification Policy](./Data_Classification_Policy.md)
- [🤝 Third-Party Management](./Third_Party_Management.md)
- [📊 Security Metrics](./Security_Metrics.md)
- [📉 Risk Register](./Risk_Register.md)

---

**Document Control:**  
**Approved by:** James Pether Sörling, CEO  
**Distribution:** All Personnel  
**Classification:** [![Confidentiality: Public](https://img.shields.io/badge/C-Public-lightgrey?style=flat-square)](./CLASSIFICATION.md#confidentiality-levels)  
**Effective Date:** 2025-08-18  
**Next Review:** 2025-11-18   
**Framework Compliance:** [![ISO 27001](https://img.shields.io/badge/ISO_27001-2022_Aligned-blue?style=flat-square&logo=iso&logoColor=white)](./CLASSIFICATION.md) [![NIST CSF 2.0](https://img.shields.io/badge/NIST_CSF-2.0_Aligned-green?style=flat-square&logo=nist&logoColor=white)](./CLASSIFICATION.md) [![CIS Controls](https://img.shields.io/badge/CIS_Controls-v8.1_Aligned-orange?style=flat-square&logo=cisecurity&logoColor=white)](./CLASSIFICATION.md)

