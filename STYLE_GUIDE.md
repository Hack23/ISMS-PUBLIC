<p align="center">
  <img src="https://hack23.github.io/cia-compliance-manager/icon-192.png" alt="Hack23 Logo" width="192" height="192">
</p>

<h1 align="center">🎨 Hack23 AB — ISMS Style Guide</h1>

<p align="center">
  <strong>Consistency and Clarity in Security Documentation</strong><br>
  <em>Ensuring Professional and Transparent ISMS Documentation</em>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Owner-CEO-0A66C2?style=for-the-badge" alt="Owner"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-1.0-555?style=for-the-badge" alt="Version"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Review-Annual-orange?style=for-the-badge" alt="Review Cycle"/></a>
</p>

**Document Owner:** CEO | **Version:** 1.0 | **Last Updated:** 2025-08-14 (UTC)  
**Review Cycle:** Annual | **Next Review:** 2026-08-14

---

## 🎯 **Purpose**

This style guide establishes the standard format and structure for all Information Security Management System (ISMS) documents at Hack23 AB. Its purpose is to ensure consistency, clarity, and professionalism across all policies, procedures, and records.

---

## 📄 **Standard Document Structure**

All ISMS documents MUST follow this structure to maintain uniformity.

### 1. **Header Section**

The header provides an at-a-glance overview of the document.

```markdown
<p align="center">
  <img src="https://hack23.github.io/cia-compliance-manager/icon-192.png" alt="Hack23 Logo" width="192" height="192">
</p>

<h1 align="center">ICON & TITLE — [Document Title]</h1>

<p align="center">
  <strong>Tagline for the document</strong><br>
  <em>Sub-tagline emphasizing security and transparency</em>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Owner-CEO-0A66C2?style=for-the-badge" alt="Owner"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-1.0-555?style=for-the-badge" alt="Version"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Effective-[DATE]-success?style=for-the-badge" alt="Effective Date"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Review-[CYCLE]-orange?style=for-the-badge" alt="Review Cycle"/></a>
</p>

**Document Owner:** CEO | **Version:** 1.0 | **Last Updated:** YYYY-MM-DD (UTC)  
**Review Cycle:** [Cycle] | **Next Review:** YYYY-MM-DD
```

### 2. **Purpose Statement**

A section quoting the CEO that connects the document's purpose to Hack23's core principles of transparency and security excellence.

### 3. **Main Content**

The body of the document, organized with clear headings, tables, and diagrams (MermaidJS).

### 4. **Related Documents**

A section linking to other relevant ISMS documents.

### 5. **Document Control Footer**

Every ISMS document MUST end with this standardized footer. This section is critical for version control, accountability, and compliance.

```markdown
---

**Document Control:**  
**Approved by:** James Pether Sörling, CEO  
**Distribution:** [Audience - e.g., All Personnel, Key Suppliers]
**Classification:** [![Confidentiality: Level](https://img.shields.io/badge/C-[Level]-[Color]?style=flat-square)](./CLASSIFICATION.md#confidentiality-levels)  
**Effective Date:** YYYY-MM-DD  
**Next Review:** YYYY-MM-DD
```

---

## 📘 ISMS Markdown Style Essentials

### 1) Header and Badges (required, in this order)
- Centered logo img (192x192), then H1 with leading emoji.
- Subtitle line (bold + italic).
- Shields badges (centered): Owner • Version • Effective • Review.
- Document Owner/Version line below badges.

Example:
```markdown
<p align="center">
  <img src="https://hack23.github.io/cia-compliance-manager/icon-192.png" alt="Hack23 Logo" width="192" height="192">
</p>

<h1 align="center">🔐 Hack23 AB — Information Security Policy</h1>

<p align="center">
  <strong>Security Through Transparency and Excellence</strong><br>
  <em>Enterprise-grade Security for Innovation-driven Consulting</em>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Owner-CEO-0A66C2?style=for-the-badge" alt="Owner"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-1.0-555?style=for-the-badge" alt="Version"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Effective-2025--08--14-success?style=for-the-badge" alt="Effective Date"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Review-Annual-orange?style=for-the-badge" alt="Review Cycle"/></a>
</p>
```

### 2) Related Documents section (mandatory)
- Title: “## 📚 Related Documents” (or “## 📚 **Related Documents**” retaining bold if used).
- Each item must use an icon + linked filename + optional short descriptor.
- Use relative links. Do not include self-references.

Canonical list (pick items relevant to the document):
```markdown
## 📚 Related Documents
- [🔐 Information Security Policy](./Information_Security_Policy.md)
- [🔑 Access Control Policy](./Access_Control_Policy.md)
- [🌐 Network Security Policy](./Network_Security_Policy.md)
- [📝 Change Management Policy](./Change_Management.md)
- [💾 Backup & Recovery Policy](./Backup_Recovery_Policy.md)
- [🆘 Disaster Recovery Plan](./Disaster_Recovery_Plan.md)
- [🔄 Business Continuity Plan](./Business_Continuity_Plan.md)
- [💻 Asset Register](./Asset_Register.md)
- [📉 Risk Register](./Risk_Register.md)
- [🤝 Third-Party Management](./Third_Party_Management.md)
- [🏷️ Data Classification Policy](./Data_Classification_Policy.md)
- [🔒 Cryptography Policy](./Cryptography_Policy.md)
- [🛠️ Secure Development Policy](./Secure_Development_Policy.md)
- [📊 Security Metrics](./Security_Metrics.md)
- [🌐 ISMS Transparency Plan](./ISMS_Transparency_Plan.md)
```

### 3) Document Control footer (required)
- Always include Approval/Distribution/Classification/Effective/Next Review.
- Classification badge must link to the anchor in CLASSIFICATION.md.

Example:
```markdown
**Document Control:**  
**Approved by:** James Pether Sörling, CEO  
**Distribution:** All Personnel  
**Classification:** [![Confidentiality: High](https://img.shields.io/badge/C-High-blue?style=flat-square)](./CLASSIFICATION.md#confidentiality-levels)  
**Effective Date:** 2025-08-14  
**Next Review:** 2026-08-14
```

### 4) Icon and link conventions
- Use consistent icons:
  - 🔐 InfoSec • 🔑 Access • 🌐 Network • 📝 Change • 💾 Backup • 🆘 DRP • 🔄 BCP
  - 💻 Asset • 📉 Risk • 🤝 Third-Party • 🏷️ Data Class • 🔒 Crypto • 🛠️ SDLC • 📊 Metrics • 🌐 Transparency
- Avoid linking to the current document in Related Documents.
- Keep short descriptors after a hyphen where helpful.

### 5) Diagrams and badges
- Prefer Mermaid with meaningful labels and accessible alt text.
- Use shields.io styles consistently:
  - for-the-badge in headers; flat-square for inline badges (e.g., classification).

### 6) Canonical reference
- Treat Information_Security_Policy.md as canonical for structure, icons, and Related Documents formatting.

---

**Document Control:**  
**Approved by:** James Pether Sörling, CEO  
**Distribution:** All Personnel
**Classification:** [![Confidentiality: Low](https://img.shields.io/badge/C-Low-yellow?style=flat-square)](./CLASSIFICATION.md#confidentiality-levels)  
**Effective Date:** 2025-08-14  
**Next Review:** 2026-08-14
