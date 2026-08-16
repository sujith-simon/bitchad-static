---
name: Aetheric Corporate
colors:
  surface: '#16111b'
  surface-dim: '#16111b'
  surface-bright: '#3d3741'
  surface-container-lowest: '#110c15'
  surface-container-low: '#1f1a23'
  surface-container: '#231e27'
  surface-container-high: '#2e2832'
  surface-container-highest: '#39323d'
  on-surface: '#eadfed'
  on-surface-variant: '#cfc2d6'
  inverse-surface: '#eadfed'
  inverse-on-surface: '#342e38'
  outline: '#988d9f'
  outline-variant: '#4d4354'
  surface-tint: '#ddb7ff'
  primary: '#ddb7ff'
  on-primary: '#490080'
  primary-container: '#b76dff'
  on-primary-container: '#400071'
  inverse-primary: '#842bd2'
  secondary: '#44e2cd'
  on-secondary: '#003731'
  secondary-container: '#03c6b2'
  on-secondary-container: '#004d44'
  tertiary: '#fabc4e'
  on-tertiary: '#432c00'
  tertiary-container: '#bd871a'
  on-tertiary-container: '#3a2600'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#f0dbff'
  primary-fixed-dim: '#ddb7ff'
  on-primary-fixed: '#2c0051'
  on-primary-fixed-variant: '#6900b3'
  secondary-fixed: '#62fae3'
  secondary-fixed-dim: '#3cddc7'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005047'
  tertiary-fixed: '#ffdead'
  tertiary-fixed-dim: '#fabc4e'
  on-tertiary-fixed: '#281900'
  on-tertiary-fixed-variant: '#604100'
  background: '#16111b'
  on-background: '#eadfed'
  surface-variant: '#39323d'
  deep-space: '#0F172A'
  electric-indigo: '#6366F1'
  soft-lilac: '#E9D5FF'
  slate-gray: '#94A3B8'
typography:
  display-hero:
    fontFamily: Hanken Grotesk
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
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
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  button-text:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 24px
  section-gap: 120px
---

## Brand & Style

The design system for BitChad LLC establishes a "Corporate Modern" aesthetic that bridges the gap between high-stakes technology and approachable creativity. It serves as a sophisticated evolution of the BurstClip product brand, transitioning from a playful consumer app to a visionary parent entity. 

The visual narrative is anchored in **Reliability** and **AI-centric Innovation**. It utilizes a structured, grid-based layout to signal stability, while integrating soft glassmorphic layers and high-fidelity blurs to evoke the fluid nature of AI-driven cinematic video. The bird imagery, once a mascot, is reimagined as a refined brand mark or subtle watermark, maintaining a lineage of friendliness within a professional framework. The target audience is investors, potential talent, and enterprise partners who value both technical rigor and creative output.

## Colors

This design system adopts a **Dark Mode** default to emphasize the "Cinematic" and "Tech-Forward" nature of the company. The palette is anchored by a vibrant **Aether Purple** (#A855F7), a direct evolution of the BurstClip brand, serving as the primary action and focus color.

- **Primary (Aether Purple):** Used for primary CTAs, active states, and brand-defining accents.
- **Secondary (Teal Spark):** Provides a high-contrast companion to purple, used specifically for AI-related status indicators and secondary highlights.
- **Neutral (Deep Space):** A dark, rich navy-black (#0F172A) serves as the foundation for surfaces, ensuring the purple and teal elements pop with professional clarity.
- **Support Colors:** Electric Indigo is used for gradients to add depth, while Slate Gray handles metadata and secondary text.

## Typography

The typography strategy focuses on precision and legibility. 

- **Hanken Grotesk** is chosen for headlines to provide a sharp, contemporary edge that feels modern and authoritative. Large-scale displays use tight letter spacing to create a high-impact, editorial feel.
- **Inter** handles the heavy lifting for body copy and descriptions. Its neutral, systematic design ensures readability across dense technical information.
- **JetBrains Mono** is utilized for metadata, tags, and AI-process labels. This monospaced choice reinforces the "developer-ready" and "AI-centric" nature of BitChad LLC.

Mobile scaling is handled by aggressive reduction in display sizes, ensuring headers remain impactful without requiring excessive scrolling.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop to maintain a premium, structured feel, transitioning to a fluid model for mobile devices.

- **Desktop Layout:** A 12-column grid with a maximum container width of 1280px. Gutters are fixed at 24px to ensure breathing room between technical specs and imagery.
- **Rhythm:** An 8px base unit drives all internal component spacing (padding, gaps). 
- **Sectioning:** Large vertical gaps (120px on desktop) are used to separate distinct corporate narratives (e.g., separating "Our Mission" from "Portfolio Companies"), creating a sense of deliberate pace and importance.
- **Reflow:** On mobile, margins reduce to 24px and the 12-column grid collapses into a single-column stack.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Glassmorphism**, rather than traditional heavy shadows.

- **Surface Levels:** The primary background is the darkest tier. Overlays and cards use a slightly lighter shade of navy with a 1px "ghost border" (low-opacity white) to define edges.
- **Backdrop Blurs:** High-priority modals and navigation bars utilize a frosted-glass effect (Blur: 20px, Opacity: 80%) to maintain context of the background while focusing the user.
- **Ambient Glow:** Instead of black shadows, primary interactive elements (like the bird-icon or key CTA buttons) may use a soft, purple-tinted outer glow to suggest the "energy" of the AI engine.

## Shapes

The shape language is **Rounded (Level 2)**. 

This middle-ground approach balances the friendliness of the BurstClip consumer app with the professional requirements of a parent company. 
- **Standard UI (Inputs, Buttons):** 0.5rem (8px) radius.
- **Featured Cards:** 1rem (16px) radius to soften the presentation of large media blocks.
- **Avatars/Icons:** Use circular (pill-shaped) clipping to maintain the "bird" motif’s organic feel.

## Components

- **Buttons:** Primary buttons use a solid gradient from Primary Purple to Electric Indigo. Hover states should include a slight scale-up (1.02x) and an intensified ambient glow. Secondary buttons use the "ghost" style with a 1px border.
- **Chips / Tags:** Utilizes the monospaced label font. Chips for "AI" or "Beta" features should use the Secondary Teal color for immediate distinction.
- **Cards:** Cards should have no background fill on the primary surface level, defined only by their 1px ghost border. On hover, they transition to a subtle dark-grey fill.
- **Input Fields:** Minimalist design with only a bottom border in the inactive state, transitioning to a full-border focus state in Primary Purple.
- **Navigation:** A top-docked, glassmorphic bar that remains persistent. The logo (BitChad wordmark + refined bird icon) sits on the far left, with monospaced navigation links on the right.
- **Video Containers:** Always use the `rounded-lg` (1rem) radius and a subtle internal inner-shadow to give the cinematic content a "contained" feel.