---
title: "AI RFP Writing Template"
category: "Procurement Guides"
status: "Approved"
last_updated: 2026-07-16
version: "1.0.0"
owner: "Operations Team"
---

# AI RFP Writing Template

This template defines the input parameter schema and markdown structure for school Request for Proposals (RFPs). AI agents can parse these configurations to automatically publish live bidding pages.

---

## 📇 RFP Parameters (Input Schema)

```yaml
rfp_parameters:
  id: "DM-RFP-[YYYY]-[INCREMENT]"
  school_name: "{{SCHOOL_NAME}}"
  delivery_address: "{{FULL_DELIVERY_ADDRESS}}"
  contact_person: "{{CONTACT_PERSON_NAME}}"
  bid_deadline: "YYYY-MM-DD HH:MM IST"
  expected_delivery: "Within {{DAYS}} days from purchase order"
  payment_terms: "{{PAYMENT_MILESTONES}}"
```

---

## 🏗️ RFP Layout Structure

AI systems must output the final school RFP document strictly matching this structure:

# Request for Proposal: {{ITEM_CATEGORY_OR_NAME}}

### RFP ID: {{RFP_ID}} | Date Posted: {{POST_DATE}}

---

## 🏫 1. Issuing Institution
- **School Name**: {{SCHOOL_NAME}}
- **Delivery Campus**: {{DELIVERY_ADDRESS}}
- **Contact Representative**: {{CONTACT_PERSON}}

---

## 🛠️ 2. Item Requirements & Spec Sheet Reference
List all required materials in this table:

| Item Name | Required Quantity | Core Technical Dimension Requirement | Reference Sheet |
| :--- | :--- | :--- | :--- |
| {{ITEM_1}} | {{QTY_1}} | {{DIM_1}} | [Spec-Sheet-URL] |
| {{ITEM_2}} | {{QTY_2}} | {{DIM_2}} | [Spec-Sheet-URL] |

---

## 🤝 3. Bid Submission Guidelines
- **Deadline**: All bids must be submitted digitally via DnyanMitra by **{{BID_DEADLINE}}**.
- **Mandatory Vendor Attachments**:
  - Valid GSTIN Certificate.
  - Signed Conflict of Interest Disclaimer.
  - Price bid breakdown per item in INR.

---

## ⚖️ 4. Payment Terms & Delivery SLA
- **Delivery Deadline**: {{EXPECTED_DELIVERY}}
- **Payment Terms**: {{PAYMENT_TERMS}}
