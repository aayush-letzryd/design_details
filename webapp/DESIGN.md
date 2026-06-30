---
name: Infrastructure of Prosperity
colors:
  surface: '#fbf9f8'
  surface-dim: '#DBDAD9'
  surface-bright: '#FFFFFF'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f2'
  surface-container: '#efedec'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1b'
  on-surface-variant: '#4A4646'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0ef'
  outline: '#817473'
  outline-variant: '#D3C3C2'
  surface-tint: '#505a96'
  primary: '#000114'
  on-primary: '#ffffff'
  primary-container: '#0a1650'
  on-primary-container: '#7781bf'
  inverse-primary: '#bac3ff'
  secondary: '#006e0d'
  on-secondary: '#ffffff'
  secondary-container: '#85fd77'
  on-secondary-container: '#00750e'
  tertiary: '#616200'
  on-tertiary: '#ffffff'
  tertiary-container: '#b0b131'
  on-tertiary-container: '#424200'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dee0ff'
  primary-fixed-dim: '#bac3ff'
  on-primary-fixed: '#08144f'
  on-primary-fixed-variant: '#38427c'
  secondary-fixed: '#85fd77'
  secondary-fixed-dim: '#69df5e'
  on-secondary-fixed: '#002201'
  on-secondary-fixed-variant: '#005307'
  tertiary-fixed: '#e8e963'
  tertiary-fixed-dim: '#cbcc4a'
  on-tertiary-fixed: '#1d1d00'
  on-tertiary-fixed-variant: '#494900'
  background: '#fbf9f8'
  on-background: '#1b1c1b'
  surface-variant: '#e4e2e1'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.5px
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  container-max: 1280px
---

## Brand & Style

The design system is built upon the concept of "Infrastructure of Prosperity." It balances high-utility operational discipline with the aspirational journey of its partners—moving from operation to earning to ownership. The visual language is rooted in **Corporate / Modern** aesthetics, emphasizing reliability, precision, and stability.

The interface should feel like a high-performance tool: utilitarian, fast, and predictable. It avoids startup "fluff" or decorative elements, opting instead for a systematic approach that mirrors the organized nature of urban mobility supply. Every design decision is intended to convey trust to platforms and dignity to drivers.

## Colors

The color palette follows a strict hierarchical utility model. This is not a palette of equals; it is a structural progression.

- **Primary (Deep Blue):** The foundation. Used for headers, primary actions, and key navigation elements to represent stability and the "operating layer."
- **Secondary (Growth Green):** The indicator of success. Reserved for positive financial metrics, active status indicators, and successful completion states.
- **Tertiary (Prosperity Yellow):** The highlight of achievement. Used sparingly for high-attention ownership milestones and critical calls to action.
- **Neutrals:** A warm off-white (`#FBF9F8`) serves as the background to reduce eye strain, while sharp white is reserved for cards and input surfaces to create clear visual separation.

**Usage Ratio:**
- 70% Foundation (Deep Blue / Neutrals)
- 25% Clarity (White Space)
- 5% Growth & Prosperity (Green/Yellow)

## Typography

This design system utilizes **Inter** exclusively to maintain a systematic, technical, and highly legible appearance across all platforms. The hierarchy is designed for clarity and rapid data scanning.

- **Headlines:** Use Bold and Semi-Bold weights to establish clear content sections.
- **Body:** Standardized at 14px for density without sacrificing legibility, essential for data-heavy operations.
- **Labels:** Used for form field descriptors and metadata, often utilizing Medium weights for contrast against body text.
- **Alignment:** Always left-aligned for Western reading patterns to ensure speed and precision in information processing.

## Layout & Spacing

The design system adheres to a strict **8px grid** to ensure mathematical consistency across all components and layouts. 

- **Grid Model:** A 12-column fluid grid is used for desktop dashboards, transitioning to a single-column layout for mobile-first driver tools.
- **Spacing Rhythm:** All margins, paddings, and component heights must be multiples of 8px. 
- **Density:** While whitespace is used to provide clarity, the layout remains efficient and modular. For operations portals, use `spacing.base` (8px) for internal component spacing and `spacing.gutter` (16px) for spacing between related elements.
- **Reflow:** On mobile, side margins are fixed at 16px to maximize screen real estate for interactive inputs.

## Elevation & Depth

To maintain the "infrastructure" feel, the design system avoids heavy shadows and decorative depth. It uses a **Tonal Layering** approach combined with **Low-Contrast Outlines**.

- **Surface Levels:** 
  - Level 0 (Background): `#FBF9F8`
  - Level 1 (Cards/Containers): `#FFFFFF` with a 1px solid border (`#D3C3C2`)
- **Shadows:** Use a single, subtle "Ambient Shadow" for primary cards: `0px 1px 3px rgba(0, 0, 0, 0.05)`.
- **Interactivity:** Elevation does not change on hover; instead, use subtle background color shifts or border weight emphasis to indicate focus. This reinforces the feeling of a sturdy, physical interface.

## Shapes

The shape language is **Soft (0.25rem / 4px - 8px)**. This provides a balance between the precision of sharp corners and the approachability of rounded forms.

- **Standard Radius:** 8px (`radius-md`) is the default for buttons, cards, and input fields.
- **Small Elements:** 4px is used for tags, chips, and checkboxes to maintain visual balance at smaller scales.
- **Exceptions:** No pill-shaped elements should be used, as they conflict with the "structured infrastructure" narrative.

## Components

### Buttons
- **Primary:** Deep Blue background with White text. Bold/Semi-bold weights. No gradients.
- **Secondary:** Transparent background with a 1.5px Deep Blue border and Deep Blue text.
- **Success/Action:** Use Growth Green only for final "Complete" or "Withdraw Earnings" actions.

### Input Fields
- **Style:** 1px border (`#817473`), 8px radius, white background.
- **Focus State:** 2px Deep Blue border.
- **Labels:** Positioned above the field in `label-md` style for maximum mobile readability.

### Cards
- **Construction:** White background, 1px `#D3C3C2` border, 8px radius.
- **Padding:** Always uses `calc(var(--grid-unit) * 2)` (16px) as the default internal padding.

### Chips & Status Indicators
- **Standard:** Neutral grey background with `on-surface-variant` text.
- **Positive Status:** Light green tint background with Growth Green text.
- **Ownership Highlight:** Prosperity Yellow background with Deep Blue text, uppercase, bold.

### Lists & Tables
- **Data Rows:** High density, 48px minimum row height for touch targets. Use alternating row colors (Level 0 and Level 1 surfaces) only in extremely large data sets.