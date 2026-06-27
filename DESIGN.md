---
name: Lumina Digital Architecture
colors:
  surface: '#15121b'
  surface-dim: '#15121b'
  surface-bright: '#3c3742'
  surface-container-lowest: '#100d16'
  surface-container-low: '#1d1a24'
  surface-container: '#221e28'
  surface-container-high: '#2c2833'
  surface-container-highest: '#37333e'
  on-surface: '#e8dfee'
  on-surface-variant: '#ccc3d8'
  inverse-surface: '#e8dfee'
  inverse-on-surface: '#332f39'
  outline: '#958da1'
  outline-variant: '#4a4455'
  surface-tint: '#d2bbff'
  primary: '#d2bbff'
  on-primary: '#3f008e'
  primary-container: '#7c3aed'
  on-primary-container: '#ede0ff'
  inverse-primary: '#732ee4'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#007184'
  on-tertiary-container: '#b7efff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#eaddff'
  primary-fixed-dim: '#d2bbff'
  on-primary-fixed: '#25005a'
  on-primary-fixed-variant: '#5a00c6'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#15121b'
  on-background: '#e8dfee'
  surface-variant: '#37333e'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 44px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
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
    lineHeight: '1.6'
  label-sm:
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The design system is engineered for a high-end Full Stack Developer portfolio, targeting tech-savvy recruiters and premium clients. The brand personality is **Elite, Technical, and Ethereal**. It captures the "Linear" aesthetic—combining ultra-precise engineering with a moody, cinematic atmosphere.

The visual style is a fusion of **Glassmorphism** and **Modern Minimalism**. It relies on deep canvas depth created through background blurs, subtle mesh gradients, and "laser-cut" thin borders. The experience should feel like interacting with a futuristic command center: responsive, tactile, and visually immersive without being cluttered. High-contrast typography ensures readability against the complex, layered background elements.

## Colors

This design system utilizes a "Deep Space" palette anchored by a rich, midnight navy background. The accent colors function as "light sources" within the dark environment:

*   **Electric Purple (#7C3AED):** Used for primary actions and brand highlights.
*   **Neon Blue (#3B82F6) & Cyan (#06B6D4):** Used for interactive secondary elements and status indicators.
*   **Emerald Green (#10B981):** Reserved for "success" states and live project badges.

The UI relies heavily on **transparency**. Surfaces are rarely solid; they are semi-transparent layers that allow background mesh gradients to peek through, creating a sense of physical glass. Use a "Grain" overlay on background gradients to add a sophisticated, filmic texture.

## Typography

Typography in this design system is architectural. **Plus Jakarta Sans** provides a friendly yet precise geometric feel for headlines, while **Inter** ensures maximum legibility for technical descriptions and body copy.

Key typographic rules:
1.  **Display Headlines:** Use tight letter-spacing and a subtle linear gradient (from white to 80% white) to give text a metallic, premium look.
2.  **Code Snippets:** Use a monospaced variant of Inter for technical details to reinforce the "Full Stack" identity.
3.  **Labels:** Always use uppercase with increased tracking for section identifiers and metadata to create a structural hierarchy.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid Grid**. Content is centered within a 1280px container, but background elements and decorative "light leaks" bleed to the edges of the viewport.

*   **The 8px Rhythm:** All spacing (padding, margins, gaps) must be a multiple of 8px to maintain mathematical harmony.
*   **Section Breaths:** We use significant vertical padding (120px+) between sections to allow the glassmorphic cards to "float" without visual crowding.
*   **Responsive Reflow:** On mobile, the 12-column desktop grid collapses to a single column. The display typography scales aggressively to maintain the "heroic" feel on smaller screens.

## Elevation & Depth

Depth is not achieved through traditional black shadows, but through **Backdrop Blur (20px-40px)** and **Inner Glows**.

1.  **Layer 0 (Canvas):** The primary background #0B0F19 with subtle, animated mesh gradients in the corners.
2.  **Layer 1 (Cards):** Semi-transparent surfaces with a 1px "stroke" border. The border should be a linear gradient (top-left to bottom-right) starting at `rgba(255,255,255,0.15)` and fading to `rgba(255,255,255,0.02)`.
3.  **Layer 2 (Popovers/Modals):** High-intensity backdrop blur (60px) with a subtle outer glow using the primary purple color at 10% opacity to simulate light emitting from the element.

## Shapes

The design system uses a **Refined Rounded** aesthetic. 
*   **Cards & Containers:** Use `rounded-lg` (1rem/16px) for a balanced, modern feel.
*   **Buttons:** Use `rounded-xl` (1.5rem/24px) or full pill-shape for primary calls-to-action to make them feel more "pressable" and distinct from the structural containers.
*   **Media/Images:** Portfolio screenshots should mirror the card roundedness (16px) and include the 1px inner border to integrate seamlessly into the glass environment.

## Components

### Buttons
Primary buttons use a vibrant gradient (Purple to Blue) with a white label. Secondary buttons are "Ghost" style—1px semi-transparent borders with a backdrop blur and a hover state that increases the blur intensity.

### Project Cards
The centerpiece of the portfolio. These use the glassmorphic style described in Elevation. On hover, the 1px border should animate its gradient position, and the background blur should decrease slightly to "focus" the content.

### Skill Chips
Small, pill-shaped tags with a low-opacity background tint (e.g., 10% Cyan for React). They use the `label-sm` typography.

### Input Fields
Dark, inset fields with `rgba(0,0,0,0.2)` background. The focus state replaces the border with a 1px solid Cyan stroke and a soft Cyan outer glow.

### Navigation Bar
A floating "dock" at the top or bottom of the screen. It must have a high-strength backdrop blur (40px) and a very thin white border to separate it from the content scrolling beneath it.