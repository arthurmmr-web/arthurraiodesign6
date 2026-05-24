---
name: Dynamic Nostalgia
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1b1b1b'
  on-surface-variant: '#5e3f38'
  inverse-surface: '#303030'
  inverse-on-surface: '#f1f1f1'
  outline: '#926f66'
  outline-variant: '#e8bdb3'
  surface-tint: '#b42800'
  primary: '#b02700'
  on-primary: '#ffffff'
  primary-container: '#dc3300'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a2'
  secondary: '#006875'
  on-secondary: '#ffffff'
  secondary-container: '#00e3fd'
  on-secondary-container: '#00616d'
  tertiary: '#626200'
  on-tertiary: '#ffffff'
  tertiary-container: '#b1b100'
  on-tertiary-container: '#424200'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad2'
  primary-fixed-dim: '#ffb4a2'
  on-primary-fixed: '#3c0700'
  on-primary-fixed-variant: '#8a1d00'
  secondary-fixed: '#9cf0ff'
  secondary-fixed-dim: '#00daf3'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004f58'
  tertiary-fixed: '#eaea00'
  tertiary-fixed-dim: '#cdcd00'
  on-tertiary-fixed: '#1d1d00'
  on-tertiary-fixed-variant: '#494900'
  background: '#f9f9f9'
  on-background: '#1b1b1b'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 80px
    fontWeight: '800'
    lineHeight: '1.0'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.1'
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 32px
  margin-mobile: 24px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style
The design system bridges the gap between high-end professional curation and the rebellious, high-energy aesthetics of 90s television and comic culture. It targets a creative audience that values personality, grit, and distinctive storytelling without sacrificing functional clarity.

The visual language is a refined execution of **Neo-Brutalism**. It utilizes a "Paper and Ink" foundation—creamy off-white backgrounds and heavy black strokes—punctuated by a hyper-saturated, electric palette. The emotional response is intended to be nostalgic yet disruptive, evoking the tactile feel of a physical zine or a classic animation cel through the use of paper grain textures, halftone patterns, and exaggerated physical offsets.

## Colors
The palette is anchored by a high-contrast base of "Vintage Cream" (#FDFCF0) and "Deep Black" (#000000). This provides a sophisticated, readable backdrop that allows the accent colors to vibrate.

- **Primary Red:** Used for critical actions and primary brand moments.
- **Secondary Cyan:** Used for interactive elements and technical highlights.
- **Neon Yellow:** Reserved for warnings, "stickers," and background highlights to evoke a highlighter-ink feel.
- **Electric Blue & Teal:** Used for secondary categorization and link hover states.

Avoid gradients. Colors should be applied as flat, solid fills to maintain the "comic book" print aesthetic. Use halftone overlays (60% opacity) of the accent colors for secondary backgrounds.

## Typography
Typography is treated as a structural element. 

- **Headlines:** Use **Bricolage Grotesque** for its expressive, slightly irregular character that mimics hand-drawn comic lettering. Headlines should be tightly tracked and scaled aggressively.
- **Body:** **Public Sans** provides a neutral, highly legible contrast to the expressive headlines. It ensures that long-form project descriptions remain professional and easy to consume.
- **Labels:** **Space Grotesk** is used for metadata, buttons, and utility text, adding a subtle "tech" or "VHS" flavor to the smaller details.

Always ensure a high contrast ratio between text and background. For "Display" styles, apply a 2px black text stroke to enhance the comic-style punch.

## Layout & Spacing
The layout follows a **Fixed-Fluid hybrid grid**. While the main content container is capped for readability, elements often "break the grid" to create a dynamic, layered feel.

- **Grid:** A 12-column system with wide 32px gutters to prevent the heavy borders from feeling cluttered.
- **Composition:** Use asymmetrical placements. One column might be occupied by a floating "sticker" or a decorative comic star that overlaps the main content area.
- **Reflow:** On mobile, margins shrink to 24px and the 12-column grid collapses to a single column, but the thick borders and shadow offsets remain scaled at 100% to preserve the brand's weight.

## Elevation & Depth
Depth is not achieved through light and physics, but through **Graphic Offsets (Neo-Brutalism)**.

- **Hard Shadows:** All primary containers and buttons feature a solid black shadow offset (4px to 8px) at a 45-degree angle. These are never blurred.
- **Outlines:** Every interactive or distinct surface must have a solid 3px black border.
- **Layering:** Use a "stacking" metaphor. Lower-priority items sit flat on the cream background; higher-priority items "pop" forward with larger shadow offsets.
- **VHS Windows:** For specific UI features (like code snippets or contact forms), use a window-style header with a black bar and three "window control" circles in accent colors.

## Shapes
The shape language is "Bubbly-Brutalist." It combines the aggressive weight of thick strokes with the friendly, exaggerated curves of 90s animation.

- **Corners:** Use a large 1rem (16px) radius for standard cards and a 2rem (32px) or full pill-shape for buttons and chips.
- **Stickers:** Decorative elements like stars, speech bubbles, and jagged "explosions" should be used to draw attention to specific CTA areas.
- **Form Elements:** Input fields should maintain the same heavy border and rounded corners as the primary buttons.

## Components

- **Buttons:** Solid fill (Primary Red or Electric Blue) with a 3px black border and a 4px hard black shadow. On hover, the shadow disappears as the button "pushes" down into the page (Translate X: 2px, Y: 2px).
- **Cards:** Cream or white backgrounds with 3px black borders. Use halftone patterns on the "shadow" side of the card for added texture.
- **Chips/Tags:** Pill-shaped with a 2px border. Background colors should rotate through the secondary accent palette (Teal, Cyan, Yellow).
- **Input Fields:** Thick borders, chunky focus states (3px Primary Red border), and placeholder text in a lower-opacity black.
- **Stickers:** Non-functional decorative components that float at various rotations (-5 to +15 degrees). These contain "Work in Progress," "New Project," or "Hire Me" text in the Label font.
- **Lists:** Separated by 3px black horizontal rules. Each list item should have a hover state that fills the background with a vibrant accent color.