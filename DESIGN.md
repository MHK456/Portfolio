---
name: Cyber-Tech Pro
colors:
  surface: '#0e1417'
  surface-dim: '#0e1417'
  surface-bright: '#333a3d'
  surface-container-lowest: '#090f12'
  surface-container-low: '#161d1f'
  surface-container: '#1a2123'
  surface-container-high: '#242b2e'
  surface-container-highest: '#2f3639'
  on-surface: '#dde3e7'
  on-surface-variant: '#bbc9cf'
  inverse-surface: '#dde3e7'
  inverse-on-surface: '#2b3134'
  outline: '#859399'
  outline-variant: '#3c494e'
  surface-tint: '#4cd6ff'
  primary: '#a4e6ff'
  on-primary: '#003543'
  primary-container: '#00d1ff'
  on-primary-container: '#00566a'
  inverse-primary: '#00677f'
  secondary: '#d3fbff'
  on-secondary: '#00363a'
  secondary-container: '#00eefc'
  on-secondary-container: '#00686f'
  tertiary: '#ffd59c'
  on-tertiary: '#442b00'
  tertiary-container: '#feb127'
  on-tertiary-container: '#6b4700'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b7eaff'
  primary-fixed-dim: '#4cd6ff'
  on-primary-fixed: '#001f28'
  on-primary-fixed-variant: '#004e60'
  secondary-fixed: '#7df4ff'
  secondary-fixed-dim: '#00dbe9'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f54'
  tertiary-fixed: '#ffddb1'
  tertiary-fixed-dim: '#ffba49'
  on-tertiary-fixed: '#291800'
  on-tertiary-fixed-variant: '#624000'
  background: '#0e1417'
  on-background: '#dde3e7'
  surface-variant: '#2f3639'
typography:
  h1:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  mono-label:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.1em
  code-snippet:
    fontFamily: monospace
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
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
  gutter: 24px
  margin: 32px
---

## Brand & Style
This design system is built for the high-stakes environment of cybersecurity and advanced web development. The personality is authoritative, precise, and technologically sophisticated. It evokes the feeling of a high-end command center—where complex data is distilled into actionable insights through a refined, translucent interface.

The aesthetic blends **Minimalism** with **Glassmorphism**. We prioritize clarity and structural integrity, using transparency and light-refraction effects to simulate layers of digital protection. Every element should feel like a piece of a calibrated machine: functional, high-performance, and secure.

## Colors
The palette is rooted in the depth of midnight operations. We use **Deep Charcoal (#121212)** for the primary canvas to minimize eye strain and maximize the pop of technical data. **Slate (#1E293B)** is utilized for elevated surfaces and container backgrounds, providing a subtle blue-grey shift that feels more sophisticated than pure black.

Accents are strictly limited to **Electric Blue (#00D1FF)** and **Cyan (#00F0FF)**. These colors serve as functional indicators: Electric Blue for primary actions and system states, and Cyan for highlights and data visualizations. Semantic colors for security (e.g., critical alerts) should lean towards high-saturation ambers or reds, but always framed within the dark slate containers.

## Typography
The typography strategy contrasts human-readable clarity with machine-like precision. **Space Grotesk** is used for all headlines and technical labels to give the UI a futuristic, geometric edge. **Inter** handles the heavy lifting for body copy and documentation, ensuring that complex technical descriptions remain highly legible across all screen densities.

To emphasize the developer-centric nature of the brand, all labels and metadata use an uppercase "Mono-Label" style with increased letter spacing, mimicking terminal headers.

## Layout & Spacing
The layout philosophy is based on a **Fixed Grid** model for desktop and a **Fluid Grid** for mobile. We utilize a 12-column system with generous 24px gutters to allow technical data to breathe. 

The rhythm follows a 4px base unit. Components should be spaced using 8px (XS) or 16px (SM) increments internally, while page sections are separated by 64px (XL) to maintain a premium, sparse feel. Grid lines may occasionally be rendered as subtle 1px "ghost lines" (10% opacity white) to reinforce the technical, blueprint-like aesthetic of the developer environment.

## Elevation & Depth
Elevation in this design system is achieved through **Glassmorphism** and **Tonal Layering** rather than traditional drop shadows. 

1.  **Backgrounds:** The lowest layer is the solid #121212.
2.  **Panels:** Floating containers use a semi-transparent #1E293B with a `backdrop-filter: blur(20px)`.
3.  **Strokes:** Each elevated panel is defined by a 1px inner border. Use a linear gradient stroke (from top-left to bottom-right) using `rgba(255, 255, 255, 0.15)` to `rgba(255, 255, 255, 0.05)`.
4.  **Glows:** Active elements (like selected cards or focused inputs) should emit a subtle outer glow using the primary #00D1FF color with a 15px blur at 20% opacity.

## Shapes
We use a **Soft (1)** roundedness approach. This allows for a modern feel without losing the "hard" edge required for a professional security product. Standard UI elements (Buttons, Cards, Inputs) should use a 4px (0.25rem) radius. Larger sections or "hero" containers can scale up to 8px (0.5rem). Elements should never be fully rounded (pill-shaped) unless they are secondary tags or status indicators.

## Components

### Buttons
- **Primary:** Solid #00D1FF background with #121212 text for maximum contrast. No border, but a subtle 00D1FF glow on hover.
- **Secondary:** Ghost style. 1px border of #00D1FF, text in #00D1FF, and a 5% opacity blue fill on hover.

### Cards
- **Technical Cards:** Slate (#1E293B) background at 80% opacity. 1px stroke. Headers inside cards should use the `mono-label` typography style with a 1px bottom border to separate the header from the content.

### Inputs & Form Fields
- **Fields:** Dark background (#121212), 1px slate border. Upon focus, the border transitions to Electric Blue with a subtle outer glow.
- **Labels:** Always use `mono-label` font style above the field.

### Status Indicators
- **Security Pulse:** Small circular indicators for system status. Use "Cyan" for active/secure and a high-visibility "Warning Yellow" for threats. Pulse animations should be slow and linear.

### Technical Data Grids
- Lists of vulnerabilities or code snippets should use alternating row highlights (zebra striping) with only 2% opacity difference to maintain a clean, high-end look. Monospaced font is mandatory for data strings.