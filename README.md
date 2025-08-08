IntelliGRC is proud to present our final submission for the **FedRAMP 20x Phase One** pilot. 
This package reflects our commitment to advancing our goals of faster, more transparent, and scalable compliance 
reviews. We are excited to work with the program to deliver practical, automation‑driven solutions for the U.S. Government.

---

# IntelliGRC 20x Accelerator

**IntelliGRC** is a SaaS‑based compliance management platform designed with agentic AI capabilities to meet the needs of 
the **FedRAMP 20x** initiative. It brings together pre‑built security control configurations, streamlined evidence 
collection, and dedicated auditor collaboration tools to speed up the full compliance lifecycle—from initial preparation 
to continuous monitoring—while ensuring accuracy and repeatability.

**Key features:**

- Pre‑aligned platform configuration with 20x Key Security Indicators (KSIs)
- AI‑assisted evidence gathering with machine‑readable (JSON) output and standardized mappings
- Integrated auditor workspace (“Auditor View”) for review, annotation, and sign‑off
- Clear progression path toward FedRAMP Moderate or High as requirements evolve
- Continuous monitoring support with dashboards and exportable reporting

This submission demonstrates IntelliGRC’s readiness to help providers achieve faster, more consistent, and well‑documented 
compliance outcomes in alignment with the 20x program.

---

# Submission Package

The complete assessment is available to the FedRAMP PMO within the IntelliGRC **Insights** dashboard. 
For transparency, a public extract of the assessment and its schema are included.

| File                                                                        | Description                                        |
| --------------------------------------------------------------------------- | -------------------------------------------------- |
| **[IntelliGRC 20x Assessment File](IntelliGRC_20x_Assessment_Public.json)** | Public version of the assessment package           |
| **[IntelliGRC 20x Schema](IntelliGRC_20x_Schema.json)**                     | JSON schema describing the assessment data format  |

> Full details and additional artifacts are available in the secure Insights workspace.

---

# IntelliGRC Evidence & Review Approach

Purpose‑built for the 20x pilot’s goals—**automation, clarity, and reduced assessment effort**—IntelliGRC simplifies the 
entire compliance cycle. Our platform uses AI to consolidate and format evidence into machine‑readable outputs linked 
directly to the KSIs, reducing manual review effort and improving traceability.

**Our approach includes:**

- **KSI Mapping & Traceability**  
  Each KSI is linked to the relevant documentation, system data, and interview content, along with clear rationale. 
  Assertions are backed by verifiable, organized artifacts.

- **Auditor Collaboration**  
  Within Insights, auditors have a focused workspace to browse KSIs, review linked evidence, add notes, and mark decisions. 
  An API is available for exporting evidence packages for use in external review systems.

- **Machine‑Readable Evidence Packages**  
  Evidence is normalized into JSON aligned to our public schema, with details such as document identifiers, upload 
  metadata, and cryptographic hashes to preserve provenance.

- **Support for Continuous Monitoring**  
  Evidence remains tied to its associated KSI over time. This supports recurring validations and helps reduce redundant work 
  during re‑authorization efforts.

- **Designed for Reuse**  
  Evidence structures and workflows are reusable across different environments and compliance baselines, making it easier 
  to adapt to new requirements or updated KSIs.

---

# Ongoing KSI Tracking

The IntelliGRC 20x Accelerator provides continuous visibility into KSI coverage. The AI‑supported workflow:

- Links uploaded or collected evidence to the correct KSI(s)
- Summarizes and structures content for reviewer efficiency
- Identifies whether coverage is complete or additional materials may be needed
- Outputs results in JSON, including evaluation notes and supporting references

Where direct system data cannot be retrieved, customers can upload their own evidence files for review within the Auditor View.

---

# IntelliGRC in Practice

## Auditor View

The **Auditor View** in Insights gives reviewers a streamlined environment to evaluate current evidence, 
leave comments, request additional input, and confirm outcomes. An API allows downloading of 
evidence sets for integration with other auditing tools.

## AI‑Assisted Evidence Collection

Wherever possible, IntelliGRC agents gather data programmatically from integrated systems (e.g., cloud configurations, 
infrastructure scans). For evidence that requires manual submission—such as policy documents or architectural diagrams—
users can upload files directly. The AI engine then categorizes and summarizes these submissions for easy mapping to KSIs.

---

*For any questions about this submission or to request secure access to the full package, please contact the IntelliGRC team at* **[info@intelligrc.app](mailto:info@intelligrc.app)**.
