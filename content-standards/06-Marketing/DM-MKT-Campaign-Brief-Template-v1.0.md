---
title: "Campaign Brief Template"
category: "Marketing"
status: "Approved"
last_updated: 2026-07-16
version: "1.0.0"
owner: "Marketing Team"
---

# Campaign Brief Template

This template defines the input schema for marketing campaign briefs. AI models can parse these parameters to auto-generate poster copy, landing pages, and email copy.

---

## 📇 Campaign Parameters (Input Schema)

```yaml
campaign:
  id: "CAMP-[PLATFORM]-[YYYY]-[INCREMENT]"
  title: "{{CAMPAIGN_TITLE}}"
  target_audience: "{{TARGET_AUDIENCE_PERSONA}}"
  primary_channel: "{{LINKEDIN_OR_GOOGLE_OR_WHATSAPP}}"
  value_proposition: "{{CORE_BENEFIT}}"
  cta_link: "https://dnyanmitra.com/{{CTA_PATH}}"
```

---

## 🏗️ Ad Copy Generation Framework

AI engines must map the campaign parameters above to generate three variations of the copy:

### Copy Variation 1: Problem-Solution Focus
- **Headline**: {{A compelling question addressing a direct operational pain point}}
- **Body**: {{Explain how the platform solves this pain, citing 15% average savings}}
- **CTA**: {{Action-oriented CTA button text}} | {{CTA_Link}}

### Copy Variation 2: Data-Driven Focus
- **Headline**: Save {{SAVINGS_PERCENTAGE}}% on your next {{SECTOR_NAME}} sourcing cycle
- **Body**: Compare multiple pre-vetted bids in 48 hours. Fully audit-ready for trust board compliance.
- **CTA**: {{Action-oriented CTA button text}} | {{CTA_Link}}

### Copy Variation 3: Short Social/WhatsApp Format
- **Copy**: {{A short, 3-bullet point text summarizing the value prop and registration URL}}
