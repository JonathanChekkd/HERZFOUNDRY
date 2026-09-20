---
name: HERZ FOUNDRY
description: A chromatic light stage for precise product reveals.
colors:
  optical-black: "#080808"
  raised-black: "#101011"
  plate-black: "#171719"
  mineral-white: "#f2f0eb"
  muted-mineral: "#aaa8a3"
  spectral-violet: "#7561ff"
  ember: "#f06835"
  soft-copy: "#c6c3bd"
typography:
  display:
    fontFamily: "Unbounded, sans-serif"
    fontSize: "clamp(3rem, 6.4vw, 6rem)"
    fontWeight: 400
    lineHeight: 0.94
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Unbounded, sans-serif"
    fontSize: "clamp(2.1rem, 5vw, 4.8rem)"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "-0.04em"
  title:
    fontFamily: "Unbounded, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
  body:
    fontFamily: "Manrope, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "Manrope, sans-serif"
    fontSize: "0.7rem"
    fontWeight: 400
    letterSpacing: "0.12em"
rounded:
  hard: "0"
  browser-thumb: "10px"
  circular-control: "50%"
spacing:
  page-gutter: "clamp(1.25rem, 4vw, 4.5rem)"
  section-space: "clamp(5rem, 10vw, 10rem)"
  control-x: "1.2rem"
  control-y: "0.75rem"
  plate-gap: "0.75rem"
components:
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.mineral-white}"
    typography: "{typography.label}"
    rounded: "{rounded.hard}"
    padding: "{spacing.control-y} {spacing.control-x}"
    height: "3rem"
  button-outline-hover:
    backgroundColor: "{colors.mineral-white}"
    textColor: "{colors.optical-black}"
  nav-call-to-action:
    backgroundColor: "transparent"
    textColor: "{colors.mineral-white}"
    typography: "{typography.label}"
    rounded: "{rounded.hard}"
    padding: "0.65rem 1rem"
  plate-label:
    backgroundColor: "rgba(8, 8, 8, 0.78)"
    textColor: "{colors.mineral-white}"
    typography: "{typography.label}"
    rounded: "{rounded.hard}"
    padding: "0.4rem 0.55rem"
  slider-handle:
    backgroundColor: "{colors.mineral-white}"
    textColor: "{colors.optical-black}"
    rounded: "{rounded.circular-control}"
    size: "2.5rem"
---

# Design System: HERZ FOUNDRY

## Overview

**Creative North Star: "Chromatic Light Stage"**

HERZ FOUNDRY behaves like a controlled optical set rather than a generic dark-agency card stack. Near-black surfaces make the supplied product imagery the brightest evidence; mineral-white type, thin measurement rules, and restrained spectral color create the sense of a precise studio instrument. Violet and ember are atmospheric light sources, never broad brand paint.

The system is cinematic but disciplined. Cropped portrait media, hard-edged controls, asymmetric image plates, and large stretches of darkness build tension without obscuring the work. The experience remains direct: the product is visible immediately, production rigor is demonstrated with real media, and contact actions are unmistakable.

**Key Characteristics:**

- Near-black optical surfaces with mineral-white typography.
- Restrained violet and ember light fields used for atmosphere and orientation.
- Hard rules, square controls, and cropped media plates instead of soft card stacks.
- Asymmetric editorial compositions that resolve into compact grids on small screens.
- Motion that clarifies active media and reveal state, with a complete reduced-motion path.

## Colors

The palette is primarily achromatic; its two chromatic accents behave as colored studio lights against optical black.

### Primary

- **Spectral Violet:** The principal cool light. Use it in low-opacity ambient fields, the browser scrollbar, and other sparse optical accents—not as a large opaque fill.

### Secondary

- **Ember:** The warm counter-light. Use it for process numerals, role labels, selection color, and restrained field gradients.

### Neutral

- **Optical Black:** The page canvas and deepest media-control surface.
- **Raised Black:** The subtle raised field used by contact and comparison surfaces.
- **Plate Black:** A slightly lighter dark for local optical planes when separation is needed.
- **Mineral White:** Primary text, hard rules in active states, controls, and the light motion-section canvas.
- **Muted Mineral:** Secondary copy, metadata, navigation, captions, and footer text.
- **Soft Copy:** Long-form introductory copy that needs more presence than muted metadata but less contrast than headings.

### Named Rules

**The Colored-Light Rule.** Violet and ember should read as light falling across a dark stage. Keep opaque accent areas rare and use restrained transparency for fields.

**The Mineral Contrast Rule.** Use mineral white against optical black for critical text and actions; use muted mineral only for genuinely secondary information.

## Typography

**Display Font:** Unbounded (with sans-serif fallback)  
**Body Font:** Manrope (with sans-serif fallback)  
**Label Font:** Manrope (with sans-serif fallback)

**Character:** Unbounded provides a wide, engineered silhouette for names, section statements, metrics, and workflow titles. Manrope keeps paragraphs and small interface labels precise and neutral, allowing the display face and product imagery to carry the identity.

### Hierarchy

- **Display** (400, fluid from `3rem` to `6rem`, `0.94` line-height): Hero identity; keep the measure compact at roughly nine characters.
- **Headline** (400, fluid from `2.1rem` to `4.8rem`, `1` line-height): Major section statements and contact proposition.
- **Title** (400, `1rem`): Workflow steps and comparison headings; use Unbounded without artificial boldness.
- **Body** (400, `1rem`, `1.65` line-height): Explanatory prose, generally constrained to `55–70ch`.
- **Label** (400, `0.7rem`, `0.12em` tracking, uppercase): Navigation, actions, media metadata, proof rails, and browser-like controls.

### Named Rules

**The Engineered Display Rule.** Unbounded is reserved for decisive names, numbers, and headings. Paragraphs and operational labels remain in Manrope.

**The Quiet Label Rule.** Labels gain hierarchy through uppercase and tracking, not bold weight.

## Layout

The page uses a centered shell capped at `112rem`, with a fluid page gutter and a fluid section interval. Thin horizontal rules establish measurement lines between title blocks, proof, metrics, services, clients, and the footer.

Desktop compositions are deliberately asymmetric. The first viewport divides the promise and the four-frame live stage into unequal columns; the primary stage plate spans all three rows while three smaller plates form a control strip. The still archive alternates a `1.2fr / 0.8fr` rhythm with staggered vertical offsets, the making section places comparisons beside a sticky workflow, and the profile gives more room to biography than portraiture.

At `980px` and below, the hero becomes one column, the proof rail leaves absolute positioning, the making section stacks, comparisons share two columns, and the client rail becomes two columns. At `680px` and below, primary navigation is hidden, all section heads stack, stills and reels remain two-up, comparisons and profile become single-column, metrics become a vertical ruled list, and the footer stacks. The live stage retains its major/minor plate relationship at a compact `30rem` height rather than collapsing into undifferentiated cards.

**The Asymmetric Plate Rule.** Media collections must keep a dominant frame and a supporting rhythm; equal cards are reserved for repeated reels or client marks where comparison is the job.

## Elevation & Depth

The system is flat by construction and uses no conventional box shadows. Depth comes from tonal layering, opacity changes, cropped imagery, active borders, saturation shifts, and large blurred violet/ember fields placed behind—not on top of—content. The active stage plate rises perceptually through full opacity, higher saturation, and a brighter rule rather than physical shadow.

### Named Rules

**The Optical Depth Rule.** Create depth with light, crop, tone, and focus. Do not introduce generic floating-card shadows.

## Shapes

The primary form language is hard and rectilinear: buttons, navigation actions, media plates, reels, logo cells, and section frames have square corners and one-pixel rules. Product media is clipped to tall `9 / 16` plates; the portrait uses `3 / 4`. Circular geometry is reserved for the comparison-slider handle, and rounded treatment is otherwise limited to the native browser scrollbar thumb.

**The Hard-Edge Rule.** Do not soften primary containers or controls. A circle should signal a draggable instrument, not a general decoration.

## Components

### Buttons

- **Shape:** Hard-edged outline with a one-pixel mineral-white stroke and a `3rem` minimum height.
- **Primary:** Transparent against the local surface with mineral-white text and compact horizontal padding.
- **Hover:** Invert to mineral white on optical black and move upward by `2px` over `250ms`.
- **Focus:** Use the global two-pixel mineral-white outline with a `5px` offset; never remove it.
- **Text link:** Underlined, tracked uppercase text with a generous `0.45rem` underline offset.

### Navigation

The header is transparent, absolutely positioned over the first viewport, and separated by a low-contrast bottom rule. The compact wordmark pairs the supplied mark with Unbounded. Links are muted, tracked, and uppercase; hover restores mineral white. The final link uses the hard outlined call-to-action treatment. Below `680px`, retain the brand and hide the compact navigation rather than compressing it into an illegible row.

### Product Plates and Live Stage

The four-frame stage is the signature component. One product plate dominates the left column; three supporting plates fill the right. Inactive plates sit at reduced opacity and saturation. Every `2.4s`, focus advances through the frames unless the visitor hovers, focuses a plate, or prefers reduced motion. The active frame reaches full opacity and saturation, gains a brighter border, and scales its image subtly. Plate labels sit directly on media in translucent optical-black fields.

### Motion Reels

Four `9 / 16` reels form a one-pixel-divided strip on mineral white. Controls sit inside each frame near the lower edge with a translucent black background and a light rule. The control toggles play and pause copy, exposes pressed state, and inverts on hover. On mobile the strip becomes a two-column grid.

### Comparison Sliders

Before/after frames layer two full-bleed images and expose the before image through a horizontal clip. A one-pixel mineral divider and circular `2.5rem` handle make the split legible. The native range input covers the entire frame with an east-west cursor and an accessible label; visual labels remain separate and non-interactive.

### Browser Surface

The browser surface participates in the visual system. The theme color is optical black; selected text uses ember on black. Scrollbars are thin, use a violet-to-ember thumb on raised black, and keep a narrow track-colored border. A skip link remains off-canvas until keyboard focus, then appears as a mineral-white slab at the upper left.

### Accessibility and Motion

Semantic landmarks, ordered headings, useful media alternative text, labeled controls, visible keyboard focus, touch-sized primary controls, and sufficient foreground contrast are required system behavior. Reduced motion disables smooth scrolling, collapses transition durations to effectively immediate, removes reveal transforms and desaturation, prevents stage auto-rotation, and bypasses observer-dependent reveals. Static content must remain complete and legible when fonts, scripting, video playback, or motion are unavailable.

## Do's and Don'ts

### Do:

- **Do** lead with real product media at full useful scale and retain its portrait crop.
- **Do** use rules, tone, saturation, and colored light to create hierarchy on dark surfaces.
- **Do** keep desktop compositions asymmetric while preserving the dominant/supporting relationship on mobile.
- **Do** preserve the mineral-white focus outline and the keyboard/touch behavior of every interactive media control.
- **Do** treat reduced motion as a complete static presentation, not merely shorter animation.
- **Do** style browser-level details—selection, scrollbar, theme color, and skip navigation—as part of the same optical world.

### Don't:

- **Don't** replace the stage with a generic equal-card grid or add rounded agency-style cards.
- **Don't** flood sections with opaque violet or ember; their restraint is what makes them feel luminous.
- **Don't** add conventional drop shadows, glass panels, glossy pills, or decorative gradients unrelated to stage lighting.
- **Don't** use Unbounded for long paragraphs or increase label hierarchy with heavy weight.
- **Don't** hide focus, rely on hover alone, autoplay video, or leave reveal content suppressed when motion is reduced.
