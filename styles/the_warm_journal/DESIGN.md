---
name: The Warm Journal
colors:
  surface: '#fbf9f1'
  surface-dim: '#dcdad2'
  surface-bright: '#fbf9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f4ec'
  surface-container: '#f0eee6'
  surface-container-high: '#eae8e0'
  surface-container-highest: '#e4e3db'
  on-surface: '#1b1c17'
  on-surface-variant: '#4e453e'
  inverse-surface: '#30312c'
  inverse-on-surface: '#f3f1e9'
  outline: '#80756d'
  outline-variant: '#d2c4bb'
  surface-tint: '#705a49'
  primary: '#322214'
  on-primary: '#ffffff'
  primary-container: '#4a3728'
  on-primary-container: '#bba08c'
  inverse-primary: '#dec1ac'
  secondary: '#5a6151'
  on-secondary: '#ffffff'
  secondary-container: '#dbe2cf'
  on-secondary-container: '#5e6556'
  tertiary: '#3e1c12'
  on-tertiary: '#ffffff'
  tertiary-container: '#573126'
  on-tertiary-container: '#cf998a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fbddc7'
  primary-fixed-dim: '#dec1ac'
  on-primary-fixed: '#28180b'
  on-primary-fixed-variant: '#574333'
  secondary-fixed: '#dee5d2'
  secondary-fixed-dim: '#c2c9b6'
  on-secondary-fixed: '#171d12'
  on-secondary-fixed-variant: '#42493b'
  tertiary-fixed: '#ffdbd1'
  tertiary-fixed-dim: '#f3b9aa'
  on-tertiary-fixed: '#31120a'
  on-tertiary-fixed-variant: '#653c31'
  background: '#fbf9f1'
  on-background: '#1b1c17'
  surface-variant: '#e4e3db'
typography:
  display:
    fontFamily: Literata
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h1:
    fontFamily: Literata
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.2'
  h2:
    fontFamily: Literata
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: Literata
    fontSize: 22px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Quicksand
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: Quicksand
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label:
    fontFamily: Quicksand
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
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
  container-max: 1100px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style

This design system is built to feel like a cherished physical object—a premium digital notebook that captures the essence of a personal portfolio. The brand personality is quiet, intentional, and human-centric, moving away from "tech-first" aesthetics toward a "life-first" philosophy.

The design style is **Tactile / Organic**, blending elements of modern minimalism with the warmth of physical stationery. It avoids the clinical coldness of standard web interfaces by utilizing soft shadows, organic shapes, and subtle textures. The emotional response should be one of calm focus and intimacy, inviting the visitor to linger and read as they would with a personal letter or a well-kept journal.

## Colors

The palette is derived from natural materials—paper, ink, clay, and foliage. 

- **Background:** The Soft Cream (#FFFDF5) serves as the "paper" stock, reducing eye strain and providing a warmer base than pure white.
- **Primary:** Warm Earthy Brown (#4A3728) replaces standard black for all text and iconography, providing high legibility without the harshness of high-contrast dark tones.
- **Secondary:** Sage Green (#D1D8C5) is used for primary actions and highlights, evoking a sense of growth and calm.
- **Tertiary:** Muted Terracotta (#E0A899) provides a gentle secondary accent for interactive elements or categories.
- **Surface:** Paper White (#FFFFFF) is reserved for elevated "cards" or "notepaper" sections to create a subtle hierarchy against the cream background.

## Typography

Typography in this design system emphasizes readability and a "bookish" feel. 

**Literata** is chosen for headlines. Its rounded serif terminals and varying stroke widths give it a mechanical yet literary quality that feels like high-end publishing. It should be used with slightly tighter tracking for larger displays to maintain a cohesive "ink-on-page" look.

**Quicksand** is used for body text and UI labels. Its rounded ends perfectly complement the organic shape language of the design system. Generous line heights (1.6+) are mandatory to ensure a breezy, unhurried reading experience.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for the main content to mimic the constraints of a physical journal page. Content should be centered with generous margins to create a sense of focus and importance.

The spacing rhythm is based on an 8px scale, but utilized loosely to allow for "breathable" white space. Layouts should favor vertical stacking with significant gaps between sections (64px+) to prevent the interface from feeling cluttered or "app-like." Use asymmetrical layouts for image galleries to reinforce the organic, scrapbooked feel.

## Elevation & Depth

This design system avoids heavy shadows and floating elements. Depth is communicated through **Tonal Layers** and extremely soft, diffused shadows.

- **Level 0 (Base):** Soft Cream (#FFFDF5) background. May include a subtle, low-opacity paper grain texture overlay.
- **Level 1 (Surface):** Paper White (#FFFFFF) surfaces. These use a 1px border of the Primary color at 5% opacity to define edges without creating harsh lines.
- **Shadows:** When used, shadows should be tinted with the Primary Earthy Brown rather than black. For example: `0 10px 30px -5px rgba(74, 55, 40, 0.08)`. This keeps the "warmth" consistent even in the shadows.

## Shapes

The shape language is defined by **Rounded (Level 2)** settings but pushed toward even softer extremes for large components. 

- Standard components (Inputs, Chips) use a **12px to 16px** radius.
- Container cards and sections use a **24px to 32px** radius.
- Avoid perfectly straight lines where possible; use "squircle" masks for images to maintain the organic, hand-trimmed feel of a personal notebook.

## Components

### Buttons
Primary buttons use the Sage Green background with Earthy Brown text. They should have a soft, pill-like appearance. On hover, the button should lift slightly (subtle shadow increase) rather than changing color dramatically.

### Cards
Cards are the "pages" of the journal. They should be Paper White with large corner radii (24px). To add a premium touch, a card might feature a subtle 1px "deckled edge" effect or a faint horizontal rule line (10% opacity Brown) to mimic notebook paper.

### Input Fields
Inputs should be Soft Cream (slightly darker than the white card they sit on) with a 1px Sage Green border when focused. The cursor should be the Primary Earthy Brown.

### Icons
Use hand-drawn style or "monoline" icons with rounded caps. Avoid sharp-edged icon sets. Icons should always be the Primary Earthy Brown.

### Chips & Tags
Used for categories or skills, these should use the Muted Terracotta or Sage Green at low opacity (15%) with full-opacity text of the same color to ensure they feel like soft "highlighted" text.

### Dividers
Avoid solid 100% width lines. Use a centered, 40px wide horizontal rule or a "three-dot" flourish to separate sections, mimicking literary breaks.