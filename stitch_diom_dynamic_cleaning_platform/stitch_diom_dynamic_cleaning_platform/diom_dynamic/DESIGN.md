---
name: DIOM Dynamic
colors:
  surface: '#fbf8ff'
  surface-dim: '#dbd9df'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f2f9'
  surface-container: '#efedf3'
  surface-container-high: '#eae7ee'
  surface-container-highest: '#e4e1e8'
  on-surface: '#1b1b20'
  on-surface-variant: '#474554'
  inverse-surface: '#303035'
  inverse-on-surface: '#f2f0f6'
  outline: '#787585'
  outline-variant: '#c8c4d6'
  surface-tint: '#574acb'
  primary: '#4234b6'
  on-primary: '#ffffff'
  primary-container: '#5b4fcf'
  on-primary-container: '#e0dbff'
  inverse-primary: '#c5c0ff'
  secondary: '#006970'
  on-secondary: '#ffffff'
  secondary-container: '#7bf1fc'
  on-secondary-container: '#006e75'
  tertiary: '#4d4761'
  on-tertiary: '#ffffff'
  tertiary-container: '#655f7a'
  on-tertiary-container: '#e3dbfb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4dfff'
  primary-fixed-dim: '#c5c0ff'
  on-primary-fixed: '#140067'
  on-primary-fixed-variant: '#3e2fb2'
  secondary-fixed: '#7ff4ff'
  secondary-fixed-dim: '#5fd7e2'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f55'
  tertiary-fixed: '#e6defe'
  tertiary-fixed-dim: '#cac2e2'
  on-tertiary-fixed: '#1d1830'
  on-tertiary-fixed-variant: '#48435d'
  background: '#fbf8ff'
  on-background: '#1b1b20'
  surface-variant: '#e4e1e8'
typography:
  h1:
    fontFamily: Outfit
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  h3:
    fontFamily: Outfit
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 24px
  margin: 32px
---

## Brand & Style

The design system for DIOM conveys a sense of clinical precision blended with approachable warmth. The brand personality is efficient, high-tech, and obsessively clean, targeting homeowners and business managers who value professional reliability. 

The aesthetic is **Corporate Modern with subtle Glassmorphic accents**. It utilizes a spacious, "breathable" layout inspired by high-end service marketplaces. The UI evokes the feeling of a freshly cleaned space—orderly, bright, and serene. By using soft lavender-to-grey gradients instead of stark whites, the interface reduces eye strain and establishes a premium, trustworthy atmosphere.

## Colors

The palette is anchored by **Bluish Violet (#5B4FCF)**, representing authority and modern service. This color is reserved for structural elements: navigation bars, section titles, and secondary interactive states. 

**Cyan (#4EC9D4)** serves as the high-energy accent, used exclusively for primary Calls to Action (CTAs), success indicators, and highlighting active service progress. 

The background is never flat white; it employs a **soft gradient** from light lavender to pale bluish-grey. This provides a sophisticated canvas that makes white component cards "pop" with natural depth. Semantic colors for errors or warnings should use softened tones to maintain the calm aesthetic.

## Typography

This design system uses a dual-typeface strategy to balance character with readability. **Outfit** is used for all headings; its geometric, open curves feel modern and professional. Headlines should be set in Bold or Semibold to establish a clear information hierarchy.

**DM Sans** is the workhorse for body copy and UI labels. Its low-contrast strokes and neutral personality ensure maximum legibility at smaller sizes. For the Spanish language, ensure line heights are generous (1.6x) to accommodate longer word lengths and character ascenders/descenders comfortably.

## Layout & Spacing

The layout follows a **Fixed-Width Grid** for desktop (12 columns) and a **Fluid Grid** for mobile. The rhythm is based on a 4px baseline, but the system prioritizes "Generous Whitespace." 

Containers and sections should be separated by large vertical gaps (`lg` or `xl`) to prevent the UI from feeling cluttered—reinforcing the "cleaning" brand promise. Components within cards use `md` (24px) padding to ensure content doesn't feel cramped.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and tonal layering. Surfaces do not use harsh black shadows; instead, they use a soft, diffused shadow tinted with the primary violet color at very low opacity (e.g., `rgba(91, 79, 207, 0.08)`).

White cards sit atop the lavender gradient background to create the primary content layer. For secondary depth, such as tooltips or dropdowns, a subtle background blur (8-12px) is applied to create a glassmorphic effect, suggesting a clean, transparent interface.

## Shapes

The shape language is defined by **large, friendly radii**. Standard UI components like input fields and buttons use a 16px radius. Large container cards and advertising banners use a 20px radius. This softness removes the "clinical" coldness of the cleaning industry, making the app feel more like a lifestyle assistant.

## Components

### Buttons
- **Primary CTA:** Cyan (#4EC9D4) background with white text. High-contrast, bold weight.
- **Secondary:** Transparent background with a Bluish Violet (#5B4FCF) border or light violet ghost fill.
- **Radius:** Consistent 16px.

### Cards & Advertising Banners
- **Service Cards:** Pure white background, soft ambient shadow, 20px corners.
- **Publicidad (Ads):** These must be visually distinct but integrated. Use a slightly different background tint (e.g., a very pale version of the accent Cyan) and include a small, uppercase label "PUBLICIDAD" in the top-right corner using the `label-sm` type style.

### Input Fields
- **Style:** Light grey stroke (2px) that turns Bluish Violet on focus. 
- **Feedback:** Error states should use a soft coral-red, avoiding aggressive neons to maintain the professional tone.

### Chips & Tags
- Used for service categories (e.g., "Limpieza Profunda," "Express"). Use a light tint of the primary color for the background with dark violet text.

### Selection Controls
- Checkboxes and Radios use the 16px roundedness where possible (softened corners) and fill with Cyan (#4EC9D4) when active to provide immediate visual confirmation.