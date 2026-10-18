---
name: Kinetic Executive Glass
colors:
  surface: '#f9f9ff'
  surface-dim: '#d4dae9'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e8eefd'
  surface-container-high: '#e3e8f7'
  surface-container-highest: '#dde2f1'
  on-surface: '#161c26'
  on-surface-variant: '#44474f'
  inverse-surface: '#2b313c'
  inverse-on-surface: '#ecf1ff'
  outline: '#747780'
  outline-variant: '#c4c6d0'
  surface-tint: '#485e8d'
  primary: '#001539'
  on-primary: '#ffffff'
  primary-container: '#102a56'
  on-primary-container: '#7c92c4'
  inverse-primary: '#b0c6fc'
  secondary: '#005ab6'
  on-secondary: '#ffffff'
  secondary-container: '#0472e3'
  on-secondary-container: '#fefcff'
  tertiary: '#001735'
  on-tertiary: '#ffffff'
  tertiary-container: '#002b5a'
  on-tertiary-container: '#4192ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#b0c6fc'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#2f4673'
  secondary-fixed: '#d7e3ff'
  secondary-fixed-dim: '#abc7ff'
  on-secondary-fixed: '#001b3f'
  on-secondary-fixed-variant: '#00458f'
  tertiary-fixed: '#d6e3ff'
  tertiary-fixed-dim: '#a9c7ff'
  on-tertiary-fixed: '#001b3d'
  on-tertiary-fixed-variant: '#00468b'
  background: '#f9f9ff'
  on-background: '#161c26'
  surface-variant: '#dde2f1'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.025em
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
    fontWeight: '700'
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
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: -0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

### Personality & Emotional Response
The design system projects performance, unyielding precision, enterprise authority, and forward-looking momentum. It caters to high-growth founders, CMOs, and venture-backed operators who demand measurable revenue velocity. The interface balances high-stakes institutional trust with aggressive modern execution. Every screen feels engineered, high-contrast, sharp, and razor-focused on conversion metrics.

### Design Movement: Modern Precision Glass
The aesthetic blends **Corporate/Modern structure** with **high-end Glassmorphic layers** and **micro-line borders**. 
- Crisp, deep oceanic backgrounds layer beneath frosted optic glass planes.
- Precise 1px micro-borders catch dynamic light highlights to establish tangible visual structure.
- High-contrast typography cuts through ambient visual glow without compromising scan speed or accessibility.

## Colors

### Hierarchy & Color Application
- **Primary (`#102A56` - Deep Navy Blue):** Establishes institutional foundation, structural anchors, deep contrast headers, dark card footings, and high-impact structural blocks.
- **Secondary (`#1677E8` - Royal Blue):** Drives active workflow states, key interactive controls, primary CTAs, and active navigation indicators.
- **Tertiary (`#2D8CFF` - Vivid Electric Blue):** Applied sparingly for high-visibility metrics, conversion highlights, focal badges, gradient stops, and interactive hover feedback.
- **Neutral (`#252B36` - Charcoal Slate):** The authoritative body text color and subtle line tint. Provides sharp, legible reading contrast against pure light surfaces.

### Surface System
- **Base Canvas (`#F8FAFD`):** An ultra-clean, faint cool-tint background ensuring pure whites pop forward with crisp separation.
- **Surface Elevation 0 (`#FFFFFF`):** Base solid card structures, interactive inputs, and light modal dialogs.
- **Surface Elevation 1 (Glassmorphic Tint):** `rgba(255, 255, 255, 0.78)` backed by `backdrop-filter: blur(16px)` over subtly gradient-mapped backdrops.
- **Dark Surface Accent (`#0B1B36`):** Used for premium high-conversion dark sections, executive metrics bento-grids, and sticky command bars.

## Typography

### Structural Pairings & Character
- **Headings & Badges (Plus Jakarta Sans):** Geometric, sculpted, and highly directional. Tighter letter spacing on display tokens produces high-impact editorial headlines suitable for high-growth positioning statements.
- **Reading Typography (Inter):** Highly legible, neutral workhorse engineered for maximum clarity across analytical metrics, case studies, and dense strategy copy.
- **Eyebrows & Metric Labels:** Rendered exclusively in `label-sm` with uppercase casing and expanded tracking (`+0.06em`) to inject architectural structure into dashboards and hero sections.

## Layout & Spacing

### Layout Architecture
- **Grid Architecture:** 12-column dynamic fluid grid on desktop (`1440px` max-width container, centered) shifting to 8-columns on tablet (`768px` to `1023px`) and 4-columns on mobile viewport (`<768px`).
- **Gutter Rhythm:** Standard `1.5rem` (24px) gutters on desktop, reduced to `1rem` (16px) on mobile for optimal information density without visual crowding.
- **Page Margin:** Generous `3rem` (48px) safe boundaries framing landing pages; tightens to `1.25rem` (20px) on mobile displays.
- **Component Padding Scale:** Built strictly upon an 8pt architectural rhythm, with `space-xs` (4px) micro-spacers for inline badges and `space-2xl` (64px) for expansive hero narrative blocks.

## Elevation & Depth

### Atmospheric Tiers
Visual elevation uses layered glass reflections and tinted ambient diffusion rather than heavy muddy drop shadows.

- **Level 0 (Flat Ground):** `#F8FAFD` canvas. No shadow.
- **Level 1 (Subtle Metric Card):** 
  - Background: `#FFFFFF` or `rgba(255, 255, 255, 0.85)` with `12px` blur.
  - Border: 1px solid `rgba(16, 42, 86, 0.08)`.
  - Shadow: `0 2px 8px -2px rgba(16, 42, 86, 0.04), 0 4px 16px -4px rgba(16, 42, 86, 0.06)`.
- **Level 2 (Interactive Glass / Floating Bento):** 
  - Background: `rgba(255, 255, 255, 0.75)` with `20px` backdrop filter.
  - Border: 1px solid `rgba(255, 255, 255, 0.8)` on top, fading to `rgba(22, 119, 232, 0.12)` along the bottom edge.
  - Shadow: `0 12px 32px -6px rgba(16, 42, 86, 0.08), 0 4px 12px -2px rgba(22, 119, 232, 0.05)`.
- **Level 3 (Modals & Command Layers):** 
  - Background: `#FFFFFF`.
  - Border: 1px solid `rgba(16, 42, 86, 0.12)`.
  - Shadow: `0 24px 64px -12px rgba(16, 42, 86, 0.18), 0 8px 24px -4px rgba(16, 42, 86, 0.08)`.

## Shapes

### Corner Curvature Scale
- **Base Geometry (`roundedness: 2`):** Primary standard UI surfaces, input forms, and cards utilize an 8px (`0.5rem`) base radius, communicating tech-forward agility and discipline.
- **Large Panels (`rounded-lg`):** Feature cards, pricing columns, and bento blocks utilize 16px (`1rem`) to soften structural layouts.
- **Structural Hero Containers (`rounded-xl`):** Primary media frames, glass backdrop wrapper boundaries, and dark executive panels leverage 24px (`1.5rem`).
- **Interactive Badges & Pills:** Conversion status chips, tag toggles, and live indicators utilize fully-rounded pill radiuses (`9999px`) to visually contrast against square-aligned data grids.

## Components

### Buttons
- **Primary CTA:** Gradient blend `linear-gradient(135deg, #1677E8 0%, #2D8CFF 100%)`, crisp white text (`#FFFFFF`), `0.5rem` radius, bold geometric label (`label-lg`). Outer shadow: `0 4px 14px rgba(22, 119, 232, 0.35)`. Hover transition: subtle scale `1.02` with amplified outer glow.
- **Executive Navy (Secondary CTA):** Solid `#102A56`, white text, 1px border `rgba(255, 255, 255, 0.12)`. Hover: background shifts to `#16376D`.
- **Ghost/Tertiary:** Transparent base, `#102A56` text with 1px border `rgba(16, 42, 86, 0.15)`. Hover: `rgba(22, 119, 232, 0.05)` fill.

### Cards & Bento Panels
- Default cards use a frosted glass container: `rgba(255, 255, 255, 0.72)` background, `backdrop-filter: blur(16px)`, `1rem` radius, framed with a razor-thin 1px micro-border (`rgba(22, 119, 232, 0.12)`).
- High-performance variant cards utilize dark navy surfaces (`#102A56`) with vivid electric blue glows (`#2D8CFF` radial ambient backlights at 15% opacity) to surface key ROI metrics.

### Form Inputs & Lead Capture
- Base field: 48px height, 8px radius, white background (`#FFFFFF`), border: 1px solid `rgba(37, 43, 54, 0.15)`.
- Focus state: Border transitions to `#1677E8` with a dual ring `0 0 0 3px rgba(45, 140, 255, 0.20)`. Placeholder rendered in `#252B36` at 45% opacity.

### Selection Controls (Checkboxes & Radios)
- Unchecked: White background, 1px solid `rgba(37, 43, 54, 0.25)`.
- Checked: `#1677E8` fill with crisp white internal icon/mark. Smooth 150ms spring animation upon state switch.

### Chips & KPI Badges
- Pill-shaped (`rounded-full`), `space-xs` vertical padding, `space-sm` horizontal padding.
- Growth indicator chip: `rgba(45, 140, 255, 0.12)` background, `#1677E8` text, accompanied by an active pulse dot.

### Specialized Agency Components
- **ROAS/Revenue Metric Cards:** Large display numbers (`headline-lg` in `#102A56` or `#2D8CFF`) paired with micro-eyebrow subtitles and comparative trend tags.
- **Floating Sticky Booking Bar:** Frosted glass dock positioned at viewport bottom with blurred background, lead agency avatar stack, and one-click strategy audit CTA.