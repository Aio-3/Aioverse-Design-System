# Aioverse Brand Assets - Complete Usage Guide

## Overview

Aioverse is the universal naming component and organizational framework for Aiotize Inc.'s brand ecosystem. This guide helps designers, developers, and stakeholders properly utilize all brand assets.

**Repository Code:** aio3-brand-assets  
**Aioverse Code:** AIO-BRAND  
**Purpose:** Centralized hub for all Aiotize Inc. brand assets, design tokens, and visual systems  
**Maintained By:** Aiotize Design Systems Team  
**Last Updated:** December 11, 2025

---

## Getting Started

### Quick Access
- **Repository:** https://github.com/Aio-3/Aioverse-Design-System
- **Website:** https://aio3.ai
- **Figma:** https://www.figma.com/design/GI2yrpDMzHWpb0lrsVxGMf/Aioverse

### Repository Structure
```
Aioverse-Design-System/
├── .github/            [CI/CD] - GitHub Actions workflows
├── assets/logos/       [AIO-LOGO] - Brand logo files
├── fonts/              [AIO-FONT] - Typography assets
├── icons/              [AIO-ICON] - Icon library
├── illustrations/      [AIO-ILLUS] - Custom illustrations
├── photos/             [AIO-PHOTO] - Photography assets
├── guidelines/         [AIO-GUIDE] - Brand guidelines
├── tokens/             [AIO-TOKEN] - Design tokens
├── agents/             [AIO-AI] - Copilot AI agents
├── README.md           - Project overview
├── AIOTIZE_BRAND_PERSONA.md
├── AIOVERSE_VISUAL_SYSTEMS.md
├── AIOVERSE_NAMING.md
├── AIOVERSE_ECOSYSTEM.md
├── AIOVERSE_BRAND_IMPLEMENTATION.md
├── BRAND_GUIDELINES_CHECKLIST.md
├── FIGMA_NOTION_SETUP_GUIDE.md
├── FOLDER_STRUCTURE.md
└── AIOVERSE_USAGE_GUIDE.md (this file)
```

---

## Asset Categories

### 1. Fonts [AIO-FONT]
**Location:** `/fonts/`  
**Primary:** Nohemi (headlines, display)  
**Accent:** TokyoTrailMono (code, tech content)  
**System:** Inter (body, UI elements)  

**Formats:** WOFF2 (web), WOFF (legacy web), TTF (desktop)  
**Usage:**
- Web: Include via `@font-face` or CDN
- Design: Install locally for Figma/Adobe

### 2. Logos [AIO-LOGO]
**Location:** `/assets/logos/` and `/logos/`  
**Variations:** Full wordmark, symbol/mark, horizontal, vertical  
**Formats:** SVG (vector), PNG (transparent), PDF, AI  

**Minimum Sizes:**
- Digital: 120px width
- Print: 1 inch width  
- Favicon: 32x32px

### 3. Icons [AIO-ICON]
**Location:** `/icons/`  
**Sizes:** 24px (UI), 32px (larger displays), 48px (touch targets)  
**Style:** Consistent 2px stroke, SVG format  
**Categories:** Navigation, Action, Status, Social, Utility

### 4. Illustrations [AIO-ILLUS]
**Location:** `/illustrations/`  
**Contents:** Brand characters, scene compositions, landing page art  
**Formats:** SVG (preferred), PNG, Figma source

### 5. Photography [AIO-PHOTO]
**Location:** `/photos/`  
**Categories:** Product, team, hero images, backgrounds  
**Resolution:** 300 DPI (print), 72 DPI (web)

### 6. Guidelines [AIO-GUIDE]
**Location:** `/guidelines/`  
**Contents:** Voice/tone, logo rules, color specs, typography guidelines

### 7. Design Tokens [AIO-TOKEN]
**Location:** `/tokens/`  
**Token Types:** Color, Typography, Spacing, Border, Shadow, Motion  

```json
{
  "aio": {
    "color": {
      "primary": { "value": "#00D4FF", "type": "color" },
      "secondary": { "value": "#00A8CC", "type": "color" }
    },
    "spacing": {
      "xs": { "value": "4px" },
      "sm": { "value": "8px" },
      "md": { "value": "16px" },
      "lg": { "value": "24px" },
      "xl": { "value": "32px" }
    }
  }
}
```

---

## Logo Usage

### Do's
- Use provided logo files, maintain aspect ratio
- Ensure clear space (minimum logo height around logo)
- Use on contrasting backgrounds

### Don'ts
- Stretch or distort the logo
- Change colors without approval
- Add effects or shadows
- Use outdated versions

---

## Color Palette Quick Reference

| Color | Hex | Usage |
|-------|-----|-------|
| Teal Primary | #00D4FF | CTAs, active states |
| Teal Secondary | #00A8CC | Professional backgrounds |
| Deep Teal | #003F5C | Grounded, stable |
| Green | #10B981 | Success, positive |
| Blue | #3B82F6 | Trust, reliability |
| Purple | #A855F7 | Innovation |
| Red | #EF4444 | Alerts, errors |

---

## Best Practices

### For Designers
1. Always use latest assets from this repository
2. Follow design tokens for colors and spacing
3. Validate color accessibility (WCAG AA: minimum 4.5:1)

### For Developers
1. Use CSS variables from `tokens/` folder
2. Optimize images (WebP, WOFF2)
3. Add alt text to images

### For Product Managers
1. Review designs against brand guidelines
2. Track asset usage and licensing
3. Keep inventory updated

---

## File Naming Convention

```
[CATEGORY]-[TYPE]-[VARIANT].[FORMAT]

Examples:
  AIO-LOGO-PRIMARY-COLOR.svg
  AIO-ICON-ARROW-24.svg
  AIO-FONT-PRIMARY-BOLD.woff2
  AIO-PHOTO-TEAM-01.jpg
```

---

## Support

- **Issues:** Report via GitHub Issues
- **Questions:** design-systems@aiotize.com
- **Figma:** https://www.figma.com/design/GI2yrpDMzHWpb0lrsVxGMf/Aioverse

---

**© 2025 Aiotize Inc. All rights reserved.**  
**Last Updated:** December 11, 2025  
**Maintained By:** Aiotize Design Systems Team
