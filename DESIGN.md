---
name: Executive Precision
colors:
  surface: '#f9f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f5'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#414753'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f0f2'
  outline: '#727784'
  outline-variant: '#c1c6d5'
  surface-tint: '#005cba'
  primary: '#004e9f'
  on-primary: '#ffffff'
  primary-container: '#0066cc'
  on-primary-container: '#dfe8ff'
  inverse-primary: '#aac7ff'
  secondary: '#5f5e60'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfe1'
  on-secondary-container: '#636264'
  tertiary: '#4f5054'
  on-tertiary: '#ffffff'
  tertiary-container: '#68686d'
  on-tertiary-container: '#e9e8ed'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e3ff'
  primary-fixed-dim: '#aac7ff'
  on-primary-fixed: '#001b3e'
  on-primary-fixed-variant: '#00458e'
  secondary-fixed: '#e4e2e4'
  secondary-fixed-dim: '#c8c6c8'
  on-secondary-fixed: '#1b1b1d'
  on-secondary-fixed-variant: '#474649'
  tertiary-fixed: '#e3e2e7'
  tertiary-fixed-dim: '#c7c6cb'
  on-tertiary-fixed: '#1a1b1f'
  on-tertiary-fixed-variant: '#46464b'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  section-gap-desktop: 160px
  section-gap-mobile: 80px
  container-max-width: 1200px
  gutter: 24px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system is engineered to project the authority, international vision, and meticulous efficiency of a high-tier Foreign Trade Sales Professional. Drawing heavy inspiration from premium consumer electronics aesthetics, it prioritizes clarity, "breathable" layouts, and a sophisticated material hierarchy.

The visual style is **High-End Minimalism** blended with **Subtle Glassmorphism**. It evokes an emotional response of trust and precision through a "less but better" approach. Every element serves a functional purpose, utilizing generous whitespace to allow professional achievements and high-quality imagery to take center stage. The aesthetic is curated, deliberate, and undeniably premium.

## Colors
The palette is rooted in the "Cupertino" ethos: high-contrast text against expansive, clean backgrounds.

- **Primary (#0066CC):** A vibrant, professional blue used sparingly for calls to action, active states, and key interactive links.
- **Secondary (#1D1D1F):** The "Eerie Black" used for primary headers and body text to ensure maximum legibility and a grounded feel.
- **Tertiary (#86868B):** A refined grey for secondary information, captions, and metadata.
- **Neutral (#F5F5F7):** The "System Gray," used for section backgrounds to create subtle visual separation without the harshness of lines.
- **Surface (#FFFFFF):** Pure white is the foundation for all primary cards and the main page canvas.

## Typography
This design system utilizes **Inter** for its systematic, neutral, and highly legible characteristics, mimicking the SF Pro aesthetic. 

Headlines utilize tight letter-spacing and bold weights to create a strong visual anchor. Body text is set with generous line-height (1.5x to 1.6x) to ensure readability during long-form reading of professional case studies or trade descriptions. Labels are occasionally set in uppercase with slight tracking to provide a distinct "meta-data" feel for categories or dates.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop to maintain a premium, editorial feel, transitioning to a fluid model for mobile.

- **Desktop:** A 12-column grid with a 1200px max-width. Margins are expansive to center the focus.
- **Spacing Rhythm:** Based on an 8px scale. Large vertical gaps (160px) between major sections are mandatory to signify a transition in narrative.
- **Mobile:** Elements reflow to a single column. Horizontal margins reduce to 20px, and section gaps compress to 80px to maintain momentum while scrolling.

## Elevation & Depth
Depth is created through **Tonal Layering** and **Glassmorphism** rather than traditional heavy shadows.

- **Surface Layering:** Cards utilize a white (#FFFFFF) fill against a light gray (#F5F5F7) background to create a natural lift.
- **Soft Shadows:** When used, shadows are highly diffused (Blur: 40px, Opacity: 4%) with no spread, appearing as an ambient occlusion rather than a direct light source.
- **Glassmorphism:** Navigation bars and floating action headers must use a `backdrop-filter: blur(20px)` with a 70% opaque white background to maintain context of the content underneath as the user scrolls.

## Shapes
The shape language is defined by large, friendly, yet professional radii. 

- **Primary Cards:** Use a 24px corner radius (`rounded-xl` equivalent) to evoke a modern, hardware-like feel.
- **Buttons:** Use fully rounded pill-shapes for primary actions and 12px radii for secondary inputs.
- **Media:** Images and data visualizations should always carry the 24px radius to match the container language.

## Components
- **Buttons:** Primary buttons are solid Blue (#0066CC) with white text. Secondary buttons are ghost-style with a subtle #F5F5F7 background and Blue text.
- **Cards:** Content is housed in 24px rounded white containers. Hover states should include a subtle scale-up (1.02x) and a slight increase in shadow density.
- **Input Fields:** Search or contact forms use a light gray (#F5F5F7) fill, 12px corners, and no border. On focus, a 2px blue outline appears.
- **Chips/Badges:** Used for trade certifications or skills. Small, 100px radius, using a light blue tint (#E5F1FF) with dark blue text.
- **Lists:** Clean, borderless rows separated by 1px light gray lines, featuring high-quality SVG icons for trade metrics (e.g., shipping, logistics, volume).
- **Data Visuals:** Charts should use the Primary Blue and a Neutral Silver (#D2D2D7) to display trade growth and efficiency metrics with minimalist axes.