---
title: "Content Pre-Publishing Checklist"
category: "Checklists"
status: "Approved"
last_updated: 2026-07-16
version: "1.0.0"
owner: "DASP Digital Team"
---

# Content Pre-Publishing Checklist

This document details the mandatory quality checks that human copywriters and AI agents must run before merging any document or deploying public copy.

---

## 🗂️ 1. Technical & Syntax Checks
- [ ] **Frontmatter Block**: Verify that a valid YAML frontmatter block is present at the very top of the file, with all fields (`title`, `category`, `status`, `last_updated`, `version`, `owner`) populated.
- [ ] **No Placeholders**: Scan the document for bracketed text (e.g. `[Insert Date]`) or Latin fillers. Ensure dynamic variables use `{{variable_name}}`.
- [ ] **File Links**: Verify all file links are valid and active. Ensure they use the `file:///` protocol and do NOT have backticks surrounding the link text.
- [ ] **Markdown Syntax**: Ensure all tables, bulleted lists, and blockquotes render correctly without broken markers.

---

## 🗣️ 2. Brand & Language Checks
- [ ] **Spelling Standard**: Confirm that all spellings align with UK/India conventions (e.g., `programme`, `centre`, `organisation`, `digitise`). Run a spellcheck.
- [ ] **Hype Word Ban**: Check for and remove promotional words like *revolutionary, cutting-edge, disruptive, game-changer, supercharge*.
- [ ] **Tone Alignment**: Check if the tone is appropriate for the target audience:
  - Formal and respectful for schools.
  - Clear and business-focused for vendors.
- [ ] **Standard Vocabulary**: Ensure correct terms are used (e.g. `Pre-Vetted Vendor` instead of `Seller`, `RFP` instead of `Order`).

---

## 🔍 3. SEO Checks (Web Pages Only)
- [ ] **H1 Constraint**: Confirm there is exactly **one** H1 heading (`#`) on the page.
- [ ] **SEO Character Limits**: Check that the title tag is 50-60 characters and the meta description is 120-150 characters.
- [ ] **Image Alt Text**: Confirm all referenced image tags include meaningful description strings in the alt field.

---

## 🔒 4. Governance & Privacy Checks
- [ ] **Anonymization**: Verify that no live customer passwords, private keys, database connection strings, or personal phone numbers are hardcoded.
- [ ] **Owner Sign-off**: Ensure the designated document owner listed in the metadata has reviewed and approved the content.
