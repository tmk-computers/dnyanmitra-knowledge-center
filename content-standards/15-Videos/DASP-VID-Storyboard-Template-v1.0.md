---
title: "Video Storyboard Template"
category: "Videos"
status: "Approved"
last_updated: 2026-07-16
version: "1.0.0"
owner: "Marketing Team"
---

# Video Storyboard Template

This template defines the visual structure, audio pacing, and technical parameters required for producing video collateral. AI agents can parse this layout to automatically feed prompts into AI video generation tools.

---

## ⚙️ Technical Export Specifications

Ensure all final exports align with these criteria:
- **Container / Codec**: MP4 (H.264 video codec, AAC audio codec).
- **Bitrate**: Minimum 10 Mbps for 1080p, 192kbps for audio.
- **Aspect Ratios**:
  - Horizontal (Default Walkthroughs): `1920 x 1080` (16:9), 30fps.
  - Vertical (Shorts/Reels): `1080 x 1920` (9:16), 30fps.

---

## 🏗️ Video Script & Storyboard Grid

Every script must separate visual directives, audio narration, and on-screen graphics into this structured schema:

```yaml
storyboard:
  video_id: "VID-[PLATFORM]-[YYYY]-[INCREMENT]"
  title: "{{VIDEO_TITLE}}"
  voice_pacing_wpm: 130 # Target words per minute
  frames:
    - number: 1
      visual_description: "Show a close-up of a school administrator looking frustrated while comparing multiple paper invoices and pricing quotes on a wooden desk."
      narration_voiceover: "Collecting and comparing school procurement quotes manually is a headache."
      onscreen_text: "Manual Procurement Delays"
      duration_seconds: 4.5
    - number: 2
      visual_description: "Transitions cleanly to a screen capture of the DnyanMitra dashboard, displaying 3 competitive vendor bids aligned side-by-side with highlight circles around the lowest cost bid."
      narration_voiceover: "DnyanMitra connects you with verified vendors, giving you side-by-side quotes in 48 hours."
      onscreen_text: "Compare 3+ Bids Instantly"
      duration_seconds: 6.0
```

---

## 🗣️ Audio & Subtitle Guidelines

- **Narration Tone**: Warm, professional, objective, and neutral Indian-accent English or clear standard Hindi.
- **On-Screen Text Accessibility**: All subtitles must be burned-in or provided via SRT sidecar files.
  - Subtitles must not exceed 2 lines per screen.
  - Max 32 characters per line to ensure readability on mobile displays.
