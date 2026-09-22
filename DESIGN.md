---
name: Editorial Noir
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c7c8'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c6c6c7'
  primary: '#ffffff'
  on-primary: '#2f3131'
  primary-container: '#e2e2e2'
  on-primary-container: '#636565'
  inverse-primary: '#5d5f5f'
  secondary: '#c7c6c6'
  on-secondary: '#2f3131'
  secondary-container: '#484949'
  on-secondary-container: '#b8b8b8'
  tertiary: '#ffffff'
  on-tertiary: '#2f3131'
  tertiary-container: '#e2e2e2'
  on-tertiary-container: '#636565'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#e3e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-hero:
    fontFamily: Bebas Neue
    fontSize: 112px
    fontWeight: '400'
    lineHeight: 96px
    letterSpacing: 0.04em
  display-hero-mobile:
    fontFamily: Bebas Neue
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: 0.03em
  headline-xl:
    fontFamily: Bebas Neue
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 60px
    letterSpacing: 0.03em
  headline-xl-mobile:
    fontFamily: Bebas Neue
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 38px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 44px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-md:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.12em
  label-sm:
    fontFamily: Geist
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.16em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 2rem
  space-xl: 4rem
---

## Brand & Style

This design system establishes a high-fashion, gallery-grade visual language for the portfolio of Nico Arnando. It bridges high-contrast editorial publishing with technical architectural brutalism. The identity projects uncompromising authority, rigorous precision, and intentional restraint, prioritizing large-scale typography, negative space, and disciplined hairline frameworks over ornamentation.

Targeted at international creative directors, luxury fashion labels, architecture firms, and high-end cultural institutions, the interface evokes the quiet gravitas of a physically printed monograph or an avant-garde exhibition space. Interactions are sharp, decisive, and immediate, avoiding soft curves or whimsical flourishes in favor of stark contrast and absolute structural clarity.

## Colors

The palette operates under a strict monochrome discipline. Depth is established through stepped values of deep obsidian, charcoal surfaces, and razor-sharp white accents without relying on colored hues.

- **Base Canvas (`#0a0a0a`)**: The deepest foundation, establishing void space and extreme contrast.
- **Surface Elevation (`#121212`, `#181818`)**: Layered containment tones for editorial sidebars, cards, and modal canvases.
- **Structural Hairlines (`#262626`, `#333333`)**: 1px dividers, gridlines, and structural borders that segment content without visual bulk.
- **Text Hierarchy (`#ffffff`, `#e5e5e5`, `#a3a3a3`)**: Pure `#ffffff` is reserved strictly for primary headlines, active states, and focal metrics; `#e5e5e5` commands continuous editorial reading; `#a3a3a3` anchors metadata, indices, and structural labels.

## Typography

The typographic tension pairs the imposing, condensed vertical rhythm of Bebas Neue with the razor-sharp clarity of Geist. 

- **Display & Headline Levels**: Handled exclusively by Bebas Neue in uppercase. Its tall x-height gives project titles, section markers, and hero statements architectural presence. Tight negative vertical spacing keeps large displays compact and editorial.
- **Body Text**: Geist provides neutral, distortion-free legibility across essays, project debriefs, and client statements.
- **Labels & Captions**: Geist set in small caps or uppercase with wide tracking (`0.12em` to `0.16em`). Used for catalog numbering, dates, tags, and coordinates to invoke technical archival stamps.

## Layout & Spacing

The layout model is anchored by an asymmetrical 12-column grid system derived from Swiss international poster design and printed art monographs.

- **Grid & Columns**: A 12-column layout on desktop breakpoints (≥1200px), collapsing to an 8-column layout on tablet (768px–1199px) and a 4-column layout on mobile (<768px). Gutters remain rigidly fixed at `1.5rem` desktop and `1rem` mobile to preserve typographic rhythm.
- **Outer Canvas Margins**: Generous margins (`3rem` on desktop) surround the content area, creating an intentional mat-board frame reminiscent of gallery framing.
- **Section Breaks**: Generous vertical intervals (`space-xl` and multiples thereof) divide projects and narrative chapters, enforcing spatial focus on individual works without sensory overload.
- **Hairline Anchors**: Grid sections are frequently bordered with full-bleed `1px` hairlines, anchoring photography and editorial columns directly into a visible matrix.

## Elevation & Depth

This design system rejects blurred dropshadows and organic depth in favor of absolute planar flatness, structural hairlines, and tonal stepping.

- **Hairline Grids & Outlines**: Visual separation relies on crisp `1px` borders in `#262626` or `#333333`. Modals, floating indices, and drawers do not bleed into the background with diffuse drop shadows; they are bounded by sharp borders.
- **Planar Tiers**:
  - `Base`: `#0a0a0a` (Main backdrop).
  - `Level 1`: `#121212` (Card backdrops, editorial modules).
  - `Level 2`: `#181818` (Sticky headers, tooltips, flyout metadata panels).
- **Overlays**: Interactive focus states, image previews, and lightboxes use pure solid `#000000` with high opacity (0.92) bounded by razor hairlines, rather than soft glassmorphic blurs.

## Shapes

The geometric framework is strictly rectilinear (`roundedness: 0`). 

- Every corner—buttons, input fields, badges, media thumbnails, dialogs, and cards—is sharp at `0px` border radius.
- Imagery must align flush to container edges or sit within disciplined 1px outline boxes.
- Interactive hover states avoid soft expansion; they utilize precise geometric transitions such as inverted color blocks, underline expansions, or crosshair cursors.

## Components

### Buttons & CTAs
- **Primary Button**: Solid white (`#ffffff`) background, pure black (`#0a0a0a`) text, 0px radius. Font: Geist uppercase, semi-bold, letter-spaced. Hover shifts background to `#e5e5e5`. Active click shifts to `#a3a3a3`.
- **Secondary / Ghost Button**: Transparent background, `1px solid #333333` border, `#ffffff` text. Hover state inverts to `#ffffff` background and `#0a0a0a` text with immediate transition.
- **Icon Actions**: Simple hairline square bounds (`40px × 40px`), centering geometric SVG glyphs drawn with `1.5px` stroke.

### Badges & Metadata Chips
- Zero-radius tags with `1px solid #262626` borders, `#121212` surface, and `#a3a3a3` text in `label-sm` sizing.
- For selected or active states, inverts to `#ffffff` background with `#0a0a0a` text.

### Form Inputs & Selectors
- **Text Inputs**: Minimal bottom-line or full structural box with `1px solid #262626`. Background `#121212`. Text typed in `#ffffff`. Focus changes border to `#ffffff` with no glow or outline ring.
- **Checkboxes & Radios**: Angular square checkboxes (`14px × 14px`) with `1px solid #333333`. Checked state fills the box with `#ffffff` and features a stark black micro-square or solid block in the center.

### Editorial Cards & Project Items
- Fully squared containers bounded by `1px solid #262626`.
- Images utilize high-contrast black-and-white treatments by default, transitioning to full tonal richness upon direct hover.
- Card footers are divided by a horizontal `1px` line separating visual assets from metadata indices (project title in Bebas Neue, year and role in Geist mono/label sizing).

### Project Index Table / List View
- Minimalist ledger layout with horizontal hairline rows (`#1e1e1e`).
- Hovering over a row displays an instantaneous preview thumbnail following the cursor, emphasizing an archival directory experience.