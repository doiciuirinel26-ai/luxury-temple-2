---
name: Vantis
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#37393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#0a0a0a'
  on-primary-container: '#7b7979'
  inverse-primary: '#5f5e5e'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#0a0a0a'
  on-tertiary-container: '#7a7979'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '400'
    lineHeight: 80px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '300'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 24px
---

## Brand & Style

This design system is engineered for the ultra-luxury sector, evoking an atmosphere of exclusivity, precision, and cinematic drama. The brand personality is authoritative yet restrained, favoring high-impact minimalism over decorative excess. It targets a high-net-worth audience that values discretion, heritage, and modern sophistication.

The visual style is a fusion of **Minimalism** and **High-Contrast Cinematic** aesthetics. It utilizes expansive negative space to create a "gallery" feel, where content is treated as art. Every interaction should feel intentional and weighted, reflecting the silent confidence of a premium brand.

## Colors

The palette is anchored in **Obsidian Black**, providing a deep, infinite canvas that allows content to recede or advance through light. **Metallic Gold (#D4AF37)** is used with extreme discipline as an accent color for key calls to action, interactive states, and premium signifiers. 

**Crisp White** is reserved strictly for high-readability typography and essential UI icons, ensuring a sharp, high-contrast finish. A secondary dark neutral (Rich Charcoal) is used for subtle container differentiation without breaking the monochromatic immersion.

## Typography

Typography in this design system follows a classic editorial hierarchy. **Playfair Display** provides a sophisticated, transitional serif voice for all headlines, utilizing generous tracking in lower sizes and tight tracking for large display headers.

**Inter** provides a functional, neutral counterpoint for body copy and UI elements. By utilizing lighter weights (300) for large body text, we maintain a sense of airiness. Small labels and utility text must be rendered in uppercase with wide letter spacing to mimic high-end architectural signage.

## Layout & Spacing

The layout philosophy is based on a **Fixed Grid** with hyper-extended margins. This creates a centered "stage" for the content, emphasizing focus and exclusivity. 

We employ a 12-column grid for desktop with wide 32px gutters to prevent information density. For mobile, we shift to a 4-column grid with a significant reduction in font scale but an increase in vertical breathing room. The spacing rhythm is intentionally "loose," favoring white space (or in this case, "black space") to signal luxury. Elements should never feel crowded; if in doubt, double the padding.

## Elevation & Depth

In a dark, high-contrast environment, traditional shadows are replaced by **Light and Glow**. 

Depth is conveyed through:
1.  **Tonal Layering:** Surfaces move from Obsidian (#0A0A0A) to Charcoal (#1A1A1A) to indicate elevation.
2.  **Gold Outlines:** A 1px subtle gold border acts as a "rim light" for elevated cards or modals.
3.  **Gold Glow:** Interactive elements or active states utilize a soft, diffused outer glow (bloom effect) using the secondary gold color with low opacity (10-15%).
4.  **Glassmorphism:** Overlays (like navigation bars) use a heavy background blur (20px+) with 80% opacity to maintain the sense of depth without obscuring the cinematic background imagery.

## Shapes

The shape language is strictly **Sharp (0px)**. Every element—from buttons and input fields to large image containers—uses 90-degree angles. This geometric rigidity conveys a sense of architectural permanence, precision, and bespoke tailoring. The only exception to this rule is the use of circular icons or specific brand-related circular motifs, which serve as soft focal points against the hard-edged layout.

## Components

### Buttons
Primary buttons are solid Obsidian with a 1px Gold border and White text. On hover, the border glow intensifies. Secondary buttons are text-only with a wide-tracked uppercase label and a gold underline that expands from the center.

### Input Fields
Inputs are minimal: a single 1px white bottom border that turns gold upon focus. Placeholders are rendered in a muted grey with high letter spacing.

### Cards
Cards use a 1px border in Charcoal (#1A1A1A). When hovered, the border transitions to Gold and a very subtle inner gold glow appears at the top edge. Images within cards should have a slight desaturation filter applied, returning to full color on interaction.

### Navigation
The navigation bar is a fixed, frosted obsidian element at the top of the viewport. Links are Playfair Display (Small) or Inter (Caps), depending on the hierarchy, with high contrast transitions.

### Progress & Status
Selection states (checkboxes, radios) are custom-designed as sharp squares. Active states are filled with Gold, while inactive states remain Obsidian with a 1px White border.