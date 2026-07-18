# DnyanMitra Knowledge Center

Welcome to the **DnyanMitra Knowledge Center**. This repository is the centralized content infrastructure and single source of truth for the **DnyanMitra** B2B procurement ecosystem and other upcoming platforms developed by **DASP Digital** (such as KridaMitra, KrushiMitra, and ZilaValley).

This repository does not contain application source code. It contains the standardized templates, guidelines, role playbooks, sales scripts, survey designs, product specifications, and governance policies required by employees, franchise partners, and AI agents.

---

## 📂 Repository Structure

The repository is organized into three primary hubs at the root level:

1. **[content-standards/](content-standards/) (Content Standards)**: Contains 25 folders detailing quality rules, stylesheets, presentation templates, and due diligence resources.
2. **[content/](content/) (Active Operations)**: Contains live presentations, sales calling scripts, and onboarding training guides.
3. **[docs/](docs/) (Operational Frameworks)**: Contains role onboarding workflows, legal templates, NDAs, and reporting forms.

### Onboarding Framework Directory
Located in [docs/30-Onboarding-Framework/](docs/30-Onboarding-Framework/):
- **Overview & Workflows**: Overview of roles and the 16-stage pipeline map.
- **03-Taluka-Head/**: Candidate forms, legal agreements, KYC checks, NDAs, and first-month plans for TH partners.
- **04-Field-Sales-Executive/**: HR files, salary structures, travel limits, and incentive frameworks for FSE staff.
- **05-Shared/**: Corporate profiles, manuals, catalogues, playbook logs, and escalation pathways.
- **06-Templates/**: Reusable emails, WhatsApp templates, minutes sheets, and review checklists.

---

## 📐 Document Naming Conventions

All documents (excluding directory-level `README.md` files) must use the following name structure:

`[Prefix]-<Category>-<DocumentName>-v[Version].md`

- **Prefixes**: `DM-` (DnyanMitra), `DASP-` (Shared corporate), `KM-` (KridaMitra), `KR-` (KrushiMitra), `ZV-` (ZilaValley).
- **Example**:
  - [DM-SALES-Cold-Calling-v1.0.md](content-standards/05-Sales/DM-SALES-Cold-Calling-v1.0.md) (DnyanMitra outbound phone script)
  - [DASP-STYLE-Writing-Mechanics-v1.0.md](content-standards/22-Style-Guide/DASP-STYLE-Writing-Mechanics-v1.0.md) (Shared style mechanics)

---

## 🤖 AI-Agent Sourcing & Auto-Generation

Every standard document in this repository is designed to be **AI-Friendly**. We utilize structured Markdown grids, YAML headers, and clear block declarations so that AI models can automatically generate downstream collateral (such as sales pitches, user manuals, RFP posts, and website copy) without requiring manual reformatting.

---

## 🤝 Contribution Guidelines

1. **Copy the Template**: To create a new standard or guide, start by copying the [DASP-TEMP-Master-Document-v1.0.md](content-standards/19-Templates/DASP-TEMP-Master-Document-v1.0.md).
2. **Execute the Checklist**: Run all verification checks inside the [DASP-CHK-Pre-Publishing-v1.0.md](content-standards/20-Checklists/DASP-CHK-Pre-Publishing-v1.0.md).
3. **Submit a Pull Request**: Submit your draft as a Git Pull Request. The changes will be reviewed by the folder owner according to the [DASP-GOV-Content-Lifecycle-v1.0.md](content-standards/21-Governance/DASP-GOV-Content-Lifecycle-v1.0.md) policy.
