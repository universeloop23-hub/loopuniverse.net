---
name: Kinetic Precision
colors:
  surface: '#f9f9fc'
  surface-dim: '#dadadc'
  surface-bright: '#f9f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f6'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e5'
  on-surface: '#1a1c1e'
  on-surface-variant: '#584238'
  inverse-surface: '#2f3133'
  inverse-on-surface: '#f0f0f3'
  outline: '#8c7166'
  outline-variant: '#e0c0b2'
  surface-tint: '#a14000'
  primary: '#a14000'
  on-primary: '#ffffff'
  primary-container: '#f26d21'
  on-primary-container: '#521d00'
  inverse-primary: '#ffb694'
  secondary: '#575f65'
  on-secondary: '#ffffff'
  secondary-container: '#dbe4ea'
  on-secondary-container: '#5d656b'
  tertiary: '#5c5f60'
  on-tertiary: '#ffffff'
  tertiary-container: '#939596'
  on-tertiary-container: '#2b2e2f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcc'
  primary-fixed-dim: '#ffb694'
  on-primary-fixed: '#351000'
  on-primary-fixed-variant: '#7b2f00'
  secondary-fixed: '#dbe4ea'
  secondary-fixed-dim: '#bfc8ce'
  on-secondary-fixed: '#151d21'
  on-secondary-fixed-variant: '#40484d'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#f9f9fc'
  on-background: '#1a1c1e'
  surface-variant: '#e2e2e5'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  button:
    fontFamily: Sora
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 48px
  stack-xl: 96px
---

## Brand & Style

The design system is engineered for a top-tier UI/UX and web design agency, projecting an image of high-tech proficiency and creative momentum. The brand personality is **authoritative yet visionary**, balancing the rigors of technical execution with the flair of innovative design. 

The aesthetic is a hybrid of **Modern Minimalism** and **Technical Sophistication**. It utilizes extreme whitespace to command attention, sharp typographic hierarchy for clarity, and subtle glassmorphic elements to suggest depth and digital layers. The goal is to evoke a sense of "engineered creativity"—where every pixel serves a functional and aesthetic purpose.

**Key visual drivers:**
- **Bold Structurality:** Using heavy-weight sans-serifs to anchor the page.
- **Kinetic Energy:** Strategic use of the brand’s vibrant orange to guide the eye and imply movement.
- **Digital Precision:** Micro-interactions and grid-aligned layouts that mirror the precision of high-end software.

## Colors

The palette is derived from the core identity, emphasizing high contrast to reinforce the "tech" narrative. 

- **Primary (Vibrant Orange):** Used for calls-to-action, active states, and highlights. It represents energy, innovation, and elevation.
- **Secondary (Charcoal Blue/Grey):** The primary color for typography and structural elements. It provides a more sophisticated and softer alternative to pure black, maintaining readability while feeling premium.
- **Neutral/Surface:** A range of cool-toned greys and whites provide the whitespace necessary for a clean, modern look.
- **Accent/Success:** Limited use of secondary tones to ensure the orange remains the dominant brand signal.

The default color mode is **Light**, utilizing high-contrast charcoal text on off-white surfaces to ensure a literary and professional feel, though a dark mode variant is supported using the Secondary color as the primary surface.

## Typography

This design system uses a triple-font strategy to communicate different layers of information:

1.  **Sora (Headlines):** A geometric sans-serif with a tech-forward personality. Used in heavy weights for impactful, high-contrast headings.
2.  **Hanken Grotesk (Body):** A highly legible, modern grotesque for long-form content, ensuring the technical nature of the site remains approachable.
3.  **JetBrains Mono (Labels/Technical Data):** Used sparingly for "meta" information, categories, and small labels to lean into the "Tech" aspect of the brand identity.

**Typographic Principles:**
- Use **Display LG** for hero sections with tight letter-spacing to create a "block" of text.
- Use **Label Caps** for eyebrow headlines above main titles to provide context.
- Maintain a generous line-height for body text to support the "ample whitespace" directive.

## Layout & Spacing

The layout philosophy follows a **12-column Fluid Grid** for desktop and a **4-column grid** for mobile. The design system prioritizes vertical rhythm and massive negative space to allow the "innovative" portfolio work to breathe.

**Breakpoints:**
- **Desktop:** 1200px+ (12 columns, 32px gutters)
- **Tablet:** 768px - 1199px (8 columns, 24px gutters)
- **Mobile:** <767px (4 columns, 16px gutters)

**Spacing Rhythm:**
Utilize the `stack-xl` (96px) spacing between major sections to emphasize the premium nature of the brand. Smaller components like card contents should adhere to a strict 8px incremental scale (`stack-sm`, `stack-md`) to ensure technical alignment.

## Elevation & Depth

Visual hierarchy is established through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.

- **Surface Levels:** The primary background is the lightest neutral. Secondary surfaces (cards, sidebars) use a subtle 1px border (`#E9ECEF`) or a very faint grey fill to distinguish them.
- **Glassmorphism:** For overlays, navigation bars, and modals, use a backdrop blur (20px) with a 70% white opacity. This maintains the "high-tech" feel without cluttering the interface.
- **Shadows:** When necessary for elevating elements (like floating action buttons), use a highly diffused, tinted shadow: `0 20px 40px rgba(44, 52, 57, 0.08)`. Avoid dark, heavy shadows.

## Shapes

The shape language is **Soft** and **Structured**. While the brand is technical, the UI avoids "sharp" corners to remain approachable and modern.

- **Base Radius:** 4px (0.25rem) for small elements like checkboxes and input fields.
- **Large Radius:** 12px (0.75rem) for cards and containers.
- **Interaction:** Interactive elements like buttons may use a slightly higher radius to feel more "tactile" under-cursor, but they should never reach full pill-shape to maintain the architectural look.

## Components

### Buttons
- **Primary:** Solid Vibrant Orange with white text. High-contrast, no shadow, subtle 2px elevation on hover.
- **Secondary:** Transparent with a 2px Charcoal Blue border and Charcoal text. 
- **Tertiary/Ghost:** Text-only with an animated underline that expands from the center on hover.

### Cards
- Use a white background with a 1px soft grey border. 
- Header text in Sora (Bold), body text in Hanken Grotesk.
- Images within cards should have a subtle 0.5s zoom-in effect on hover to imply elevation.

### Input Fields
- Underlined style or subtle light grey background. 
- The focus state should use a 2px Orange bottom border. 
- Use JetBrains Mono for placeholder text to reinforce the technical aesthetic.

### Chips & Tags
- Used for categories (e.g., "UI/UX", "Web3", "SaaS").
- Small font size (Label-caps), Charcoal Blue background with white text, or Orange tint background with Orange text for active states.

### Lists
- Clean, no bullets. Use the Vibrant Orange for custom chevron icons or numerical indicators.
- High vertical padding between list items (16px+).