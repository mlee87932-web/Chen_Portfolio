---
name: Crystalline Professional
colors:
  surface: '#101415'
  surface-dim: '#101415'
  surface-bright: '#363a3b'
  surface-container-lowest: '#0b0f10'
  surface-container-low: '#191c1e'
  surface-container: '#1d2022'
  surface-container-high: '#272a2c'
  surface-container-highest: '#323537'
  on-surface: '#e0e3e5'
  on-surface-variant: '#c8c5d3'
  inverse-surface: '#e0e3e5'
  inverse-on-surface: '#2d3133'
  outline: '#918f9c'
  outline-variant: '#474651'
  surface-tint: '#c3c0ff'
  primary: '#c3c0ff'
  on-primary: '#272377'
  primary-container: '#312e81'
  on-primary-container: '#9c9af4'
  inverse-primary: '#5654a8'
  secondary: '#b6c4ff'
  on-secondary: '#05297a'
  secondary-container: '#264191'
  on-secondary-container: '#9db2ff'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#00404c'
  on-tertiary-container: '#00b3d1'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#100563'
  on-primary-fixed-variant: '#3e3c8f'
  secondary-fixed: '#dce1ff'
  secondary-fixed-dim: '#b6c4ff'
  on-secondary-fixed: '#00164e'
  on-secondary-fixed-variant: '#264191'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#101415'
  on-background: '#e0e3e5'
  surface-variant: '#323537'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style
The brand personality is high-end, innovative, and technically precise. Designed for an IT professional specializing in ERP and Web Development, the aesthetic balances the reliability of enterprise systems with the creative edge of modern web technology.

The design style is **Creative Glassmorphism**. This approach utilizes translucent layers, high-contrast backdrop blurs, and vibrant accent gradients to create a sense of depth and digital sophistication. The UI should feel like a series of glass panes floating over a deep, luminous void, evoking a "command center" atmosphere that is both professional and futuristic.

## Colors
The palette is built on a "Deep Sea" foundation to ensure maximum contrast for glass effects.
- **Primary (Deep Indigo):** Used for base gradients and deep structural shadows.
- **Secondary (Royal Blue):** Used for interactive states and mid-tone accents.
- **Tertiary (Cyan):** Reserved for high-visibility highlights, active indicators, and focal points.
- **Neutral:** A crisp off-white for maximum legibility against dark, translucent backgrounds.

Glass effects are achieved using a semi-transparent white stroke (`rgba(255, 255, 255, 0.1)`) and a background fill of `rgba(15, 23, 42, 0.6)` combined with a heavy backdrop-blur.

## Typography
**Plus Jakarta Sans** is selected for its modern, geometric, and friendly characteristics. It provides the "tech-forward" feel necessary for an IT portfolio. 

Large display titles should use the Bold or ExtraBold weights with tight letter spacing to create a strong visual impact. Body text maintains a generous line height (1.6) to ensure readability against complex blurred backgrounds. Label styles use uppercase and slightly increased letter spacing to differentiate metadata and tags from narrative content.

## Layout & Spacing
The layout uses a **Fluid Grid** system with a focus on "Floating" containers.
- **Desktop:** 12-column grid, 1200px max-width, 24px gutters.
- **Tablet:** 8-column grid, 24px side margins.
- **Mobile:** 4-column grid, 16px side margins.

Spacing follows an 8px rhythmic scale. Components should utilize generous internal padding (`md` or `lg`) to emphasize the "breathable" nature of the glassmorphic style. Large sections should be separated by `xl` spacing to allow the background gradients and blurs to be seen, preventing the UI from feeling cluttered.

## Elevation & Depth
Depth is created through a hierarchy of transparency and blur, rather than traditional drop shadows.
- **Level 1 (Base):** Dark background with subtle animated mesh gradients (Indigo/Royal Blue).
- **Level 2 (Standard Cards):** Background blur (20px), `rgba(15, 23, 42, 0.5)` fill, and 1px border `rgba(255, 255, 255, 0.1)`.
- **Level 3 (Floating Elements/Modals):** Background blur (40px), `rgba(30, 41, 59, 0.7)` fill, and a more prominent top-left light source highlight on the border.

Shadows, when used, are colored (Indigo or Cyan) with very low opacity (15%) and a large spread (30px+) to simulate a neon glow rather than a physical shadow.

## Shapes
A **Rounded** (0.5rem base) shape language is applied to maintain a balance between professional structure and modern softness.
- **Buttons and Chips:** Use `rounded-xl` or full pill shapes to contrast against the larger, more structured cards.
- **Cards:** Use `rounded-lg` (1rem) to provide a substantial, architectural feel.
- **Inputs:** Use `rounded-md` (0.5rem) for a precise, "data-entry" professional look.

## Components
- **Buttons:** Primary buttons use a linear gradient from Royal Blue to Cyan with a "glow" hover effect. Secondary buttons are ghost-style with a semi-transparent white border and backdrop blur.
- **Glass Cards:** The signature component. Must include a `backdrop-filter: blur(16px)`, a thin white border at 10% opacity, and a subtle inner glow.
- **Chips/Tags:** Used for tech stacks (e.g., "ERP", "React"). These should be semi-transparent Cyan with high-contrast white text.
- **Inputs:** Darker background than the card they sit on to create a "recessed" look. The focus state should illuminate the border with a Cyan glow.
- **Progress Bars:** For skill levels, use a dual-tone gradient (Royal Blue to Cyan) with a subtle pulse animation to suggest "active" technical systems.
- **Floating Navigation:** A fixed-position glass dock at the bottom or side of the screen, housing high-level categories with frosted glass backgrounds.