---
name: Botanical Essence
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#424843'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#727973'
  outline-variant: '#c1c8c1'
  surface-tint: '#436651'
  primary: '#163826'
  on-primary: '#ffffff'
  primary-container: '#2d4f3c'
  on-primary-container: '#9ac0a7'
  inverse-primary: '#a9cfb7'
  secondary: '#964824'
  on-secondary: '#ffffff'
  secondary-container: '#fd9a6f'
  on-secondary-container: '#76300d'
  tertiary: '#20362d'
  on-tertiary: '#ffffff'
  tertiary-container: '#364d42'
  on-tertiary-container: '#a4bdaf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c5ecd2'
  primary-fixed-dim: '#a9cfb7'
  on-primary-fixed: '#002112'
  on-primary-fixed-variant: '#2c4e3b'
  secondary-fixed: '#ffdbcd'
  secondary-fixed-dim: '#ffb597'
  on-secondary-fixed: '#360f00'
  on-secondary-fixed-variant: '#77320e'
  tertiary-fixed: '#cee9da'
  tertiary-fixed-dim: '#b3ccbf'
  on-tertiary-fixed: '#092017'
  on-tertiary-fixed-variant: '#354c41'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding-mobile: 20px
  container-padding-desktop: 40px
  gutter: 24px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is rooted in the concept of "Nurtured Growth." It aims to evoke a sense of calm, clarity, and organic connection, transforming the technical task of plant maintenance into a mindful ritual. The target audience includes urban dwellers and gardening enthusiasts who seek an escape from high-friction digital interfaces.

The visual style is **Contemporary Organic Minimalism**. It blends the structural reliability of modern SaaS interfaces with the soft, tactile qualities of nature. By utilizing generous whitespace and a "living" color palette, the system ensures that the plant photography—the true hero of the application—remains the focal point. Expect a serene, high-end editorial feel that remains highly functional and accessible.

## Colors

The palette is derived from the natural lifecycle of a plant and its environment.

- **Primary (Forest):** A deep, grounding green used for core navigation, primary actions, and high-level headings. It represents stability and life.
- **Secondary (Terracotta):** A warm, earthy orange-red used sparingly for accents, notifications, or call-to-actions that require warmth without appearing aggressive.
- **Tertiary (Sage):** A soft, muted green used for secondary UI elements, backgrounds, and subtle highlights.
- **Neutral (Cream/Clay):** The primary background color is a soft cream (`#F9F7F2`) rather than pure white, reducing eye strain and providing a paper-like, organic texture. Grays are warm-toned to maintain a cohesive, "indoor" atmosphere.

## Typography

The typographic pairing balances heritage and modern utility. 

**Noto Serif** provides the editorial, botanical authority required for headings and plant names. It should be used for all "display" moments to instill a sense of timelessness. 

**Be Vietnam Pro** is used for all functional UI, body text, and labels. Its friendly, contemporary terminals and open counters ensure legibility in data-dense areas like care schedules and moisture levels. Use medium and semi-bold weights for labels to maintain hierarchy against the expressive serif headlines.

## Layout & Spacing

This design system utilizes a **fluid grid** with an emphasis on "breathing room." 

- **Mobile:** A 4-column grid with 20px outside margins. 
- **Desktop:** A 12-column grid centered in a max-width container of 1280px. 
- **Spacing Logic:** All spacing follows an 8px base unit. Vertical rhythm is critical; use `stack-lg` (32px) between major sections to prevent the UI from feeling cluttered.

Incorporate asymmetric layouts for gallery sections to mimic the natural, irregular growth of plants, while keeping utility screens (like "My Collection") strictly aligned to the grid for efficiency.

## Elevation & Depth

The system avoids heavy shadows in favor of **Tonal Layering** and **Soft Depth**. 

- **Surfaces:** Use subtle shifts in background color (e.g., a slightly darker Clay tone against a Cream background) to define containers.
- **Shadows:** When necessary for floating elements like FABs or Modals, use "Ambient Moss" shadows—very soft, highly diffused (blur 20px+), and tinted with a hint of the primary green (`rgba(45, 79, 60, 0.08)`).
- **Glassmorphism:** Use for overlays and navigation bars. A light background blur (12px) with a semi-transparent cream fill allows plant colors to peek through as the user scrolls, creating a sense of immersion.

## Shapes

The shape language is **Softly Organic**. 

Standard components use a 0.5rem (8px) radius to maintain a modern feel, but primary "Plant Cards" and "Hero Images" should use `rounded-xl` (1.5rem / 24px) to mimic the curves of leaves and terracotta pots. 

Buttons are fully rounded (pill-shaped) to appear approachable and tactile. Avoid sharp 90-degree corners entirely to maintain the "calming" brand promise.

## Components

- **Buttons:** Primary buttons are pill-shaped, filled with Forest Green, and use white text. Secondary buttons use a Sage outline with Sage text.
- **Care Chips:** Small, rounded indicators for "Water," "Sunlight," and "Mist." Use subtle tonal backgrounds (e.g., light blue for water, soft yellow for sun) rather than high-contrast alerts.
- **Plant Cards:** Feature large, high-quality imagery with a `rounded-xl` corner radius. The plant name is set in Noto Serif, while care status is set in Be Vietnam Pro labels.
- **Input Fields:** Use a "soft-filled" style rather than a border-only style. A light Clay (`#EFEDE8`) background with a 0.5rem corner radius and a subtle 1px Forest Green border on focus.
- **Progress Bars (Moisture):** Use thick, rounded tracks in light Sage with the progress indicator in a rich Emerald. 
- **Icons:** Use 2pt stroke weight, "Open-path" icons with rounded terminals. Icons should be minimalist and organic, avoiding sharp points.