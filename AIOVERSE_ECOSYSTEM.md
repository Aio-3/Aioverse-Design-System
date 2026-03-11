# Aioverse Ecosystem Map

> **Aioverse** is Aiotize Inc.'s unified naming and organizational system spanning all brand, design, and technical repositories.

## Ecosystem Overview

The Aioverse ecosystem comprises interconnected repositories that follow consistent naming, structure, and governance patterns.

### Core Principles
- **Universal Naming**: All repositories follow Aioverse naming conventions
- **Semantic Codes**: Each repository type has a unique identifier (AIO-*)
- **Hierarchical Organization**: Folders follow consistent categorization patterns
- **Version Control**: Semantic versioning applied consistently
- **Discoverability**: Clear descriptions at all levels

---

## Primary Repositories

### 1. aio3-brand-assets [AIO-BRAND]
**Code**: `aio3-brand-assets`  
**Aioverse Code**: `AIO-BRAND`  
**Repository URL**: `github.com/Aio-3/Aioverse-Design-System`  
**Purpose**: Centralized brand assets, typography, logos, icons, photos, guidelines  
**Key Folders**:
- `fonts/` [AIO-FONT] - Typography system
- `logos/` [AIO-LOGO] - Brand marks
- `icons/` [AIO-ICON] - UI icons
- `illustrations/` [AIO-ILLUS] - Custom artwork
- `photos/` [AIO-PHOTO] - Brand photography
- `guidelines/` [AIO-GUIDE] - Brand standards
- `tokens/` [AIO-TOKEN] - Design tokens

**Status**: Active  
**Maintained By**: Aiotize Design Systems Team

---

### 2. aio3-design-system [AIO-DESIGN]
**Code**: `aio3-design-system`  
**Aioverse Code**: `AIO-DESIGN`  
**Purpose**: Component library, design patterns, and system documentation  
**Key Contents**:
- Component specifications [AIO-COMP]
- Design patterns [AIO-PATTERN]
- Usage documentation [AIO-DOC]
- Accessibility guidelines [AIO-A11Y]

**Status**: Active  
**Maintained By**: Aiotize Design Systems Team

---

### 3. aio3-icon-system [AIO-ICON-SYSTEM]
**Code**: `aio3-icon-system`  
**Aioverse Code**: `AIO-ICON-SYSTEM`  
**Purpose**: Extended icon sets beyond brand-assets repository  
**Key Contents**:
- UI icon library [AIO-ICON-UI]
- Social media icons [AIO-ICON-SOCIAL]
- System icons [AIO-ICON-SYSTEM]
- Custom icon creation guides [AIO-ICON-GUIDE]

**Status**: Active  
**Maintained By**: Aiotize Design Systems Team

---

### 4. aio3-component-library [AIO-COMPONENT-LIB]
**Code**: `aio3-component-library`  
**Aioverse Code**: `AIO-COMPONENT-LIB`  
**Purpose**: Reusable UI component implementations  
**Key Contents**:
- React/Vue components [AIO-COMP-REACT, AIO-COMP-VUE]
- Web components [AIO-COMP-WEB]
- Component documentation [AIO-COMP-DOC]

**Status**: Active  
**Maintained By**: Aiotize Engineering Team

---

### 5. aio3-design-tokens [AIO-TOKEN-SYSTEM]
**Code**: `aio3-design-tokens`  
**Aioverse Code**: `AIO-TOKEN-SYSTEM`  
**Purpose**: Centralized design token management and distribution  
**Key Contents**:
- Color tokens [AIO-TOKEN-COLOR]
- Typography tokens [AIO-TOKEN-TYPO]
- Spacing tokens [AIO-TOKEN-SPACE]
- Animation tokens [AIO-TOKEN-ANIM]

**Status**: Active  
**Maintained By**: Aiotize Design Systems Team

---

## Inter-Repository Dependencies

```
aio3-brand-assets
├─ provides tokens to → aio3-design-tokens
├─ provides icons to → aio3-icon-system
└─ provides guidelines to → aio3-design-system

aio3-design-tokens
└─ consumed by → aio3-component-library → aio3-design-system

aio3-component-library
├─ uses → aio3-design-tokens
├─ uses → aio3-design-system
└─ uses → aio3-brand-assets (fonts, colors)
```

---

## Repository Naming Convention

```
aio3-[category]-[descriptor]

Examples:
  aio3-brand-assets
  aio3-design-system
  aio3-icon-system
  aio3-component-library
  aio3-design-tokens
```

## Aioverse Code System

| Repository | Aioverse Code | Examples |
|------------|---------------|----------|
| Brand Assets | `AIO-BRAND` | AIO-BRAND-ASSETS |
| Design System | `AIO-DESIGN` | AIO-DESIGN-v1 |
| Icon System | `AIO-ICON-SYSTEM` | AIO-ICON-SYSTEM-001 |
| Component Library | `AIO-COMPONENT-LIB` | AIO-COMPONENT-LIB-REACT |
| Design Tokens | `AIO-TOKEN-SYSTEM` | AIO-TOKEN-SYSTEM-v1 |

---

## Related Repositories

- [Aio-3/Aioverse-Design-System](https://github.com/Aio-3/Aioverse-Design-System) - Brand Central (this repo)
- [S-Sethi8/Aioverse-Design-System-Agent](https://github.com/S-Sethi8/Aioverse-Design-System-Agent) - Copilot Agent scaffold
- [Shivansh9000/Aioverse-BrandNew](https://github.com/Shivansh9000/Aioverse-BrandNew) - Brand assets source

---

**Aioverse v1.0** - December 2025  
**Made by the Aiotize Design Systems Team**
