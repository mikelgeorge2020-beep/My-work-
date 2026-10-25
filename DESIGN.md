---
name: Sacred Grace
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#4a4453'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#7b7485'
  outline-variant: '#ccc3d6'
  surface-tint: '#713dcc'
  primary: '#420093'
  on-primary: '#ffffff'
  primary-container: '#5b21b6'
  on-primary-container: '#c7aaff'
  inverse-primary: '#d3bbff'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fe932c'
  on-secondary-container: '#663500'
  tertiary: '#003b17'
  on-tertiary: '#ffffff'
  tertiary-container: '#005524'
  on-tertiary-container: '#6bcc80'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ebddff'
  primary-fixed-dim: '#d3bbff'
  on-primary-fixed: '#250059'
  on-primary-fixed-variant: '#581db3'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#95f8a7'
  tertiary-fixed-dim: '#79db8d'
  on-tertiary-fixed: '#00210a'
  on-tertiary-fixed-variant: '#005323'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: IBM Plex Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 42px
  headline-lg-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: IBM Plex Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-sm:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-lg:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: IBM Plex Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

### Personality & Values
The design system reflects a modern spiritual sanctuary: warm, dignified, deeply reverent, and effortlessly accessible. It serves congregants, ministry leaders, and servants with an interface that feels sacred yet progressive. The experience bridges ancient liturgical gravitas with contemporary digital refinement, fostering community belonging, transparent pastoral care, and joyful commitment.

### Visual Style
- **Aesthetic Direction:** Elevated Modern Spiritualism with subtle Glassmorphic warmth.
- **Atmosphere:** Illuminated ivory canvas grounded by liturgical royal purple, illuminated by gentle liturgical gold, and balanced with natural warm olive-green faith accents.
- **Visual Weight:** Light, airy, and respectful. Avoid heavy, unyielding blocks of deep ink; instead, utilize layered luminous surfaces, feather-light translucent containers, and pristine Arabic typographic craft.

## Colors

### Palette Architecture
- **Primary (Royal Liturgical Violet - `#5b21b6`, accent `#7c3aed`):** Evokes spiritual sovereignty, solemn devotion, and sacred authority. Applied to key interactive controls, ministry headers, and active state indicators.
- **Secondary (Warm Radiant Gold - `#d97706`, accent `#f59e0b`):** Recalls altar light, divine blessing, and liturgical vessels. Dedicated to celebration states, donation highlights, liturgical milestones, and spiritual achievements.
- **Tertiary (Verdant Faith Green - `#15803d`, accent `#22c55e`):** Represents spiritual renewal, service life, pastoral health, and compassionate ministry records.
- **Neutrals & Canvas:** Pure alabaster and cream-tinted off-whites (`#fdfbf7` to `#f8fafc`) form the base, paired with muted stone slate (`#1e293b`) for pristine typography without harsh pure-black contrast.

### Contrast & Balance
Maintain high-legibility ratios exceeding WCAG AAA for Arabic body text against light surfaces. Use golden tones primarily for surface accents, borders, and badge backgrounds rather than thin text on light fields.

## Typography

### Structural Selection & Arabic Typesetting
The design system deploys **IBM Plex Sans Arabic** across all levels to balance reverent traditional calligraphic balance with modernist clarity.

- **Vertical Rhythm for Arabic Script:** Arabic characters require expansive vertical breathing room; line heights are calibrated 25–35% wider than standard Latin baselines to preserve diacritics (Harakat) and tall ascenders/descenders (Alif, Lam, Yaa) without clipping.
- **Hierarchy:** Display headers employ deliberate weight (`700`) for pastoral titles and liturgical feasts. Body copy maintains a measured weight (`400`) at comfortable sizes for prolonged reading of scriptures, service logs, and circulars.

## Layout & Spacing

### Layout Architecture
- **Responsive Framework:** A 12-column responsive fluid grid on desktop (max-width `1280px`), adapting to an 8-column grid on tablet, and a 4-column system on mobile devices.
- **RTL-First Orientation:** The grid, sidebars, and contextual flows flow strictly Right-to-Left (RTL) to support natural Arabic reading patterns.
- **Rhythm & Cadence:** Generous margins create contemplative, unhurried negative space that conveys peace, eliminating visual anxiety for elderly churchgoers and busy pastoral staff alike.

## Elevation & Depth

### Atmospheric Glassmorphism & Sacred Layers
Depth is achieved via soft frosted-glass containers layered over subtly warm, illuminated backdrops.

- **Base Layer (L0):** Background surface in `#fcfaf7` with subtle ambient radial gradients of diluted royal violet and warm gold (opacity 3–5%).
- **Card Tier 1 (L1 - Surface Container):** Translucent ivory (`rgba(255, 255, 255, 0.85)`) with a `backdrop-filter: blur(12px)`, bordered by a whisper-soft outline (`rgba(91, 33, 182, 0.08)`), cast over an ambient shadow: `0 8px 32px -4px rgba(91, 33, 182, 0.06), 0 2px 8px -2px rgba(217, 119, 6, 0.04)`.
- **Raised Interactive Layer (L2 - Modals & Floating Menus):** Pure optical white (`rgba(255, 255, 255, 0.95)`) backed by `blur(20px)`, framed by a delicate dual-tone rim highlight (`rgba(245, 158, 11, 0.2)` top border edge) and multi-tier ambient shadows: `0 20px 40px -8px rgba(30, 41, 59, 0.08)`.

## Shapes

### Shape Language & Geometry
The geometry combines welcoming, non-aggressive curves with controlled structure:
- **Base Components:** Standard cards, form fields, and dropdowns adopt `0.5rem` (`rounded-md`).
- **Prominent Modules & Banners:** Large liturgical announcement blocks, spiritual quote widgets, and service cards employ `1rem` (`rounded-lg`).
- **Pill Elements:** Interactive actions, role badges (e.g., Shammas, Servant, Coordinator), prayer request tags, and action chips take fully rounded pill contours (`9999px`) to emphasize warmth, ease, and tactile receptivity.

## Components

### Buttons & Interactive Controls
- **Primary CTA:** Liturgical Royal Violet gradient (`linear-gradient(135deg, #7c3aed 0%, #5b21b6 100%)`) with white text, pill-shaped (`9999px`), accompanied by a soft violet glow shadow (`0 4px 14px rgba(91, 33, 182, 0.28)`). Hover brings a slight upward translation (`-1px`) and intensified golden rim reflection.
- **Secondary CTA:** Sheer gold tint surface (`rgba(245, 158, 11, 0.08)`) with deep amber typography (`#b45309`) and a `1px` subtle golden perimeter border (`rgba(217, 119, 6, 0.25)`).
- **Subtle / Ghost:** Pure transparent background with royal violet icon/label, darkening gently on tap.

### Glass Cards (Parishioner & Service Records)
Cards use semi-translucent frosted backdrops (`rgba(255, 255, 255, 0.82)`) over a `12px` Gaussian blur, framed by a delicate `1px` stroke using purple-tinted stone. Top edges can feature an ultra-fine 2px golden accent line for honorific alerts, sacrament reminders, or solemn feasts.

### Badges, Service Ranks & Liturgical Tags
- **Deacon / Servant Badges:** Compact pill tags with soft amber background (`#fef3c7`), gold borders (`#fde68a`), and deep amber text (`#92400e`), complemented by miniature custom liturgical symbols (Censer, Cross, Olive Branch).
- **Confession / Pastoral Status:** Subtle green-tinted chips (`#dcfce7`) paired with forest green copy (`#166534`) to represent living pastoral care and active visitation status.

### Form Inputs & Pastoral Notes
- **Text Fields & Inputs:** Clean white fill with a generous internal padding (`0.875rem 1.25rem`), a `1px` baseline border in slate mist (`#e2e8f0`), and an active focus state transitioning to a royal purple glow ring (`0 0 0 3px rgba(124, 58, 237, 0.15)`). Right-aligned Arabic labels float with clear contrast.

### Lists & Visitation Trackers
Rows feature discrete separators with inset margins, displaying member details, attendance markers, and family links cleanly. Hovering across desktop rows activates a feathered translucent purple wash (`rgba(91, 33, 182, 0.03)`).