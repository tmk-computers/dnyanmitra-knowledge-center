---
title: "Document Naming Conventions"
category: "Documentation"
status: "Approved"
last_updated: 2026-07-16
version: "1.0.0"
owner: "DASP Digital Team"
---

# Document Naming Conventions

This document establishes the file naming rules and YAML metadata schemas required for all files across the DASP Digital repository suite.

---

## 📐 The Naming Schema

Every markdown document created in this repository must use this format:

`[Prefix]-<Category>-<DocumentName>-v1.0.md`

### 1. Prefix (Platform Identifier)
- **`DM`**: DnyanMitra (Education B2B procurement)
- **`KM`**: KridaMitra (Sports & PE sourcing)
- **`KR`**: KrushiMitra (Agriculture marketplace)
- **`ZV`**: ZilaValley (Local governance & municipal contracting)
- **`DASP`**: Shared corporate standards, policies, and style guides

### 2. Category
Must be a 3-to-6 letter uppercase code indicating the directory or domain context:
- `BRAND` (Brand Guidelines)
- `PPT` (Presentations)
- `SPCH` (Speech & Pitch Scripts)
- `DOC` (Documentation Standards)
- `ROLE` (Role Manuals)
- `SALES` (Outbound Scripts & Sales Strategy)
- `MKT` (Marketing Copy & Campaign Briefs)
- `RES` (Research Reports & Insights)
- `SURVEY` (Surveys & Questionnaires)
- `PROC` (Procurement Specifications)
- `INST` (Institutional Excellence)
- `AI` (Prompt Engineering & Agent Rules)
- `WEB` (SEO & Landing Page Layouts)
- `TRAIN` (Training Manuals)
- `IMG` (Image Assets)
- `VID` (Video Production)
- `PROD` (Product Specs & API References)
- `KB` (Knowledge Base Self-Help)
- `SOP` (Standard Operating Procedures)
- `TEMP` (Master Templates)
- `CHK` (Quality Checklists)
- `GOV` (Lifecycle Policy)
- `STYLE` (Style Guides)
- `EX` (Practical Implementation Examples)
- `ARC` (Archiving Regulations)

### 3. Document Name
- Kebab-case, capitalization of major words separated by hyphens (e.g. `Cold-Calling`, `Guidelines`, `Taluka-Head`).

### 4. Version Suffix
- Every file must end in `-v[number].[number].md` (typically starting at `v1.0.md`).

---

## 📇 Frontmatter Metadata Schema

Every Markdown file must begin with a YAML block formatted precisely as follows:

```yaml
---
title: "Detailed Document Title"
category: "One of the standard folders"
status: "Draft / Approved / Deprecated"
last_updated: YYYY-MM-DD
version: "1.0.0"
owner: "Designated Team Owner"
---
```
