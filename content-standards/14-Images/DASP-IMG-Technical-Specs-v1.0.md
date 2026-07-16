---
title: "Image Technical Specifications"
category: "Images"
status: "Approved"
last_updated: 2026-07-16
version: "1.0.0"
owner: "Marketing Team"
---

# Image Technical Specifications

This document outlines the technical formats, resolution guidelines, compression rules, and naming conventions for static graphics in all DASP Digital repositories.

---

## ⚙️ Technical Blueprint Matrix

To optimize page load times across mobile and web platforms, enforce the following technical criteria:

| Asset Category | Extension | Ideal Resolution / Aspect | Max Size | Notes |
| :--- | :--- | :--- | :--- | :--- |
| **Web Banners** | `.webp` | 1920 x 1080 (16:9) | 200 KB | Set compression rate to 80% |
| **Screenshots** | `.png` / `.webp` | 1280 x 720 (16:9) | 150 KB | Crop outer OS browser borders |
| **Icons & Logos** | `.svg` | Scalable Vector Graphic | 30 KB | Remove inline XML editor tags |
| **Headshots** | `.webp` | 512 x 512 (1:1) | 50 KB | For team bio and testimonials |

---

## 🗂️ Image File Naming Schema

All static files must use lowercase, hyphen-separated names indicating the target page, category type, description, and resolution parameters.

### Pattern
`[prefix]-[page-context]-[asset-category]-[description]-[resolution].[ext]`

### Examples
- *Correct*: `dm-homepage-banner-school-desks-1920x1080.webp`
- *Correct*: `km-dashboard-screenshot-booking-calendar-1280x720.png`
- *Incorrect*: `image_1.png`
- *Incorrect*: `PuneVendorList.PNG`

---

## 🛡️ Aesthetic & Cultural Guidelines

- **Indian Context Only**: Do not use stock images containing Western classrooms, lockers, or dollar notes. All graphics must display Indian schools, local vendors, and realistic domestic educational setups.
- **Contrast Check**: Ensure all visual text overlays have a contrast ratio of at least **4.5:1** against the background graphic (Web Content Accessibility Guidelines - WCAG 2.1 compliance).
- **Screenshot Masking**: Before uploading product screenshots, mask out all active database passwords, security tokens, private mobile numbers, and bank account numbers.
