---
title: "School and Vendor Feedback Surveys"
category: "Surveys"
status: "Approved"
last_updated: 2026-07-16
version: "1.0.0"
owner: "Operations Team"
---

# School and Vendor Feedback Surveys

This document defines the questions, metrics, and JSON specifications for customer feedback surveys within the DnyanMitra ecosystem.

---

## 🏫 School Feedback Questionnaire (Post-Procurement)

Use this format to collect feedback from school principals and trust board members after an RFP is completed:

```json
{
  "survey_id": "SURVEY-DM-SCHOOL-POST-PROC",
  "title": "School Procurement Feedback",
  "questions": [
    {
      "id": "q1",
      "text": "How would you rate the speed of collecting bids on DnyanMitra?",
      "type": "scale_5_point",
      "labels": ["Extremely Slow", "Slow", "Neutral", "Fast", "Extremely Fast"]
    },
    {
      "id": "q2",
      "text": "Were the side-by-side quote comparisons clear and easy to understand?",
      "type": "yes_no_neutral"
    },
    {
      "id": "q3",
      "text": "How satisfied were you with the quality of vendor communication?",
      "type": "scale_5_point",
      "labels": ["Extremely Dissatisfied", "Dissatisfied", "Neutral", "Satisfied", "Extremely Satisfied"]
    },
    {
      "id": "q4",
      "text": "Please share any suggestions for improving our verification process.",
      "type": "open_text"
    }
  ]
}
```

---

## 🚚 Vendor Feedback Questionnaire (Onboarding Phase)

Use this format to survey newly onboarded vendors within 30 days of registration:

```json
{
  "survey_id": "SURVEY-DM-VENDOR-ONBOARDING",
  "title": "Vendor Onboarding Feedback",
  "questions": [
    {
      "id": "v1",
      "text": "How clear was the DnyanMitra KYC and vetting process?",
      "type": "scale_5_point",
      "labels": ["Very Confusing", "Somewhat Confusing", "Neutral", "Clear", "Extremely Clear"]
    },
    {
      "id": "v2",
      "text": "Were you able to submit bids for active RFPs without tech support?",
      "type": "yes_no"
    },
    {
      "id": "v3",
      "text": "Which feature would help you submit quotes faster?",
      "type": "multiple_choice",
      "options": [
        "WhatsApp RFP Alerts",
        "Automated Bid Estimator",
        "Specifications Template Downloader",
        "Other"
      ]
    }
  ]
}
```
