---
title: "AI Presentation Template"
category: "Presentations"
status: "Approved"
last_updated: 2026-07-16
version: "1.0.0"
owner: "Marketing Team"
---

# AI Presentation Template

This template is structured so that AI agents can parse the layout parameters and content blocks to auto-generate slide decks (e.g., in PPTX, HTML slides, or PDF) without requiring manual formatting.

---

## 🎨 Design System Variables (AI Configuration)

AI engines generating slides from this file must apply these CSS/Design tokens:

```json
{
  "theme": {
    "aspect_ratio": "16:9",
    "fonts": {
      "header": "Outfit-Bold",
      "body": "Inter-Regular"
    },
    "colors": {
      "dark_background": "#0B3C5D",
      "light_background": "#F9F9F9",
      "primary_text_dark": "#FFFFFF",
      "primary_text_light": "#1D2731",
      "accent_highlight": "#D9B310",
      "slate_muted": "#328CC1"
    }
  }
}
```

---

## 🏗️ Slide Blocks

Use the `<SLIDE>` and `</SLIDE>` tags to define separate slides.

<SLIDE type="title" background="dark_background">
# {{SLIDE_TITLE}}
## {{SLIDE_SUBTITLE}}

**Footer**: DnyanMitra – Powered by DASP Digital
</SLIDE>

<SLIDE type="content" background="light_background">
## {{SECTION_HEADER}}

- **{{POINT_1_HEADER}}**: {{POINT_1_BODY}}
- **{{POINT_2_HEADER}}**: {{POINT_2_BODY}}
- **{{POINT_3_HEADER}}**: {{POINT_3_BODY}}

**Visual Asset**: {{IMAGE_PATH_OR_DIAGRAM_DESCRIPTION}}
</SLIDE>

<SLIDE type="data" background="light_background">
## {{DATA_SLIDE_HEADER}}

| Metric | Target Value | Direct Impact |
| :--- | :--- | :--- |
| {{METRIC_1}} | {{VALUE_1}} | {{IMPACT_1}} |
| {{METRIC_2}} | {{VALUE_2}} | {{IMPACT_2}} |

> [!TIP]
> {{STRATEGIC_TAKEAWAY}}
</SLIDE>

<SLIDE type="closing" background="dark_background">
# {{CLOSING_HOOK}}
## Contact Us to Begin Onboarding

- **Web**: [dnyanmitra.com](https://dnyanmitra.com)
- **Email**: {{CONTACT_EMAIL}}
- **Phone**: {{CONTACT_PHONE}}
</SLIDE>
