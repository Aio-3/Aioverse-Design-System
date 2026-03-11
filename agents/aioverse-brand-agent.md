# Aioverse Brand Design Agent

## Overview

The **Aioverse Brand Design Agent** is a specialized Copilot agent for the Aiotize design system. It provides authoritative guidance on brand identity, visual systems, design tokens, and creative direction for all Aiotize products and communications.

This agent ensures brand consistency across every touchpoint — from UI components to marketing materials, from drone HMI interfaces to executive presentations.

---

## Agent Identity

| Field | Value |
|-------|-------|
| **Name** | Aioverse Brand Design Agent |
| **Slug** | `aioverse-brand-agent` |
| **Version** | 1.0.0 |
| **Maintained By** | Aiotize Design Systems Team |
| **Primary Repo** | `Aio-3/Aioverse-Design-System` |
| **Agent Repo** | `S-Sethi8/Aioverse-Design-System-Agent` |

---

## Capabilities

This agent is trained on the full Aioverse design system documentation and can help with:

### 1. Brand Identity & Persona
- Aiotize brand attributes: Innovative, Reliable, Precise, Visionary, Trusted
- Brand voice and tone guidance for different contexts (technical, executive, marketing)
- Brand character expression in design and communication
- Drone logistics and IoT sector positioning

### 2. Visual Design System
- Color palette: primary, secondary, accent, neutral, and semantic colors
- Typography system: font families, weights, sizes, line heights, and usage rules
- Spacing and layout grid system
- Iconography style and usage
- Design token values and implementation

### 3. Asset Naming & Taxonomy
- Aioverse naming conventions for all design assets
- File naming standards across Figma, GitHub, and production
- Component naming patterns
- Version control conventions for design files

### 4. Ecosystem & Repository Structure
- Aioverse multi-repo architecture overview
- Which repo owns what (design tokens, components, agents, docs)
- Contribution guidelines and PR standards
- Team structure and ownership map

### 5. Brand Implementation Workflow
- Step-by-step brand implementation for new products
- Onboarding checklist for new team members
- Design-to-dev handoff standards
- Figma and Notion tool integration

### 6. Compliance & Guidelines
- Brand guidelines checklist for internal review
- Do's and don'ts for logo, color, and typography usage
- Accessibility requirements (WCAG 2.1 AA minimum)
- Legal and trademark usage guidance

---

## Quick Reference

### Brand Colors

```
Primary:    #F5C842  (Aiotize Gold)
Dark:       #0A0A0A  (Deep Black)
Light:      #FFFFFF  (Pure White)
Accent:     #1A1A2E  (Navy Deep)
Secondary:  #FFD700  (Highlight Gold)
```

### Brand Typography

```
Display:    Space Grotesk (Bold 700)
Heading:    Space Grotesk (SemiBold 600)
Body:       Inter (Regular 400 / Medium 500)
Code/Mono:  JetBrains Mono
Min Size:   12px body, 10px caption
```

### Brand Voice

```
Tone:       Precise, Confident, Forward-thinking
Persona:    Expert engineer meets strategic visionary
Audience:   Defense, logistics, enterprise, investors
Avoid:      Jargon overload, vagueness, casual slang
```

---

## Usage Instructions

### Invoking the Agent

In GitHub Copilot Chat, mention this agent using:

```
@aioverse-brand-agent What color should I use for CTA buttons?
@aioverse-brand-agent Review this copy for brand voice alignment.
@aioverse-brand-agent What is the correct logo clearspace?
@aioverse-brand-agent Generate a color palette for the drone dashboard UI.
```

### Best Use Cases

1. **Designers** — Validate design decisions against the Aioverse design system
2. **Developers** — Look up design token values and implementation guidance
3. **Writers** — Align copy with brand voice and tone guidelines
4. **Product Managers** — Check brand compliance for new feature designs
5. **Marketing** — Ensure campaigns are on-brand before launch

### Example Prompts

```
- "What fonts should I use for the Aiotize investor deck?"
- "Show me the approved color tokens for dark mode."
- "What is the brand positioning for Aiotize in defense markets?"
- "Review my UI design for brand consistency."
- "What naming convention should I use for this Figma component?"
```

---

## Related Agents

- See `agents/` directory for other specialized agents
- Design System Agent: Code and component guidance
- Brand Voice Agent: Copy and communication alignment

---

## Source Documentation

This agent is grounded in the following brand documents:

| Document | Purpose |
|----------|---------|
| AIOTIZE_BRAND_PERSONA.md | Brand character and attributes |
| AIOVERSE_VISUAL_SYSTEMS.md | Colors, typography, design tokens |
| AIOVERSE_NAMING.md | Asset taxonomy and naming |
| AIOVERSE_ECOSYSTEM.md | Repository and team structure |
| AIOVERSE_BRAND_IMPLEMENTATION.md | Implementation workflow |
| BRAND_GUIDELINES_CHECKLIST.md | Compliance verification |
| FIGMA_NOTION_SETUP_GUIDE.md | Tool integration |
| AIOVERSE_USAGE_GUIDE.md | Complete usage reference |

---

**Maintained By:** Aiotize Design Systems Team  
**Source Repos:**
- [Aio-3/Aioverse-Design-System](https://github.com/Aio-3/Aioverse-Design-System) (primary)
- [S-Sethi8/Aioverse-Design-System-Agent](https://github.com/S-Sethi8/Aioverse-Design-System-Agent) (agent template)
