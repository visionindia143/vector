---
name: Vector Gallery
colors:
  surface: '#f8faf8'
  surface-dim: '#d9dad9'
  surface-bright: '#f8faf8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f2'
  surface-container: '#edeeed'
  surface-container-high: '#e7e8e7'
  surface-container-highest: '#e1e3e1'
  on-surface: '#191c1b'
  on-surface-variant: '#404947'
  inverse-surface: '#2e3130'
  inverse-on-surface: '#f0f1ef'
  outline: '#707977'
  outline-variant: '#bfc8c6'
  surface-tint: '#316761'
  primary: '#003631'
  on-primary: '#ffffff'
  primary-container: '#134e48'
  on-primary-container: '#87beb6'
  inverse-primary: '#9ad1c9'
  secondary: '#80561f'
  on-secondary: '#ffffff'
  secondary-container: '#fdc483'
  on-secondary-container: '#784f19'
  tertiary: '#2d3031'
  on-tertiary: '#ffffff'
  tertiary-container: '#434647'
  on-tertiary-container: '#b2b4b5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b5ede5'
  primary-fixed-dim: '#9ad1c9'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#154f49'
  secondary-fixed: '#ffddb9'
  secondary-fixed-dim: '#f4bc7c'
  on-secondary-fixed: '#2b1700'
  on-secondary-fixed-variant: '#643e08'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#f8faf8'
  on-background: '#191c1b'
  surface-variant: '#e1e3e1'
  deep-teal: '#0F3D39'
  material-gold: '#9A6D36'
  soft-mint: '#ECF2F1'
  surface-border: '#E2E8F0'
  status-blue: '#2B6CB0'
  status-purple: '#6B46C1'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 1.5rem
  margin-mobile: 1rem
  stack-xs: 0.5rem
  stack-md: 1.5rem
  stack-lg: 3rem
---

## Brand & Style

This design system is tailored for a professional CNC and laser-cut design marketplace. The brand personality is **Precise, Architectural, and Dependable**. It caters to makers, architects, and industrial designers who value technical accuracy and aesthetic sophistication.

The design style is **Corporate / Modern** with subtle **Minimalist** influences. It utilizes a structured grid, ample white space, and a refined color palette to ensure the complex geometry of the vector designs remains the focal point. High-quality imagery of finished physical products (wood, metal, acrylic) provides a tactile contrast to the clean digital interface.

## Colors

The palette is anchored by a deep **Emerald/Teal Green** (`#134E48`), which conveys stability and industrial professionalism. A **Material Gold/Brown** (`#B58449`) serves as the secondary accent, specifically used for material previews, CTA highlights, and premium indicators to evoke the warmth of wood and brass.

- **Primary:** Used for main branding, primary buttons, and active states.
- **Secondary:** Reserved for accents, material-related badges, and high-importance highlights.
- **Tertiary/Neutral:** A series of cool grays and near-whites to keep the interface airy and allow the intricate design previews to pop.
- **Functional Colors:** The design utilizes distinct hues (Blue, Purple, Orange) strictly for step-by-step progress indicators to help users differentiate stages of the production flow.

## Typography

This design system uses **Plus Jakarta Sans** for headlines to provide a friendly yet modern architectural feel. Its geometric clarity matches the nature of vector design. **Inter** is used for body copy and UI labels due to its exceptional legibility and neutral, technical tone.

- **Scale:** Large display sizes use tight tracking and heavy weights for impact.
- **Hierarchy:** Use `label-caps` for small secondary metadata like file formats or "New" badges.
- **Responsiveness:** Headlines scale down significantly on mobile to maintain vertical rhythm without overwhelming the viewport.

## Layout & Spacing

The system employs a **12-column fixed grid** for desktop, maxing out at 1280px, centered in the viewport. On tablet, this transitions to an 8-column fluid grid, and a 4-column grid on mobile.

- **Rhythm:** A base 8px (0.5rem) unit dictates all spacing.
- **Margins:** Desktop uses 48px side margins; mobile uses 16px.
- **Reflow:** Card grids should transition from 4-columns (desktop) to 2-columns (tablet) to 1-column (mobile) to ensure design intricate details remain visible.

## Elevation & Depth

Visual hierarchy is primarily achieved through **Tonal Layers** and **Low-Contrast Outlines**.

- **Surface 1 (Base):** White background.
- **Surface 2 (Cards/Inputs):** White with a 1px border (`#E2E8F0`) and a very soft, diffused shadow (0px 4px 20px rgba(0,0,0,0.05)).
- **Active Elevation:** When a card or button is hovered, the shadow deepens slightly, and the border color shifts to the primary teal.
- **Floating Elements:** Search bars and dropdowns use a slightly higher elevation to appear above the main content stream.

## Shapes

The shape language is **Rounded**, reflecting the precision of CNC toolpaths while maintaining a modern, approachable digital feel.

- **Small elements (Checkboxes, small tags):** 4px radius.
- **Standard elements (Buttons, Inputs, Cards):** 8px (0.5rem) radius.
- **Large elements (Search bars, Hero containers):** 16px (1rem) radius.
- **Step Indicators:** Strictly circular (50% radius) to differentiate them from functional UI components.

## Components

### Search Bars
The primary search bar is a centerpiece component. It should be oversized with a 16px corner radius, a subtle 1px border, and a prominent magnifying glass icon. Include a secondary "All Formats" dropdown integrated into the right side of the input field.

### Progress Indicators (Production Flow)
Circular indicators used to show the "Step-by-Step" process.
- **Layout:** Horizontal on desktop with connecting arrows; vertical on mobile.
- **Styling:** A thick border circle with the step number inside. Each step should have a unique identifying color (Teal, Green, Blue, Purple, Orange, Gold) to signal progression.

### Cards
- **Product Cards:** Featured design preview at the top, followed by a title, category tag, and price. Use a 1px light gray border.
- **Category Chips:** Pill-shaped backgrounds with small icons representing the design type (e.g., a "Gate" icon for Gate Designs).

### Buttons
- **Primary:** Solid Emerald Green with white text.
- **Secondary/Outline:** Emerald Green border and text with a white or transparent background.
- **View More:** Large, wide-pill buttons for navigating deep into galleries.

### Input Fields
Inputs should use a "Soft" roundedness with a light gray border that thickens and turns Teal upon focus. Labels should be placed above the field in `label-caps` style.