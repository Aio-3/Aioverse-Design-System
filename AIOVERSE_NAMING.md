# Aioverse Naming System & Asset Taxonomy

> **Aioverse™** is the universal naming component and organizational framework for Aiotize Inc.'s brand assets, design systems, and digital ecosystem.

## 1. Aioverse Core Principles

### Philosophy
- **Universal**: One consistent naming convention across all Aiotize ecosystems
- **Semantic**: Names convey purpose, category, and hierarchy
- **Scalable**: Grows with organizational complexity without losing clarity
- **Accessible**: Easy to read, remember, and search for all team members

### Core Tenets
1. **Asset-First Naming** - Assets define their category and purpose
2. **Hierarchical Clarity** - Folder depth reflects conceptual hierarchy
3. **Consistency Over Creativity** - Predictable naming beats unique names
4. **Localization-Ready** - Framework supports multi-language teams

---

## 2. Aioverse Asset Classification

All assets fall into one of these primary categories:

### Category: `fonts/`
- **Aioverse Code**: `AIO-FONT`
- **Purpose**: Typography system for all brand communications
- **Structure**: `fonts/[weight]/[family-name]/`
- **Example**: `fonts/primary/Nohemi/` (primary typeface)
- **Example**: `fonts/secondary/TokyoTrailMono/` (accent typeface)
- **Naming Pattern**: `[FontName]-[Weight]-[Style].[format]`
  - `Nohemi-Regular.woff2`
  - `Nohemi-Bold-Italic.ttf`

### Category: `logos/`
- **Aioverse Code**: `AIO-LOGO`
- **Purpose**: Primary and secondary brand marks
- **Structure**: `logos/[variation]/[format]/`
- **Naming Pattern**: `Aioverse-[Type]-[Version]-[ColorMode].[format]`
  - `Aioverse-Primary-v1-Dark.svg`
  - `Aioverse-Wordmark-v1-Light.png`
  - `Aioverse-Symbol-v1-Mono.pdf`

### Category: `icons/`
- **Aioverse Code**: `AIO-ICON`
- **Purpose**: UI icons and symbol sets
- **Structure**: `icons/[set-name]/[variant]/`
- **Naming Pattern**: `[IconName]-[Size]-[State].[format]`
  - `menu-24-default.svg`
  - `close-32-hover.png`
  - `aio-logo-16-active.svg`

### Category: `illustrations/`
- **Aioverse Code**: `AIO-ILLUS`
- **Purpose**: Custom illustrations and visual narratives
- **Structure**: `illustrations/[style]/[use-case]/`
- **Naming Pattern**: `[Concept]-[Scene]-[Version].[format]`
  - `Workflow-Dashboard-v1.svg`
  - `Team-Collaboration-v2.png`

### Category: `photos/`
- **Aioverse Code**: `AIO-PHOTO`
- **Purpose**: Branded photography and imagery
- **Structure**: `photos/[subject]/[collection]/`
- **Naming Pattern**: `Aioverse-[Subject]-[DateTaken]-[Reference].[format]`

### Category: `guidelines/`
- **Aioverse Code**: `AIO-GUIDE`
- **Purpose**: Brand standards, usage rules, and documentation
- **Structure**: `guidelines/[aspect]/`
- **Naming Pattern**: `Aioverse-[Aspect]-Guidelines-[Version].[format]`

### Category: `tokens/`
- **Aioverse Code**: `AIO-TOKEN`
- **Purpose**: Design system variables and tokens
- **Structure**: `tokens/[format]/[domain]/`
- **Naming Pattern**: `aioverse-[domain]-[version].[format]`
  - `aioverse-colors-v1.json`
  - `aioverse-typography-v1.yaml`
  - `aioverse-spacing-v1.css`

---

## 3. Universal File Naming Convention

```
[AssetType]-[Descriptor]-[Variant]-[Version].[Format]
```

### Examples
```
Aioverse-Logo-Dark-v1.svg
Aioverse-Button-Hover-20250115.png
Component-Card-Light-Mobile-v2.ai
Icon-Menu-24-Active.svg
Font-Nohemi-Bold-Italic.woff2
```

---

## 4. Aioverse Code System

| Category | Code | Usage |
|----------|------|-------|
| Fonts | `AIO-FONT` | `AIO-FONT-01`, `AIO-FONT-02` |
| Logos | `AIO-LOGO` | `AIO-LOGO-PRIMARY-01` |
| Icons | `AIO-ICON` | `AIO-ICON-UI-001` |
| Illustrations | `AIO-ILLUS` | `AIO-ILLUS-WEB-001` |
| Photos | `AIO-PHOTO` | `AIO-PHOTO-BRANDED-001` |
| Guidelines | `AIO-GUIDE` | `AIO-GUIDE-LOGO-v1` |
| Tokens | `AIO-TOKEN` | `AIO-TOKEN-COLOR-v1` |

---

## 5. Color & State Variants

```
Light → Light theme variant
Dark → Dark theme variant
Monochrome → Black and white only
Default → Standard state
Hover → Mouse over state
Active → Currently selected/active
Focus → Keyboard focus state
Disabled → Inactive/disabled state
```

---

## 6. Repository Naming Pattern

```
aio3-[AioCategory]-[Descriptor]
Examples:
  aio3-design-system
  aio3-brand-assets
  aio3-component-library
  aio3-icon-system
```

---

## 7. Common Naming Errors to Avoid

❌ `logo.svg` → Too generic  
❌ `Logo-Updated-Final-FINAL.svg` → Too vague  
❌ `LOGO_V1_DARK_FINAL_2025.svg` → Inconsistent casing  
✅ `Aioverse-Logo-Primary-Dark-v1.svg` → Clear and consistent  
✅ `Aioverse-Icon-Menu-24-Active.svg` → Descriptive  
✅ `aioverse-colors-v1.json` → Lowercase tokens convention  

---

Last Updated: December 2025  
Aioverse Version: 1.0  
Maintained By: Aiotize Design Systems Team
