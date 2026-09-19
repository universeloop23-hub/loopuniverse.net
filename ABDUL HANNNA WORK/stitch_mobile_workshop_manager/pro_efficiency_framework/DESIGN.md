---
name: Pro-Efficiency Framework
colors:
  surface: '#f9f9ff'
  surface-dim: '#d8d9e5'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3fe'
  surface-container: '#ecedf9'
  surface-container-high: '#e6e8f3'
  surface-container-highest: '#e0e2ed'
  on-surface: '#181c23'
  on-surface-variant: '#414755'
  inverse-surface: '#2d3039'
  inverse-on-surface: '#eef0fc'
  outline: '#717786'
  outline-variant: '#c1c6d7'
  surface-tint: '#005bc1'
  primary: '#0058bc'
  on-primary: '#ffffff'
  primary-container: '#0070eb'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#5d5e63'
  on-secondary: '#ffffff'
  secondary-container: '#e0dfe4'
  on-secondary-container: '#626267'
  tertiary: '#9e3d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c64f00'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#e3e2e7'
  secondary-fixed-dim: '#c6c6cb'
  on-secondary-fixed: '#1a1b1f'
  on-secondary-fixed-variant: '#46464b'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb595'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7c2e00'
  background: '#f9f9ff'
  on-background: '#181c23'
  surface-variant: '#e0e2ed'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 41px
    letterSpacing: -0.4px
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.2px
  body-base:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: -0.4px
  body-sm:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.2px
  label-caps:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.1px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.4px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base_unit: 8px
  safe_area_inset: env(safe-area-inset-bottom)
  gutter: 16px
  margin_mobile: 16px
  margin_desktop: 32px
  touch_target_min: 44px
---

## Brand & Style
The design system focuses on a high-utility, professional atmosphere tailored for industrial and service environments. It is characterized by extreme clarity, functional minimalism, and a "utility-first" aesthetic. Drawing inspiration from modern OS-level design, the interface prioritizes content and actionable data over decorative elements.

The target audience consists of workshop managers and technicians who require rapid information retrieval and high-precision input on mobile devices. The emotional response is one of reliability, order, and efficiency. The style utilizes **Corporate / Modern** foundations with **Glassmorphism** used selectively for structural orientation (headers and navigation) to maintain context during scroll.

## Colors
This design system utilizes a dynamic palette that shifts between Light and Dark modes to ensure maximum legibility in varying workshop lighting conditions.

- **Primary:** The signature Blue (#007AFF) is reserved for primary actions, active states, and critical paths.
- **Neutrals:** A multi-step gray scale is used for hierarchy. In Light mode, backgrounds use a tiered "System Gray" approach (F2F2F7). In Dark mode, true black (#000000) is used for OLED efficiency and high contrast, with elevated surfaces using dark charcoal grays.
- **Status:** Semantically strict application of Green, Amber, and Red for job completion, pending parts, and overdue tasks respectively.

## Typography
The typography system uses **Inter** to replicate the systematic, neutral, and highly legible qualities of modern San Francisco-based interfaces. 

- **Hierarchy:** High contrast in weight is used to distinguish between data labels and values.
- **Readability:** Body text is set at 17px to ensure ease of reading during active movement in a workshop.
- **Mobile Optimization:** Large "Display" titles collapse into "Headline" styles on mobile scroll to maximize vertical screen real estate.
- **Spacing:** Tight letter spacing is applied to larger headers for a compact, professional look, while labels utilize slightly increased spacing for clarity in high-density data tables.

## Layout & Spacing
The layout follows a fluid-grid model optimized for PWA constraints. 

- **Safe Areas:** All mobile views must respect `env(safe-area-inset-*)` variables, particularly for the Dynamic Island and the home indicator area.
- **Grid:** A 4-column grid for mobile and 12-column for desktop. Content containers use a maximum width of 1200px on desktop to maintain readability.
- **Rhythm:** An 8px linear scale governs all padding and margins. Vertical rhythm is strictly enforced to ensure lists and forms feel organized.
- **Touch Targets:** A minimum interactive area of 44x44px is required for all mobile controls to accommodate gloved or moving hands in a workshop environment.

## Elevation & Depth
Depth is communicated through functional layering rather than decorative shadows.

- **Tonal Layering:** The primary background is the lowest layer. Cards and containers use a secondary background color (Pure White in Light, Dark Gray in Dark).
- **Glassmorphism:** Navigation bars and toolbars utilize a `backdrop-filter: blur(20px)` with a 70% opaque background color. This allows the user to maintain a sense of content depth while scrolling.
- **Shadows:** Only used on floating action buttons (FABs) and modals. Shadows are large, soft, and low-opacity (10-15%), using the system gray rather than pure black to avoid a "dirty" look.
- **Outlines:** In high-density data views, 0.5pt (1px) hairlines are used to separate list items, mimicking the high-contrast professional feel of system-level utilities.

## Shapes
The shape language follows a "squircle-inspired" approach. 

- **Standard Elements:** Buttons, input fields, and cards utilize a 10px-12px corner radius (`rounded-lg`), providing a modern yet professional appearance.
- **Small Elements:** Checkboxes and tags use a 4px radius (`rounded-sm`).
- **Context:** In full-width mobile list views, cards may lose side radii to maximize space, but top and bottom items in a group retain their corner rounding to form "grouped inset" patterns.

## Components
- **Buttons:** Large, prominent shapes. Primary buttons use the accent blue with white text. Secondary buttons use a light-gray fill with blue text.
- **Input Fields:** Inset styles with clear labels. Focus states are indicated by a 2px blue ring or high-contrast border.
- **Lists (Grouped Inset):** Data is presented in "Grouped Inset" lists—rounded containers with white backgrounds (light mode) that sit against the light gray system background.
- **Chips/Badges:** Used for status (e.g., "In Progress"). These use a low-opacity tint of the status color for the background and a high-opacity version for the text.
- **Navigation:** A persistent bottom tab bar for mobile, and a glass-morphic top bar for global actions (Search, Profile).
- **Cards:** Used for high-level summaries (Total Jobs, Revenue). Cards include a subtle 1px border in addition to the background color to ensure definition in Dark mode.