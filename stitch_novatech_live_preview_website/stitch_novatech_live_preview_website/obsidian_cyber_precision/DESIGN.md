---
name: Obsidian Cyber-Precision
colors:
  surface: '#0e1321'
  surface-dim: '#0e1321'
  surface-bright: '#343948'
  surface-container-lowest: '#090e1c'
  surface-container-low: '#161b2a'
  surface-container: '#1a1f2e'
  surface-container-high: '#252a39'
  surface-container-highest: '#303444'
  on-surface: '#dee2f6'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#dee2f6'
  inverse-on-surface: '#2b303f'
  outline: '#849495'
  outline-variant: '#3a494b'
  surface-tint: '#00dce6'
  primary: '#e0fdff'
  on-primary: '#00373a'
  primary-container: '#00f2fe'
  on-primary-container: '#006a70'
  inverse-primary: '#00696f'
  secondary: '#c0c1ff'
  on-secondary: '#1000a9'
  secondary-container: '#3131c0'
  on-secondary-container: '#b0b2ff'
  tertiary: '#ecfaff'
  on-tertiary: '#003640'
  tertiary-container: '#91e8ff'
  on-tertiary-container: '#00697c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ff6ff'
  primary-fixed-dim: '#00dce6'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f53'
  secondary-fixed: '#e1e0ff'
  secondary-fixed-dim: '#c0c1ff'
  on-secondary-fixed: '#07006c'
  on-secondary-fixed-variant: '#2f2ebe'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#0e1321'
  on-background: '#dee2f6'
  surface-variant: '#303444'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 38px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  telemetry-badge:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system targets enterprise CTOs, VP-level engineering leaders, and procurement heads evaluating mission-critical deep-tech infrastructure. The design communicates institutional stability, technical rigor, and cutting-edge digital execution.

The aesthetic fuses **Corporate Modernism** with **High-Precision Technical Futurism**:
- Deep obsidian foundations avoid stark pure black, prioritizing rich, atmospheric slate depths.
- Precise, luminous accents in cyan and electric indigo function as energetic focal points, suggesting computational speed and high-bandwidth capability.
- Micro-engineered surface layering: ultra-fine semi-translucent borders, controlled ambient backdrops, and monospaced telemetry metrics elevate standard enterprise layouts into precision flight decks.
- Interactions are fast, low-friction, and grounded in definitive mechanical feedback without superfluous ornamentation.

## Colors

The palette is engineered specifically for deep-contrast technical visualization in a dark environment.

### Color Tokens & Roles
- **Primary (`#00F2FE` - Luminous Cyan):** Used for focal interactive drivers, critical telemetry indicators, live execution pulses, and primary status emphasis.
- **Secondary (`#6366F1` - Electric Indigo):** Applied to structural brand accents, secondary interactive targets, multi-stop gradient flows, and interactive hover backgrounds.
- **Tertiary (`#06B6D4` - Deep Cyan):** Mid-tone bridging accent for interactive state transitions, active outlines, and focused boundary highlights.
- **Base Surfaces:**
  - `Canvas Base`: `#0A0F1D` (Deepest obsidian canvas)
  - `Surface Layer 1`: `#111827` (Card and panel background)
  - `Surface Layer 2`: `#1E293B` (Elevated modals, tooltips, and floating controls)
  - `Surface Glass`: `rgba(17, 24, 39, 0.72)` (Translucent panels with backdrop blur)
- **Text & Contrast:**
  - `Text Primary`: `#F8FAFC` (High-contrast titles, metrics, and core actions)
  - `Text Secondary`: `#94A3B8` (Descriptive paragraphs, contextual labels)
  - `Text Muted`: `#64748B` (Inactive states, metadata, disabled markers)
- **Borders & Micro-Accents:**
  - `Border Default`: `rgba(148, 163, 184, 0.12)`
  - `Border Highlight`: `rgba(0, 242, 254, 0.45)`
  - `Border Subtle`: `rgba(255, 255, 255, 0.06)`

## Typography

The typographic hierarchy enforces a division between corporate positioning, editorial readability, and computational telemetry.

- **Plus Jakarta Sans** provides structural authority for titles and headlines. Tight negative letter spacing at display scales maintains visual density and impact.
- **Inter** handles narrative clarity, descriptions, enterprise feature copy, and microcopy with neutral, reliable geometry.
- **JetBrains Mono** surfaces system stats, latency rates, telemetry badges, version tags, terminal inputs, and programmatic data markers.

Apply uppercase transformations with positive letter-spacing (`+0.06em`) strictly to telemetry badges, status flags, and table column titles.

## Layout & Spacing

The layout is structured around an adaptive 12-column fluid grid system pinned to a maximum content container width of 1440px.

- **Desktop (1024px+):** 12 columns, 24px gutters, 32px safe outer margin. High-density dashboards and engineering consoles expand up to full-bleed with persistent padding.
- **Tablet (768px – 1023px):** 8 columns, 16px gutters, 24px margins. Dual-card groupings transition into 2-up grids; complex data panels fold into stacked modular views.
- **Mobile (< 768px):** 4 columns, 16px gutters, 16px margins. Complex interactive controls switch from inline layouts to vertical toolbars or nested tab views.

### Rhythmic Discipline
Vertical cadence uses an 8px base grid. Structural sections maintain 80px to 120px gaps on desktop to give technical visualizations breathing room, compressing to 48px to 64px on mobile devices.

## Elevation & Depth

Visual hierarchy operates through luminous edge diffraction and tonal tiering rather than heavy, murky drop shadows.

### Surface Tiers
- **Tier 0 (Canvas Base):** Deep `#0A0F1D`. Passive foundation.
- **Tier 1 (Panels & Modules):** `#111827` overlaid with `backdrop-filter: blur(16px)` and a micro-border `rgba(148, 163, 184, 0.1)`.
- **Tier 2 (Floating Consoles, Menus, Modals):** `#1E293B` at 85% opacity, bounded by `rgba(0, 242, 254, 0.2)` with a diffuse ambient shadow: `0 20px 40px -15px rgba(0, 0, 0, 0.7)`.

### Precision Glow & Boundary Effects
- **Micro-Borders:** All interactive and elevated containers feature a crisp 1px solid stroke. Transparent inner glows (`box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.08)`) create subtle edge illumination.
- **Active State Glow:** Focused cards or active telemetry streams emit an ambient cyan/indigo aura (`0 0 24px -4px rgba(0, 242, 254, 0.25)`). Never use blurred drop shadows without a containing micro-border.

## Shapes

The design system enforces a **Soft Precision (`1`)** shape language:
- Base buttons, form inputs, telemetry chips, and tab controls utilize `rounded` (0.25rem / 4px) to retain an architectural, instrument-like feel.
- Standard cards, interactive consoles, and modular containers use `rounded-lg` (0.5rem / 8px).
- Large display modals, code blocks, and feature showcases use `rounded-xl` (0.75rem / 12px).
- Avoid pill shapes (`rounded-full`) except for status dot indicators and circular avatar frames.

## Components

### Buttons
- **Primary CTA:** High-tech gradient background (`linear-gradient(135deg, #00F2FE 0%, #6366F1 100%)`), text `#0A0F1D` (semibold), 1px border `rgba(255, 255, 255, 0.3)`. Hover: 10% opacity increase with a subtle cyan glow (`0 0 16px rgba(0, 242, 254, 0.4)`).
- **Secondary (Technical Outline):** Background `rgba(17, 24, 39, 0.8)`, text `#F8FAFC`, border 1px solid `rgba(0, 242, 254, 0.3)`. Hover: border shifts to `#00F2FE`, background to `rgba(0, 242, 254, 0.08)`.
- **Ghost Action:** Background transparent, text `#94A3B8`. Hover: text `#F8FAFC`, background `rgba(255, 255, 255, 0.05)`.

### Chips & Telemetry Badges
- Displayed with `JetBrains Mono` at `11px`, tracking `0.06em`, uppercase.
- Contained in 4px rounded frames with 1px border.
- **Operational / Live:** Background `rgba(0, 242, 254, 0.08)`, border `rgba(0, 242, 254, 0.3)`, text `#00F2FE`. Features a 6px pulsing dot.
- **Standby / Metric:** Background `rgba(30, 41, 59, 0.6)`, border `rgba(148, 163, 184, 0.2)`, text `#94A3B8`.

### Cards & Container Panels
- Surface: `#111827` with 12px backdrop blur.
- Border: 1px `rgba(148, 163, 184, 0.1)`.
- Interactive cards elevate on hover with a 1px border transition to `rgba(99, 102, 241, 0.4)` and a slight upward translate (-2px).

### Input Fields & Controls
- Height: 44px (desktop), background `rgba(10, 15, 29, 0.8)`, border 1px `rgba(148, 163, 184, 0.2)`.
- Text: `#F8FAFC`, placeholder `#64748B`.
- Focus state: Border transitions to `#00F2FE` with a continuous inner shadow (`inset 0 0 0 1px #00F2FE`).

### Checkboxes & Radios
- Box size: 16px × 16px, 3px border-radius.
- Border: 1px `rgba(148, 163, 184, 0.3)`.
- Checked: Background `#00F2FE`, checkmark glyph `#0A0F1D` (2px stroke thickness).

### Interactive Live Previews & Code Terminals
- Top header containing file path/telemetry status with faux terminal controls (8px status dots in mute slate).
- Background: `#070B14`, interior font: `JetBrains Mono`, 13px, with syntax-highlighted cyan, indigo, and emerald tokens.
- Fixed 1px perimeter border `rgba(99, 102, 241, 0.25)`.