---
title: "Deprecation and Archiving Rules"
category: "Archive"
status: "Approved"
last_updated: 2026-07-16
version: "1.0.0"
owner: "DASP Digital Team"
---

# Deprecation and Archiving Rules

This document establishes the official procedure for deprecating, renaming, and moving outdated files within the DASP Digital repository suite.

---

## 🧭 Why Archive?

To prevent active users, writers, and automated AI agents from referencing obsolete business rules, outdated software specs, or old brand assets. We never delete files outright; moving them to the `/24-Archive` directory preserves administrative history while keeping active directories clean.

---

## 🔄 Archiving Steps

When a file is identified as obsolete:

1. **Update YAML Status**: Open the target file's YAML block and set `status: "Deprecated"`. Set `last_updated` to the current date.
2. **Rename File**: Prepend `deprecated-` to the filename (e.g. `DM-SOP-Vendor-KYC-Verification-v1.0.md` becomes `deprecated-DM-SOP-Vendor-KYC-Verification-v1.0.md`).
3. **Move File**: Move the file into `/24-Archive`.
4. **Link Clean-Up**: Search the workspace for files linking to the old path. Update those links to point to the new location or remove the links.

---

## 📓 Log of Deprecated Documents

List deprecated documents below:

| Date | Deprecated File Path | New Replacement Reference | Reason |
| :--- | :--- | :--- | :--- |
| *No entries yet* | – | – | – |
