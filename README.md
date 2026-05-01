# Colombia Tourism Design System

**Brand:** CO Colombia — Official Tourism Agency of Colombia  
**Adapted from:** Diamond Rose Sanctuary visual identity  
**Aesthetic:** Refined, editorial, luxury and cultural tourism  
**Audience:** International travelers seeking premium, historically rich experiences in Colombia

---

## Overview

This design system supports Colombia's official tourism brand presence — a contemplative, editorial identity that conveys the depth and diversity of the country: cloud forests, colonial cities, Caribbean coasts, Amazonian wilderness. The visual language is quiet, prestigious, and grounded — never loud, never generic.

The system is adapted from the Diamond Rose Sanctuary nature retreat identity and brings that intimate, contemplative aesthetic into the service of cultural and luxury tourism.

---

## Sources

- **Logo:** `assets/Colombia_Marca.png` — official CO Colombia institutional logo (multicolor, fixed asset, do not recolor)
- **Brand brief:** Provided as structured design specification (see below)
- No codebase or Figma link was provided; this system is built from the brand specification document.

---

## Files

| File | Purpose |
|------|---------|
| `README.md` | This file — brand overview, foundations, index |
| `colors_and_type.css` | CSS custom properties for all color + typography tokens |
| `assets/Colombia_Marca.png` | Official CO Colombia institutional logo |
| `preview/` | Design System tab cards (colors, type, components, etc.) |
| `ui_kits/website/` | Tourism website UI kit (homepage, destination, itinerary) |
| `SKILL.md` | Agent skill descriptor for Claude Code compatibility |

---

## CONTENT FUNDAMENTALS

### Voice & Tone

Contemplative, precise, quietly authoritative. The brand speaks like a country that knows its own beauty — without performing it. Sentences are short. Pauses are intentional. The language invites, never pressures.

**Write like this:**
- "Where the Andes meet the Amazon, the land holds centuries of living culture."
- "Come not as a visitor. Come as a witness."
- "Colombia does not perform. It simply is."

**Never write like this:**
- "Discover Colombia's amazing destinations and book your dream vacation today!"
- "World-class experiences at unbeatable prices!"

### Casing & Punctuation
- Headlines: sentence case or two-line split structure (see Typography)
- Eyebrows / labels: ALL CAPS, widely tracked (Jost)
- No exclamation marks in headlines — ever
- No generic tourism vocabulary: amazing, stunning, breathtaking, dream

### Key Vocabulary
`territory` · `living` · `witness` · `depth` · `ancient` · `hold` · `unfold` · `presence` · `rooted` · `light` · `preserve` · `rise` · `breath` · `stillness` · `encounter`

### Headline Structure Pattern
Two-line split, different visual weight per line:
- Line 1: lowercase noun, large, Forest color
- Line 2: qualifier or place name, slightly lighter
- Examples: *"colombia / Unseen"* — *"the coast / Awakens"* — *"what we / preserve"*

### Emoji & Unicode
No emoji. No unicode icon substitutes. Iconography is typographic or photographic only.

---

## VISUAL FOUNDATIONS

### Color
- **Forest #1E3A2F** — primary brand color; dark backgrounds, nav, footer
- **Accent #2D5C3A** — hover states, active elements
- **Sage #4E7B56** — icons, eyebrows, decorative details
- **Mist #7BA882** — soft borders, ornamental dividers
- **Warm White #FAF8F4** — primary page background
- **Cream #F5F0E6** — text on dark, card fills
- **Sand #D9CEAC** — dividers, borders, separators
- **Stone #B0A890** — secondary text, captions, metadata
- **Charcoal #2A2A28** — body text, footer background
- **Gold #C09A4E** — prices, premium badges
- **Gold Light #E6D49A** — badge backgrounds, warm accents

Color rules: never pure black or white — always warm near-whites/near-blacks. No gradients on UI. Borders replace shadows throughout.

### Typography
- **Display:** Cormorant Garamond — headlines, hero titles, pull quotes, destination names. Weights 300/400/400 italic. Heritage, editorial luxury.
- **Body:** Jost — navigation, labels, body text, CTAs, metadata. Weights 300/400/500. Clarity, modernity.
- Google Fonts substitutions used (no proprietary font files provided).

**Scale:**
- Hero: Cormorant Garamond 300, 52–60px, line-height 0.95
- H1: Cormorant Garamond 300, 38px, line-height 1.05
- H2: Cormorant Garamond 400, 28px, line-height 1.15
- H3: Cormorant Garamond 400 italic, 19px, line-height 1.3
- Eyebrow: Jost 400, 11px, tracking 0.20em, UPPERCASE
- Body: Jost 300, 15px, line-height 1.75
- Small: Jost 400, 12px, Stone color
- Caption/Nav: Jost 500, 11px, tracking 0.14em, UPPERCASE

### Backgrounds
- Light pages: Warm White #FAF8F4 base, Cream #F5F0E6 for card fills
- Dark sections: Forest #1E3A2F or Charcoal #2A2A28
- No gradients on UI components
- Photography: full-bleed editorial images with dark overlay for text legibility
- No repeating patterns, textures, or hand-drawn illustration

### Animation
- Minimal: subtle opacity fade-ins on scroll
- No bounces, no spring physics, no dramatic transitions
- Hover states: opacity shift or color change only (no scale, no glow)

### Hover / Press States
- Primary button hover: Accent #2D5C3A background
- Secondary button hover: Forest fill, Cream text
- Link hover: Stone → Forest color shift
- No scale transforms, no shadows, no glows

### Borders & Shadows
- **No box-shadows anywhere**
- 0.5px Sand — subtle dividers, card outlines
- 1px Forest/Sand — interactive components
- 2px — emphasis states (selected card, active filter)
- No rounded corners on primary components (buttons, cards, destination tiles)
- 4px radius: small badges, tags
- 8px radius: input fields, modals

### Cards
- Sharp corners (0px radius)
- 0.5px Sand border or no border
- No shadow
- Image top, metadata below on Cream/Warm White background

### Imagery
- Natural light, no heavy filters
- Wide establishing shots with small human figure
- Colonial architecture: stonework, wooden beams, tiled rooftops
- Cultural moments: unhurried, observational, never posed
- Color temperature: warm golden hour or cool cloud forest green
- Never stock-photo energy — always specific, place-rooted, quiet

### Layout
- Generous negative space — emptiness is intentional
- Max two typefaces per layout
- No busy layouts
- Spacing scale: 4 / 8 / 12 / 16 / 24 / 40 / 64 / 96px

---

## ICONOGRAPHY

No custom icon set is defined in this brand. The approach is **typographic-only**: ornamental marks are created from thin lines and a diamond motif (the ornamental divider). No icon font, no emoji, no unicode substitutes.

**Ornamental Divider:** a 0.5px Sand horizontal line on both sides with a centered 6×6px rotated square (diamond), 1px Mist border — the only recurring decorative element.

For UI components requiring functional icons (accordion toggle, close button), minimal geometric marks in Sage are used: a simple + or × constructed from 1px lines, contained in a 16px circle with Mist border.

If an icon system is required in production, **Lucide Icons** (stroke-based, weight 1–1.5) is the closest stylistic match to the brand's restraint. Never use filled icon styles.

---

## OFFICIAL LOGO RULES

The CO Colombia logo (`assets/Colombia_Marca.png`) is an institutional fixed asset:
- **Never recolor or modify**
- Place only on Warm White #FAF8F4 or Cream #F5F0E6 backgrounds
- Never on dark backgrounds (Forest, Charcoal) — internal colors lose legibility
- Never overlay on photography
- Never adjacent to Gold or Sage color blocks
- Minimum size: 80px wide
- Separate from editorial design elements with 40px+ whitespace or 0.5px Sand border
- Think of it as an institutional stamp — present and credible, not the visual protagonist

---

## SECTION PATTERNS

1. **Hero dark:** Forest background, Cream headline, Sand secondary text, two CTAs
2. **Editorial light:** Warm White background, eyebrow in Sage, H1 in Forest, body in Charcoal
3. **CTA dark:** Charcoal background, centered Cormorant headline in Cream, two buttons
4. **Footer:** Charcoal background, brand name in Cormorant Cream, links in Stone/Jost 300

