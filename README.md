# 🎨 Aiotize Brand Central (aioverse)

> **The definitive source of truth for Aiotize's brand identity, design system, and visual assets.**

---

## 👋 Welcome to the Aioverse

This repository serves as the **central hub** for all brand-related resources across the Aiotize ecosystem. Whether you're designing a new product, creating marketing materials, or building customer-facing interfaces, everything you need starts here.

---

## 📚 Table of Contents

1. [Brand Guidelines](#-brand-guidelines)
2. [Visual Identity](#-visual-identity)
3. [Design System](#-design-system)
4. [Asset Library](#-asset-library)
5. [Usage & Compliance](#-usage--compliance)
6. [Contributing](#-contributing)
7. [Support](#-support)

---

## 📖 Brand Guidelines

### Brand Mission
**Aiotize** empowers organizations to harness AI and automation intelligently. We build tools that amplify human potential, not replace it.

### Brand Voice
- **Clear & Direct** — No jargon, no fluff
- **Empowering** — We enable, we don't dictate
- **Trustworthy** — Security and reliability first
- **Innovative** — Forward-thinking without being trendy

### Brand Values
1. **Intelligence First** — AI-driven, human-centered
2. **Open & Transparent** — No black boxes
3. **Security by Design** — Trust is non-negotiable
4. **Simplicity** — Complexity hidden, power revealed

---

## 🎨 Visual Identity

### Logo Files
- **Primary Logo**: [Download SVG](assets/logos/aiotize-primary.svg)
- **Wordmark**: [Download SVG](assets/logos/aiotize-wordmark.svg)
- **Icon/Symbol**: [Download SVG](assets/logos/aiotize-icon.svg)
- **Dark Mode Variants**: [Download ZIP](assets/logos/dark-mode/)

### Color Palette

#### Primary Colors
```css
--aiotize-blue: #0066FF;        /* Primary brand color */
--aiotize-dark: #0A1628;        /* Dark backgrounds */
--aiotize-light: #F8FAFC;       /* Light backgrounds */
```

#### Secondary Colors
```css
--aiotize-green: #00D4AA;       /* Success, AI active */
--aiotize-purple: #7B61FF;      /* Premium features */
--aiotize-orange: #FF6B35;      /* Alerts, CTAs */
```

#### Semantic Colors
```css
--success: #10B981;
--warning: #F59E0B;
--error: #EF4444;
--info: #3B82F6;
```

### Typography

**Primary Font**: **Inter** (Sans-serif)  
- Headings: Inter Bold (700)
- Body: Inter Regular (400)
- Emphasis: Inter Medium (500)

**Monospace Font**: **JetBrains Mono**  
- Code snippets and technical content

---

## 📐 Design System

### Component Library
Our design system is built on **Figma** and implemented in **React + Tailwind CSS**.

- **Figma Files**: [https://www.figma.com/design/GI2yrpDMzHWpb0lrsVxGMf/Aioverse?node-id=0-1&t=bG6zJhTxpOvhHHvz-1)
- **Storybook**: [components.aiotize.com](https://components.aiotize.com)
- **NPM Package**: `@aiotize/ui-components`

### Design Tokens
All design tokens are available in multiple formats:
- **CSS Variables**: `design-tokens/css/`
- **Tailwind Config**: `design-tokens/tailwind.config.js`
- **JSON**: `design-tokens/tokens.json`

---

## 🖼️ Asset Library

### Directory Structure
```
aioverse/
├── assets/
│   ├── logos/              # SVG, PNG logos (all sizes)
│   ├── icons/              # Icon set (Heroicons + custom)
│   ├── illustrations/      # Marketing illustrations
│   ├── photography/        # Stock photos, team photos
│   └── templates/          # Slide decks, social templates
├── design-system/
│   ├── components/         # React components
│   ├── design-tokens/      # Colors, spacing, typography
│   └── figma-export/       # Auto-synced from Figma
├── brand-guidelines/
│   ├── voice-tone.md       # Writing guidelines
│   ├── logo-usage.md       # Logo do's and don'ts
│   └── brand-story.md      # Company narrative
└── templates/
    ├── presentations/      # PowerPoint, Keynote, Google Slides
    ├── social-media/       # Instagram, Twitter, LinkedIn
    └── print/              # Business cards, letterheads
```

---

## ✅ Usage & Compliance

### Logo Usage Rules
✅ **DO:**
- Use official logo files from this repo
- Maintain clear space (minimum 20px padding)
- Use on approved background colors
- Scale proportionally

❌ **DON'T:**
- Modify logo colors or proportions
- Add effects (shadows, gradients, outlines)
- Place on busy backgrounds
- Use outdated versions

### Approval Process
For external use (partnerships, press, events):
1. Submit request via [Brand Asset Request Form](#)
2. Marketing team reviews within 2 business days
3. Approved assets provided with usage guidelines

---

## 🤝 Contributing

### For Designers
1. Create branch: `design/feature-name`
2. Add assets to appropriate folders
3. Update documentation in README
4. Submit PR for review

### For Developers
1. Use design tokens from `design-tokens/`
2. Reference components from `@aiotize/ui-components`
3. Never hardcode colors or spacing

### Asset Naming Convention
```
{category}-{variant}-{size}.{ext}

Examples:
logo-primary-dark.svg
icon-settings-24px.svg
illustration-hero-homepage.png
```

---

## 📞 Support

### Brand Team
- **Email**: brand@aiotize.com
- **Slack**: #brand-design
- **Office Hours**: Wednesdays 2-4 PM IST

### Quick Links
- 🌐 [aiotize.com](https://aiotize.com)
- 📦 [AIO3 Platform](https://aio3.ai)
- 👨‍💻 [Developer Docs](https://docs.aiotize.com)
- 📊 [Brand Analytics Dashboard](https://analytics.aiotize.com/brand)

---

## 📅 Version History

| Version | Date | Changes |
|---------|------|----------|
| 1.0.0 | Feb 2026 | Initial brand central setup |

---

**Maintained by**: Brand & Design Team @ Aiotize Inc.  
**License**: Internal use only (Aiotize Enterprise)  
**Last Updated**: February 7, 2026
