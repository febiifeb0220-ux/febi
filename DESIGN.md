---
name: Warm Editorial Scrapbook
colors:
  surface: '#fff8f6'
  surface-dim: '#e2d8d6'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fcf1ef'
  surface-container: '#f6ecea'
  surface-container-high: '#f0e6e4'
  surface-container-highest: '#eae0de'
  on-surface: '#1f1b1a'
  on-surface-variant: '#544247'
  inverse-surface: '#352f2e'
  inverse-on-surface: '#f9eeec'
  outline: '#877277'
  outline-variant: '#d9c0c6'
  surface-tint: '#9b3e61'
  primary: '#9b3e61'
  on-primary: '#ffffff'
  primary-container: '#e57a9e'
  on-primary-container: '#631135'
  inverse-primary: '#ffb1c8'
  secondary: '#4b6546'
  on-secondary: '#ffffff'
  secondary-container: '#cdebc3'
  on-secondary-container: '#516b4b'
  tertiary: '#6d5960'
  on-tertiary: '#ffffff'
  tertiary-container: '#ad969d'
  on-tertiary-container: '#402f35'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e2'
  primary-fixed-dim: '#ffb1c8'
  on-primary-fixed: '#3e001d'
  on-primary-fixed-variant: '#7d2649'
  secondary-fixed: '#cdebc3'
  secondary-fixed-dim: '#b2cfa8'
  on-secondary-fixed: '#092008'
  on-secondary-fixed-variant: '#344d30'
  tertiary-fixed: '#f7dce4'
  tertiary-fixed-dim: '#dac0c8'
  on-tertiary-fixed: '#26171d'
  on-tertiary-fixed-variant: '#544248'
  background: '#fff8f6'
  on-background: '#1f1b1a'
  surface-variant: '#eae0de'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 44px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  subheading:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2.5rem
  margin-sm: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system blends an editorial high-fashion magazine layout with the tactile, personal charm of a creative curator's scrapbook. Crafted specifically for an elite UI/UX designer's portfolio landing page, the interface radiates warmth, craftsmanship, wit, and discerning aesthetic sensibility. It discards sterile tech minimalism in favor of an intimate, art-directed experience characterized by delicate coquette sensibilities, literary typography, polaroid photo mounts, and hand-collected artifacts.

### Visual Style
- **Aesthetic Movement:** Tactile Editorial & Romantic Scrapbook.
- **Atmospheric Expression:** Sunlit paper textures, soft cream canvas backings, subtle offset rotations (-1.5deg to 1.5deg on polaroids and cards), deckled edges, and whimsical sparkle glyphs (`✦`, `✧`).
- **Tone & Mood:** Warm, imaginative, highly refined, nostalgic yet ultra-modern in usability and craft.

## Colors

The color palette is grounded in warm, organic pastels reminiscent of sun-bleached prints, fresh matcha leaf, and strawberry confections, anchored firmly by rich warm charcoal to preserve editorial readability and contrast.

### Palette Roles
- **Primary (`#E57A9E` - Strawberry Rose):** Used for focal action points, hero highlights, key badges, category emphasis, and link interactions.
- **Secondary (`#8CA884` - Matcha Sage):** Provides an earthy, grounding counterbalance. Applied to secondary tags, botanical accents, active status indicators, and client logos.
- **Tertiary (`#F7DCE4` - Soft Blush):** Acts as a delicate tint for hover fills, pill containers, decorative backdrops, and scrapbook tape simulations.
- **Neutral Primary (`#2B2625` - Warm Charcoal):** The dominant ink tone for headings, body copy, and hairline borders, avoiding the sterile harshness of pure `#000000`.
- **Canvas Base (`#FDF8F6` - Warm Cream):** The underlying foundation simulating artisanal cotton paper. Pure white (`#FFFFFF`) is reserved strictly for polaroid frames and foreground content cards to create physical layering.

## Typography

The typographical interplay juxtaposes the romantic, high-contrast serif **Playfair Display** with the approachable, geometrically balanced **Plus Jakarta Sans**.

### Usage Guidelines
- **Editorial Emphasis:** Use italicized `subheading` or italic spans in `display-hero` (e.g., *"Crafting thoughtful"* in Roman, *"digital keepsakes"* in italic) to inject editorial cadence.
- **Sparkle Accents:** Accompany titles and badges with inline Unicode sparkles (`✦`, `✧`) rendered in Strawberry Rose or Matcha Sage.
- **Legibility:** Maintain high line-height ratios on body text to honor the spaciousness of a printed literary journal.

## Layout & Spacing

The layout philosophy mirrors an open editorial magazine spread, marrying structured column alignment with deliberate, organic overlaps.

### Layout System
- **Grid Structure:** 12-column fluid grid on desktop (`> 1024px`) with a max container width of `1280px`. 8-column layout on tablet (`768px - 1023px`), and 4 columns on mobile (`< 767px`).
- **Offset Scrapbook Arrangement:** Case study cards and polaroid media blocks alternate horizontal alignment, occasionally stepping into neighboring column gutters or applying slight vertical offsets (`margin-top: -1.5rem`) to feel hand-placed.
- **Rhythm:** Generous outer canvas margins ensure breathing room around collages and text features, reinforcing the luxurious pace of a personal art monograph.

## Elevation & Depth

Visual hierarchy does not use harsh drop shadows or digital elevation tiers. Instead, depth is built through **tonal paper layering** and **warm ambient halos**.

### Layering Hierarchy
- **Canvas Base:** `#FDF8F6` provides the warm, matte foundation.
- **Polaroid & Surface Cards:** Bright `#FFFFFF` set over `#FDF8F6` with an ultra-soft, low-opacity warm ambient shadow: `box-shadow: 0 8px 24px -4px rgba(43, 38, 37, 0.06), 0 2px 6px -1px rgba(43, 38, 37, 0.03)`.
- **Washi Tape & Pin Elements:** Cast a miniature, crisp contact shadow (`box-shadow: 0 1px 3px rgba(43, 38, 37, 0.12)`) to evoke physical paper taped or pinned onto the page.
- **Ghost Borders:** Elements rely on an exceptionally subtle hairline border (`1px solid rgba(43, 38, 37, 0.08)`) instead of heavy outlines, ensuring elements appear tactile without feeling boxed in.

## Shapes

The shape system blends structured editorial geometry with soft, pill-shaped tactile objects.

### Shape Expression
- **Standard Cards & Media:** Rely on standard rounded corners (`0.5rem` to `1rem`) mimicking rounded printed photo prints and vintage cards.
- **Pills & Badges:** Interactive buttons, category labels, and status badges take full pill radii (`9999px`), imparting a soft, approachable feel.
- **Polaroid Framing:** Rigid rectangular image containers with an exaggerated bottom border space (mimicking traditional Polaroid instant prints: `padding: 12px 12px 32px 12px`).

## Components

### Buttons
- **Primary Action:** Full pill shape. Background `#E57A9E`, text `#FFFFFF`, padding `12px 28px`. Hover elevates with a soft floral scale (`scale(1.02)`) and deeper strawberry glow.
- **Secondary Scrapbook Button:** Outline style with `1.5px solid #2B2625`, background `#FFFFFF` or transparent, text `#2B2625`. Subtle hover transition fills container with Soft Blush (`#F7DCE4`).
- **Text Link Button:** Playfair serif or Jakarta label, underlined with a playful wavy or hand-drawn strawberry border and accompanied by a trailing `✦`.

### Chips & Badges
- **Editorial Tag:** Micro pill pill with Soft Blush (`#F7DCE4`) background and Strawberry Rose (`#E57A9E`) text in `label-caps`.
- **Matcha Status Badge:** Matcha Sage (`#8CA884`) background at 15% opacity with solid `#8CA884` text, preceded by a solid pulse dot to signal availability: `"✦ Available for projects"`.

### Case Study Cards (The Polaroid & Editorial Spread)
- **Polaroid Card:** Crisp `#FFFFFF` card containing a `1:1` or `4:5` aspect ratio image, framed with wide paper margins and a handwritten-style italic caption underneath. Micro-rotation applied by default (`transform: rotate(-1deg)`), straightening smoothly on hover (`transform: rotate(0deg) scale(1.01)`).
- **Project Feature Card:** Asymmetric two-column split containing editorial typography on the left and a stacked collage preview on the right, decorated with pseudo-element washi tape strips across one corner.

### Form Inputs & Textareas
- **Input Fields:** Warm cream interior (`rgba(253, 248, 246, 0.6)`), bordered by `1px solid rgba(43, 38, 37, 0.15)`, text in `#2B2625`.
- **Focus State:** Border shifts cleanly to `#E57A9E` with a matching `0 0 0 3px rgba(229, 122, 158, 0.2)` soft halo. Placeholder text in muted charcoal (`rgba(43, 38, 37, 0.45)`).

### Interactive Scrapbook Details
- **Washi Tape Strip:** Semi-opaque rectangular badge placed across card headers (`background: rgba(247, 220, 228, 0.7)`), featuring clipped zig-zag ends.
- **Sparkle Accents:** SVG and glyph markers (`✦`) placed strategically beside headings, testimonial cards, and custom cursor followers.