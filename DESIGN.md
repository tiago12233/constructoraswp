---
name: Modern Contractor
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#5a4136'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#8e7164'
  outline-variant: '#e2bfb0'
  surface-tint: '#a04100'
  primary: '#a04100'
  on-primary: '#ffffff'
  primary-container: '#ff6b00'
  on-primary-container: '#572000'
  inverse-primary: '#ffb693'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#5e5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#999999'
  on-tertiary-container: '#313131'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcc'
  primary-fixed-dim: '#ffb693'
  on-primary-fixed: '#351000'
  on-primary-fixed-variant: '#7a3000'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e3e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  stat-number:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.0'
spacing:
  base: 8px
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  grid-margin: 24px
  grid-gutter: 24px
  container-max: 1280px
---

## Brand & Style

This design system is built for the residential construction and remodeling sector, emphasizing reliability, momentum, and visible results. The personality is "Direct Professionalism"—it avoids the soft, ephemeral qualities of luxury design in favor of a grounded, high-contrast, and energetic aesthetic.

The visual style is **Modern/Corporate with a Brutalist edge**. It utilizes heavy typography, a rigid grid, and a purposeful lack of excessive ornamentation. The emotional response should be one of confidence and efficiency; the user should feel that the contractor is organized, fast-moving, and capable of handling complex physical builds. 

Key visual drivers include:
- **High-Contrast Verticality:** Deep charcoals paired with stark whites to create a rhythmic, editorial feel.
- **Data-Driven Confidence:** Large numerical indicators and bold labels that treat project stats as hero elements.
- **Material Honesty:** Sharp edges and structural lines that mirror the architectural nature of the work.

## Colors

The palette is engineered for maximum legibility and "call-to-action" urgency. 

- **Primary (Construction Orange):** Used exclusively for interactive elements, progress indicators, and critical brand moments. It provides a high-energy contrast against the neutral base.
- **Secondary (Deep Charcoal):** The foundation for all typography and structural boundaries. It replaces standard black to provide a more sophisticated, architectural depth.
- **Neutral (Concrete & White):** A range of cool grays used for background layering to define different project phases and content zones without cluttering the UI.

The system defaults to a **light mode** with high-contrast containers to maintain a "blueprint" clarity.

## Typography

The typography system uses a dual-sans approach to balance impact with utility.

- **Headlines (Montserrat):** Set in bold and extra-bold weights to command attention. Letter spacing is slightly tightened in larger sizes to create a "compact" and powerful feel.
- **Body (Inter):** Chosen for its exceptional legibility at all sizes, especially when describing technical project details or contract terms.
- **Labels (JetBrains Mono):** A monospaced font used for technical data, step numbers, and status tags to evoke the precision of architectural plans and engineering documents.

## Layout & Spacing

This design system utilizes a **12-column rigid grid** for desktop and a **4-column grid** for mobile. 

The layout philosophy is "Editorial Impact." Instead of uniform spacing, the system uses "high-contrast" white space—generous gaps between major sections (120px) contrasted with tight, structured spacing within component groups (8px, 16px).

- **Vertical Rhythm:** Content should flow in distinct blocks. Use "Full-Bleed" imagery for project showcases followed by "Inset" text blocks to create a dynamic visual cadence.
- **Alignment:** Strictly left-aligned typography. Center alignment should be avoided to maintain a direct, no-nonsense professional tone.

## Elevation & Depth

To maintain the "Modern Contractor" grounded aesthetic, the design system avoids soft shadows and "floaty" elements.

- **Flat Layering:** Depth is achieved through tonal shifts in background color (e.g., a light gray section placed against a white background).
- **Hard Strokes:** Use 1px or 2px solid borders in `#1A1A1A` or `#E0E0E0` to define card boundaries.
- **Zero Shadow Policy:** Shadows are replaced by high-contrast outlines or solid "block shadows" (a 4px solid offset of the primary color) if emphasis is required on a hover state.
- **Image Overlays:** Use semi-transparent charcoal overlays on photography to ensure white headlines remain legible while maintaining the "industrial" vibe.

## Shapes

The shape language is **strictly geometric and sharp**.

- **Corners:** 0px radius (Sharp) for all buttons, cards, and input fields. This communicates precision, structural integrity, and a "no-frills" attitude.
- **Icons:** Use thick-stroke (2pt) icons with square terminals. Avoid rounded or bubbly icon sets.
- **Dividers:** Use heavy 4px horizontal rules for section headers and thin 1px rules for list items.

## Components

### Buttons & CTAs
- **Primary:** Solid Primary Color background, White text, 0px border-radius. Text must be Uppercase (Label-caps).
- **Secondary:** Solid Secondary Color (Charcoal) background, White text.
- **Tertiary:** 2px solid Secondary Color border, no fill.

### Project Cards
- **Structure:** Aspect ratio 4:5 or 1:1 for "Before/After" impact.
- **Details:** Text is placed in a high-contrast white block below or slightly overlapping the image. Use a monospaced "Label-caps" for project location or type.

### Step Indicators (The Construction Timeline)
- Large, bold Montserrat numerals (e.g., "01", "02").
- Vertical orientation with a solid 2px line connecting phases.
- Active steps use the Primary Color; completed steps use Secondary.

### Testimonial Blocks
- Large "quote" marks are omitted in favor of a bold, heavy left border (4px) in the Primary Color.
- Author details include the project type and date in monospaced font.

### Input Fields
- Underline-only or 1px solid black border. 
- Labels stay visible above the field at all times.
- Focused state uses a 2px solid Primary Color border.

### Progress Bars
- Thick (8px) solid bars. No rounded ends.
- Background is a light gray; the fill is the Primary brand color.