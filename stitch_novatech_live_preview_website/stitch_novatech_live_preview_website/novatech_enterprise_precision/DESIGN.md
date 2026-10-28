---
name: NovaTech Enterprise Precision
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
  on-surface-variant: '#434655'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#747686'
  outline-variant: '#c4c5d7'
  surface-tint: '#2151da'
  primary: '#0037b0'
  on-primary: '#ffffff'
  primary-container: '#1d4ed8'
  on-primary-container: '#cad3ff'
  inverse-primary: '#b7c4ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#003ca3'
  on-tertiary: '#ffffff'
  tertiary-container: '#0051d6'
  on-tertiary-container: '#c9d4ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001551'
  on-primary-fixed-variant: '#0039b5'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  title:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.01em
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
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system establishes a high-performance, structured visual language tailored for technical program directors, enterprise IT architects, and project managers. The core personality communicates absolute operational clarity, trust, institutional efficiency, and modern rigor. The aesthetic synthesizes Modern Corporate precision with purposeful SaaS data architecture—stripping away visual noise in favor of information hierarchy and cognitive speed.

Key principles:
- **Engineered Clarity**: Data-dense environments require minimal visual interference. Whitespace operates as a functional boundary, not purely aesthetic buffer.
- **Systemic Consistency**: Rigid alignments, deterministic status colorings, and unified typographic treatments reassure decision-makers handling high-stakes systems delivery.
- **Subtle Modernity**: Tactful micro-elevations, crisp borders, and balanced neutral scales prevent enterprise fatigue during extended dashboard workflows.

## Colors

The system relies on a high-contrast corporate sapphire foundation paired with cool slate neutrals to build sharp, luminous interfaces.

### Core Swatches
- **Primary Cobalt / Sapphire (`#1D4ED8`)**: Used for primary action affordances, key active states, selection outlines, and emphasized interactive glyphs.
- **Secondary Deep Slate (`#0F172A`)**: Anchor tone for high-contrast primary typography, persistent navigation frameworks, and critical data titles.
- **Tertiary Bright Cobalt (`#2563EB`)**: Interactive hover states, link highlights, and secondary active indicators.
- **Neutral Foundations**:
  - Base White: `#FFFFFF` (Primary card canvases, input backgrounds, active table rows)
  - Surface Muted: `#F8FAFC` (Canvas background, passive container surfaces)
  - Surface Subdued: `#F1F5F9` (Nested table headers, secondary bar backgrounds, inactive tab rails)
  - Border Subdued: `#E2E8F0` (Structural dividing lines, crisp container perimeters)
  - Border Strong: `#CBD5E1` (Input boundaries, focused table separators)
  - Body Text: `#475569` (Secondary labels, structural captions, supporting metadata)

### Status Tokens
Status indicators operate via high-contrast, self-contained semantic pairs (background tint + solid ink):
- **Completed / Approved (Emerald)**: `#10B981` (Ink) | `#ECFDF5` (Surface) | `#A7F3D0` (Border)
- **In Progress / Pending (Amber)**: `#D97706` (Ink) | `#FFFBEB` (Surface) | `#FDE68A` (Border)
- **Overdue / Critical Bug (Rose)**: `#DC2626` (Ink) | `#FEF2F2` (Surface) | `#FECACA` (Border)
- **Under Review (Violet)**: `#7C3AED` (Ink) | `#F5F3FF` (Surface) | `#DDD6FE` (Border)
- **On Hold / Unscheduled (Slate)**: `#475569` (Ink) | `#F8FAFC` (Surface) | `#E2E8F0` (Border)

## Typography

The type scale is driven entirely by Plus Jakarta Sans to combine contemporary geometric clarity with enterprise-grade legibility across complex dashboards.

- **Numbers & Metrics**: Quantitative dashboard metrics render with `headline-lg` or `display` weights, pairing `font-variant-numeric: tabular-nums` to guarantee aligned columns in dynamic data tables and charts.
- **Section Headers & Tables**: Column headers use `label-caps` in uppercase format with wide tracking (`0.06em`) for immediate scannability.
- **Hierarchy Integrity**: Avoid stacking more than two bold typographic levels within a single composite component or card header.

## Layout & Spacing

The system enforces an explicit, modular layout strategy centered around a fixed-width left navigation rail and a fluid 12-column dynamic work pane.

### Shell Architecture
- **Left Sidebar Navigation**: Fixed at `260px` width on desktop (`>= 1280px`), collapsable to an icon rail of `64px` on tablet viewports (`768px - 1279px`), and hidden behind an off-canvas overlay drawer on mobile viewports (`< 768px`).
- **Main Canvas**: Fluid with horizontal edge margins defined by `margin` (`2rem` desktop, `1rem` mobile). Maximum inner container clamp is `1600px` for wide monitoring consoles.

### Grid Rhythm & Adapters
- **Desktop (>= 1280px)**: 12-column layout with `gutter: 1.5rem`.
- **Tablet (768px - 1279px)**: 8-column layout with `gutter-sm: 1rem`. Metrics grids fold from 4 columns to 2 columns.
- **Mobile (< 768px)**: 4-column single-stack flow. Sticky sub-headers become horizontally scrollable segmented buttons.
- **Vertical Spacing Cadence**: Multiples of `4px` with a strict `8px` baseline grid. Dashboard widgets maintain `space-lg` (`1.5rem`) vertical margins between functional row partitions.

## Elevation & Depth

The design system minimizes dramatic dropped shadows, relying instead on structural containment via low-contrast outlines (`1px solid #E2E8F0`) augmented by quiet, ambient floor shadows.

### Elevation Hierarchy
- **Level 0 (Flat / Canvas)**: `#F8FAFC`. Background canvas base for dashboard shells. No borders or shadows.
- **Level 1 (Card & Containers)**: `#FFFFFF`. Bounded by `1px solid #E2E8F0`. Shadow: `0 1px 2px 0 rgba(15, 23, 42, 0.04)`. Used for metric cards, table containers, and filter toolbars.
- **Level 2 (Hover & Context Panels)**: `#FFFFFF`. Bounded by `1px solid #CBD5E1`. Shadow: `0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`. Used for interactive cards upon mouse hover, flyout contextual toolbars, and filter popovers.
- **Level 3 (Modals, Slide-overs & Dropdowns)**: `#FFFFFF`. Bounded by `1px solid #CBD5E1`. Shadow: `0 12px 24px -4px rgba(15, 23, 42, 0.12), 0 4px 8px -2px rgba(15, 23, 42, 0.06)`. Applied to ticket detail side panels, assignment menus, and confirmation dialogs.

## Shapes

The interface embraces a disciplined, compact shape system (`roundedness: 1`), providing an engineered visual tone that avoids playful curves while eliminating sharp harshness.

- **Base Radius (`0.25rem` / `4px`)**: Checkboxes, toggle switches, inline code tags, compact badge icons, and table cell hover indicators.
- **Intermediate Radius (`0.375rem` / `6px`)**: Buttons, standard input fields, dropdown trigger targets, and status chips.
- **Container Radius (`0.5rem` / `8px` - `rounded-lg`)**: Metric summary cards, data grid containers, modal windows, and flyout drawer elements.
- **Inner Nested Rule**: Any child element nested within an 8px container must respect a `4px` or `6px` radius to maintain concentric perimeter alignment.

## Components

### Buttons
- **Primary**: Solid sapphire fill (`#1D4ED8`), white text (`#FFFFFF`), `6px` radius, `height: 38px`, padding `0 16px`. Hover: `#2563EB`. Active: `#1E40AF`.
- **Secondary / Outline**: `#FFFFFF` background, `1px solid #E2E8F0`, slate-900 text (`#0F172A`). Hover: `#F8FAFC` background with border `#CBD5E1`.
- **Destructive**: White background with `1px solid #FECACA`, text `#DC2626`. Hover: `#FEF2F2`.

### Status Badges & Chips
- Rendered at `height: 24px`, padding `2px 8px`, `6px` border-radius.
- Composed of `label-md` text paired with a leading `6px` circular status indicator dot.
- Uses semantic tints: Background tint (e.g., `#ECFDF5`), high-contrast ink text (e.g., `#065F46`), and a subtle bounding border (`1px solid #A7F3D0`).

### Data Tables
- **Container**: Elevated to Level 1 (`#FFFFFF`, `1px solid #E2E8F0`, `8px` radius).
- **Header Row**: `#F8FAFC` background, height `40px`, uppercase text (`label-caps`), subtle border bottom (`1px solid #E2E8F0`).
- **Data Rows**: White background, height `48px`, border bottom `1px solid #F1F5F9`. Hover state transitions row background to `#F8FAFC`.
- **Alignment**: Text left-aligned; numerical values, milestones, and dates right-aligned with monospace/tabular numerical figures.

### Form Inputs & Selects
- Height `38px`, background `#FFFFFF`, border `1px solid #CBD5E1`, radius `6px`, padding `0 12px`, text `body-md` (`#0F172A`).
- **Placeholder**: `#94A3B8`.
- **Focus**: Border `#1D4ED8`, box-shadow `0 0 0 3px rgba(29, 78, 216, 0.15)`. Outline: None.

### Checkboxes & Radios
- Size `16px x 16px`, radius `4px` for checkboxes, `50%` circular for radios.
- Unchecked: `#FFFFFF` fill, border `1.5px solid #CBD5E1`.
- Checked: `#1D4ED8` fill, border `#1D4ED8`, crisp white check icon (`#FFFFFF`).

### Metric Cards (KPI Displays)
- Level 1 elevation, `p-4` (`1rem`) internal spacing, `8px` corner radius.
- Structure: Subtitle label (`label-caps`, `#64748B`) at top, primary metric display (`28px`, bold, `#0F172A`) centered, and trend indicator badge (+4.2% vs target) anchored to bottom margin.

### Left Sidebar Navigation Rail
- Background `#FFFFFF` with right border `1px solid #E2E8F0`.
- Navigation items: Height `36px`, horizontal padding `12px`, corner radius `6px`, text `#475569`.
- **Active State**: Light sapphire tint background (`#EFF6FF`), text `#1D4ED8`, font weight `600`, with a left border accent bar of `3px solid #1D4ED8`.