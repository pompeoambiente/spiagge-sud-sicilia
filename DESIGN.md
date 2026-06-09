---
name: Solara Travel System
colors:
  surface: '#f7f9ff'
  surface-dim: '#d7dae0'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4fa'
  surface-container: '#ebeef4'
  surface-container-high: '#e5e8ee'
  surface-container-highest: '#dfe3e8'
  on-surface: '#181c20'
  on-surface-variant: '#40484e'
  inverse-surface: '#2d3135'
  inverse-on-surface: '#eef1f7'
  outline: '#70787f'
  outline-variant: '#bfc8cf'
  surface-tint: '#00658b'
  primary: '#005373'
  on-primary: '#ffffff'
  primary-container: '#0d6c93'
  on-primary-container: '#c5e7ff'
  inverse-primary: '#86cffb'
  secondary: '#a43d13'
  on-secondary: '#ffffff'
  secondary-container: '#fe7e50'
  on-secondary-container: '#6b1f00'
  tertiary: '#005931'
  on-tertiary: '#ffffff'
  tertiary-container: '#007441'
  on-tertiary-container: '#92f8b5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c5e7ff'
  primary-fixed-dim: '#86cffb'
  on-primary-fixed: '#001e2d'
  on-primary-fixed-variant: '#004c6a'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ffb59c'
  on-secondary-fixed: '#390c00'
  on-secondary-fixed-variant: '#822700'
  tertiary-fixed: '#92f8b5'
  tertiary-fixed-dim: '#76db9a'
  on-tertiary-fixed: '#00210f'
  on-tertiary-fixed-variant: '#00522c'
  background: '#f7f9ff'
  on-background: '#181c20'
  surface-variant: '#F1F4F9'
  ocean-deep: '#0D6C93'
  sunset-orange: '#E0683C'
  reserve-green: '#1D8A52'
  blue-flag: '#1F6FB8'
  search-purple: '#7A3CC0'
  sand-bg: '#F2EDE0'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 57px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.25px
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  title-lg:
    fontFamily: Manrope
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0.5px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.25px
  label-lg:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.1px
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.5px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  edge-margin-mobile: 16px
  edge-margin-desktop: 32px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
  touch-target: 48px
---

## Brand & Style

This design system embodies the warmth and clarity of the Mediterranean coast. It is built on a **Corporate / Modern** foundation, specifically drawing from Material Design 3 (M3) principles, but infused with a "Solar" personality that feels high-end and inviting. 

The aesthetic is characterized by expansive whitespace, soft lighting effects, and a systematic approach to depth. It aims to evoke a sense of professional reliability and vacation-ready optimism. By combining structural rigor with organic, rounded shapes and a vibrant, nature-inspired palette, the interface balances functional utility with an editorial travel-guide feel.

## Colors

The palette is derived from the Sicilian landscape: the deep Ionian sea, the warm citrus groves, and the protected coastal reserves. 

- **Primary (Ocean Deep):** Used for key branding, active navigation states, and primary actions. It has been tuned for WCAG AA accessibility against white surfaces.
- **Secondary (Sunset Orange):** Reserved for high-visibility highlights, map markers, and call-to-action buttons that require immediate attention.
- **Tertiary (Reserve Green):** Indicates nature, ecological status, and positive environmental markers.
- **Neutral:** A range of sophisticated grays and off-whites that prevent the UI from feeling "cold" or clinical.

Color is used functionally to categorize beach types (sand vs. rock) and environmental conditions, using the dynamic surface palettes as subtle background tints behind content cards.

## Typography

The system uses a dual-font strategy to balance character with legibility. 

**Manrope** is used for headlines and titles. Its geometric yet slightly softened forms provide a modern, professional editorial feel that complements high-quality travel photography. 

**Hanken Grotesk** is the functional workhorse for body text, labels, and data. It offers exceptional readability at small sizes, particularly for weather metrics and beach descriptions. 

For a distinctive "travel guide" touch, the design narrative allows for the use of *Italic* weights in headlines to emphasize location names or poetic descriptors, creating a more sophisticated hierarchy.

## Layout & Spacing

The design system employs a **Fixed Grid** for desktop and a **Fluid Sheet** model for mobile.

- **Mobile:** Uses a bottom-sheet interaction model where the content layer sits above the map. Spacing follows a 4px baseline grid, with 16px standard side margins.
- **Desktop:** A dual-pane layout. The sidebar has a fixed width of 400px, while the map expands to fill the remaining viewport. 
- **Rhythm:** Vertical spacing between cards and content blocks should remain consistent at 16px (stack-md) to maintain a clean, organized flow. All interactive elements must adhere to a minimum 48px touch target to ensure accessibility while traveling.

## Elevation & Depth

This design system uses **Tonal Layers** combined with **Ambient Shadows** to create a sense of organized depth.

- **Level 0 (Base):** The Map layer. It is the foundation of the experience.
- **Level 1 (Surface):** Standard cards and sheet content. These use a very soft, diffused shadow (12% opacity, 16px blur) to appear as if they are floating just above the map.
- **Level 2 (Active/Floating):** Primary action buttons (FABs) and active filter chips. These use a more pronounced shadow to indicate interactability.
- **Backdrop Blurs:** Used sparingly on navigation bars and the bottom sheet "grip" area to maintain context of the map underneath, creating a modern, "Glassmorphism Lite" effect that feels airy and light.

## Shapes

The shape language is "Rounded" to evoke friendliness and comfort. 

- **Cards & Sheets:** Use a minimum radius of 16px (rounded-lg) to create a soft, modern container for information.
- **Buttons & Chips:** Use fully rounded (pill-shaped) ends. This distinguishes interactive elements from static content containers.
- **Images:** Should always follow the container's corner radius. Internal thumbnails (e.g., in a list) use an 8px (standard rounded) radius.

## Components

- **Buttons:** Primary buttons are pill-shaped with a solid Ocean Deep fill. Secondary buttons use an outline or tonal fill.
- **Chips:** Used for filtering (e.g., "Sabbia", "Riparata"). They use a tonal background (Surface Variant) when inactive and the Primary color when selected.
- **Cards:** The central container for beach data. Cards should have no border, relying on soft shadows and subtle background color shifts (dynamic palettes) to define their boundaries.
- **Weather Pills:** Small, condensed data badges with icons and labels. Use Hanken Grotesk Bold for the numerical data to ensure quick scanning.
- **Bottom Sheet:** The primary navigation container on mobile. It features a visible "grab handle" at the top and snaps to three states: Peek (metrics only), Half (list view), and Full (detail view).
- **Map Markers:** Custom pins using the brand colors, featuring a white circular inner core with a themed emoji or icon for immediate recognition.