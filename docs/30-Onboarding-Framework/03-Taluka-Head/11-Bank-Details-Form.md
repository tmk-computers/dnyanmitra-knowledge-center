# Bank Details Verification Form

# Document Information
- **Document Name**: Bank Details Verification Form
- **Purpose**: Collect account routing info for direct commission settlement transfers.
- **Target Audience**: Partners, Operations Accountant.
- **Owner**: Finance Director
- **Version**: 1.0.0
- **Last Updated**: 2026-07-18
- **Review Frequency**: Annually
- **Related Documents**:
  - [03-KYC-Requirements.md](03-KYC-Requirements.md)

---

## 🏦 Account Routing Layout

- **Account Holder Legal Name**: [Must match Aadhaar/PAN name exactly]
- **Name of Bank**: [e.g. State Bank of India]
- **Account Type**: [Savings / Current]
- **Account Number**: [Full Account Number]
- **IFS Code**: [11-character Alphanumeric Code]
- **Branch Address**: [Full branch address details]

*A cancelled cheque or copy of passbook front page must be attached below.*

---

## 🏁 Review Checklist
- [ ] Conduct Pennydrop test (₹1 transaction) via payment gateway API.
- [ ] Confirm validation status matches CRM records.
