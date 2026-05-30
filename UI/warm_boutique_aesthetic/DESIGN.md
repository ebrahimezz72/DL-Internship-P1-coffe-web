---
name: Warm Boutique Aesthetic
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#504442'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#827472'
  outline-variant: '#d3c3c0'
  surface-tint: '#745853'
  primary: '#271310'
  on-primary: '#ffffff'
  primary-container: '#3e2723'
  on-primary-container: '#ae8d87'
  inverse-primary: '#e3beb8'
  secondary: '#655d5a'
  on-secondary: '#ffffff'
  secondary-container: '#ece0dc'
  on-secondary-container: '#6b6360'
  tertiary: '#001d03'
  on-tertiary: '#ffffff'
  tertiary-container: '#003508'
  on-tertiary-container: '#60a35c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#e3beb8'
  on-primary-fixed: '#2b1613'
  on-primary-fixed-variant: '#5b403c'
  secondary-fixed: '#ece0dc'
  secondary-fixed-dim: '#cfc4c0'
  on-secondary-fixed: '#201a18'
  on-secondary-fixed-variant: '#4c4542'
  tertiary-fixed: '#acf4a4'
  tertiary-fixed-dim: '#91d78a'
  on-tertiary-fixed: '#002203'
  on-tertiary-fixed-variant: '#0c5216'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
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
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The visual identity of the design system is anchored in a **Sophisticated Cozy** aesthetic. It blends the clarity of **Modern Minimalism** with the warmth of a **Tactile** boutique experience. The goal is to evoke the sensory richness of a premium coffee shop: the aroma of dark roasts, the smoothness of steamed milk, and the quiet comfort of a well-designed space.

The UI should feel intentional and unhurried. We achieve this through generous whitespace (breathing room), a curated earthy palette, and soft, organic transitions. This approach creates a high-end atmosphere that remains approachable and inviting for everyday customers.

## Colors

The palette is derived from natural elements found in a premium café environment.

*   **Primary (Coffee Bean):** A deep brown used for core branding, primary actions, and high-level headings. It provides the grounding "anchor" for the UI.
*   **Secondary (Steamed Milk):** A warm beige used for secondary buttons, subtle dividers, and container backgrounds. It bridges the gap between the dark primary and light neutral colors.
*   **Tertiary (Forest Green):** An accent color used sparingly to denote freshness, organic ingredients, or special "Chef’s Choice" highlights. 
*   **Neutral (Porcelain):** A soft cream that serves as the primary canvas color. It is warmer and more inviting than a sterile pure white, reducing eye strain and enhancing the cozy feel.

## Typography

This design system utilizes a dual-font strategy to balance premium precision with approachable warmth.

**Manrope** is used for headlines and display text. Its modern, geometric structure conveys a sense of professional craftsmanship and high-end service.

**Be Vietnam Pro** handles all body copy and UI labels. Its slightly wider apertures and friendly terminals ensure maximum readability, even on small screens, while maintaining a contemporary, welcoming tone.

Use tight tracking for large displays to maintain a cohesive look, and slightly increased tracking for small labels to ensure legibility against the cream background.

## Layout & Spacing

The layout philosophy is based on a **12-column fluid grid** for desktop and a **4-column grid** for mobile. We prioritize "generous breathing room" to prevent the interface from feeling cluttered, reflecting the relaxed atmosphere of a physical café.

*   **Vertical Rhythm:** Built on an 8px baseline. Use `lg` and `xl` spacing for section separators to emphasize the premium feel.
*   **Horizontal Alignment:** Content should be centered with wide `margin-desktop` values to create a "boutique" focused column.
*   **Reflow:** On mobile, components like product cards transition from multi-column grids to a single-stack list with increased vertical padding to maintain touch-friendly targets.

## Elevation & Depth

We use **Ambient Shadows** and **Tonal Layers** to create a sense of physical space.

1.  **Level 0 (Floor):** The `#F5F5F5` cream background.
2.  **Level 1 (Card):** White surfaces with a very soft, diffused shadow. Use a primary color tint (`rgba(62, 39, 35, 0.05)`) for shadows instead of pure black to maintain the warm aesthetic.
3.  **Level 2 (Interactive):** Elements like active buttons or hovered cards should lift slightly using a more pronounced, blurred shadow.

Avoid harsh borders. Depth is primarily communicated through subtle shifts in color (using the beige for containers) and soft, expansive shadows.

## Shapes

The shape language is **Rounded**, reflecting the soft edges of ceramic cups and organic furniture. 

*   **Standard Elements:** Buttons, input fields, and small cards use a `0.5rem` radius.
*   **Large Containers:** Main content cards or image containers use `1.5rem` (rounded-xl) to emphasize the soft, welcoming nature of the brand.
*   **Iconography:** Icons should feature rounded caps and corners. Avoid sharp geometric icons in favor of more humanist, flowing line work.

## Components

### Buttons
*   **Primary:** Solid Deep Coffee (#3E2723) with Cream text. 8px rounded corners. Use a subtle lift on hover.
*   **Secondary:** Solid Warm Beige (#D7CCC8) with Deep Coffee text. Ideal for less urgent actions like "View Menu."
*   **Ghost:** Deep Coffee outline (1px) or just text. Used for tertiary actions.

### Cards
Cards are the primary vessel for menu items. They feature a white background, `rounded-xl` corners, and a 24px internal padding. Product images should be cropped with soft corners to match the card radius.

### Input Fields
Inputs use the Warm Beige (#D7CCC8) at a very low opacity (10-15%) for the fill, providing a tactile, recessed feel. The border should only appear on focus using the Primary color.

### Chips & Badges
Used for categories (e.g., "Espresso," "Pastries") or status (e.g., "Seasonal"). Use the Forest Green (#1B5E20) for "New" or "Organic" badges to provide a fresh visual pop against the browns and beiges.

### Lists
Menu lists should have generous 16px vertical spacing between items, using the Primary color for the item name and the Secondary color for the price/description to create a clear typographic hierarchy.