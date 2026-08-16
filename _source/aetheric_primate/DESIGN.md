---
name: Aetheric Primate
colors:
  surface: '#141312'
  surface-dim: '#141312'
  surface-bright: '#3b3937'
  surface-container-lowest: '#0f0e0d'
  surface-container-low: '#1d1b1a'
  surface-container: '#211f1e'
  surface-container-high: '#2b2a28'
  surface-container-highest: '#363433'
  on-surface: '#e6e1df'
  on-surface-variant: '#d4c4b6'
  inverse-surface: '#e6e1df'
  inverse-on-surface: '#32302f'
  outline: '#9d8e82'
  outline-variant: '#50453a'
  surface-tint: '#f2bc84'
  primary: '#f4be86'
  on-primary: '#492900'
  primary-container: '#d6a36d'
  on-primary-container: '#5c390c'
  inverse-primary: '#7e5627'
  secondary: '#e7bdb1'
  on-secondary: '#442a22'
  secondary-container: '#5d4037'
  on-secondary-container: '#d4aca0'
  tertiary: '#d4c6b4'
  on-tertiary: '#372f22'
  tertiary-container: '#b8ab9a'
  on-tertiary-container: '#483f32'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdcbc'
  primary-fixed-dim: '#f2bc84'
  on-primary-fixed: '#2c1700'
  on-primary-fixed-variant: '#633f12'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#e7bdb1'
  on-secondary-fixed: '#2c160e'
  on-secondary-fixed-variant: '#5d4037'
  tertiary-fixed: '#efe0cd'
  tertiary-fixed-dim: '#d2c4b2'
  on-tertiary-fixed: '#221a0f'
  on-tertiary-fixed-variant: '#4f4538'
  background: '#141312'
  on-background: '#e6e1df'
  surface-variant: '#363433'
typography:
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 16px
  container-max: 1280px
---

## Brand & Style

This design system embodies a fusion of **Corporate Modern** professionalism and **Glassmorphism**. It is designed for high-stakes environments where precision meets visionary aesthetics. The brand personality is stoic, authoritative, and intellectually sophisticated, drawing direct inspiration from the low-poly ape logo's geometric structure and "tech-forward" earthy tones.

The UI targets a professional audience that values clarity, performance, and a premium "executive" experience. It relies on a dark-mode foundation to evoke depth and focus, utilizing translucent layers and sharp, intentional highlights to maintain an "Aetheric" feel. The emotional response is one of calm confidence and technical mastery.

## Colors

The palette is derived from the low-poly primate's natural yet technical color shifts.

- **Primary (#D6A36D):** A vibrant, golden tan used for high-importance actions, active states, and key data points. It provides the "tech-forward" energy against the dark backdrop.
- **Secondary (#5D4037):** A deep, rich chocolate brown used for subtle branding, secondary buttons, and tonal accents that ground the UI.
- **Tertiary (#F5E6D3):** A bright bone/cream used sparingly for high-contrast text or decorative linework to ensure maximum legibility.
- **Surface & Background (#121110):** An ultra-dark, warm charcoal that provides the foundation for the Aetheric Corporate aesthetic.

Maintain a high contrast ratio (7:1) for all primary text elements to ensure a premium, accessible experience. Use the primary color for interactive elements and critical feedback paths.

## Typography

The typography strategy emphasizes structural clarity and technical precision.

- **Headlines:** Use **Hanken Grotesk** for its sharp, contemporary geometry. It mirrors the low-poly facets of the logo.
- **Body:** **Inter** is used for its unmatched legibility and systematic feel, essential for corporate data density.
- **Data & Labels:** **JetBrains Mono** is introduced for labels, metadata, and technical readouts, reinforcing the "Aetheric Corporate" tech-forward narrative.

Use tight tracking on large headlines for a more aggressive, premium look, while maintaining generous line-heights in body text for optimal reading comfort in dark mode.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop to maintain an architectural, controlled feel, transitioning to a **Fluid Grid** for mobile.

- **Desktop:** 12-column grid, 1280px max-width, 24px gutters. Content is centered with significant outer margins (64px) to emphasize the "Aetheric" whitespace.
- **Tablet:** 8-column grid, 32px margins.
- **Mobile:** 4-column grid, 16px margins.

The spacing rhythm is based on a 4px baseline. Components should use increments of 8px for internal padding (e.g., 16px, 24px) to ensure mathematical harmony. Layouts should prioritize vertical stacking with clear, logical groupings separated by 48px or 64px blocks of space.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Glassmorphism**.

1.  **Background:** The deepest layer (#121110).
2.  **Surface:** Elevated containers use a slightly lighter brown-tinted grey with 40% opacity and a 20px backdrop blur.
3.  **Accents:** Thin, 1px low-contrast outlines (#D6A36D at 15% opacity) are used to define container boundaries instead of heavy shadows.
4.  **Shadows:** When necessary, use extremely soft, long-range ambient shadows with a warm tint (#000000 at 40% opacity, 30px blur) to simulate objects floating in a dark space.

Avoid heavy solid fills for containers; lean into transparency to maintain the "Aetheric" quality.

## Shapes

The shape language is **Soft** but structured. While the logo is low-poly and sharp, the UI uses subtle rounding to balance the "Corporate" aspect and ensure the interface feels modern and approachable.

- **Base Radius:** 4px (0.25rem) for inputs, small buttons, and tags.
- **Large Radius:** 8px (0.5rem) for cards and modals.
- **Geometric Elements:** Occasional use of 45-degree chamfered corners on decorative elements or icons can be used to echo the low-poly logo's aesthetic.

## Components

- **Buttons:** Primary buttons use a solid #D6A36D fill with dark text. Secondary buttons use a transparent background with a #5D4037 border and Primary-colored text. All buttons have a subtle inner-glow on hover.
- **Input Fields:** Dark, semi-transparent backgrounds with a 1px bottom-border highlight in the primary color when focused. Use JetBrains Mono for placeholder text.
- **Cards:** Utilize the glassmorphic style—20px backdrop blur, subtle primary-tinted border, and deep tonal background.
- **Chips/Tags:** Small, pill-shaped elements using the Primary color at 10% opacity with solid Primary text for high readability.
- **Lists:** Separated by thin, 1px lines in the Secondary color. Use generous 16px vertical padding for list items to maintain the premium feel.
- **Data Visualizations:** Use a palette of Primary (tan), Secondary (rich brown), and an additional "Tech Blue" or "Amber" accent for status-specific data points.