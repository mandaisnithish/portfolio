---
name: Nithish Kaliannan Ananth · Portfolio
description: One AI accelerator chip, explored in 3D; each floorplan block is a section of the portfolio.
colors:
  graphite: "#121314"
  graphite-raised: "#18191b"
  graphite-sunk: "#0d0e0f"
  panel: "rgba(18,19,20,.95)"
  hairline: "#2c2f33"
  hairline-strong: "#43474d"
  text: "#ecebe8"
  text-2: "#b8b9bb"
  text-3: "#8e9196"
  copper: "#d98c55"
  copper-hi: "#e8a678"
  copper-ink: "#121314"
  data-blue: "#7aa6dc"
  data-orange: "#f08046"
  data-mid: "#2b2f35"
  si-die: "#262b31"
  si-cpu: "#3a4250"
  si-sram: "#33404e"
  si-npu: "#2f3946"
  si-cache: "#3a4250"
  si-rom: "#353c46"
  si-pad: "#6b6f75"
  si-lid: "#8b8f95"
  si-substrate: "#1c1d1f"
typography:
  display:
    fontFamily: "'Schibsted Grotesk', 'Atkinson Hyperlegible Next', system-ui, sans-serif"
    fontSize: "clamp(2.6rem, 5.2vw, 4.75rem)"
    fontWeight: 800
    lineHeight: 0.98
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "'Schibsted Grotesk', 'Atkinson Hyperlegible Next', system-ui, sans-serif"
    fontSize: "clamp(1.75rem, 3vw, 2.5rem)"
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: "-0.03em"
  title:
    fontFamily: "'Schibsted Grotesk', 'Atkinson Hyperlegible Next', system-ui, sans-serif"
    fontSize: "1.15rem"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.012em"
  reading:
    fontFamily: "'Schibsted Grotesk', 'Atkinson Hyperlegible Next', system-ui, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.02em"
    fontFeature: "'tnum' 1"
  body:
    fontFamily: "'Atkinson Hyperlegible Next', 'Atkinson Hyperlegible', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
  body-small:
    fontFamily: "'Atkinson Hyperlegible Next', 'Atkinson Hyperlegible', system-ui, -apple-system, 'Segoe UI', sans-serif"
    fontSize: "0.95rem"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "'Martian Mono', ui-monospace, SFMono-Regular, Menlo, monospace"
    fontSize: "0.75rem"
    fontWeight: 400
    lineHeight: 1.5
rounded:
  none: "0px"
spacing:
  hairline: "1px"
  xs: "0.4rem"
  sm: "0.75rem"
  md: "1rem"
  lg: "1.5rem"
  xl: "2.5rem"
  panel: "clamp(1.25rem, 2.6vw, 2.25rem)"
  bar-height: "3.5rem"
  shell: "min(1280px, 100% - 2.5rem)"
  column: "min(640px, 46vw)"
components:
  button-copper:
    backgroundColor: "{colors.copper}"
    textColor: "{colors.copper-ink}"
    rounded: "{rounded.none}"
    padding: "0.7rem 1.35rem"
    height: "2.875rem"
  button-copper-hover:
    backgroundColor: "{colors.copper-hi}"
    textColor: "{colors.copper-ink}"
  button-line:
    backgroundColor: "{colors.graphite}"
    textColor: "{colors.text}"
    rounded: "{rounded.none}"
    padding: "0.7rem 1.35rem"
    height: "2.875rem"
  button-line-hover:
    backgroundColor: "{colors.graphite}"
    textColor: "{colors.copper}"
  bond-pad:
    textColor: "{colors.text-2}"
    typography: "{typography.label}"
    padding: "0 0.7rem"
    height: "2.75rem"
  bond-pad-active:
    textColor: "{colors.text}"
    typography: "{typography.label}"
  test-pad:
    backgroundColor: "{colors.graphite-raised}"
    textColor: "{colors.text}"
    typography: "{typography.reading}"
    rounded: "{rounded.none}"
    padding: "0.85rem 1rem"
  panel:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.text}"
    rounded: "{rounded.none}"
    padding: "{spacing.panel}"
    width: "{spacing.column}"
  chart-frame:
    backgroundColor: "{colors.graphite-sunk}"
    rounded: "{rounded.none}"
    height: "190px"
  metric-tag:
    textColor: "{colors.text}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0.3rem 0.6rem"
  sub-panel:
    backgroundColor: "{colors.graphite-raised}"
    rounded: "{rounded.none}"
    padding: "1.15rem"
  chip-tooltip:
    backgroundColor: "{colors.graphite-sunk}"
    textColor: "{colors.text}"
    typography: "{typography.label}"
    padding: "0.3rem 0.55rem"
---

# Design System: Nithish Kaliannan Ananth · Portfolio

## Overview

**Creative North Star: "The Accelerator Floorplan"**

The page is a single AI accelerator chip seen in 3D on a graphite ground. On arrival the package lid lifts away, and the camera settles over the die. Scrolling flies the camera from block to block. Each floorplan block (CPU core, SRAM, NPU array, cache, ROM, I/O ring) stands for one section of the portfolio, and the reading happens on solid graphite panels set beside the scene. The tone is precise and instrument-like: square edges, hairlines, mono readings, one copper highlight. It is never decorative glow.

Density is calm. One reading column carries all the prose. The chip holds the remaining width as a fixed scene, and it never sits behind text that the visitor has to read. The chip is a metaphor for how the work is organised. It is not a claim about the work, so every value it displays is a figure already stated in the text.

This world replaces an earlier dark-and-gold portfolio. Gold, glow effects and the flat stack of cards over a hero grid have all been rejected.

**Key Characteristics:**
- Graphite black ground, blue-grey silicon blocks in distinct metal tones, copper interconnect; no gold.
- Square corners everywhere; 1px hairlines carry structure instead of shadows.
- Mono for labels, readings and chart text; a highly legible sans for prose; a heavy grotesk for headings.
- One copper highlight marks the active block, the current bond pad and the primary action.
- One scroll-driven camera path, one lid lift, and nothing else moves on its own.

## Colors

The palette is graphite with blue-grey silicon. Copper is the only warm accent, and two data colours are reserved for charts.

### Primary
- **Interconnect Copper** (copper): the single accent. Used for the primary action (Contact, Send a message), the active bond pad, focus outlines, selection, the chip's wiring, the edge of the lit block, the two contact pads on the I/O ring, bullet and test-pad markers, and "now" or "core" states. **Hot Copper** (copper-hi) is its hover state only. **Copper Ink** (copper-ink) is the text colour on copper fills.

### Secondary
- **Reading Blue** (data-blue): a data colour. It marks actual values, correct outcomes, baselines, timeline bars, role tags and "working" skill levels.
- **Signal Orange** (data-orange): a data colour. It marks predictions, forecasts, errors, feature-importance fills and the model curve. It is used only in charts and data marks, never in chrome.
- **Ramp Floor** (data-mid): the dark end of the mid-to-orange ramp, used for low-intensity bars and bubbles.

### Tertiary (silicon)
- **Die** (si-die), **CPU Core** (si-cpu), **SRAM** (si-sram), **NPU Array** (si-npu), **Cache** (si-cache), **ROM** (si-rom): blue-grey metal tones that give each floorplan block a slightly different shade. They appear only on the 3D chip and on the flat fallback drawing.
- **Bond Pad** (si-pad), **Lid** (si-lid), **Substrate** (si-substrate): the package's pads, its lifting lid and its base.

### Neutral
- **Graphite** (graphite): the page ground, the bar, the footer and the WebGL clear colour.
- **Raised Graphite** (graphite-raised): test pads, reflex cards, sub-panels and architecture nodes.
- **Sunk Graphite** (graphite-sunk): chart wells, the timeline frame and the chip tooltip.
- **Panel** (panel): reading panels at 95% graphite, so the scene barely shows through. Under `prefers-contrast: more` this becomes solid graphite.
- **Hairline** (hairline) and **Strong Hairline** (hairline-strong): every border, divider, grid line and block edge.
- **Bone** (text), **Ash** (text-2), **Slate** (text-3): the three text levels. Bone is for headings and values, Ash for prose, and Slate for captions, ticks and sources. All three are raised under `prefers-contrast: more`.

### Named Rules
**The One Copper Rule.** Copper means "this one": the active section, the primary action, the live state. A screen never shows two competing copper calls to action, and copper is never used as general decoration.

**The Data Pair Rule.** Blue and orange belong to data. In every chart, blue is the observed or correct value and orange is the predicted value or the error. Interface chrome never uses them, with two exceptions: the role tags and skill-level labels, which are coloured to match the data meanings.

**The Gold-Free Rule.** No gold, yellow-brass or warm metallic gradients. The previous gold world is retired.

## Typography

**Display Font:** Schibsted Grotesk, 600–800 (with Atkinson Hyperlegible Next, system-ui)
**Body Font:** Atkinson Hyperlegible Next, 400–700 (with Atkinson Hyperlegible, system-ui)
**Label/Mono Font:** Martian Mono, 400–500 (with ui-monospace, SFMono-Regular, Menlo)

**Character:** A tight, heavy grotesk names things. A legibility-first sans does the reading. A wide mono reads like probe output: block names, readings, axis ticks, sources. All three faces load from Google Fonts. The 3D chip's label textures are drawn with the same mono face once the fonts are ready.

### Hierarchy
- **Display** (800, fluid 2.6–4.75rem, line-height 0.98, tracking −0.035em): the name in the hero only. On phones it runs from 2.2rem to 2.6rem.
- **Headline** (800, fluid 1.75–2.5rem, 1.1): one per section panel, written as an implication-first sentence. The contact headline steps up to 2–3rem.
- **Title** (700, 1.15rem; project titles run 1.25–1.55rem; role titles 1.3rem): role, project and education titles.
- **Reading** (700, 1.5rem, tabular numerals): test-pad values and confusion-matrix counts. These are figures, so they get the display face.
- **Hero role** (Schibsted 600, 1.05–1.25rem/1.4, Ash): the role line under the name.
- **Body** (400, 1.0625rem/1.65, max 68ch): all prose. Secondary prose steps down to 0.9–0.98rem.
- **Label** (Martian Mono 400/500, 0.75rem): bond pads, block tags, chart captions, ticks, pills, metric tags, dates, sources and footer. The bottom nav on phones uses 0.6875rem.

### Named Rules
**The Reading Rule.** Any number that is a measured outcome uses tabular numerals: in the display face when it is the headline figure, and in mono when it is inline in a caption or tag.

**The Mono-Is-Instrument Rule.** Mono is only for things an instrument would print: names, readings, ticks, sources. Prose is never set in mono.

## Layout

On desktop (1000px and wider), the 3D scene is fixed full-bleed behind the page, and the camera's view is offset so the chip sits in the left and centre. Every section is a single reading column on the right (the column width token). The shell centres it at up to 1280px, with a 1.25rem gutter on each side. The hero has no panel: the name, role, a meta line, the statement, the actions and a 2×2 grid of test pads sit directly on the graphite. Each following section starts after about 62vh of open scroll, which gives the camera room to fly to the next block, and it presents one solid panel. The last section adds 30vh below it.

On phones and tablets (below 1000px), the column goes full width. The chip occupies a band in roughly the top third of the screen: the view is offset down by 33% of the height, and the camera backs off on portrait screens so each block stays whole. The hero becomes a panel that starts below that band, and its order changes to name, role, test pads, actions, statement, source, so a 30-second skim sees the proof before the prose. The gap between sections drops to 58svh.

Below 860px the bond-pad nav moves to a fixed bottom bar with short labels (Work, Study), and the body gets matching bottom padding. Grids collapse at 700px (skills: 3 columns to 1), 560px (reflexes: 2 to 1; timeline labels stack; architecture rows go vertical) and 480px (feature-importance names move above their bars).

Rhythm comes from the spacing scale: 0.4rem inside tag groups, 0.75–1rem between related items, 1.5rem between groups, and 2–2.5rem between blocks within a panel. The panel's own padding scales fluidly with the viewport. Anchors offset by the bar height plus 1rem.

## Elevation & Depth

The interface is flat and hairline-built: no box-shadows anywhere. Depth comes from three things. The first is tonal stepping: sunk (wells) < graphite (ground) < raised (pads, cards). The second is the 1px gap technique: a grid whose background is the hairline colour, with cells in raised graphite, so the gaps read as ruled lines. The third, and the only real depth, is the 3D scene: a hemisphere light, a white key light and a faint copper rim light on physically based metal materials. The chip's colours are taken from the CSS tokens at runtime.

### Named Rules
**The Hairline Rule.** Structure is drawn with 1px lines in the two hairline tones, never with shadows or glow. The only emissive light on the page is the copper on the chip itself.

**The Solid Reading Rule.** Text always sits on graphite that is at least 95% opaque. The 3D scene never shows behind prose at legible strength.

## Shapes

Every corner is square: radius 0 on buttons, panels, pads, tags, charts and tooltips (the focus outline uses a 1px radius only to soften antialiasing). Small hollow squares are the recurring mark, as the pad glyph: 0.55rem on bond pads, 0.7rem on test pads and the wordmark, 0.45rem on bullets, and a filled 0.5rem copper square on the hero meta line. Chart marks follow the same geometry: square bubbles and square threshold markers, butt-ended bars, and lines with round joins. Wiring on the chip is Manhattan-routed, so turns are right angles.

## Components

### Buttons
- **Shape:** square (0px), minimum height 2.875rem (2.375rem in the top bar), Atkinson 700 at 0.95rem.
- **Copper:** copper fill with copper-ink text. Used for the single primary contact action, in the bar and in the contact section.
- **Line:** graphite fill with a strong hairline border and Bone text. On hover the border and text turn copper. Used for secondary actions such as "See the work" and LinkedIn. External links carry a small square-capped arrow drawn as inline SVG.
- **Hover / Focus:** colour transitions of 0.2s. Focus is shown as a 2px copper outline offset by 3px.

### Navigation (bond-pad bar)
- A fixed 3.5rem graphite bar with a hairline bottom edge. On the left is the "NKA" wordmark in mono, preceded by a hollow copper square with a copper centre dot. In the centre are the bond pads, and on the right the copper Contact button.
- Each pad is a mono label preceded by a 0.55rem hollow square. On hover the square's border turns copper. When the section is current (`aria-current`), the square fills copper and the label turns Bone. The current section is tracked with an observer on the middle band of the viewport.
- Number keys 1–5 jump to the five sections and move focus to each section's heading.
- Below 860px the pads move into a fixed bottom bar, each a 3.5rem touch target with the square stacked above a short label.

### Test pads
- The hero proof grid: 2×2, hairline-gapped, with raised graphite cells. Each cell has a hollow copper square, a reading value in the display face (1.5rem, 1.25rem on phones), and an Ash label. A mono Slate source line below names where the figures come from. The four readings are the case-study figures already stated on the page.

### Panels
- One per section: 95% graphite, a hairline border, fluid padding, the reading column's width. The panel head pairs the headline with a mono block tag on the right (for example "CPU · about"). The block name is copper and the section name Slate, which ties the panel to its block on the chip.
- **Sub-panels** (raised graphite, hairline border, 1.15rem padding) hold the secondary figures: feature importance and the confusion matrix.
- **Reflex cards** are a 2×2 hairline-gapped grid of raised cells, each with a title and short prose.

### Tags, pills and badges
- All are mono at 0.75rem in square hairline boxes. **Metric tags** have a copper border and Bone text and state outcomes. **Pills and badges** have a hairline or strong hairline border and Ash or Bone text. A badge marked hot turns copper (used for First Class Honours). **Stack tags** use 0.8125rem sans in Slate.

### Charts
- **Frame:** a sunk graphite well with a hairline border, 190px tall by default (the late-rate chart is 220px). It is drawn on a 2D canvas at device pixel ratio, capped at 2, and redrawn on resize.
- **Caption:** above the chart, a mono line with a bold Ash title on the left and a Slate key on the right. If the data is reconstructed, a "≈" note below it says so ("Illustrative reconstruction…").
- **Marks:** hairline grid lines, 11px mono ticks in Slate, 2px lines (blue for actual values, dashed orange for predictions), square points, and copper only for the annotated window or threshold. Bars and bubbles ramp from Ramp Floor to orange by intensity.
- **Accessibility:** every canvas is `role="img"` with a full text description of what it shows. The timeline has a visually hidden caption.
- **Draw-in:** a 900ms ease-out draw when the chart first scrolls into view. Feature bars fill over 1s in sequence, 90ms apart.
- **Other data components:** the experience timeline (blue bars, with a copper bar for the current role, on 2023–2026 ticks), the confusion matrix (blue tints for correct cells, orange tints for error cells) and the architecture diagram (mono nodes joined by hairline wires, with the new path in copper).

### The 3D chip (signature component)
- **Build:** three.js 0.160, imported as a module from jsDelivr. It has a substrate, a die, five floorplan blocks with strong-hairline edges and mono labels, internal detail cells, a 12-per-side I/O ring of bond pads, copper Manhattan wiring in the channels between blocks, the name etched along the die's bottom edge, and a lid marked "NKA · AI ACCELERATOR · 2026".
- **Block-to-section mapping:** CPU CORE → About (four cores, one per reflex). SRAM → Experience (four rows laid on the 2023–2026 axis, one per role, the current role in copper). NPU ARRAY → Projects (five tiles, the wide one for the case study). CACHE → Skills (one column of cells per skill group, coloured copper for core, blue for working and grey for developing, matching the listed counts). ROM → Education (two cells). I/O RING → Contact (two copper pads).
- **Camera stations:** seven positions and look-at points: the package three-quarter view for the hero, then one for each block in order, ending at the I/O ring's copper pads. Between a section's panel leaving and the next section arriving, scroll position interpolates between stations with a smoothstep curve, and the camera eases toward its target (exponential, rate 3.2/s). Portrait viewports pull the camera back by up to 1.9×.
- **Highlight:** the active block gets a faint copper emission (0.07) and a copper edge. The contact pads glow at 0.6 when contact is active, and 0.15 otherwise.
- **Interaction:** on fine pointers there is a gentle tilt of up to ±0.04 rad, with no dragging. Hovering a block lights it and shows a mono tooltip (graphite-sunk with a copper border, "BLOCK → section"). Clicking or tapping a block scrolls to its panel. Hit-testing ignores pointers over panels, the bar and links.
- **Lid lift:** 350ms after start, the lid rises 7 units over 1.7s with a cubic ease-out and fades to nothing, then it is hidden.
- **Rendering:** the scene renders only while something is moving or has changed.
- **Fallbacks:** reduced motion hides the lid and holds the camera at the hero station, so the visitor sees a still chip with no scroll flight and no tilt. If WebGL fails, or the module has not reported within 6 seconds, the page shows a flat SVG floorplan drawing with the same block colours and labels, placed where the chip would be.

## Do's and Don'ts

### Do:
- **Do** keep one copper accent per state: the active block, the current pad, the primary action.
- **Do** put every new section on a solid 95%-graphite panel in the right-hand column, and give it a block tag that names its floorplan block.
- **Do** show only figures that are stated in the text. Chip details may encode real counts and dates (roles, projects, skill levels) and nothing else.
- **Do** label any reconstructed or confidential chart as an illustrative reconstruction, directly below it, with the "≈" note.
- **Do** give every chart a text description and use the blue/orange data pair consistently: blue for observed, orange for predicted or error.
- **Do** keep reduced-motion and no-WebGL paths working: a still chip and a flat floorplan drawing.
- **Do** use square corners and 1px hairlines for every new surface.

### Don't:
- **Don't** use gold, glow or warm metallic gradients. The earlier gold world is retired.
- **Don't** add box-shadows or blur to cards. Depth comes from tonal steps and the 3D scene only.
- **Don't** put prose over the live scene without a panel, or set prose in mono.
- **Don't** present the chip as data. It is a metaphor for the page's structure, and its readings repeat stated figures; it never introduces new ones.
- **Don't** add a second autonomous animation. The motion is one lid lift, one scroll-driven camera path and chart draw-ins.
- **Don't** fall back to the flat stack of dark cards or the hero-over-grid template.
