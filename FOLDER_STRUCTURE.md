# Brand Assets Folder Structure

This repository follows a clear, scalable organizational system for brand assets and design tokens.

## Repository Structure

```
Aioverse-Design-System/
├── .github/                  CI/CD workflows
│   ├── steps/                  GitHub step documentation
│   └── workflows/              GitHub Actions (Jekyll, CI)
├── assets/
│   └── logos/                  [AIO-LOGO] Brand logo files
├── fonts/                    [AIO-FONT] Typography assets
│   ├── primary/Nohemi/         Primary brand typeface
│   └── secondary/TokyoTrailMono/ Accent/mono typeface
├── logos/                    [AIO-LOGO] Extended logo variations
│   ├── svg/                    Scalable vector logos (digital, print)
│   ├── png/                    Raster logos (web, presentations)
│   └── pdf/                    High-quality vector (print, docs)
├── icons/                    [AIO-ICON] Icon sets and UI icons
│   ├── 24px/                   Standard UI icons
│   ├── 32px/                   Medium display icons
│   └── 48px/                   Touch target icons
├── illustrations/            [AIO-ILLUS] Brand artwork
├── photos/                   [AIO-PHOTO] Photography assets
├── guidelines/               [AIO-GUIDE] Brand documentation
├── tokens/                   [AIO-TOKEN] Design tokens
│   ├── json/                   JSON token export
│   ├── css/                    CSS variable exports
│   └── figma/                  Figma token files
├── agents/                   [AIO-AI] Copilot AI agents
├── docs/                     Additional documentation
├── README.md
├── AIOTIZE_BRAND_PERSONA.md
├── AIOVERSE_VISUAL_SYSTEMS.md
├── AIOVERSE_NAMING.md
├── AIOVERSE_ECOSYSTEM.md
├── AIOVERSE_BRAND_IMPLEMENTATION.md
├── BRAND_GUIDELINES_CHECKLIST.md
├── FIGMA_NOTION_SETUP_GUIDE.md
├── FOLDER_STRUCTURE.md (this file)
├── AIOVERSE_USAGE_GUIDE.md
└── SUMMARY.md
```

## Folder Descriptions

### `fonts/` [AIO-FONT]
Contains all typeface files organized by usage category.
- `primary/Nohemi/` - Primary brand typeface (headlines, display)
- `secondary/TokyoTrailMono/` - Accent/monospace typeface (code, tech)
- Formats: WOFF2 (web), WOFF (legacy), TTF (desktop)

### `logos/` and `assets/logos/` [AIO-LOGO]
Brand logo files in various formats and sizes.
- `svg/` - Scalable vector logos (digital and print)
- `png/` - Raster logos with transparent backgrounds (web, presentations)
- `pdf/` - High-quality vector logos (print and documentation)
- Includes: Primary mark, wordmark, symbol/icon only, horizontal, vertical

### `icons/` [AIO-ICON]
Icon sets and UI icons (SVG, PNG).
- Organized by size: 24px, 32px, 48px
- Consistent 2px stroke weight
- Categories: Navigation, Action, Status, Social, Utility

### `illustrations/` [AIO-ILLUS]
Brand illustrations and custom artwork.
- Brand character illustrations
- Scene compositions
- Landing page graphics
- Formats: SVG (preferred), PNG, AI

### `photos/` [AIO-PHOTO]
Brand photography and image assets.
- Product, team, hero images
- Resolution: 300 DPI (print), 72 DPI (web)

### `guidelines/` [AIO-GUIDE]
Brand guidelines documentation and reference materials.
- Voice and tone guide
- Logo usage rules
- Color specifications
- Typography guidelines

### `tokens/` [AIO-TOKEN]
Design tokens source of truth.
- Color tokens (primary, secondary, semantic)
- Typography tokens (font families, scales)
- Spacing tokens (8px base unit)
- Border, shadow, motion tokens
- Formats: JSON, CSS variables, Figma tokens

### `agents/` [AIO-AI]
GitHub Copilot custom agents for AI-assisted brand work.
- `aioverse-brand-agent.md` - Brand design specialist agent

---

## Usage

1. **Designers**: Use `guidelines/` and `logos/` for brand reference
2. **Developers**: Reference `tokens/` for CSS variables, spacing, typography
3. **Asset Management**: Add new files to appropriate type-based folders

## Naming Conventions

- Use descriptive folder names (lowercase, hyphens for spaces)
- Keep file names consistent and version-numbered when needed: `v1`, `v2`
- Use subfolders within main categories for further organization
- Follow Aioverse naming: `[CATEGORY]-[TYPE]-[VARIANT]-[VERSION].[FORMAT]`

---

**Maintained By:** Aiotize Design Systems Team  
**Last Updated:** March 2026
