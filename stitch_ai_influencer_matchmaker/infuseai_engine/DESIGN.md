---
name: InfuseAI Engine
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#4fdbc8'
  on-secondary: '#003731'
  secondary-container: '#04b4a2'
  on-secondary-container: '#003f38'
  tertiary: '#ffb2b7'
  on-tertiary: '#67001b'
  tertiary-container: '#ff516a'
  on-tertiary-container: '#5b0017'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#71f8e4'
  secondary-fixed-dim: '#4fdbc8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005048'
  tertiary-fixed: '#ffdadb'
  tertiary-fixed-dim: '#ffb2b7'
  on-tertiary-fixed: '#40000d'
  on-tertiary-fixed-variant: '#92002a'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
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
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  data-numeral:
    fontFamily: JetBrains Mono
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 24px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 20px
  container-max: 1440px
---

## Brand & Style

The design system is engineered to evoke a sense of high-velocity intelligence and professional precision. It blends a "hackathon-cool" aesthetic—characterized by technical density and dark surfaces—with the polished reliability of an enterprise SaaS platform.

The visual style is a hybrid of **Modern Corporate** and **Glassmorphism**. It utilizes deep obsidian backgrounds to allow vibrant, neon-adjacent accents to pop, signifying "active" AI processes. The interface should feel like a sophisticated dashboard or a "Matching Engine," where data is the hero and every UI element serves to clarify complex influencer metrics. Expect semi-transparent overlays, subtle glow effects, and high-precision linework.

## Colors

The palette is anchored in a deep, multi-tonal dark mode to reduce eye strain during intensive data analysis.

- **Primary (Electric Indigo):** Used for primary actions, active states, and "AI-driven" highlights. It represents the energy of the platform.
- **Secondary (Teal):** Used for growth metrics, authenticity scores, and success states. It provides a technical, "calibrated" feel.
- **Tertiary (Rose):** Reserved for high-alert data points, negative trends, or critical "mismatch" warnings.
- **Neutral (Slate/Obsidian):** A range of cool grays used for surfaces, borders, and secondary text to maintain hierarchy without sacrificing the dark aesthetic.

## Typography

The typography system prioritizes legibility and a "systematic" feel. 

- **Inter** is the workhorse, providing a clean, neutral canvas for all primary interface copy.
- **JetBrains Mono** is introduced for labels, metadata, and numerical data to reinforce the "Engine" and "Hackathon" aesthetic, suggesting precision and algorithmic output.
- All headlines use tighter letter spacing to maintain a modern, "designed" look at larger scales.
- Numerical data in dashboards should always use tabular lining to ensure columns of figures align perfectly.

## Layout & Spacing

This design system utilizes a **Fluid Grid** with fixed maximum constraints for desktop viewing. 

- **Grid:** A 12-column system is used for the main dashboard area. On mobile, this collapses to a single column with 16px side margins.
- **Rhythm:** A 4px baseline grid governs all vertical rhythm.
- **Dashboard Structure:** A persistent left-hand "Command Rail" (collapsed to 64px or expanded to 240px) houses primary navigation, keeping the "Engine" tools always within reach.
- **Density:** The layout is high-density. Information is packed efficiently using 16px and 24px gaps to allow for simultaneous viewing of multiple data visualizations.

## Elevation & Depth

Depth is conveyed through **Tonal Layering** and **Glassmorphism**, rather than traditional heavy shadows.

- **Level 0 (Background):** The base layer is `#0F172A`.
- **Level 1 (Cards/Panels):** Surfaces are slightly lighter (`#1E293B`) with a 1px subtle border in a low-opacity Indigo to define edges.
- **Level 2 (Modals/Overlays):** These utilize a "Glass" effect: `backdrop-filter: blur(12px)` with a semi-transparent fill (`rgba(30, 41, 59, 0.7)`).
- **Accents:** High-priority elements use an "Outer Glow" (soft bloom) using the Primary Indigo color at 20% opacity to simulate a light-emitting screen.

## Shapes

The shape language is "Soft-Technical." Corners are noticeably rounded to keep the UI approachable, but remain conservative to maximize screen real estate and maintain a professional "tool" feel.

- **Standard Elements:** 4px (0.25rem) radius for input fields and small buttons.
- **Cards/Containers:** 8px (0.5rem) radius to create a distinct framing for influencer profiles.
- **Progress Bars:** Fully rounded (pill) ends to contrast against the rectangular grid and highlight "fluid" metrics like authenticity scores.

## Components

- **Primary Buttons:** High-contrast Electric Indigo fills with white text. Hover states should include a subtle Indigo outer glow.
- **Authenticity Progress Bars:** Use a dual-track system. The background track is a dark neutral; the fill is a gradient from Teal to Electric Indigo. Include a "glow" head at the leading edge of the progress.
- **Creator Profile Cards:** A "Glass" header area for the avatar and name, with a dense grid of JetBrains Mono labels below showing stats (Engagement, Reach, CPM).
- **Data Visualization:** Charts should use thin 2px lines. Area charts should have a subtle vertical gradient from the stroke color to transparent.
- **Status Chips:** Small, monospaced labels with a low-opacity background tint (e.g., a "Matched" chip has a Teal background at 10% opacity with a solid Teal border).
- **Input Fields:** Dark backgrounds with a 1px Slate border that transitions to Indigo on focus. Use monospaced font for technical inputs like "Search Query" or "Budget Range."