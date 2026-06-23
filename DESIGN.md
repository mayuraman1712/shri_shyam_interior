---
name: Artisan Timber & Light
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#cfc4c6'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#988e90'
  outline-variant: '#4c4547'
  surface-tint: '#cdc4c5'
  primary: '#cdc4c5'
  on-primary: '#342f30'
  primary-container: '#231f20'
  on-primary-container: '#8d8687'
  inverse-primary: '#635d5e'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#dec1ac'
  on-tertiary: '#3f2d1e'
  tertiary-container: '#2d1d10'
  on-tertiary-container: '#9c8371'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9e0e1'
  primary-fixed-dim: '#cdc4c5'
  on-primary-fixed: '#1e1b1c'
  on-primary-fixed-variant: '#4b4546'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#fbddc7'
  tertiary-fixed-dim: '#dec1ac'
  on-tertiary-fixed: '#28180b'
  on-tertiary-fixed-variant: '#574333'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-xl:
    fontFamily: Bodoni Moda
    fontSize: 80px
    fontWeight: '700'
    lineHeight: 90px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: 0.1em
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: 0.05em
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.2em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  margin-page: 5vw
  gutter: 2rem
  section-gap: 8rem
  stack-sm: 0.5rem
  stack-md: 1.5rem
  stack-lg: 3rem
---

## Brand & Style

The design system embodies "Avant-Garde Craftsmanship"—a fusion of raw, organic materials and high-fashion editorial precision. It targets a discerning audience that values the intersection of traditional woodworking and contemporary luxury. 

The visual style is **Cinematic Minimalism** mixed with **Tactile Luxury**. It leverages deep, moody environments to make "Artisan" products appear like gallery pieces. The emotional response is one of quiet confidence, heritage, and exclusivity. By utilizing high-contrast typography and rich physical textures, the UI moves away from digital abstraction and toward a visceral, high-end physical experience.

## Colors

The palette is rooted in a "Dark Mode" expression of luxury. 
- **Ebony (#121212)** serves as the atmospheric void for the background.
- **Deep Walnut (#231F20)** provides structural tonal shifts for containers.
- **Artisan Gold (#D4AF37)** is used sparingly for high-impact accents.

**Texture Tokens:**
Do not use flat colors for primary actions or hero sections. Apply the `brushed_gold` gradient to call-to-action buttons and dividers. Use `walnut_grain` for large surface areas (like sidebars or cards) to ground the digital experience in materiality. `soft_fabric` should be applied to subtle overlays to soften the edges of the dark UI.

## Typography

This design system utilizes a high-contrast serif for an editorial feel. **Bodoni Moda** is the voice of the brand—dramatic, elegant, and authoritative. 

For headlines, use wide `letterSpacing` (0.1em) to evoke a sense of breathing room and luxury. **Hanken Grotesk** provides a clean, contemporary counterpoint for functional text and body copy, ensuring legibility against textured backgrounds. Always use `label-caps` for small identifiers and metadata to maintain the high-fashion aesthetic.

## Layout & Spacing

The layout philosophy is **Cinematic White Space**. Content should never feel crowded. 
- Use a **12-column fixed grid** for desktop with generous 5vw side margins.
- Sections are separated by large vertical gaps (`section-gap`) to allow the eye to rest.
- **Asymmetric alignment:** Shift imagery and text blocks off-center to mimic a physical lookbook. 
- Elements should "float" within the dark void, using wide gutters to prevent visual clutter.

## Elevation & Depth

Depth is conveyed through **Material Layering** rather than traditional drop shadows.
- **Primary Surfaces:** Ebony background (#121212).
- **Secondary Surfaces:** Walnut texture with a subtle inner-glow (1px stroke of #FFFFFF0A) to define edges.
- **Interactive Layers:** Use "Brushed Gold" for elements that are physically "raised" toward the user.
- **Atmospheric Blur:** Use high-radius backdrop blurs (40px+) behind navigation bars to simulate frosted glass resting on top of wood and fabric.
- **Shadows:** If used, they should be extremely soft, large, and tinted with the secondary Walnut color (#4A3728) to feel like natural ambient occlusion.

## Shapes

To balance the sharp edges of the typography, UI elements use a **Rounded** (0.5rem) base. Large-scale components like hero cards and image containers should use `rounded-xl` (1.5rem) to mimic the organic, hand-sanded curves of high-end furniture. Buttons and inputs maintain a soft but defined radius to feel modern yet approachable.

## Components

- **Buttons:** Primary buttons use the `brushed_gold` texture with `label-caps` typography in ebony. Secondary buttons are "ghost style" with a 1px gold stroke.
- **Cards:** Cards use the `walnut_grain` background. They feature no borders, instead relying on the texture shift and internal padding (`stack-lg`) to define their shape.
- **Inputs:** Minimalist bottom-border only, using a subtle gold highlight when focused. 
- **Chips/Labels:** Small, pill-shaped elements with a low-opacity gold fill (#D4AF3715) and gold text.
- **Product Lists:** High-margin layouts where the image takes 60% of the container, with the serif headline overlapping the edge of the image slightly for an editorial look.
- **Dividers:** Use a 1px horizontal line with a gold-to-transparent gradient fade.