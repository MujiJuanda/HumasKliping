---
name: Nusantara Humas System
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d4'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ed'
  surface-container: '#f5ece7'
  surface-container-high: '#efe6e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#504443'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#827472'
  outline-variant: '#d4c3c1'
  surface-tint: '#795553'
  primary: '#321716'
  on-primary: '#ffffff'
  primary-container: '#4a2c2a'
  on-primary-container: '#bd928f'
  inverse-primary: '#eabcb8'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#1e1f1d'
  on-tertiary: '#ffffff'
  tertiary-container: '#343432'
  on-tertiary-container: '#9d9c99'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#eabcb8'
  on-primary-fixed: '#2e1413'
  on-primary-fixed-variant: '#5f3e3c'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e4e2de'
  tertiary-fixed-dim: '#c8c6c3'
  on-tertiary-fixed: '#1b1c1a'
  on-tertiary-fixed-variant: '#474744'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-tablet: 32px
  margin-mobile: 16px
---

## Brand & Style

The visual identity of this design system centers on **Modern Indonesian Heritage**. It balances the authoritative nature of government and academia with the warmth of traditional Indonesian craftsmanship. The goal is to evoke a sense of prestige, "Wibawa" (authority/charisma), and cultural pride without feeling dated.

The design style is a hybrid of **Minimalism** and **Tactile Modernism**. It utilizes expansive white space to ensure clarity for complex PR tasks, while integrating subtle, high-fidelity textures inspired by Indonesian artistry—specifically mahogany wood grains and geometric "Mega Mendung" or "Kawung" patterns reduced to ultra-fine, low-opacity line work. This creates a digital-first environment that feels anchored in tradition.

## Colors

The palette is derived from natural and noble materials found across the Indonesian archipelago.

- **Primary (Deep Mahogany):** A rich, dark brown used for primary navigation, headers, and key branding elements. It represents stability and the sturdy foundations of university and government institutions.
- **Secondary (Heritage Gold):** A refined, non-metallic gold used for calls to action, active states, and decorative accents. It symbolizes excellence and the "Golden Generation."
- **Background (Off-White/Parchment):** A soft `tertiary` white that reduces eye strain compared to pure white, mimicking high-quality textured paper or ivory.
- **Neutrals:** Deep charcoals instead of pure blacks are used for typography to maintain a sophisticated, organic feel.

## Typography

This design system uses a high-contrast typographic pairing to reinforce the "Professional-meets-Heritage" theme.

- **Headings:** **EB Garamond** provides a literary, academic, and authoritative voice. Its classical proportions are used for all major page titles and section headers.
- **Body & Interface:** **Public Sans** is chosen for its origins in government design systems. It is highly legible, neutral, and ensures that data-heavy PR management screens remain functional and accessible.
- **Hierarchy Note:** Labels and small metadata should use Public Sans with increased letter spacing and semi-bold weights to maintain a clean, organized "official document" aesthetic.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain the "prestigious" feel of a curated dashboard, transitioning to a fluid model for mobile devices. 

- **Grid:** A 12-column grid is used for desktop (1280px max-width).
- **Rhythm:** An 8px linear scale governs all padding and margins. 
- **White Space:** Generous margins (`margin-desktop`) are intentional, ensuring the UI feels "premium" rather than crowded.
- **Batik Overlays:** The background of the main scaffold should feature a subtle, fixed geometric Batik pattern (e.g., *Parang* or *Kawung*) in a very light tint (2% opacity of the Primary color) to add depth without distracting from the data.

## Elevation & Depth

To maintain a "digital-first" professional look, this design system avoids heavy shadows in favor of **Tonal Layers** and **Refined Outlines**.

- **Surface Tiers:** Backgrounds use the off-white `tertiary` color. Cards and containers use pure white to pop forward.
- **Depth:** Instead of high-blur shadows, use "Soft-Plinth" elevations—1px borders in a light mahogany tint (#4A2C2A at 10% opacity) combined with a very subtle 4px blur shadow.
- **Interactions:** Hover states on primary elements should utilize a slight "lift" (2px translation) and a Heritage Gold glow rather than a standard grey shadow.

## Shapes

The shape language is **Soft** and disciplined. 

- **Corner Radii:** Most containers and buttons use a `0.25rem` (4px) radius. This "semi-sharp" look mimics the precision of traditional wood carving and formal architectural structures. 
- **Decorative Elements:** Use the "Heritage Gold" as a vertical accent line (2px width) on the left side of active list items or card headers to draw the eye, echoing the decorative pillars of a *Pendopo*.

## Components

- **Buttons:** Primary buttons use the Deep Mahogany background with White text. Secondary buttons use a Gold outline with Gold text. High-action buttons should feature a subtle 1px "inner-glow" to simulate a polished wood finish.
- **Input Fields:** Use "Material-style" floating labels but with a refined Public Sans font. Borders are only on the bottom by default, turning into a full Heritage Gold frame upon focus.
- **Cards:** White backgrounds with a top-border accent (2px) in Mahogany or Gold depending on priority. 
- **Status Chips:** Instead of bright neon colors, use muted "Earth Tones"—Sage Green for success, Terracotta for warnings, and Slate for neutral.
- **Navigation:** The sidebar should be high-contrast (Mahogany background, Gold icons/active states) to act as the "anchor" of the application.
- **PR Specifics:** "Press Release" cards should feature a dedicated "Official Seal" watermark area in the background to reinforce the institutional nature of the content.