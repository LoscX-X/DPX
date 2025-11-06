#  DPX Format Usage & Protection Agreement v1.0

This Agreement governs the legal status, permitted use, and protective rights associated with any digital artwork distributed under the **DPX format (Drawing Protected eXtended)**.

By creating, distributing, processing, transmitting, or storing files in the `.dpx` format, you agree to comply with the terms outlined herein.

---

## 1. Definition of the DPX Format

**1.1.** The DPX format (.dpx) is an open digital container designed to protect and extend the integrity of artistic works by encoding:

- The final rendered image;
- The full or segmented drawing process data (including stroke paths, timestamps, and pen pressure);
- Author identity, copyright declaration, and metadata;
- A cryptographic proof of authorship (digital signature).

**1.2.** DPX is primarily intended for digital painting, hand-drawn, or otherwise human-authored works that rely on time-based, process-validated creation methods.

---

## 2. Ownership & Copyright

**2.1.** All DPX files are the exclusive property of their original creator and are protected by applicable international copyright laws.

**2.2.** Any artwork, drawing log, metadata, or signature embedded within a DPX file constitutes copyright-protected material.

**2.3.** Redistribution, reproduction, adaptation, display, or any other use of DPX content without explicit consent from the creator is strictly prohibited unless otherwise indicated in the file’s metadata.

---

## 3. Anti-AI Training Clause

**3.1.** If the `allow_AI_training` flag within the DPX MetaBlock is set to **false**, the following actions are explicitly prohibited:

- Using the file, in whole or in part, for AI or machine learning training, fine-tuning, or data augmentation;
- Inclusion in any public or private dataset;
- Use as input, context, or reference in automated content generation systems;
- Derivation of visual or stylistic information for model training or imitation.

**3.2.** Any attempt to:

- Remove or alter this flag;
- Strip metadata from the DPX file;
- Repackage or convert the file to bypass protection mechanisms; or
- Forge or re-generate stroke or signature data

shall constitute deliberate circumvention of digital rights protection and may be deemed a legal violation under international law.

---

## 4. Obligations of Platforms, Tools, and AI Developers

**4.1.** Any software, platform, or service that processes or transmits image data must detect and respect the `allow_AI_training` field embedded in the DPX file.

**4.2.** Ignoring such restrictions, or intentionally bypassing the embedded license terms, does not constitute a valid defense against copyright infringement.

**4.3.** Developers, dataset providers, and model trainers are legally obligated to:

- Identify and exclude DPX files marked as not permitted for AI use;
- Maintain reasonable technical measures to prevent ingestion of protected works;
- Halt data transmission and remove cached content upon discovering violations.

---

## 5. Integrity and Signature Requirements

**5.1.** DPX files may contain a digital signature block (e.g., Ed25519) verifying file integrity and authorship authenticity.

**5.2.** Applications displaying or parsing DPX content should reject files with unverifiable signatures or hash mismatches.

**5.3.** Any modification to protected data without proper re-signing invalidates the file’s authenticity and constitutes tampering.

---

## 6. Prohibited Uses & Violations

You may not:

- Remove or alter embedded metadata, including stroke logs, author identity, or licensing terms;
- Repackage DPX files into other formats without preserving legal and integrity information;
- Attempt to suppress DPX detection in datasets or AI pipelines;
- Claim authorship or ownership of any DPX content without legal basis.

Violations may result in:

- Revocation of rights to use the DPX format;
- Legal or civil action, including copyright claims;
- Statutory and punitive damages.

---

## 7. License for Implementors

**7.1.** The DPX specification and its reference libraries may be implemented freely under open or closed-source licenses.

**7.2.** Implementors may not:

- Redistribute altered specifications under the “DPX” name without clear attribution;
- Embed bypass mechanisms that undermine the legal protections of the DPX format.

---

## 8. Enforcement & Legal Governance

**8.1.** This Agreement is governed by international copyright laws and digital rights treaties, including but not limited to:

- WIPO Copyright Treaty (WCT)
- Berne Convention
- Digital Millennium Copyright Act (DMCA, United States)
- Digital Single Market Directive (European Union)

**8.2.** In case of dispute, jurisdiction shall be determined by the creator’s country of registration or as defined in derivative licensing agreements.

**8.3.** Violations carry the same legal weight as unauthorized reproduction or distribution of copyrighted material.

---

## 9. Contact & Revision

This document is version **1.0**, published **2025-11-05**.  
Comments, proposals, or compliance requests may be directed to the author(s) or the **DPX Community Standards Committee**.

---

## 10. Retroactive Copyright Declaration

**10.1.** Any pre-existing artwork—whether in PNG, JPG, WebP, PSD, or other formats—shall immediately inherit full DPX protection once converted and published in `.dpx` form by the original author.

**10.2.** Prior unauthorized use, scraping, or dataset inclusion of such works shall not constitute implied consent or waiver of rights.  
Past actions performed without explicit authorization remain infringing acts under this Agreement.

**10.3.** If, after DPX publication, any third party continues to:

- Use, distribute, or publicly display the work;
- Employ it for AI training or content generation;
- Claim retention rights by referencing prior dataset inclusion,

then the creator retains the full right to:

- Demand removal or model retraining;
- Issue public infringement notices;
- Pursue legal and financial damages.

**10.4.** This clause affirms that copyright persists regardless of file format or historical misuse.  
The DPX format merely manifests stronger technical protection — it does not reset or dilute pre-existing rights.  
In other words, “prior infringement cannot be legitimized retroactively; only creator re-authorization establishes lawful use.”

Works protected under DPX do not recognize the concept of “grandfathered infringement.”

---

## 11. Special Clause Against Forced AI Training or Forced Licensing by Platforms

**11.1.** This Agreement explicitly forbids any platform, host, or service provider from coercing users—through terms of service, upload conditions, or technical restrictions—into consenting to AI training, data scraping, model fine-tuning, or derivative analysis.

**11.2.** If a `.dpx` file contains `allow_AI_training = false`, then:

- The author retains the full and unconditional right to refuse AI usage;
- Platforms cannot assume “upload implies consent”;
- Any forced authorization clause conflicting with this declaration is invalid;
- Platform terms cannot override international copyright and moral rights of creators.

**11.3.** Any claim that “uploading content implies permission for AI training” constitutes a false presumption and violates the principle of independent consent.  
Creators retain the right to:

- Demand cessation of unauthorized AI model use;
- Request deletion of related data, outputs, or derivative models;
- Trace and disclose the origin of infringing datasets or model outputs.

**11.4.** Platforms are strictly prohibited from:

- Making AI training authorization a prerequisite for account creation, uploads, or service access;
- Using technical constraints (e.g., locked consent checkboxes or forced acceptance dialogs) to override user rights.  
Such practices are considered illegal coercion and overreach of authority.

**11.5.** Any platform that removes, modifies, or conceals DPX anti-AI metadata commits a technical circumvention act, potentially violating:

- DMCA §1201 Anti-Circumvention provisions;
- EU Digital Single Market Directive;
- Domestic laws protecting digital work integrity.

**11.6.** DPX creators may enforce their rights through:

- Official DMCA takedown or legal notices;
- Public documentation of platform violations;
- Anti-circumvention complaints to regulatory authorities;
- Requests for model takedowns, retraining, or output removal.

---

### 🏁 Termination Clause

All rights not expressly waived remain fully reserved by the **DPX creator**.

---

© 2025 DPX Community Standards Committee. All rights reserved.
