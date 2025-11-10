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
  <p><strong>Radical Transparency with Minimal Redaction</strong><br>
  This document is published in full. Only specific sensitive values (credentials, API keys, account numbers) replaced with [REDACTED].<br>
  All processes, procedures, configurations, and operational details are public to demonstrate our security practices.</p>
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
  root((Hack23 Assets))
    Identities
      Google MFA
      GitHub: pethers MFA
      AWS Identity Center MFA
    SaaS & Platforms
      Accounting: Bokio
      Banking: SEB
      Dev: GitHub Org
      Payments: Stripe
      Marketing: YouTube · ProductHunt · X · TikTok
      Search: GSC · Bing Webmaster
    AWS Org (Control Tower)
      Audit: [REDACTED]
      Log Archive: [REDACTED]
      hack23master: [REDACTED]
      Permission Sets: Admin · PowerUser · ReadOnly · ServiceCatalog
    Domains
      hack23.com
      blacktrigram.com
    IP & Repos
      Black Trigram
      CIA Compliance Manager
      Citizen Intelligence Agency
      Lambda in Private VPC
      Sonar CloudFormation Plugin
```


## 1) Identities and Accounts

### 1.1 Human identities
| #️⃣ ID | 👤 Person | ✉️ Email | 🛠️ Platforms | 🔐 MFA | 📝 Notes | 🏷️ Types |
|-------|-----------|----------|---------------|--------|----------|----------|
| U-001 | James Pether Sörling | [REDACTED] | 🔎 Google • 🐙 GitHub (pethers) • ☁️ AWS SSO | Enabled | Google account is the hub for SaaS sign-ins listed below | [![Executive](https://img.shields.io/badge/Process-Executive-gold?style=for-the-badge&logo=university&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |

### 1.2 Linked services (via Google account)
| #️⃣ ID | 🧩 Service | 👤 Account/Handle | ✅ Status | 🔐 MFA/2FA | 📝 Notes | 🏷️ Types |
|-------|------------|-------------------|-----------|------------|----------|----------|
| G-001 | 🧾 Bokio | Google login | Active ✅ | N/A (IdP) | Connected via Google | [![Compliance](https://img.shields.io/badge/Type-Compliance_Platform-green?style=for-the-badge&logo=clipboard-check&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Finance](https://img.shields.io/badge/Process-Finance-darkblue?style=for-the-badge&logo=dollar-sign&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| G-002 | 💳 Stripe | Google login | Active ✅ | N/A (IdP) | Connected via Google | [![API](https://img.shields.io/badge/Type-API_Services-purple?style=for-the-badge&logo=cloud&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Sales](https://img.shields.io/badge/Process-Sales-darkgreen?style=for-the-badge&logo=handshake&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| G-003 | 🔎 Google Search Console | [REDACTED] | Active ✅ | Google MFA | Site verification | [![Analytics](https://img.shields.io/badge/Type-Data_Analytics-orange?style=for-the-badge&logo=chart-line&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| G-004 | 🔎 Bing Webmaster Tools | [REDACTED] | Active ✅ | Google MFA | Site verification | [![Analytics](https://img.shields.io/badge/Type-Data_Analytics-orange?style=for-the-badge&logo=chart-line&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| G-005 | ▶️ YouTube | @ via Google | Active ✅ | Google MFA | Connected | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| G-006 | 🦄 Product Hunt | Google login | Active ✅ | N/A (IdP) | Connected | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| G-007 | 🎵 TikTok | Google login | Active ✅ | N/A (IdP) | Connected | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| G-008 | ✖️ X (Twitter) | Google login | Active ✅ | N/A (IdP) | Connected | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| G-009 | 💼 LinkedIn (CEO) | https://www.linkedin.com/in/jamessorling/ | Active ✅ | Platform MFA | Professional profile | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=linkedin&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Executive](https://img.shields.io/badge/Process-Executive-gold?style=for-the-badge&logo=university&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| G-010 | 💼 LinkedIn (Company) | https://www.linkedin.com/company/hack23/ | Active ✅ | Platform MFA | Company page | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=linkedin&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |

### 1.3 GitHub account and integrations
| #️⃣ ID | 🐙 Account | 🔐 MFA | 🔌 Connected Apps | 📝 Notes | 🏷️ Types |
|-------|------------|--------|-------------------|----------|----------|
| GH-001 | pethers | Enabled | — | Used across Hack23 org projects | [![DevTools](https://img.shields.io/badge/Type-Development_Tools-lightblue?style=for-the-badge&logo=wrench&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| GH-INT-001 | Integration: SonarSource (SonarCloud) | N/A | — | SAST (static analysis) | [![Security](https://img.shields.io/badge/Type-Security_Tools-darkblue?style=for-the-badge&logo=shield-alt&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| GH-INT-002 | Integration: FOSSA | N/A | — | Open source compliance (license/security) | [![Security](https://img.shields.io/badge/Type-Security_Tools-darkblue?style=for-the-badge&logo=shield-alt&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Legal](https://img.shields.io/badge/Process-Legal-darkred?style=for-the-badge&logo=balance-scale&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |

---

## 2) SaaS and Platforms (summary)
See SUPPLIER.md for detailed posture (costs, SLAs, risks).
<!-- Note: Includes free providers authenticated via Google/GitHub; some used only for public repos. -->

| #️⃣ ID | ☁️ Service | 🏢 Account/Org | 📦 Plan/Status | 👤 Owner | 🔐 MFA | 📝 Notes | 🏷️ Classification |
|-------|------------|----------------|----------------|----------|--------|----------|--------------------|
| S-001 | ☁️ AWS | Hack23 (Control Tower) | Active ✅ | CEO | Enforced via AWS Identity Center | Mission critical | [![Core](https://img.shields.io/badge/Type-Core_Infrastructure-red?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Mission Critical](https://img.shields.io/badge/Availability-Mission_Critical-red?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-002 | 🐙 GitHub | hack23 (org) | Active ✅ | CEO | Required | Version control, CI/CD | [![DevTools](https://img.shields.io/badge/Type-Development_Tools-lightblue?style=for-the-badge&logo=wrench&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability High](https://img.shields.io/badge/Availability-High-orange?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-003 | 🏦 SEB | Corporate Banking | Active ✅ | CEO | Bank MFA | Payments/payroll | [![API](https://img.shields.io/badge/Type-API_Services-purple?style=for-the-badge&logo=cloud&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Finance](https://img.shields.io/badge/Process-Finance-darkblue?style=for-the-badge&logo=dollar-sign&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability High](https://img.shields.io/badge/Availability-High-orange?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-004 | 🧾 Bokio | Company workspace | Active ✅ | CEO | IdP (Google) | Accounting | [![Compliance](https://img.shields.io/badge/Type-Compliance_Platform-green?style=for-the-badge&logo=clipboard-check&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Finance](https://img.shields.io/badge/Process-Finance-darkblue?style=for-the-badge&logo=dollar-sign&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Moderate](https://img.shields.io/badge/Availability-Moderate-yellow?style=for-the-badge&logo=server&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-005 | 🎶 Suno | Subscription | Active ✅ | CEO | Platform MFA | Marketing content | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-006 | 🎙️ ElevenLabs | Subscription | Active ✅ | CEO | Platform MFA | Audio/voice | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-007 | 🤖 OpenAI | API | Active ✅ | CEO | API / Account MFA | AI services | [![API](https://img.shields.io/badge/Type-API_Services-purple?style=for-the-badge&logo=cloud&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Moderate](https://img.shields.io/badge/Availability-Moderate-yellow?style=for-the-badge&logo=server&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-008 | 💳 Stripe | Platform | Active ✅ | CEO | Platform MFA | Payments | [![API](https://img.shields.io/badge/Type-API_Services-purple?style=for-the-badge&logo=cloud&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Sales](https://img.shields.io/badge/Process-Sales-darkgreen?style=for-the-badge&logo=handshake&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Mission Critical](https://img.shields.io/badge/Availability-Mission_Critical-red?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-009 | 🔎 Google Search Console | [REDACTED] | Active (Free) ✅ | CEO | Google MFA | SEO verification & metrics | [![Analytics](https://img.shields.io/badge/Type-Data_Analytics-orange?style=for-the-badge&logo=chart-line&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-010 | 🔎 Bing Webmaster Tools | [REDACTED] | Active (Free) ✅ | CEO | Google MFA | SEO coverage for Bing | [![Analytics](https://img.shields.io/badge/Type-Data_Analytics-orange?style=for-the-badge&logo=chart-line&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-011 | ▶️ YouTube | Channel via Google | Active (Free) ✅ | CEO | Google MFA | Marketing channel | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-012 | 🦄 Product Hunt | hack23 | Active (Free) ✅ | CEO | IdP (Google) | Launch listings | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-013 | 🎵 TikTok | hack23 | Active (Free) ✅ | CEO | IdP (Google) | Social marketing | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-014 | ✖️ X (Twitter) | hack23 | Active (Free) ✅ | CEO | IdP (Google) | Social updates | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-015 | 💼 LinkedIn (CEO) | jamessorling | Active (Free) ✅ | CEO | Platform MFA | Executive profile | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=linkedin&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Executive](https://img.shields.io/badge/Process-Executive-gold?style=for-the-badge&logo=university&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-016 | 💼 LinkedIn (Company) | Hack23 AB | Active (Free) ✅ | CEO | Platform MFA | Company page | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=linkedin&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-017 | 🛡️ SonarSource (SonarCloud) | GitHub org integration | Active (Free/public) ✅ | CEO | GitHub OAuth | SAST for public repos only | [![Security](https://img.shields.io/badge/Type-Security_Tools-darkblue?style=for-the-badge&logo=shield-alt&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability High](https://img.shields.io/badge/Availability-High-orange?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |
| S-018 | ⚖️ FOSSA | GitHub org integration | Active (Free/public) ✅ | CEO | GitHub OAuth | OSS license/security for public repos | [![Compliance](https://img.shields.io/badge/Type-Compliance_Platform-green?style=for-the-badge&logo=clipboard-check&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Process Legal](https://img.shields.io/badge/Process-Legal-darkred?style=for-the-badge&logo=balance-scale&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Availability Standard](https://img.shields.io/badge/Availability-Standard-lightgreen?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#availability-levels) |

---

## 3) AWS Organization (Control Tower)

Supplier: AWS (accounts via AWS Organizations). Control Tower is used for governance/security and SSO; IAM Identity Center with MFA enforced.  
Note: AWS WorkMail uses MFA through Identity Center.

### 3.1 Accounts
| #️⃣ ID | 🏷️ Account Name | 🆔 Account ID | ✉️ Root Email | 🎯 Purpose | 🏷️ Types |
|-------|------------------|---------------|---------------|-----------|----------|
| AWS-001 | Audit | [REDACTED] | audit@hack23.com | Security/audit (CT Log/Audit pattern) | [![Core](https://img.shields.io/badge/Type-Core_Infrastructure-red?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| AWS-002 | Log archive | [REDACTED] | log-archive@hack23.com | Central immutable logs | [![Core](https://img.shields.io/badge/Type-Core_Infrastructure-red?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| AWS-003 | hack23master | [REDACTED] | [REDACTED] | Primary workload/management | [![Core](https://img.shields.io/badge/Type-Core_Infrastructure-red?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |

### 3.2 Permission sets / access
| #️⃣ ID | 🛡️ Permission Set | 📍 Scope | 🔑 Keys |
|-------|--------------------|---------|---------|
| PS-001 | AWSAdministratorAccess | Audit, hack23master | Access keys in use (as provided) |
| PS-002 | AWSPowerUserAccess | Audit, hack23master | Access keys in use (as provided) |
| PS-003 | AWSReadOnlyAccess | Audit, hack23master | Access keys in use (as provided) |
| PS-004 | AWSServiceCatalogAdminFullAccess | hack23master | Access keys in use (as provided) |
| PS-005 | AWSServiceCatalogEndUserAccess | hack23master | Access keys in use (as provided) |

### 3.3 Visual: AWS Organization Diagram
```mermaid
flowchart LR
  A["Control Tower Org"]
  AU["Audit\n[REDACTED]\naudit&#64;hack23.com"]
  LA["Log Archive\n[REDACTED]\nlog-archive&#64;hack23.com"]
  HM["hack23master\n[REDACTED]\n[REDACTED]"]

  A --> AU
  A --> LA
  A --> HM

  subgraph "Permission Sets"
    PS1["AWSAdministratorAccess"]
    PS2["AWSPowerUserAccess"]
    PS3["AWSReadOnlyAccess"]
    PS4["AWSServiceCatalogAdminFullAccess"]
    PS5["AWSServiceCatalogEndUserAccess"]
  end

  AU --- PS1
  AU --- PS2
  AU --- PS3
  HM --- PS1
  HM --- PS2
  HM --- PS3
  HM --- PS4
  HM --- PS5

  classDef ct fill:#ffecb3,stroke:#ffa000,stroke-width:2px,color:#333;
  classDef acct fill:#e3f2fd,stroke:#42a5f5,color:#0d47a1;

  class A ct;
  class AU,LA,HM acct;
```

### 3.4 DNS (Route 53) and Domain Security
- DNS provider: Amazon Route 53 (hosted zones in AWS)
- DNSSEC: Enabled for both domains (DS records published at registrar)

| Domain | Hosted Zone | DNSSEC | Notes |
|--------|-------------|--------|-------|
| hack23.com | Route 53 | Enabled | Registrar lock on; alerts configured |
| blacktrigram.com | Route 53 | Enabled | Registrar lock on; alerts configured |

### 3.5 AWS Services in Use (27 Active Services)

#### Security & Compliance Services (8 Services)
| Service | Purpose | Data Classification | Status |
|---------|---------|-------------------|---------|
| WAF | Web application firewall for hack23.com/blacktrigram.com | [![Availability Mission Critical](https://img.shields.io/badge/A-Mission_Critical-red?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Security Hub | Centralized security findings and compliance | [![Integrity Critical](https://img.shields.io/badge/I-Critical-red?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Detective | Security investigation and threat hunting | [![Confidentiality High](https://img.shields.io/badge/C-High-blue?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Inspector | Vulnerability assessment for EC2/Lambda/containers | [![Integrity Critical](https://img.shields.io/badge/I-Critical-red?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| GuardDuty | Threat detection across accounts | [![Confidentiality High](https://img.shields.io/badge/C-High-blue?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Config | Compliance rules and resource tracking | [![Integrity High](https://img.shields.io/badge/I-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Macie | Sensitive data discovery in S3 | [![Confidentiality Extreme](https://img.shields.io/badge/C-Extreme-black?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| CloudTrail | API audit logging across all accounts | [![Integrity Critical](https://img.shields.io/badge/I-Critical-red?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |

#### Core Infrastructure Services (11 Services)
| Service | Purpose | Data Classification | Status |
|---------|---------|-------------------|---------|
| RDS | PostgreSQL for CIA application | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Route 53 | DNS management with DNSSEC | [![Availability Mission Critical](https://img.shields.io/badge/A-Mission_Critical-red?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| WorkMail | Corporate email (james@hack23.com) | [![Confidentiality High](https://img.shields.io/badge/C-High-blue?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| KMS | Encryption key management | [![Confidentiality Extreme](https://img.shields.io/badge/C-Extreme-black?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| S3 | Static website hosting, backups, logs | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| VPC | Network isolation for Lambda/RDS | [![Integrity High](https://img.shields.io/badge/I-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Glacier | Long-term backup storage | [![Availability Standard](https://img.shields.io/badge/A-Standard-lightgreen?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| CloudFront | CDN for hack23.com and blacktrigram.com | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Lambda | Serverless functions for APIs | [![Integrity Critical](https://img.shields.io/badge/I-Critical-red?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Control Tower | Multi-account governance | [![Integrity Critical](https://img.shields.io/badge/I-Critical-red?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Identity Center | SSO and permission management | [![Confidentiality Extreme](https://img.shields.io/badge/C-Extreme-black?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |

#### Monitoring & Analytics Services (4 Services)
| Service | Purpose | Data Classification | Status |
|---------|---------|-------------------|---------|
| Cost Explorer | Cost analysis and optimization | [![Confidentiality Moderate](https://img.shields.io/badge/C-Moderate-yellow?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| CloudWatch Events | Event-driven automation | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| CloudWatch | Metrics, logs, and alarms | [![Integrity High](https://img.shields.io/badge/I-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Data Transfer | Cross-region and internet transfer | N/A | ✅ Active |

#### Resilience & DR Services (4 Services)
| Service | Purpose | Data Classification | Status |
|---------|---------|---------------------|--------|
| Resilience Hub | Application resilience assessment and policy gating | [![Availability Mission Critical](https://img.shields.io/badge/A-Mission_Critical-red?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Fault Injection Service | Chaos experiments to validate failover/recovery | [![Integrity High](https://img.shields.io/badge/I-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| AWS Backup | Centralized backup plans, cross-region copies, immutable vaults | [![Confidentiality High](https://img.shields.io/badge/C-High-blue?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |
| Backup Audit Manager | Backup compliance controls and reporting | [![Integrity High](https://img.shields.io/badge/I-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | ✅ Active |

#### Planned Services (Q2-Q3 2025)
| Service | Purpose | Data Classification | Timeline |
|---------|---------|-------------------|----------|
| API Gateway | REST/GraphQL APIs for Black Trigram | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | Q2 2025 |
| DynamoDB | NoSQL for game state and user data | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | Q2 2025 |
| Cognito | User authentication for products | [![Confidentiality High](https://img.shields.io/badge/C-High-blue?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | Q3 2025 |
| ECS/Fargate | Container hosting for microservices | [![Availability High](https://img.shields.io/badge/A-High-orange?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) | Q3 2025 |

### 3.6 Security Architecture

```mermaid
graph TB
    subgraph Detection["🔍 Detection Layer"]
        GD[GuardDuty<br/>Threat Detection]
        DT[Detective<br/>Investigation]
        MC[Macie<br/>Data Discovery]
    end
    
    subgraph Protection["🛡️ Protection Layer"]
        WAF[WAF<br/>Web Protection]
        IN[Inspector<br/>Vulnerability Scan]
        KMS[KMS<br/>Encryption]
    end
    
    subgraph Compliance["📋 Compliance Layer"]
        SH[Security Hub<br/>Posture Management]
        CFG[Config<br/>Compliance Rules]
        CT[CloudTrail<br/>Audit Logs]
    end
    
    subgraph Infrastructure["🏗️ Infrastructure"]
        CT_ORG[Control Tower<br/>Governance]
        IDC[Identity Center<br/>SSO]
        VPC[VPC<br/>Network Isolation]
    end
    
    GD --> SH
    DT --> SH
    MC --> SH
    IN --> SH
    CFG --> SH
    CT --> S3[S3<br/>Log Storage]
    CT --> GL[Glacier<br/>Archive]
    
    style Detection fill:#e8f5e9
    style Protection fill:#e3f2fd
    style Compliance fill:#fff3e0
    style Infrastructure fill:#fce4ec
```

---

## 4) Domains

| #️⃣ ID | 🌐 Domain | 🏢 Owner | ✅ Status | 📝 Notes | 🏷️ Types |
|-------|----------|----------|-----------|----------|----------|
| D-001 | hack23.com | Hack23 AB | Active ✅ | DNS: Route 53 • DNSSEC: ON | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| D-002 | blacktrigram.com | Hack23 AB | Active ✅ | DNS: Route 53 • DNSSEC: ON | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Sales](https://img.shields.io/badge/Process-Sales-darkgreen?style=for-the-badge&logo=handshake&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |

---

## 5) Intellectual Property

Statement: All copyrights remain with the CEO and sole owner of Hack23.com.

| Project | Repository | Website | 🏗️ Project Type | 🏢 Process Types |
|--------|------------|---------|------------------|------------------|
| 🎮 Black Trigram | https://github.com/Hack23/blacktrigram | https://blacktrigram.com | [![Frontend](https://img.shields.io/badge/Type-Frontend_Apps-yellow?style=for-the-badge&logo=window-maximize&logoColor=black)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) | [![Marketing](https://img.shields.io/badge/Process-Marketing-blueviolet?style=for-the-badge&logo=bullhorn&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Sales](https://img.shields.io/badge/Process-Sales-darkgreen?style=for-the-badge&logo=handshake&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| 🛡️ CIA Compliance Manager | https://github.com/Hack23/cia-compliance-manager | https://hack23.github.io/cia-compliance-manager/ | [![Compliance](https://img.shields.io/badge/Type-Compliance_Platform-green?style=for-the-badge&logo=clipboard-check&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) | [![Legal](https://img.shields.io/badge/Process-Legal-darkred?style=for-the-badge&logo=balance-scale&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| 🏛️ Citizen Intelligence Agency | https://github.com/Hack23/cia | https://hack23.com/cia-features.html | [![Analytics](https://img.shields.io/badge/Type-Data_Analytics-orange?style=for-the-badge&logo=chart-line&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) | [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| ☁️ Lambda in Private VPC | https://github.com/Hack23/lambda-in-private-vpc | - | [![Core](https://img.shields.io/badge/Type-Core_Infrastructure-red?style=for-the-badge&logo=server&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) | [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |
| 🔍 Sonar CloudFormation Plugin | https://github.com/Hack23/sonar-cloudformation-plugin | - | [![Security](https://img.shields.io/badge/Type-Security_Tools-darkblue?style=for-the-badge&logo=shield-alt&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#project-type-classifications) | [![Operations](https://img.shields.io/badge/Process-Operations-brown?style=for-the-badge&logo=cogs&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#business-process-types) |

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
      MFA on Google, GitHub, AWS
      Quarterly app reviews
      Passkeys where supported
      Single IdP strategy Google
    AWS Security 27 Services
      8 security services active
      GuardDuty threat detection
      Security Hub centralized
      Macie data discovery
      WAF application protection
      Inspector vulnerability scans
      Detective investigation
      Config compliance rules
      CloudTrail full audit
    Infrastructure Controls
      Control Tower governance
      Identity Center SSO
      KMS encryption everything
      VPC network isolation
      Route 53 DNSSEC
      S3 versioning enabled
      Glacier immutable backups
      WorkMail secure email
    SaaS Management
      Google IdP central
      18 integrated services
      Quarterly access audits
      Export procedures ready
      Alternative suppliers mapped
    Domains & DNS
      Route 53 hosted zones
      DNSSEC both domains
      Registrar locks active
      Auto-renewal configured
      Expiry alerts CloudWatch
    IP Protection
      5 active repositories
      Open source licensing
      Copyright CEO owned
      FOSSA compliance scan
      SonarCloud quality gate
```

### 6.2 SWOT — Comprehensive Asset Management

```mermaid
%%{
  init: { 'theme': 'base', 'themeVariables': { 'primaryColor': '#ffe0b2', 'lineColor': '#fb8c00' } }
}%%
mindmap
  root((SWOT Analysis))
    Strengths
      27 AWS services deployed
      8 dedicated security tools
      Control Tower multi-account
      100% MFA coverage
      DNSSEC all domains
      CloudTrail complete audit
      KMS encryption at rest
      Automated threat detection
      5 IP assets documented
    Weaknesses
      Single person dependency
      Access keys still active
      No break glass procedure
      Limited DR testing
      Manual security reviews
      18 SaaS dependencies
      Google IdP single point
    Opportunities
      Automate with AWS APIs
      Implement SCPs
      SSO token rotation
      Lambda automation
      GitHub Actions CI/CD
      API Gateway monetization
      DynamoDB scaling
      Cognito user management
    Threats
      Supply chain attacks
      Zero day vulnerabilities
      AWS service outages
      Sophisticated phishing
      NIS2 compliance changes
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
    AWS 27 Services
      Security 8
        WAF, GuardDuty, Detective
        Inspector, Macie, Security Hub
        Config, CloudTrail
      Infrastructure 11
        RDS, Route 53, WorkMail
        KMS, S3, VPC, Glacier
        CloudFront, Lambda
        Control Tower, Identity Center
      Monitoring 4
        CloudWatch, Events
        Cost Explorer, Data Transfer
      Planned 4
        API Gateway, DynamoDB
        Cognito, ECS Fargate
    SaaS 18 Services
      Critical 4
        GitHub, SEB, Stripe, Bokio
      Marketing 10
        YouTube, TikTok, X
        Product Hunt, LinkedIn
        Google Search Console
        Bing Webmaster
      Content 2
        Suno, ElevenLabs
      Security 2
        SonarCloud, FOSSA
    Domains 2
      hack23.com
      blacktrigram.com
    IP Assets 5
      Black Trigram game
      CIA Compliance Manager
      Citizen Intelligence Agency
      Lambda in Private VPC
      Sonar CloudFormation Plugin
```

### 6.4 Risk-Based Control Priorities

```mermaid
%%{
  init: { 'theme': 'base', 'themeVariables': { 'primaryColor': '#fce4ec', 'lineColor': '#f48fb1' } }
}%%
mindmap
  root((Risk Priorities))
    Critical Risks
      Single point of failure CEO
      AWS root account security
      Access key exposure
      Domain hijacking
      IP theft exposure
    High Risks  
      GitHub supply chain
      Google IdP dependency
      Data breach potential
      Compliance gaps NIS2
      WorkMail compromise
    Medium Risks
      Cost overruns AWS
      Service degradation
      Third party failures
      Documentation gaps
      Backup restore failures
    Low Risks
      Content generation delays
      Social media issues
      Free tier limits
      Marketing tool failures
      Analytics disruption
```

### 6.5 Comprehensive Security Posture

```mermaid
graph LR
    subgraph "🔐 Identity & Access"
        ID1[Google MFA]
        ID2[GitHub MFA]
        ID3[AWS SSO MFA]
        ID4[18 SaaS via Google]
    end
    
    subgraph "🛡️ AWS Security Stack"
        SEC1[8 Security Services]
        SEC2[CloudTrail Audit]
        SEC3[Control Tower]
        SEC4[KMS Encryption]
    end
    
    subgraph "🌐 Web & Domains"
        WEB1[hack23.com]
        WEB2[blacktrigram.com]
        WEB3[Route 53 DNSSEC]
        WEB4[CloudFront CDN]
    end
    
    subgraph "💼 Business Systems"
        BUS1[SEB Banking]
        BUS2[Bokio Accounting]
        BUS3[Stripe Payments]
        BUS4[WorkMail Email]
    end
    
    subgraph "🚀 Development"
        DEV1[GitHub Repos]
        DEV2[5 IP Assets]
        DEV3[Lambda Functions]
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

## 7) Change Log
| Date (UTC) | Change |
|------------|--------|
| 2025-11-05 | Added § 5.1 IPR Handling and § 5.2 Asset Return/Termination procedures (ISO 27001 A.5.11, A.5.32, A.6.5) |
| 2025-08-14 | Stripe status confirmed active (removed 'planned'); Insurance (Trygg Hansa) planned start 2025-09-01 |
| 2025-08-12 | Initial complete register created from provided inputs |

---

## 8) Compliance & Audit Trail
| Date | Finding | Action | Status |
|------|---------|--------|--------|
| 2025-08-14 | 27 AWS services documented | Complete service inventory | ✅ Completed |
| 2025-08-14 | 8 security services active | Enterprise-grade security posture | ✅ Active |
| 2025-08-14 | 18 SaaS services integrated | Documented dependencies | ✅ Completed |
| 2025-08-14 | 5 IP assets registered | Copyright protection confirmed (see Open Source Policy) | ✅ Active |
| 2025-08-14 | 2 domains with DNSSEC | Enhanced DNS security | ✅ Completed |
| 2025-08-14 | Access keys in use | Plan migration to SSO tokens | ⏳ In Progress |
| 2025-08-14 | No SCPs configured | Implement organizational policies | 🔴 Not Started |
| 2025-08-14 | No break-glass procedure | Document emergency access | 🔴 Not Started |

---

**📋 Document Control:**  
**✅ Approved by:** James Pether Sörling, CEO  
**📤 Distribution:** Public  
**🏷️ Classification:** [![Confidentiality: Public](https://img.shields.io/badge/C-Public-lightgrey?style=flat-square)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md#confidentiality-levels)  
**📅 Effective Date:** 2025-11-05  
**⏰ Next Review:** 2026-11-05  
**🎯 Framework Compliance:** [![ISO 27001](https://img.shields.io/badge/ISO_27001-2022_Aligned-blue?style=flat-square&logo=iso&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) [![NIST CSF 2.0](https://img.shields.io/badge/NIST_CSF-2.0_Aligned-green?style=flat-square&logo=nist&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md) [![CIS Controls](https://img.shields.io/badge/CIS_Controls-v8.1_Aligned-orange?style=flat-square&logo=cisecurity&logoColor=white)](https://github.com/Hack23/ISMS-PUBLIC/blob/main/CLASSIFICATION.md)
