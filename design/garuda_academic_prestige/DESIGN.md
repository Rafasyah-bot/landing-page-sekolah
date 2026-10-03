---
name: Garuda Academic Prestige
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
  on-surface-variant: '#59413e'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#8c706d'
  outline-variant: '#e0bfbb'
  surface-tint: '#ae302a'
  primary: '#670006'
  on-primary: '#ffffff'
  primary-container: '#8b1515'
  on-primary-container: '#ff978d'
  inverse-primary: '#ffb4ab'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#253042'
  on-tertiary: '#ffffff'
  tertiary-container: '#3b4659'
  on-tertiary-container: '#a9b4cb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#8c1616'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#d8e3fb'
  tertiary-fixed-dim: '#bcc7de'
  on-tertiary-fixed: '#111c2d'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
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

The design system projects academic excellence, dignified nationalism, and progressive global readiness. Designed for prospective students, proud parents, alumni, and academic partners, the interface balances state institution gravitas with modern pedagogical innovation. 

The aesthetic is **Corporate / Modern Editorial**: disciplined layouts, generous white space, bespoke warm gold accents, and structured typographic rhythm. The experience feels prestigious without being distant, warm without losing institutional authority, and structured to convey trust, discipline, and achievement.

## Colors

The palette derives its core power from the spirit of Indonesian institutional heritage paired with academic distinction.

- **Primary (`#8B1515` - Deep Crimson Maroon)**: Anchors institutional authority, leadership, and school spirit. Applied to hero sections, primary headers, active states, and core branding elements.
- **Secondary (`#D4AF37` - Garuda Gold)**: Symbolizes honor, academic distinction, and victory. Used strategically for admission (PPDB) calls to action, badges of achievement, medal indicators, and active highlights.
- **Tertiary (`#1E293B` - Deep Slate)**: Replaces harsh pure black to deliver readable, dignified typography and high-contrast structural framing.
- **Neutral (`#64748B` - Slate Muted)**: Provides calm informational hierarchies across metadata, descriptions, and passive borders.
- **Backgrounds**: Pure crisp white (`#FFFFFF`) forms the foundational canvas, while soft warm gray (`#F8FAFC`) delineates alternate content tiers, programmatic feature cards, and curriculum modules.

## Typography

Typographic scale is structured around **Plus Jakarta Sans** for editorial presence and humanist clarity, paired with **Inter** for dense transactional elements, data chips, tables, and form controls.

- Display headers use tight tracking and heavy weights to express confidence and institutional pride.
- Body text remains open, legible, and balanced with generous line heights to accommodate detailed Indonesian academic terminology and international curriculum descriptions.
- Micro-labels (`label-sm`) default to uppercase tracking for badges (e.g., "AKREDITASI A", "IB WORLD SCHOOL", "PPDB ONLINE").

## Layout & Spacing

The system implements a structured 12-column responsive fluid grid with maximum container width constrained to `1280px` for optimal readability and balanced composition.

- **Breakpoints**: Mobile (<640px, 4 columns), Tablet (640px–1024px, 8 columns), Desktop (>1024px, 12 columns).
- **Rhythm**: Alternating background rows alternate between `#FFFFFF` and `#F8FAFC` to partition distinct functional zones (e.g., Sambutan Kepala Sekolah, Profil Kurikulum, Prestasi Siswa, Alur Pendaftaran).
- **Component Padding**: Standardized card surfaces use `space-lg` internally, while major section blocks employ `space-xl` multiplied symmetrically for generous breathing room.

## Elevation & Depth

Visual hierarchy uses **tonal surfaces and soft ambient shadows** tinted lightly with cool slate to maintain an uncluttered academic ambiance.

- **Level 0 (Flat)**: Background canvas (`#FFFFFF` or `#F8FAFC`) with hair-thin borders (`1px solid #E2E8F0`).
- **Level 1 (Cards & Modules)**: `0 4px 20px -2px rgba(15, 23, 42, 0.05)`, used for curriculum items, facility profiles, and news feeds.
- **Level 2 (Hover & Active Overlays)**: `0 12px 28px -4px rgba(15, 23, 42, 0.08)`, applied during card hover states and interactive previews.
- **Level 3 (Modal & PPDB Floating Drawers)**: `0 20px 40px -8px rgba(15, 23, 42, 0.14)` for registration dialogs and sticky action bars.
- **Gold Accent Elevation**: Priority CTA buttons and honor badges feature a subtle warm underglow: `0 4px 14px 0 rgba(212, 175, 55, 0.25)`.

## Shapes

The design system maintains a modern rounded profile (`roundedness: 2`), reflecting approachability alongside disciplined structure.

- Standard buttons, form fields, and dropdowns use `0.5rem` (`8px`) border radius.
- Feature cards, facility gallery containers, and statistics panels utilize `rounded-lg` (`1rem` / `16px`).
- Badges, status markers, and tags utilize `9999px` full-pill geometries to create visual contrast against architectural rectangular cards.

## Components

### Buttons
- **Primary Institutional Button**: Deep Crimson Maroon (`#8B1515`) background, white text, semi-bold font weight. On hover: shifts to darker crimson (`#701010`) with slight upward translation.
- **Accent / PPDB Action Button**: Garuda Gold (`#D4AF37`) background, tertiary deep slate (`#1E293B`) text for maximum contrast and prestige. Subtle golden ambient glow.
- **Secondary / Outline**: Clean 1.5px border in `#8B1515` or `#CBD5E1` with transparent background, turning to `#F8FAFC` on hover.

### Cards
- **Curriculum & Program Cards**: Clean white surface with `1px solid #E2E8F0` border and `rounded-lg` corners. Features an accent top-border stripe in Deep Crimson Maroon or Gold denoting program tracks (e.g., MIPA, IPS, Cambridge International).
- **Prestasi (Achievement) Cards**: Incorporates high-resolution imagery, floating top-left gold pill badge for the award category, and bold headline detailing the competition tier (Nasional / Internasional).

### Chips & Badges
- **Status Chips**: Micro-capsule shapes (`label-sm`).
  - *Akreditasi / Gold*: Gold tint background (`#FEF9C3`) with deep gold text (`#854D0E`).
  - *Informasi PPDB*: Crimson tint background (`#FEE2E2`) with primary maroon text (`#991B1B`).

### Input Fields & Selectors
- Background: `#FFFFFF` encased in a crisp border (`#CBD5E1`).
- Focus state: `2px` focus ring in Primary Crimson (`#8B1515`) with a `0 0 0 3px rgba(139, 21, 21, 0.1)` offset ring.
- Labels are positioned outside the input container using `label-md` in `#1E293B`.

### Lists & Timelines
- **PPDB Roadmap & Academic Calendar**: Vertical connected-node timeline with crimson check indicators, slate connecting rules, and gold highlight badges for active registration milestones.