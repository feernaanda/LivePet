---
name: Enterprise Governance Console
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#444651'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#00311f'
  on-tertiary: '#ffffff'
  tertiary-container: '#004a31'
  on-tertiary-container: '#27c38a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
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
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system is engineered for enterprise operations, privileged identity orchestration, and security administration on mobile and responsive platforms. The brand voice balances operational precision, institutional authority, and effortless clarity.

### Personality & Attitude
- **Authoritative & Trustworthy:** Interfaces reflect bank-grade stability and zero-ambiguity workflows.
- **Systematic & Utilitarian:** Prioritizes high information density without visual chaos; every pixel communicates state, permission, or action.
- **Fast & Decisive:** Frictionless navigation with immediate tactile and visual feedback for audit and management actions.

### Design Movement
- **Modern Corporate / Systematic:** Merges dense utility with refined surfaces. Employs crisp border definitions, subtle tone shifts across neutral layers, and strict typographic hierarchy to instill confidence during mission-critical tasks.

## Colors

The palette establishes immediate hierarchy between structural containers, key interactive nodes, and system statuses.

### Palette Architecture
- **Primary (`#1E3A8A`)**: Deep Navy. Anchors top-level headers, primary brand markers, active navigation structures, and high-authority states.
- **Secondary (`#2563EB`)**: Royal Blue. Used for core interactive items: primary CTA buttons, focused outlines, active tabs, and interactive user links.
- **Tertiary / Success (`#10B981`)**: Emerald Green. Dedicated to positive verifications, active session indicators, approved compliance states, and successful mutations.
- **Error / Critical Alert (`#EF4444`)**: Crimson Red. Reserved exclusively for destructive actions, revocation triggers, error validation banners, and suspension states.
- **Neutral Canvas & Surfaces**:
  - Global Canvas / Base: `#F8FAFC` (Slate 50)
  - Surface Card / Raised Modals: `#FFFFFF`
  - Subdued / Row Alternation: `#F1F5F9` (Slate 100)
- **Text & Borders**:
  - Primary Typography: `#0F172A` (Slate 900)
  - Secondary & Field Labels: `#334155` (Slate 700)
  - Helper & Meta Text: `#64748B` (Slate 500)
  - Structural Divider / Border: `#E2E8F0` (Slate 200)
  - Focus Ring / Highlight: `rgba(37, 99, 235, 0.2)`

## Typography

The typography scale relies entirely on Inter to ensure clean metrics, neutral letterforms, and legible micro-data tables.

- **Display & Large Headlines:** Used for dashboard metrics, user detail titles, and primary screens. Features tight negative tracking to maintain punch and compactness.
- **Mobile Adaptations:** Large view headers gracefully downscale via `headline-lg-mobile` to avoid line wrapping on phone screens.
- **Labels & Micro-copy:** Labels leverage medium and semi-bold weights with slight positive tracking to ensure high-visibility statuses on user role tags, permission chips, and table headers.

## Elevation & Depth

To preserve an enterprise-grade, high-trust aesthetic, depth is established via low-contrast outlines combined with subtle ambient shadows.

### Elevation Levels
- **Level 0 (Flat / Canvas):** Neutral background (`#F8FAFC`). No shadow, no outline.
- **Level 1 (Card & Module Surface):** Surface `#FFFFFF`, wrapped in a crisp 1px border (`#E2E8F0`), supported by an ambient drop shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.04)`.
- **Level 2 (Hover / Floating Cards / Dropdowns):** Surface `#FFFFFF`, border `#CBD5E1`, with shadow: `0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`.
- **Level 3 (Modals / Action Drawers):** Surface `#FFFFFF`, backdrop overlay `rgba(15, 23, 42, 0.45)`, with shadow: `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.06)`.

## Shapes

The design uses a refined rounded corner profile (`roundedness: 2`) that softens administrative density while remaining crisp and structured.

- **Base Radius (0.5rem / 8px):** Applied to standard input fields, secondary buttons, notification banners, and dropdown items.
- **Card & Container Radius (`rounded-xl` / 1.5rem / 24px):** Enforces prominent framing for administrative user cards, modal shells, and multi-row list blocks.
- **Full Pill Radius (9999px):** Applied exclusively to role chips, status badges, and circular avatar containers.

## Components

### Buttons
- **Primary:** Background `#2563EB`, text `#FFFFFF`, radius 8px (`rounded-md`), vertical padding `space-sm` (10px), horizontal `space-md` (16px). Font `label-lg`. Active tap shifts to `#1E3A8A`.
- **Destructive:** Background `#EF4444`, text `#FFFFFF`. Used for user offboarding, role revocation, and access revocation.
- **Secondary / Outline:** Background `#FFFFFF`, 1px solid border `#E2E8F0`, text `#334155`. Hover shifts border to `#CBD5E1` and background to `#F8FAFC`.

### Badges & Role Pills
- Full pill curvature (`rounded-full`). Padding: 2px top/bottom, 10px left/right. Font: `label-sm` (uppercase, letter-spacing `0.04em`).
- **Super Admin:** Background `rgba(30, 58, 138, 0.08)`, border `1px solid rgba(30, 58, 138, 0.25)`, text `#1E3A8A`.
- **Active / Verified:** Background `rgba(16, 185, 129, 0.1)`, border `1px solid rgba(16, 185, 129, 0.3)`, text `#047857`.
- **Suspended / Locked:** Background `rgba(239, 68, 68, 0.1)`, border `1px solid rgba(239, 68, 68, 0.3)`, text `#B91C1C`.

### Form Inputs
- Height: 44px (touch-optimized mobile standard).
- Background: `#FFFFFF`, 1px solid border `#CBD5E1`, radius 8px.
- Internal padding: `0.75rem` horizontal. Font: `body-md`.
- Focus state: Border color `#2563EB` accompanied by an outer shadow ring `0 0 0 3px rgba(37, 99, 235, 0.15)`.
- Helper labels: Positioned above the field in `label-md`, color `#334155`.

### Cards
- Radius: `rounded-xl` (24px).
- Surface: `#FFFFFF` with 1px border `#E2E8F0`.
- Padding: `space-lg` (24px) for desktop/tablet; `space-md` (16px) for mobile devices.
- Internal separation: 1px divider lines using `#F1F5F9` to segregate metadata, user stats, and audit actions.

### Checkboxes & Radios
- Size: 20px x 20px. Radius: 4px for checkboxes, 50% for radios.
- Unchecked: Border 1.5px solid `#94A3B8`, background `#FFFFFF`.
- Checked: Border `#2563EB`, background `#2563EB`, display white checkmark or center dot.

### Administrative User Lists
- Compact vertical stacking with `space-sm` gap.
- Each list tile features an avatar or role badge on the leading edge, user metadata (name, email, last login) in the body, and a right-aligned disclosure chevron or action trigger.
- Row touch targets meet the minimum height of 48px to accommodate one-handed administrative operations.