# IntraAct Website — Design Guideline

## 1. Brand Positioning

**From:** Global literacy charity / small nonprofit
**To:** Evidence-based literacy system used by educators, schools, and districts

The visual design must communicate **trust, scale, and professionalism** — similar to Lexia Learning, Amplify, and established education platforms. Every design decision should reinforce that IntraAct is an institutional-grade literacy system, not a small mission-driven NGO.

---

## 2. Color Palette

### Primary Colors
| Name | Hex | Usage |
|------|-----|-------|
| Navy Dark | `#0F2440` | Headings, hero backgrounds, footer |
| Navy | `#1B3A5C` | Secondary backgrounds, gradients |
| Navy Light | `#2A5A8C` | Hover states, gradient endpoints |

### Accent Colors
| Name | Hex | Usage |
|------|-----|-------|
| Blue | `#2E86C1` | CTAs, links, active states, icons |
| Blue Light | `#EBF5FB` | Card icon backgrounds, badges, light sections |

### Neutral Colors
| Name | Hex | Usage |
|------|-----|-------|
| Text Dark | `#2C3E50` | Body headings, nav text |
| Text Light | `#5D6D7E` | Body paragraphs, descriptions |
| Background | `#FFFFFF` | Page background |
| Background Alt | `#F8F9FA` | Alternating section backgrounds |
| Border | `#D5DBDB` | Subtle borders, dividers |

### Functional Colors
| Name | Hex | Usage |
|------|-----|-------|
| Success | `#27AE60` | Success states, positive indicators |
| Warm Accent | `#E67E22` | Sparingly, for emphasis (not primary) |

### Rules
- Hero sections use a **gradient** from `#0F2440` → `#1B3A5C` → `#2A5A8C`
- Never use bright, saturated colors — keep the palette muted and professional
- Blue (`#2E86C1`) is the only color used for interactive elements (buttons, links)
- Alternating sections use `#F8F9FA` or `#EBF5FB` to create visual rhythm

---

## 3. Typography

### Font Family
**Inter** (Google Fonts) — clean, modern, highly legible sans-serif

Fallback stack: `'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`

### Type Scale
| Element | Size | Weight | Line Height | Color |
|---------|------|--------|-------------|-------|
| H1 (Hero) | 3.25rem (52px) | 800 | 1.2 | White (on dark bg) |
| H1 (Page) | 2.75rem (44px) | 700 | 1.3 | White (on dark bg) |
| H2 (Section) | 2.25rem (36px) | 700 | 1.3 | `#0F2440` |
| H3 (Card) | 1.5rem (24px) | 700 | 1.3 | `#0F2440` |
| H4 (Sub) | 1.25rem (20px) | 700 | 1.3 | `#0F2440` |
| Body | 1rem (16px) | 400 | 1.7 | `#5D6D7E` |
| Body Large | 1.15–1.2rem | 400 | 1.7 | `#5D6D7E` |
| Small / Caption | 0.85–0.9rem | 500 | 1.5 | `#5D6D7E` |
| Label / Badge | 0.875rem | 600 | 1 | `#2E86C1` |

### Rules
- Section labels are **uppercase, letter-spaced (2px), 0.875rem, weight 600, color `#2E86C1`**
- Never use more than 3 font weights on a single page (400, 600, 700 or 800)
- Minimum body text size: 16px (1rem)
- Maximum content width for text: 700px (section headers), 560px (hero paragraphs)

---

## 4. Spacing System

### Section Spacing
| Element | Value |
|---------|-------|
| Section padding (vertical) | 5rem (80px) |
| Hero padding top | 10rem (160px) — accounts for fixed nav |
| Page hero padding top | 9rem (144px) |
| Section header margin bottom | 3rem (48px) |

### Component Spacing
| Element | Value |
|---------|-------|
| Card padding | 2.5rem (40px) |
| Grid gap | 2rem (32px) |
| Feature section gap | 4rem (64px) |
| Button padding | 0.85rem 1.75rem |
| Button padding (large) | 1rem 2.25rem |

### Content Max Width
| Element | Value |
|---------|-------|
| Container | 1200px |
| Section header text | 700px |
| Hero description | 560px |
| Hero content block | 680px |

---

## 5. Component Library

### Buttons
- **Primary**: Blue (`#2E86C1`) background, white text, 50px border-radius (pill shape)
- **Secondary**: Semi-transparent white background with white border (used on dark backgrounds)
- **Outline**: Transparent with blue border and blue text
- **White**: White background, navy text (used on dark CTA sections)
- Hover: 2px upward translate + box shadow
- All buttons use `font-weight: 600`

### Cards
- White background, 16px border-radius, 2.5rem padding
- Subtle shadow: `0 2px 15px rgba(0,0,0,0.08)`
- Hover: 4px upward translate, stronger shadow, faint blue border
- Icon container: 56x56px, `#EBF5FB` background, 12px border-radius

### Navigation
- Fixed top, white background with blur (`backdrop-filter: blur(10px)`)
- Height: 72px
- Logo: Bold weight, "Intra" in navy, "Act" in blue
- Links: 0.9rem, weight 500, pill-shaped hover state
- CTA button in nav: Blue pill button
- Mobile: Hamburger toggle, dropdown menu

### Hero Sections
- **Homepage**: Full gradient background (`#0F2440` → `#1B3A5C` → `#2A5A8C`), decorative radial gradient overlay, bottom fade to white
- **Inner pages**: Shorter gradient header, centered text
- Stats bar with top border separator

### Section Layout Patterns
1. **Section Header + Grid**: Centered label + heading + description, followed by card grid
2. **Feature (Image + Text)**: Two-column split with content and image/illustration placeholder
3. **Stats Bar**: 4-column centered number display
4. **Testimonials**: Quote cards with decorative open-quote mark
5. **Steps/Timeline**: Numbered circles connected by a line
6. **CTA Section**: Dark gradient background, centered text, button group

### Badges / Labels
- Pill shape (50px radius), light blue background, blue text
- Uppercase, small font, weight 600
- Used above section headings to categorize content

### Testimonials
- White card with large decorative `"` in light blue
- Italic quote text, bold author name, light role text
- Shadow and rounded corners

---

## 6. Layout Grid

### Desktop (>1024px)
- Max container width: 1200px, centered
- Cards: 2, 3, or 4 column grids
- Feature sections: 2-column (content + image), alternating direction
- Stats bar: 4 columns

### Tablet (768–1024px)
- Cards: 2 columns
- Feature sections: 2 columns with smaller gap
- Stats bar: 2 columns

### Mobile (<768px)
- Everything stacks to 1 column
- Hero heading: 2.25rem
- Section headings: 1.75rem
- Nav collapses to hamburger menu
- Buttons stack vertically

---

## 7. Iconography

- Style: **Outline/stroke icons** (not filled)
- Stroke width: 1.5–2px
- Size: 28x28px within cards, 120x120px for feature illustrations
- Color: `#2E86C1` (accent blue)
- Source: Inline SVGs for performance (no icon library dependency)
- Icons are placed inside 56x56px containers with `#EBF5FB` background

---

## 8. Imagery Direction

### Current Problem
The existing site uses imagery that signals developing-world NGO contexts. This must change.

### New Direction
- **Classroom photography**: Modern U.S./international school settings
- **Diverse students**: Show students of diverse backgrounds in professional school environments
- **Teacher-focused**: Highlight educators actively teaching, not just students
- **Professional settings**: Clean, well-lit classrooms — not outdoor/rural contexts
- **Abstract illustrations**: For sections without photos, use geometric/abstract placeholders in brand colors

### Placeholder Strategy (Current)
Until photography is sourced, we use SVG icon illustrations on gradient backgrounds in brand colors. These are professional and clean, avoiding the impression of a "stock photo" site.

---

## 9. Animations & Interactions

### Scroll Animations
- Elements fade in + slide up (30px) as they enter the viewport
- Duration: 0.6s ease
- Staggered delays: 0.1s increments for grid items (delay-1 through delay-4)
- Triggered once (no re-animation on scroll up)

### Hover Effects
- Cards: translateY(-4px) + stronger shadow
- Buttons: translateY(-2px) + colored shadow
- Links: Color transition to navy
- Duration: 0.3s ease for all transitions

### Rules
- No parallax effects
- No auto-playing carousels
- No animation on text content — only on cards, images, and containers
- Respect `prefers-reduced-motion` (to be implemented)

---

## 10. Page Structure

Every page follows this structure:

```
[Fixed Navigation Bar]
[Hero Section — gradient background]
[Content Sections — alternating white / light gray / light blue]
[CTA Section — dark gradient, centered]
[Footer — dark navy, 4-column grid]
```

### Alternating Section Pattern
Sections alternate backgrounds to create visual rhythm:
1. White (`#FFFFFF`)
2. Light gray (`#F8F9FA`) — class: `section--alt`
3. White
4. Light blue (`#EBF5FB`) — class: `section--blue`
5. White
6. CTA (dark gradient)

---

## 11. Content Voice & Tone

### Do
- Use professional, institutional language
- Lead with evidence and outcomes ("80% of students...")
- Reference research and frameworks ("aligned with the science of reading")
- Speak to educators as peers ("A structured framework for teaching reading")

### Don't
- Use emotional NGO-style appeals ("Help children in need")
- Reference developing-world poverty or global charity
- Use informal or casual language
- Make claims without supporting evidence

### Key Phrases to Use
- "Evidence-based literacy instruction"
- "Structured literacy approach"
- "Grounded in cognitive science"
- "Science of reading"
- "Implementation for schools and districts"
- "Professional development for educators"

### Key Phrases to Avoid
- "Donate" / "Support our mission"
- "Third-world" / "developing countries"
- "Charity" / "nonprofit"
- "Save children" / "Fight illiteracy"

---

## 12. Accessibility Requirements

- Color contrast: Minimum 4.5:1 for body text, 3:1 for large text
- All interactive elements keyboard-accessible
- Semantic HTML: proper heading hierarchy (h1 → h2 → h3)
- Alt text on all images
- Focus indicators on all interactive elements
- `aria-label` on icon-only buttons (e.g., nav toggle)
- Form inputs with associated labels

---

## 13. Performance Guidelines

- Inline SVGs for icons (no external icon libraries)
- Google Fonts loaded with `display=swap` and `preconnect`
- No JavaScript frameworks — vanilla JS only
- CSS in a single file (`css/style.css`)
- Images optimized for web (WebP preferred, JPEG fallback)
- Target: <2s first contentful paint on 3G

---

## 14. File Structure

```
/
├── index.html              (Home)
├── method.html             (The IntraAct Method)
├── research.html           (Research & Evidence)
├── implementation.html     (Implementation for Schools)
├── results.html            (Results & Case Studies)
├── team.html               (Team & Organization)
├── contact.html            (Partnerships & Contact)
├── css/
│   └── style.css           (All styles)
├── images/                 (Photography & assets)
├── .github/
│   └── workflows/
│       └── deploy.yml      (GitHub Pages deployment)
└── DESIGN_GUIDELINE.md     (This file)
```
