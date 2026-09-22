---
name: Nordic Monotone Bento
colors:
  surface: '#f9f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f5'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f0f2'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdf'
  on-secondary-container: '#626262'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d1b1a'
  on-tertiary-container: '#868381'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e4e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e6e1df'
  tertiary-fixed-dim: '#cac6c3'
  on-tertiary-fixed: '#1d1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
typography:
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 54px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Inter
    fontSize: 34px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1.25rem
  margin-md: 2.5rem
  margin-lg: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system delivers a calm, hyper-focused portfolio experience rooted in Scandinavian minimalism and modern editorial tech layouts. Designed for senior creators, software architects, and design engineers, the interface serves as an unobtrusive, high-fidelity gallery where work samples take precedence over decorative UI elements.

Key aesthetic characteristics:
- **Strict Monotone Palette:** Completely neutral greyscale execution devoid of chromatic saturation, producing an authoritative, museum-grade canvas.
- **Editorial Bento Architecture:** Dense, structured modular cards with balanced negative space, referencing high-density Notion dashboards and Swiss rationalism.
- **Micro-Precision Tactility:** Crisp hairline boundaries, refined negative tracking on titles, and micro-diffused ambient lift for interactive components.

## Colors

The palette operates strictly within a curated spectrum of greyscale values to establish precise optical hierarchies without color distraction.

- **Canvas Background (`#F5F5F7`):** A soft, cool-tinted off-white that prevents eye fatigue and provides clean separation from pure white surfaces.
- **Surface Layer (`#FFFFFF`):** Reserved strictly for bento cards, popovers, and elevated interactive panels.
- **Primary Ink (`#111111`):** Deep off-black applied to primary headlines, dominant icons, structural active states, and high-emphasis elements.
- **Secondary Ink (`#666666`):** Balanced mid-grey for metadata, secondary descriptions, passive icons, and breadcrumb trails.
- **Hairline Structural Border (`#E5E7EB`):** Subtle neutral grey for bounding boxes, dividers, and modular bento gutters.
- **Hover/Interactive Surface (`#EAEAEA`):** Minimal tint used exclusively for subtle pressed and hovered chip states.

## Typography

Typography relies entirely on the precision and neutral geometry of **Inter**. Typographic hierarchy is achieved strictly through weight, optical size, and meticulous letter spacing rather than chromatic differentiation.

- **Headlines & Display:** Tightly tracked with subtle negative values (`-0.03em` down to `-0.01em`) to create a cohesive editorial rhythm typical of architectural monographs and technical product launches.
- **Body:** Neutral tracking set at line heights between 1.45x and 1.5x to preserve effortless scanability across technical project descriptions and changelogs.
- **Labels & Microcopy:** Crisp medium-to-semibold weights with slight positive tracking (`+0.01em` to `+0.04em`) when applied to all-caps metadata or tag chips.

## Layout & Spacing

The layout is built around a flexible 12-column bento grid engineered for modular composition and structured asymmetry.

- **Desktop Layout (1024px+):** Fixed container max-width at `1200px` centered within a `#F5F5F7` canvas. Bento modules span 3, 4, 6, 8, or 12 columns with standard `1.5rem` (`24px`) gutters and inner card padding set to `1.5rem` or `2rem`.
- **Tablet Layout (768px - 1023px):** 8-column layout with `1rem` gutters and `2.5rem` outer margins. Bento cells adapt to 4 or 8 column spans.
- **Mobile Layout (<768px):** Single-column stacked stream with `1.25rem` outer canvas padding and `1rem` element gaps. Complex bento arrangements linearize sequentially based on information hierarchy.

## Elevation & Depth

Visual hierarchy is maintained through flat tonal contrasts, structural borders, and imperceptible micro-shadows rather than pronounced drop shadows:

- **Level 0 (Base Canvas):** Solid `#F5F5F7` un-elevated backdrop.
- **Level 1 (Bento Cards & Surfaces):** Pure white (`#FFFFFF`) with a 1px solid border in `#E5E7EB` and an ambient, ultra-soft shadow: `0 1px 3px 0 rgba(0, 0, 0, 0.04)`.
- **Level 2 (Active/Hover Cards & Popovers):** Elevates slightly upon cursor contact or modal invocation: `0 4px 12px -2px rgba(0, 0, 0, 0.06)`, maintaining the 1px `#E5E7EB` border.
- **Dividers & Structural Rules:** Set to a crisp 1px hairline border (`#E5E7EB`), never using double borders or heavy inset bevels.

## Shapes

The geometric personality features soft, deliberate rounding calibrated to distinguish structural containers from inline controls:

- **Bento Modules & Shell Cards:** Fixed at `16px` (`1rem`) border radius, framing content sections with a balanced, hardware-inspired profile.
- **Buttons, Badges, & Chips:** Fixed at `8px` (`0.5rem`) border radius, maintaining structural alignment with internal card elements.
- **Micro Avatars & System Dot Indicators:** Fully circular (`9999px`) to offset the rectangular discipline of the grid.

## Components

### Buttons
- **Primary:** Background `#111111`, foreground `#FFFFFF`, border-radius `8px`, font size `14px`, medium weight. Subtle opacity shift to `0.88` on hover. No harsh shadows.
- **Secondary / Ghost:** Background `#FFFFFF`, foreground `#111111`, 1px border `#E5E7EB`, border-radius `8px`. Hover shifts background to `#F5F5F7`.

### Bento Cards
- Background `#FFFFFF`, border-radius `16px`, 1px solid `#E5E7EB` border, ambient shadow `0 1px 3px rgba(0, 0, 0, 0.04)`.
- Internal padding is consistent at `24px` (`1.5rem`).
- Hoverable interactive cards implement a smooth CSS transition (`200ms ease`) raising shadow to `0 4px 12px rgba(0, 0, 0, 0.06)`.

### Tags & Chips
- Background `#F5F5F7`, text `#111111`, font size `11px` or `13px`, medium weight, border-radius `8px`, internal padding `4px 10px`. 
- Active state transitions background to `#111111` with `#FFFFFF` text.

### Form Inputs & Search Fields
- Surface `#FFFFFF`, border 1px solid `#E5E7EB`, text `#111111`, placeholder `#666666`, border-radius `8px`, height `40px`, padding `0 12px`.
- Focus state applies a 1px ring in `#111111` without blur or glow halos.

### Checkboxes & Selection Controls
- Base state: 16px square, 4px border-radius, 1px `#E5E7EB` border, background `#FFFFFF`.
- Checked state: background `#111111`, border `#111111`, displaying a hairline white checkmark.

### Project Metric & Tech Stack List
- Minimal tabular design separated by 1px hairline `#E5E7EB` bottom dividers.
- Left column displays metric title or technology in `#666666` (`body-sm`), right column displays numeric output or spec value in `#111111` (`body-sm`, medium weight).