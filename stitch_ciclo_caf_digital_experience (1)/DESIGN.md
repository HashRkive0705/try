---
name: Ciclo Café Editorial System
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#504443'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#827472'
  outline-variant: '#d4c3c1'
  surface-tint: '#795553'
  primary: '#321716'
  on-primary: '#ffffff'
  primary-container: '#4a2c2a'
  on-primary-container: '#bd928f'
  inverse-primary: '#eabcb8'
  secondary: '#605e5a'
  on-secondary: '#ffffff'
  secondary-container: '#e6e2dd'
  on-secondary-container: '#666460'
  tertiary: '#05240e'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c3a21'
  on-tertiary-container: '#83a584'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#eabcb8'
  on-primary-fixed: '#2e1413'
  on-primary-fixed-variant: '#5f3e3c'
  secondary-fixed: '#e6e2dd'
  secondary-fixed-dim: '#c9c6c1'
  on-secondary-fixed: '#1c1c19'
  on-secondary-fixed-variant: '#484743'
  tertiary-fixed: '#c8ecc8'
  tertiary-fixed-dim: '#acd0ad'
  on-tertiary-fixed: '#03210b'
  on-tertiary-fixed-variant: '#2f4e33'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
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
  section-gap-lg: 120px
  section-gap-md: 80px
---

## Brand & Style

The design system is rooted in **Luxury Minimalism** and **Modern Editorial** aesthetics. It bridges the gap between high-end hospitality and active lifestyle culture. The visual narrative is sophisticated yet grounded, evoking the sensory experience of a premium café—warmth, precision, and community.

The emotional response should be one of "Refined Comfort." We employ heavy whitespace, intentional asymmetric layouts, and high-quality photography to elevate the bicycle-inspired accents from "sporty" to "curated." The style borrows from the "Global Boutique" movement seen in luxury slow-living publications, prioritizing legibility, organic flow, and a tactile sense of quality.

## Colors

The palette is a sophisticated "Earth-Tone Luxe" collection. 

- **Primary (Deep Coffee Brown):** Used for primary actions, branding, and high-contrast typography to provide a sturdy, grounded feel.
- **Secondary (Cream Beige):** Acts as a soft surface color to reduce visual fatigue and separate content sections without harsh lines.
- **Accent (Forest Green):** Represents the bicycle/outdoor element; used sparingly for success states, active indicators, and lifestyle callouts.
- **Highlight (Terracotta):** A warm, energetic tone used for micro-interactions, special offers, or "new" tags to draw the eye.
- **Text & Background:** We utilize Charcoal Black on Warm Off-White to maintain an editorial, "printed-paper" feel that is softer than pure black-on-white.

## Typography

This design system uses a high-contrast typographic pairing to reinforce its editorial roots. 

**Playfair Display** is the voice of the brand—used for headings and hero sections. It should be typeset with tight leading and slight negative letter-spacing in large formats to feel like a premium magazine masthead.

**Montserrat** provides a clean, functional counterpoint. For body text, we use a generous line height (1.6) to ensure breathability. Labels and metadata should use the bold weight of Montserrat with increased letter-spacing and uppercase styling to create a clear functional hierarchy.

## Layout & Spacing

The layout philosophy follows a **Fixed-Width Centered Grid** for desktop to maintain the "contained" feel of a luxury menu or lookbook. On mobile, it transitions to a fluid single-column layout.

- **Grid:** A 12-column grid is used for desktop. Content should often be intentionally offset (e.g., spanning columns 2 through 10) to create sophisticated whitespace "lungs" on the sides of the screen.
- **Rhythm:** We use a base-8 spacing scale. Large vertical gaps (Section-Gap-LG) are critical to separate different "stories" or menu categories, reinforcing the slow-living brand pace.
- **Alignment:** While text is primarily left-aligned for readability, featured quotes or "Chef's Notes" may be center-aligned to break the rhythm.

## Elevation & Depth

To maintain a premium feel, this design system avoids heavy shadows. We use **Tonal Layers** and **Ambient Shadows** to create a sense of soft, natural depth.

1.  **Level 0 (Background):** Warm Off-White (#FAF8F5).
2.  **Level 1 (Cards/Surfaces):** Cream Beige (#F7F3EE) or White, with a very soft, diffused shadow (Blur: 20px, Y: 4px, Opacity: 4%, Color: Primary).
3.  **Level 2 (Interactive/Floating):** Used for navigation bars or modals. These use a slightly tighter but still soft shadow to indicate they are closer to the user.

We also use **Backdrop Blurs** (10px) on navigation overlays to maintain a sense of context and light within the physical café space.

## Shapes

The shape language is **Modern Rounded**. We avoid sharp, aggressive corners to mimic the organic shapes of coffee beans, ceramic mugs, and bicycle frames. 

- **Cards & Containers:** Use a standard `rounded-lg` (16px) to feel approachable.
- **Buttons:** Use a `rounded-xl` (24px) or full-pill shape to emphasize the "lifestyle" and "community" aspect.
- **Accents:** Occasional use of "Organic Squiggles" or circular image masks can be used as decorative bicycle-wheel motifs.

## Components

### Buttons
- **Primary:** Deep Coffee Brown background, White text. Pill-shaped. On hover, background shifts to Terracotta for a warm "glow."
- **Secondary:** Transparent with a 1px Deep Coffee Brown border. On hover, fills with Cream Beige.
- **Ghost:** Forest Green text with no border. Used for "Read More" editorial links.

### Cards
- **Product/Menu Cards:** White background, `rounded-lg` corners, and a soft ambient shadow. Images should have a subtle 5% Primary color overlay to keep photos feeling "warm."
- **Lifestyle/Event Cards:** Cream Beige background with an offset image layout to mimic a scrapbook or magazine.

### Input Fields
- Underlined style or softly rounded containers. Focus state is a 2px bottom border in Terracotta. Labels are always small, uppercase Montserrat.

### Chips & Tags
- Used for "Origin," "Roast Level," or "Bicycle Friendly." Small, pill-shaped, using the Accent (Forest Green) or Highlight (Terracotta) colors with 10% opacity backgrounds and full-strength text colors.

### Navigation
- A floating "Header" bar that is semi-transparent with a backdrop blur. Links are Montserrat Bold, 12px, Uppercase.