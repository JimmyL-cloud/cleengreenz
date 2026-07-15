---
name: Cleen Greenz
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
  on-surface-variant: '#40493d'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#707a6c'
  outline-variant: '#bfcaba'
  surface-tint: '#1b6d24'
  primary: '#0d631b'
  on-primary: '#ffffff'
  primary-container: '#2e7d32'
  on-primary-container: '#cbffc2'
  inverse-primary: '#88d982'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#485860'
  on-tertiary: '#ffffff'
  tertiary-container: '#607079'
  on-tertiary-container: '#e2f4fe'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a3f69c'
  primary-fixed-dim: '#88d982'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005312'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#d4e5ef'
  tertiary-fixed-dim: '#b8c9d3'
  on-tertiary-fixed: '#0d1e25'
  on-tertiary-fixed-variant: '#394951'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
The brand personality is professional, dependable, and rooted in local expertise. It avoids the cluttered, aggressive marketing common in the landscaping industry in favor of a **Corporate Modern** aesthetic that emphasizes precision and reliability. The target audience is homeowners and property managers in Niles, Michigan, who value quality and a "job well done."

The visual style utilizes generous whitespace and a clean, structured layout to evoke a sense of order and meticulous care. It balances the warmth of a local business with the systematic polish of a high-end service provider. The emotional response should be one of "effortless curb appeal" and "total confidence."

## Colors
The palette is built around **Rich Lawn Green**, representing health and growth. **Pure White** serves as the primary canvas to maintain a "clean" feel, while **Charcoal Gray** provides the necessary grounding for typography and structural elements. 

**Bright Lime Green** is used sparingly as a high-visibility highlight for calls-to-action and success states, ensuring they pop against the deeper primary green. The neutral scale is kept cool and clean, avoiding muddy tones to ensure the green hues remain the focus.

## Typography
This design system uses a dual-font approach to balance character with utility. **Montserrat** is used for headlines to convey confidence and a modern, geometric strength. **Inter** is used for all body copy and UI labels to ensure maximum legibility and a systematic, clean feel.

Maintain a strict vertical rhythm by adhering to the defined line heights. For headlines, tighter letter spacing is encouraged to create a more impactful, "locked-in" appearance. Body text should always prioritize readability with standard tracking.

## Layout & Spacing
The system follows a **Fixed Grid** model on desktop to maintain a premium, editorial feel, transitioning to a fluid model on mobile devices. A 12-column grid is used for desktop layouts, while a 4-column grid is standard for mobile.

Spacing is based on an 8px base unit. Generous internal padding (v-space) is encouraged between sections to allow the brand to "breathe," mirroring the open space of a well-maintained lawn. Use 80px - 120px gaps between major sections on desktop to signify a premium experience.

## Elevation & Depth
The system uses **Ambient Shadows** to create a sense of organized layers without appearing heavy. Shadows should be soft, extra-diffused, and use a slight Charcoal Gray (#37474F) tint to avoid a "dirty" look.

- **Level 1 (Cards/Inputs):** 0px 2px 8px rgba(55, 71, 79, 0.08).
- **Level 2 (Hover states/Modals):** 0px 8px 24px rgba(55, 71, 79, 0.12).
- **Surface Layering:** Use the neutral light gray (#F5F5F5) for background sections to distinguish them from the Pure White content cards, creating depth through tonal shifts rather than just shadows.

## Shapes
A **Rounded** shape language is utilized to make the professional aesthetic feel approachable and friendly. Standard UI components like buttons and input fields use an 8px (0.5rem) radius. For larger containers and cards, a 16px (1rem) radius is preferred to emphasize the modern, soft-touch feel of the brand.

## Components
- **Buttons:** Primary buttons use the Rich Lawn Green background with Pure White text. Secondary buttons use a Charcoal Gray outline with 2px weight. High-priority CTAs (e.g., "Get a Quote") may use the Bright Lime Green with Charcoal text for maximum contrast.
- **Input Fields:** Use a 1px Charcoal Gray border at 20% opacity. Upon focus, the border thickens to 2px and changes to Rich Lawn Green.
- **Cards:** White backgrounds with Level 1 shadows. Use 24px internal padding. Content should be left-aligned for a structured, professional look.
- **Chips:** Used for service tags (e.g., "Mowing," "Fertilization"). Use a light tint of the primary green (10% opacity) with dark green text.
- **Icons:** Use 2px stroke weight line-art icons. Icons should be Charcoal Gray for general use, or Rich Lawn Green when highlighting a specific service or benefit.
- **Service Lists:** Use custom checkmarks in Bright Lime Green to signify completion and health.