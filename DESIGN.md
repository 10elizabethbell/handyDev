---
name: Handy Dev
description: One local handyman's yard through the seasons; every surface ends in a text to Dev.
colors:
  work-glove-orange: "#f28c28"
  work-glove-orange-hot: "#ff9d3a"
  glove-ink: "#1d1a12"
  pine: "#173a26"
  pine-deep: "#122f1f"
  dusk: "#1d3a48"
  moss: "#2f6b3a"
  sage-lawn: "#e6ecd9"
  winter-slate: "#1f3447"
  snow-white: "#eef2f4"
  yard-ink: "#13301f"
  yard-ink-soft: "#3c5a44"
  paper: "#f2f1e6"
  paper-soft: "#c8d6c2"
  frost-soft: "#bfd0de"
  hero-mid: "#1b3d36"          # middle stop of the dusk-to-pine hero gradient
  moss-deep: "#24472f"         # ghost button hover on pine
  frost-icon: "#9fc3e0"        # winter group icon
  bubble-green: "#2f7d4a"      # message-preview chat bubble (desktop only)
  bubble-text: "#fff"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(44px, 12.4vw, 96px)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(36px, 6vw, 68px)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(24px, 3vw, 32px)"
    fontWeight: 900
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  numeral:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(56px, 7vw, 84px)"
    fontWeight: 900
    lineHeight: 0.8
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1
  display-close:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(54px, 8vw, 96px)"
    fontWeight: 900
    lineHeight: 0.95
  display-area:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(42px, 8vw, 96px)"
    fontWeight: 900
    lineHeight: 0.95
  wordmark:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 900
    lineHeight: 1
  name-line:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(17px, 2.1vw, 22px)"
    fontWeight: 800
    lineHeight: 1.3
  name-line-close:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(17px, 2vw, 22px)"
    fontWeight: 800
    lineHeight: 1.3
  pitch:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(14px, 3.9vw, 20px)"
    fontWeight: 400
    lineHeight: 1.45
  quote:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(19px, 2vw, 24px)"
    fontWeight: 700
    lineHeight: 1.38
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.5
  mock-ui:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.45
  mock-ui-caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.4
rounded:
  pill: "999px"
  bubble: "20px"
  bubble-tail: "6px"
  focus: "6px"
  card: "26px"
  circle: "50%"
spacing:
  gutter: "clamp(16px, 4vw, 48px)"
  container: "1200px"
  section-y: "clamp(40px, 6vw, 72px)"
  column-gap: "56px"
  action-gap: "12px"
  tap-row: "58px"
components:
  button-primary:
    backgroundColor: "{colors.work-glove-orange}"
    textColor: "{colors.glove-ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "58px"
  button-primary-hover:
    backgroundColor: "{colors.work-glove-orange-hot}"
    textColor: "{colors.glove-ink}"
  button-ghost:
    backgroundColor: "rgba(23,58,38,.88)"
    textColor: "{colors.paper}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "58px"
  button-ghost-hover:
    backgroundColor: "#24472f"
    textColor: "{colors.paper}"
  service-row:
    textColor: "{colors.yard-ink}"
    padding: "10px 4px"
    height: "58px"
  service-row-go:
    backgroundColor: "rgba(19,48,31,.08)"
    textColor: "{colors.yard-ink}"
    rounded: "{rounded.circle}"
    size: "34px"
  service-row-go-hover:
    backgroundColor: "{colors.work-glove-orange}"
    textColor: "{colors.glove-ink}"
  service-row-winter:
    textColor: "{colors.paper}"
    padding: "10px 4px"
    height: "58px"
  service-row-winter-go:
    backgroundColor: "rgba(242,241,230,.12)"
    textColor: "{colors.paper}"
    rounded: "{rounded.circle}"
    size: "34px"
  sticky-text-bar:
    backgroundColor: "rgba(18,47,31,.94)"
    padding: "10px 16px"
  message-card:
    backgroundColor: "rgba(242,241,230,.96)"
    textColor: "{colors.yard-ink}"
    rounded: "{rounded.card}"
    padding: "22px 22px 18px"
---

# Design System: Handy Dev

## Overview

**Creative North Star: "The Yard Through the Seasons"**

The page is Dev's workplace, not a contractor's brochure: the yards and driveways of Ocean County, walked top to bottom from an autumn dusk, across a mown lawn, into a winter drift, out onto fresh snow, and back to pine as the grass grows in again. Each section is a full-bleed seasonal ground, and the seams between grounds are alive: grass blades, snow drifts and falling leaves drawn on canvas, pushed by the pointer or a finger, always in the colors of the ground they lead into. There are no photos, no icon cards, no quote form. The world carries the identity; the type and the buttons stay plain and loud.

Density is low and thumb-sized. Heavy uppercase system-sans headlines (up to 96px) sit over a quiet 17px body, and every interactive thing is at least 58px tall because the visitor is on a phone with a job in mind. One color does the work of "act here": work-glove orange, which marks the text button, the call icon, the hover state of every job row, focus, selection, and the brand accent in the wordmark and the headline's second line.

The build is phone-first in its CSS: base rules describe the phone, and wider layouts are added with `min-width` queries only.

**Key Characteristics:**
- Full-bleed seasonal bands in fixed order: pine/dusk hero, sage services, slate winter, snow-white steps, pine close, pine-deep footer.
- A living canvas edge between bands whose front layer is the next band's color, so sections grow into each other instead of meeting at a line.
- Heavy uppercase system sans for headings; plain system sans for reading.
- Work-glove orange is the single action color and the single brand accent.
- Every service is a whole-row text link with a pre-filled SMS; there is no form.
- A sticky text bar on phones whenever the inline buttons are out of view.

## Colors

A cool, dark outdoor palette of pine, dusk and slate grounds alternating with pale lawn and snow grounds, lit by exactly one warm accent.

### Primary
- **Work-Glove Orange** (`work-glove-orange`): the action color. Fills the primary "Text for a free estimate" pill, fills a job row's arrow circle on hover, colors the top-bar phone icon, the focus ring (3px) and text selection. Also the brand accent: the "Dev" in the wordmark, the second headline line, the "HD" monogram letters.
- **Hot Glove** (`work-glove-orange-hot`): hover fill for the primary pill only.
- **Glove Ink** (`glove-ink`): text and icon color on any orange fill. Never paper on orange.

### Secondary
- **Moss** (`moss`): the working green. Group icons on sage, step numerals on snow, and the mid layer of every grass field. It is a hard-coded value in the build, used across CSS and canvas; treat it as a token.

### Neutral (grounds)
- **Pine** (`pine`): hero base and close ground, body background, theme color. The home ground of the page.
- **Pine Deep** (`pine-deep`): footer ground and scrollbar track; the sticky bar is pine-deep at 94%.
- **Dusk** (`dusk`): top of the hero sky gradient only (dusk 0% to pine 70%).
- **Sage Lawn** (`sage-lawn`): services ground; also the front grass tufts of the hero, which become the services band.
- **Winter Slate** (`winter-slate`): winter ground; also the front drift of the sage-to-slate edge.
- **Snow White** (`snow-white`): how-it-works ground; also the front drift of the winter field.

### Neutral (text)
- **Yard Ink** (`yard-ink`): headings and row text on sage and snow.
- **Yard Ink Soft** (`yard-ink-soft`): secondary text on sage and snow (intros, group subtitles, step copy, notes).
- **Paper** (`paper`): primary text on pine and slate; the ghost button's 2px outline.
- **Paper Soft** (`paper-soft`): secondary text on pine (pitch line, area copy, quote attribution, footer).
- **Frost Soft** (`frost-soft`): secondary text on slate.

Hairline dividers are tints of the text color of their band, never a separate gray: yard ink at 16% on light grounds, paper at 16-18% on dark grounds.

### Named Rules
**The One Glove Rule.** Work-glove orange is reserved for actions (buttons, action icons, row hover, focus, selection) and the brand accent (wordmark "Dev", the headline's second line). It is never a section ground, a decorative fill, or body text. The autumn leaf colors in the canvas field are world material in their own hues, not the UI accent, and are never used in CSS.

**The No-Black Rule.** No ground is black or near-neutral dark. The darkest surface is pine deep; shadows are pine-tinted (`rgba(5,20,12,…)`), never pure black.

**The Band Text Rule.** Each ground has a fixed text pair: paper / paper soft on pine, paper / frost soft on slate, yard ink / yard ink soft on sage and snow. Do not mix pairs across grounds.

## Typography

**Display Font:** system sans (`-apple-system`, SF Pro Display, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** the same system stack

**Character:** One family, two voices. Headings are weight 900, uppercase, tight (-0.02em, 0.95 line height), balanced, and shout like a truck-door decal; body text is the phone's own native sans at a comfortable 17px, so the reading voice sounds like a text message.

### Hierarchy
- **Display** (900, clamp 44px to 96px, 0.95, uppercase): the hero headline, set as two block lines with the second in orange. The close's "Ocean County, NJ" and "Handy Dev" headings use the same 96px ceiling (clamped from 42px and 54px).
- **Headline** (900, clamp 36px to 68px, 0.95, uppercase): section headings ("Fix it. Mow it. Shovel it.", "How it works") and the Winter heading, which is promoted to headline size because it is its own band.
- **Title** (900, clamp 24px to 32px, uppercase): service group heads beside their line icon; step titles at a fixed 24px.
- **Numeral** (900, clamp 56px to 84px, 0.8, moss): step numbers, spanning two rows beside the step title and copy.
- **Lead** (400, 18px, 1.55): section intros and band subtitles, capped at 46-48ch.
- **Body** (400, 17px, 1.55): everything else; step copy capped at 34ch.
- **Label** (800, 17px, 1): button labels. Job rows use 700 at 18px. Supporting bold lines (hero name, final subtitle) are 800 at clamp 17px to 22px; the founder quote is 700 at clamp 19px to 24px, 1.38.

### Named Rules
**The 96 Ceiling Rule.** No type exceeds 96px. Display sizes scale with viewport width and stop at 96.

**The Uppercase-Is-Heading Rule.** Uppercase belongs to h1-h3 and the wordmark only. Body, labels, buttons and rows stay sentence case; there are no small uppercase labels above headings.

**The 16px Floor Rule.** Reading text on the page never goes below 16px. The pitch line is fitted to one line between 20px and 16px by script, then wraps rather than shrink further.

## Layout

Phone-first. Base CSS is the phone layout; every layout change is a `min-width` query at one of the build's breakpoints: 561px (button pair goes side by side; hero becomes a near-full-viewport centered band; top-bar number appears), 720px (sticky bar retires), 860px (service groups and steps go multi-column), 960px (hero gains the message-preview column, 1.35fr / 1fr), 1100px (close splits into title and action columns). The canvas uses a separate 640px phone check to thin out blades and particles.

Content sits in a single centered container (`spacing.container`) with fluid side gutters (`spacing.gutter`). Bands are full-bleed; only their content is contained. Vertical band padding is fluid on a shared rhythm (`spacing.section-y` on most band tops), with extra bottom padding where a canvas ground needs room (hero, winter). Two-column splits use a 56px column gap; stacked groups use 40-44px; the action pair uses 12px.

Edges between bands are their own 64-80px strips (sage-to-slate, snow-to-pine) carrying a canvas, so the transition is drawn, not ruled.

**The Thumb Rule.** Every tap target is at least 44px; buttons and job rows are 58px. On phones the button pair stacks full-width.

## Elevation & Depth

Depth comes from the world, not from cards: layered canvas grass (back greens, mid greens, front tufts in the next band's color), leaves falling between the back and front grass layers, and two-layer drifts. CSS shadows are few, soft, and pine-tinted, and only lift things the hand is meant to reach.

### Shadow Vocabulary
- **Pill lift** (`0 10px 22px -10px rgba(5,20,12,.55)`, hover `0 16px 28px -12px rgba(5,20,12,.6)` with a 2px rise): the primary button only.
- **Held card** (`0 30px 60px -24px rgba(5,20,12,.7), 0 8px 18px -8px rgba(5,20,12,.4)`): the message-preview card, which is tilted 1.5deg like a phone in a hand.
- **Bar underglow** (`0 -10px 30px -12px rgba(5,20,12,.6)` plus 10px backdrop blur): the sticky text bar, casting upward.

### Named Rules
**The Lift-What-You-Tap Rule.** Shadows go on the primary action, the sticky bar and the message card. Lists, sections and text blocks are flat.

## Shapes

Soft and round where the hand goes, square everywhere else. The pitch line is sized by script between 16px and 20px on one line (the 14px CSS floor is only a pre-script fallback); `mock-ui` sizes live only inside the desktop message preview, which imitates a phone screen and is exempt from the 16px floor. Buttons are full pills (`rounded.pill`), the arrow on each job row is a circle (`rounded.circle`), the message card is a generous rounded rectangle (`rounded.card`) with a chat bubble inside (20px with a 6px tail corner). Bands are hard full-bleed rectangles whose top and bottom seams are broken by organic canvas silhouettes: tapered quadratic grass blades, sine-summed drift crests, two-curve leaves. Line icons are drawn at 2.2-2.4 stroke with round caps and joins, sized 20-30px.

## Components

### Buttons
Two pills that always travel as a pair, same height, same 2px outline weight, so "Text" and "Call" read as equals in size and the color alone ranks them.
- **Shape:** full pill (`rounded.pill`), 58px tall, 26px side padding, 22px leading line icon, 10px icon gap.
- **Primary:** "Text for a free estimate" with a speech-bubble icon; orange fill and border, glove-ink label. Its href is an `sms:` link with a pre-filled body.
- **Ghost:** "Call (609) 467-9972" with a phone icon; pine at 88% fill, 2px paper outline, paper label.
- **Hover (hover-capable devices only):** primary to hot glove with a 2px rise and deeper shadow; ghost to a lighter pine with the same rise. Active presses 1px down.
- **Focus:** 3px orange outline, 3px offset.
- **Layout:** stacked full-width on phones; side by side from 561px.

### Service Rows
The job list is the menu and the form at once.
- **Structure:** each job is a single full-width link (the whole row is the `sms:` target, pre-filled with that job's name) holding the job name on the left and a 34px arrow-in-circle on the right.
- **Rules:** 1px hairline above each row and below the last, tinted from the band's text color.
- **Hover:** the name slides 8px right, the circle slides 4px left and fills orange with a glove-ink arrow.
- **Winter variant:** paper text, paper-tinted hairlines and circle on slate; two columns from 860px.
- **Group head:** a 30px moss line icon (pale blue on slate) beside an uppercase title, then a soft subtitle.

### Sticky Text Bar
- Phones only (hidden from 720px). A full-width primary pill in a pine-deep 94% bar with backdrop blur and safe-area padding.
- Slides up (0.45s, ease-out) only while neither the hero nor the close button pair is on screen; the footer reserves room for it.

### Navigation (top bar)
- Absolute over the hero, 68px tall: uppercase 900 wordmark "Handy **Dev**" (Dev in orange) left, a tel: link right with an orange phone icon; the number text appears from 561px. No menu.

### Message Preview Card
- Desktop only (960px+), right column of the hero. Paper card at 96%, 26px radius, tilted 1.5deg, held-card shadow; a pine avatar with orange "HD", and a moss chat bubble containing the exact pre-filled text the primary button sends. It shows the action, not a testimonial.

### Steps
- Three numbered steps on snow: a moss numeral spanning title and copy, stacked on phones, three columns from 860px.

### Living Field (signature)
One canvas renderer, `Field(canvas, options)`, draws every seasonal ground. Canvases sit absolutely behind band content (`pointer-events: none`, `aria-hidden`).
- **Ground layers:** `grass` (array of layers, back to front, each with height range, blade width and color set) or `drift` (back and front crest heights, amplitude, two colors), plus an optional 3px `base` strip in the next band's color to seal the seam.
- **Particles:** `parts` of kind `leaf` (five autumn hues, bezier leaf with a shaded half, flips and rotates, can come to rest on the grass and be kicked loose) or `flake` (three pre-rendered radial sprites, settle into the drift surface). Counts differ for desk and phone.
- **Seam doctrine:** the front grass layer or front drift is always the color of the band below, so the next section literally grows up out of the current one. Leaves draw between the back and front grass.
- **Interaction:** a shared loop tracks pointer and touch with velocity; blades are pushed and spring back with a wobble, the drift digs into a trench that slowly refills, particles are shoved and flung.
- **Tunables:** the `T` object at the top of the IIFE (`WIND_SPEED`, `BLADE_GAP`, `BLADE_GAP_PHONE`, `PUSH_RADIUS`, `PUSH_FORCE`, `SPRING`, `DAMP`, `LEAF_RADIUS`, `DRIFT_SPRING`, `DRIFT_DAMP`). Adjust feel there, not inside the step function.
- **Performance and motion:** frames run only while a canvas is within 80px of the viewport; DPR capped at 2; rebuilds on resize. With reduced motion, each field draws one still frame and never animates.
- **Instances:** hero (four grass layers ending in sage tufts, leaves resting on the grass), sage-to-slate edge (drift ending in slate), winter (snowfall, drift ending in snow white), snow-to-pine edge (spring grass ending in pine), close (leaves only).

## Do's and Don'ts

### Do:
- **Do** write base CSS for the phone and add wider layouts with `min-width` queries only.
- **Do** keep work-glove orange for actions and the brand accent; put glove ink on top of it.
- **Do** keep every ground in the pine, dusk, sage, slate, snow family; darkest is pine deep.
- **Do** join bands with a `Field` edge whose front layer is the next band's color.
- **Do** make the whole service row the link, ending in the arrow-in-circle, with a pre-filled `sms:` body naming the job.
- **Do** ship primary and ghost buttons as a same-height pair with the same 2px outline.
- **Do** gate hover motion behind `(hover: hover)` and give every canvas a reduced-motion still frame.
- **Do** cap display type at 96px and keep headings uppercase 900.

### Don't:
- **Don't** use black or neutral-gray grounds, or pure-black shadows.
- **Don't** use orange as a section ground, decoration, or text color outside the brand accent.
- **Don't** put small uppercase kicker or eyebrow labels above headings.
- **Don't** add thin decorative highlight lines (glossy top-edge strokes, accent rules under headings, gradient hairlines). The only 1px lines are the structural list and section dividers tinted from the band's own text color.
- **Don't** introduce a web display font; the system stack is the brand voice.
- **Don't** add a contact form, icon-card grids, or stock photography; the text link and the living field carry the page.
