# DnyanMitra Content Standards Repository

Welcome to the **DnyanMitra Content Standards Repository**. This is the single source of truth for all content, design templates, sales guides, training documentation, and AI agent instructions for **DnyanMitra** and other platforms under **DASP Digital** (such as KridaMitra, KrushiMitra, ZilaValley).

This repository is built to be modular, scalable, and AI-friendly. All documents are written in professional Markdown with standard YAML frontmatter blocks and strict file naming conventions.

---

## 📐 Document Naming Conventions

All documents in this repository (excluding directory `README.md` files) follow this unified naming structure:

`[Platform/Owner]-<Category>-<DocumentName>-v1.0.md`

- **`DM-`**: DnyanMitra platform specific documents.
- **`KM-`**: KridaMitra platform specific documents (Future).
- **`KR-`**: KrushiMitra platform specific documents (Future).
- **`ZV-`**: ZilaValley platform specific documents (Future).
- **`DASP-`**: Shared corporate standards across all DASP Digital platforms.

### Examples
- `DM-SALES-Cold-Calling-v1.0.md` (DnyanMitra tele-sales script)
- `DM-ROLE-Taluka-Head-v1.0.md` (DnyanMitra Taluka regional leader role guide)
- `DASP-STYLE-Writing-Mechanics-v1.0.md` (Shared DASP Digital style mechanics guide)

---

## 📂 Repository Structure

The repository is structured into 24 specialized directories. Each directory contains a `README.md` defining its scope and a list of templates/examples following the naming conventions.

```text
content-standards/
├── README.md                           # This file (Repository Overview)
├── 01-Brand/                           # Brand guidelines & multi-platform expansion
├── 02-Presentations/                   # Presentation design systems & slide deck copy
├── 03-Documentation/                   # Markdown formatting & file naming guidelines
├── 04-Role-Guides/                     # Human role manuals & AI agent instructions
├── 05-Sales/                           # Outreach templates & cold calling scripts
├── 06-Marketing/                       # Campaign briefs & social media copy guidelines
├── 07-Research/                        # Academic and market intelligence publications
├── 08-Surveys/                         # Feedback loops & survey questionnaire design
├── 09-Procurement-Guides/              # Specifications sheets & RFP writing templates
├── 10-Institutional-Excellence/        # School trust board engagement resolutions
├── 11-AI/                              # Prompt engineering standards & system instructions
├── 12-Website/                         # Landing page structures & SEO metadata guides
├── 13-Training/                        # Onboarding playbooks & module checklists
├── 14-Images/                          # Naming conventions, formats, dimensions
├── 15-Videos/                          # Storyboards, script layouts, subtitle guides
├── 16-Product-Documentation/           # Release notes & API documentation templates
├── 17-Knowledge-Base/                  # KB article structures & search tag protocols
├── 18-SOP/                             # SOP structures & Mermaid workflow diagrams
├── 19-Templates/                       # Master document template (Markdown + YAML)
├── 20-Checklists/                      # Quality and pre-publishing checklists
├── 21-Governance/                      # Content lifecycle, review loops, access control
├── 22-Style-Guide/                     # Writing mechanics, spellings, numbers, currency
├── 23-Examples/                        # Reference files showcasing implementations
└── 24-Archive/                         # Deprecation and archiving rules
```

---

## 🤖 AI-Agent Interface Design

Every document in this repository is designed to be **AI-Friendly**. We use clear Markdown blocks, key-value mappings, and schema definitions to allow AI agents to automatically parse and generate downstream assets:
- **Slide Decks**: Structure slides automatically from JSON-like tables in `/02-Presentations`.
- **RFP Drafts**: Build RFPs directly using specification sheets in `/09-Procurement-Guides`.
- **Role Guides**: Auto-generate regional onboarding manuals using the `/04-Role-Guides` structure.
- **Style Compliance**: Run auto-checks on any generated content using the rules in `/22-Style-Guide` and `/20-Checklists`.
