---
name: Vintage Hoop Spirit
colors:
  surface: '#fdf9f0'
  surface-dim: '#dddad1'
  surface-bright: '#fdf9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ea'
  surface-container: '#f1eee5'
  surface-container-high: '#ece8df'
  surface-container-highest: '#e6e2d9'
  on-surface: '#1c1c17'
  on-surface-variant: '#4e4634'
  inverse-surface: '#31312b'
  inverse-on-surface: '#f4f0e7'
  outline: '#7f7662'
  outline-variant: '#d1c5ae'
  surface-tint: '#755b00'
  primary: '#755b00'
  on-primary: '#ffffff'
  primary-container: '#f5c842'
  on-primary-container: '#6c5400'
  inverse-primary: '#eec13c'
  secondary: '#a83900'
  on-secondary: '#ffffff'
  secondary-container: '#fc7138'
  on-secondary-container: '#5f1c00'
  tertiary: '#00687b'
  on-tertiary: '#ffffff'
  tertiary-container: '#74dbf8'
  on-tertiary-container: '#005f72'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe08f'
  primary-fixed-dim: '#eec13c'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#584400'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ffb59a'
  on-secondary-fixed: '#380d00'
  on-secondary-fixed-variant: '#812900'
  tertiary-fixed: '#afecff'
  tertiary-fixed-dim: '#6dd4f1'
  on-tertiary-fixed: '#001f27'
  on-tertiary-fixed-variant: '#004e5d'
  background: '#fdf9f0'
  on-background: '#1c1c17'
  surface-variant: '#e6e2d9'
typography:
  display:
    fontFamily: Lexend
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h1:
    fontFamily: Lexend
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  h2:
    fontFamily: Lexend
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-padding: 24px
  gutter: 16px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system captures the nostalgic energy of community basketball tournaments from the 70s and 80s, filtered through a modern, clean lens. The visual direction is **Retro-Modern High-Contrast**, leaning into the playfulness of rubber-hose cartoon aesthetics found in the reference logo. 

The personality is approachable, high-energy, and inclusive. By combining "burnt" and "golden" tones with soft pastel backgrounds, the UI feels weathered yet fresh—like a vintage jersey that’s never been worn. The goal is to evoke the excitement of a Saturday morning tournament: loud, rhythmic, and undeniably fun.

## Colors

The palette utilizes "sun-faded" versions of classic athletic colors. The off-white/cream (#FDF9F0) acts as the expansive canvas, replacing clinical whites to provide a warm, paper-like texture. 

- **Primary (Golden Yellow):** Used for key highlights and active states.
- **Secondary (Burnt Orange):** Used for calls to action and "game-time" energy.
- **Tertiary (Sky Blue):** Used for supportive accents and secondary interactive elements.
- **Pastel Variants:** These are used exclusively for large surface areas like horizontal cards, ensuring the bold primary colors pop when used on text or icons.

## Typography

This design system uses **Lexend** for headlines to leverage its athletic, highly readable, and geometric character. Its wide stance mimics vintage sports typography without the clunky nature of traditional block slabs. 

**Be Vietnam Pro** serves as the body typeface, providing a contemporary contrast that ensures long-form tournament rules, player bios, or bracket details remain legible. For an extra "retro" touch, labels and buttons use uppercase Lexend with slight letter-spacing to mimic embroidered jersey names.

## Layout & Spacing

The layout follows a **fluid grid** model with generous margins to allow the "bouncy" brand personality room to breathe. Horizontal spacing is driven by a 12-column grid, but the vertical rhythm is defined by a flexible stack model.

Horizontal card layouts are the signature structural element. These cards should span the full width of their container on mobile and 6-8 columns on desktop, emphasizing a "list-based" flow that mimics a game schedule or scoreboard.

## Elevation & Depth

To maintain the vintage/cartoon feel, this design system avoids realistic shadows. Depth is instead communicated through **Tonal Layers** and **Low-Contrast Outlines**.

- **Cards:** No shadows. Instead, use a 1px solid border colored slightly darker than the pastel background of the card itself (e.g., a Sky Blue card gets a darker blue stroke).
- **Interactive Elements:** Use a "hard shadow" technique for hover states—a solid 4px offset block of color (usually Burnt Orange) that appears behind buttons, giving them a sticker-like quality.
- **Modals:** Use a dark-tinted overlay (20% opacity of the Text-Main color) to dim the background, keeping the focus on the centered, high-contrast surface.

## Shapes

The shape language is dominated by **Rounded** and **Pill** geometries. 
- **Cards & Inputs:** Use a 1rem (16px) corner radius to feel soft and approachable.
- **Buttons & Chips:** Always use a fully pill-shaped (rounded-full) radius. This mimics the shape of a basketball court's key and free-throw circle.
- **Images:** Basketball player portraits or action shots should be housed in circles or heavily rounded rectangles to maintain the cartoon-inspired softness.

## Components

### Buttons & Navigation
Buttons are strictly pill-shaped. The primary action button uses the Burnt Orange background with off-white text. Secondary buttons use a thick 2px Burnt Orange border with no fill.

### Horizontal Cards
These are the workhorses of the design system. Used for player stats, game matchups, and news. They feature a soft pastel background (Yellow, Blue, or Orange) and a left-aligned thumbnail. Text is stacked to the right with clear hierarchical separation between the title (Lexend) and metadata.

### Chips & Tags
Used for "Live," "Final," or "Upcoming" status indicators. These are small pill shapes with high-contrast background colors and bold, all-caps Lexend labels.

### Input Fields
Inputs use the cream background with a slightly darker stroke. When focused, the stroke thickens and changes to Sky Blue, providing a clear but soft visual cue.

### Scoreboards
A specialized component that uses a darker, high-contrast background (the Text-Main color) with bright Primary Yellow typography to mimic old-school stadium light-up scoreboards.