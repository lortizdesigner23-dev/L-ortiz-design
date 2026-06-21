---
name: L.Ortiz Design System
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1b1b1d'
  surface-container: '#1f1f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#343536'
  on-surface: '#e4e2e4'
  on-surface-variant: '#c5c6cd'
  inverse-surface: '#e4e2e4'
  inverse-on-surface: '#303032'
  outline: '#8f9097'
  outline-variant: '#44474d'
  surface-tint: '#b9c7e4'
  primary: '#b9c7e4'
  on-primary: '#233148'
  primary-container: '#0a192f'
  on-primary-container: '#74829d'
  inverse-primary: '#515f78'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#e7bf99'
  on-tertiary: '#432b10'
  tertiary-container: '#281400'
  on-tertiary-container: '#9d7b5a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#ffdcbd'
  tertiary-fixed-dim: '#e7bf99'
  on-tertiary-fixed: '#2b1701'
  on-tertiary-fixed-variant: '#5d4124'
  background: '#131315'
  on-background: '#e4e2e4'
  surface-variant: '#343536'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Inter
    fontSize: 13px
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system is built for a professional creative studio, balancing the precision of high-end design with a welcoming, accessible energy. It draws inspiration from premium asset marketplaces, emphasizing clarity, discoverability, and creative inspiration.

The aesthetic follows a **Modern-Creative** approach: 
- **Clean & Premium:** High use of whitespace and structured grids to ensure content is the hero.
- **Welcoming:** Softened by generous border radii and subtle glows that prevent the interface from feeling overly corporate.
- **Dynamic:** Utilizing depth through layered cards and soft gradients to guide the user's eye toward key actions.

The emotional response should be one of "Explora. Crea. Innova." — an invitation to explore a curated world of design, the tools to create with confidence, and the inspiration to innovate.

## Colors
The palette is anchored by a deep, sophisticated Navy (**#0A192F**) that serves as the canvas for both Light and Dark modes. 

- **Primary:** Used for backgrounds, deep headers, and primary text in light mode.
- **Secondary:** Used for high-contrast text and clean card backgrounds in light mode.
- **Accent:** A vibrant Orange (**#FF6B35**) used sparingly for CTAs, active states, and "innovation" highlights.

In Dark Mode, use the **Primary Surface** gradient to create depth on the background. Use the **Accent Glow** behind featured cards or icons to create a soft, backlit "halo" effect reminiscent of premium asset previews.

## Typography
This design system utilizes a dual-font strategy. **Montserrat** provides a bold, geometric presence for headings, conveying the "Innova" aspect of the brand. **Inter** is used for all functional and body text to ensure maximum legibility and a systematic, modern feel.

- **Scale:** High contrast between display sizes and body text to create a clear editorial hierarchy.
- **Weight:** Use Semibold (600) for subheaders to maintain a premium "weighted" feel.
- **Letter Spacing:** Tighten headings slightly (-0.02em) for a more "locked-in" professional look; widen labels slightly for readability in small caps.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a 12-column structure for desktop. 

- **Vertical Rhythm:** Built on an 8px base unit. Component heights and internal padding should always be multiples of 8.
- **Safe Zones:** Generous external margins (64px on desktop) ensure the content feels premium and uncrowded.
- **Responsive Behavior:** On mobile, the 12-column grid collapses to a 4-column layout, and internal card padding reduces from 32px to 20px to maximize screen real estate.

## Elevation & Depth
Depth is created through "Soft Layering." This design system avoids harsh shadows in favor of ambient, multi-layered blurs.

- **Level 1 (Cards):** Small 2px Y-offset shadow with 15% opacity of the primary color.
- **Level 2 (Hover/Modals):** Large 20px blur, 10px Y-offset, with 10% opacity. 
- **Glassmorphism:** For navigation bars and overlay panels, use a Backdrop Blur (20px) with a 70% transparent secondary or primary color fill (depending on mode) and a 1px "inner-glow" border.

## Shapes
The shape language is defined by significant rounding to evoke a friendly, approachable atmosphere.

- **Standard Elements:** Use `rounded-lg` (16px) for standard buttons and input fields.
- **Containers:** Use `rounded-xl` (24px) for cards and main content areas.
- **Feature Elements:** Use `rounded-2xl` (32px) for hero images or large call-out sections to create a soft, organic look.

## Components
- **Buttons:** Primary buttons use the Orange gradient with a subtle drop shadow. Text is bold and white. Secondary buttons use a transparent background with a 2px Orange border.
- **Cards:** Premium asset-style cards with a fixed aspect ratio for imagery. Titles appear in Montserrat (Headline-MD) below the image. Footers inside cards use Label-SM for metadata (tags, categories).
- **Inputs:** High-quality fields with a soft 1px border. On focus, the border transitions to Orange with a 4px soft outer glow.
- **Chips/Tags:** Used for categorization. These should have a subtle background tint (5% of accent color) and fully rounded (pill) corners.
- **Search Bar:** A central feature component. Large, rounded-2xl, with a subtle internal shadow to suggest depth and an Orange search icon.