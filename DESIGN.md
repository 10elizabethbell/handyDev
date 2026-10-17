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
  frost-icon: "#9fc3e0"        # winter group icon
  bubble-green: "#2f7d4a"      # message-preview chat bubble (desktop only)
  bubble-text: "#fff"
  focus: "#7cc6ff"             # focus ring on dark grounds
  focus-light: "#1f63a8"       # focus ring on light grounds (sage, snow)
  facebook-glyph: "#8fb4ff"    # Facebook mark inside the Facebook pill
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
    fontSize: "clamp(19px, 5.4vw, 22px)"
    fontWeight: 900
    lineHeight: "44px"
    letterSpacing: "-0.01em"
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
  message-card:
    backgroundColor: "rgba(242,241,230,.96)"
    textColor: "{colors.yard-ink}"
    rounded: "{rounded.card}"
    padding: "22px 22px 18px"
  facebook-pill:
    backgroundColor: "rgba(242,241,230,.1)"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
    padding: "0 18px 0 14px"
    height: "48px"
  facebook-pill-hover:
    backgroundColor: "rgba(242,241,230,.18)"
    textColor: "{colors.paper}"
  top-call:
    textColor: "{colors.paper}"
    height: "44px"
---

# Design System: Handy Dev

## Overview

**Creative North Star: "The Yard Through the Seasons"**

The page is Dev's workplace, not a contractor's brochure: the yards and driveways of Ocean County, walked top to bottom from an autumn dusk, across a lawn Dev's mower is cutting, into a winter drift, out onto fresh snow, and back to pine as the grass grows in again. Each section is a full-bleed seasonal ground, and the seams between grounds are alive: grass blades, snow drifts and falling leaves drawn on canvas, pushed by the pointer or a finger, always in the colors of the ground they lead into. In the hero the visitor can take over a push mower and cut the lawn themselves. There are no photos, no icon cards, no quote form. The world carries the identity; the type and the button stay plain and loud. The copy speaks in Dev's own first person ("Text me", "I'll tell you a fair price").

Density is low and thumb-sized. Heavy uppercase headlines (up to 96px) sit over a quiet 17px body, and every primary interactive thing is 58px tall because the visitor is on a phone with a job in mind. One color does the work of "act here": work-glove orange, which fills the single text button, colors the header phone icon, fills the hover state of every job row, and marks the brand accent in the wordmark and the headline's second line. Focus is deliberately not orange: it is a clear blue ring so a focused button never reads as its own fill.

The build is phone-first in its CSS: base rules describe the phone, and wider layouts are added with `min-width` queries only.

**Key Characteristics:**
- Full-bleed seasonal bands in fixed order: pine/dusk hero, sage services, slate winter, snow-white steps, pine close, pine-deep footer.
- A living canvas edge between bands whose front layer is the next band's color, so sections grow into each other instead of meeting at a line.
- A push mower in the hero lawn that mows on its own until touched, then follows the finger or mouse; cut grass regrows.
- Heavy uppercase sans for headings; plain sans for reading; copy in Dev's first-person voice.
- Work-glove orange is the single action color and the single brand accent; focus is blue.
- One action per spot: a single orange "Text for a free estimate" pill in the hero and the close; every service is a whole-row text link with a pre-filled SMS. The phone number lives only in the header and the footer.

## Colors

A cool, dark outdoor palette of pine, dusk and slate grounds alternating with pale lawn and snow grounds, lit by exactly one warm accent.

### Primary
- **Work-Glove Orange** (`work-glove-orange`): the action color. Fills the "Text for a free estimate" pill, fills a job row's arrow circle on hover, colors the header phone icon and text selection. Also the brand accent: the "Dev" in the wordmark, the second headline line, the "D" of the favicon and the "HD" avatar letters.
- **Hot Glove** (`work-glove-orange-hot`): hover fill for the primary pill only.
- **Glove Ink** (`glove-ink`): text and icon color on any orange fill. Never paper on orange.

### Secondary
- **Moss** (`moss`): the working green. Group icons on sage, step numerals on snow, and the mid layer of every grass field. It is a hard-coded value in the build, used across CSS and canvas; treat it as a token.

### Focus
- **Sky Focus** (`focus`): the 3px focus ring on dark grounds (hero, winter, close, footer). Global default.
- **Deep Focus** (`focus-light`): the same ring on light grounds (services sage, how-it-works snow), where the pale blue would wash out.

### Neutral (grounds)
- **Pine** (`pine`): hero base and close ground, body background, theme color, favicon tile. The home ground of the page.
- **Pine Deep** (`pine-deep`): footer ground and scrollbar track.
- **Dusk** (`dusk`) and **Hero Mid** (`hero-mid`): the hero sky gradient, dusk at 0%, hero mid at 38%, pine at 70%. Nowhere else.
- **Sage Lawn** (`sage-lawn`): services ground; also the front grass tufts of the hero, which become the services band.
- **Winter Slate** (`winter-slate`): winter ground; also the front drift of the sage-to-slate edge.
- **Snow White** (`snow-white`): how-it-works ground; also the front drift of the winter field.

### Neutral (text and small marks)
- **Yard Ink** (`yard-ink`): headings and row text on sage and snow.
- **Yard Ink Soft** (`yard-ink-soft`): secondary text on sage and snow (intros, notes, step copy).
- **Paper** (`paper`): primary text on pine and slate.
- **Paper Soft** (`paper-soft`): secondary text on pine (pitch line, area copy, quote attribution, footer).
- **Frost Soft** (`frost-soft`): secondary text on slate.
- **Frost Icon** (`frost-icon`): the winter group's snowflake line icon on slate.
- **Facebook Glyph** (`facebook-glyph`): the Facebook "f" inside the Facebook pill; a light Facebook blue legible on pine. The only brand-third-party color on the page.
- **Bubble Green / Bubble Text** (`bubble-green`, `bubble-text`): the outgoing chat bubble inside the desktop message preview only.

Hairline dividers are tints of the text color of their band, never a separate gray: yard ink at 16% on light grounds, paper at 16-18% on dark grounds.

### Named Rules
**The One Glove Rule.** Work-glove orange is reserved for actions (the text button, the header phone icon, row hover, selection) and the brand accent (wordmark "Dev", the headline's second line, the favicon "D"). It is never a section ground, a decorative fill, body text, or the focus ring. In the canvas world the one orange object is Dev's own push mower deck: his equipment wears the glove color because it is the thing the visitor's hand takes over. The autumn leaf colors are world material in their own hues, not the UI accent, and are never used in CSS.

**The Blue Focus Rule.** Keyboard focus is a 3px blue outline with a 3px offset and 6px corner, sky blue on dark grounds and deep blue on sage and snow. Never orange, so focus never merges with the button fill.

**The No-Black Rule.** No ground is black or near-neutral dark. The darkest surface is pine deep; shadows and text halos are pine- or slate-tinted, never pure black.

**The Band Text Rule.** Each ground has a fixed text pair: paper / paper soft on pine, paper / frost soft on slate, yard ink / yard ink soft on sage and snow. Do not mix pairs across grounds.

## Typography

**Display Font:** the platform sans stack (`-apple-system`, SF Pro Display, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** the same stack

**Character:** One family, two voices. Headings are weight 900, uppercase, tight (-0.02em, 0.95 line height) and balanced, like a truck-door decal; body text is a comfortable 17px that reads like a text message.

### Hierarchy
- **Display** (900, clamp 44px to 96px, 0.95, uppercase): the hero headline, set as two block lines with the second in orange. The close's "Ocean County, NJ" and "Handy Dev" headings share the 96px ceiling (clamped from 42px and 54px).
- **Headline** (900, clamp 36px to 68px, 0.95, uppercase): section headings ("Fix it. Mow it. Shovel it.", "How it works") and the Winter heading, promoted to headline size because it is its own band. Multi-phrase headings keep each phrase unbroken with no-wrap spans, so lines break only between phrases.
- **Title** (900, clamp 24px to 32px, uppercase): service group heads beside their line icon; step titles at a fixed 24px.
- **Numeral** (900, clamp 56px to 84px, 0.8, moss): step numbers, spanning two rows beside the step title and copy.
- **Lead** (400, 18px, 1.55): section intros and band subtitles, capped at 46-48ch.
- **Body** (400, 17px, 1.55): everything else; step copy capped at 34ch.
- **Small** (400, 16px, 1.5): row notes, the quote attribution, the footer.
- **Label** (800, 17px, 1): button and Facebook pill labels. Job rows use 700 at 18px; the header number 800 at 16px. Supporting bold lines (hero name, final subtitle) are 800 at clamp 17px to 22px; Dev's quote is 700 at clamp 19px to 24px, 1.38, capped at 38ch.
- **Wordmark** (900, clamp 19px to 22px, uppercase, -0.01em): "Handy **Dev**", sized to sit beside the phone number on a 360px screen.

### Named Rules
**The System-Stack Rule.** The platform sans stack is the brand voice, by Ellie's house style for these sites (`pitch-site` ellie-taste.md, Type: "the system font stack, heavy uppercase display headings ... It's fast and it worked"). It is a deliberate owner choice that overrides Impeccable's craft-floor preference for a sourced display face: no web fonts, no font downloads, nothing to slow the first screen on cellular.

**The 96 Ceiling Rule.** No type exceeds 96px. Display sizes scale with viewport width and stop at 96.

**The Uppercase-Is-Heading Rule.** Uppercase belongs to h1-h3 and the wordmark only. Body, labels, buttons and rows stay sentence case.

**The 16px Floor Rule.** Reading text on the page never goes below 16px. The pitch line is fitted to one line between 20px and 16px by script, then wraps rather than shrink further (its 14px CSS floor is only a pre-script fallback). The `mock-ui` sizes (15px, 13px) live only inside the desktop message preview, which imitates a phone screen.

## Layout

Phone-first. Base CSS is the phone layout; every layout change is a `min-width` query at one of the build's breakpoints: 561px (the hero becomes a near-full-viewport centered band, the mow zone grows from 96px to 120px, buttons stop being full-width), 860px (service groups and steps go multi-column), 960px (hero gains the message-preview column, 1.35fr / 1fr), 1100px (close splits into title and action columns). The canvas uses a separate 640px phone check to thin blades and particles and shrink the mower.

Content sits in a single centered container (`spacing.container`) with fluid side gutters (`spacing.gutter`). Bands are full-bleed; only their content is contained. Vertical band padding is fluid on a shared rhythm (`spacing.section-y` on most band tops), with extra bottom padding where a canvas ground needs room (hero, winter). Two-column splits use a 56px column gap; stacked groups use 40-44px.

The header is a 68px strip over the hero: wordmark left, tap-to-call number right, on every width. The number appears there and in the footer only; nowhere else on the page carries a Call control.

Edges between bands are their own 64-80px strips (sage-to-slate, snow-to-pine) carrying a canvas, so the transition is drawn, not ruled.

**The Thumb Rule.** Every tap target is at least 44px; the text button and job rows are 58px, the Facebook pill 48px. On phones the text button runs full-width.

**The Lawn-Is-A-Surface Rule.** Over the hero's lawn band a transparent mow zone (96px phone, 120px wider) takes `touch-action: none`, so a drag in any direction mows instead of scrolling; the page sets `overscroll-behavior-y: none` so mowing never rubber-bands the page. Keep the zone to the lawn band only, never over copy or the button.

## Elevation & Depth

Depth comes from the world, not from cards: layered canvas grass (back greens, mid greens, front tufts in the next band's color), leaves falling between the back and front grass layers, two-layer drifts, and the mower drawn in front of the lawn it cuts. CSS shadows are few, soft, and pine-tinted, and only lift things the hand is meant to reach.

### Shadow Vocabulary
- **Pill lift** (`0 10px 22px -10px rgba(5,20,12,.55)`, hover `0 16px 28px -12px rgba(5,20,12,.6)` with a 2px rise): the primary button only.
- **Held card** (`0 30px 60px -24px rgba(5,20,12,.7), 0 8px 18px -8px rgba(5,20,12,.4)`): the message-preview card, tilted 1.5deg like a phone in a hand.
- **Ground halo** (pine `0 0 18px rgba(23,58,38,.95), 0 0 6px rgba(23,58,38,.9)` on hero copy and the header; slate `0 0 14px / 0 0 5px` at the same alphas on winter; pine `0 0 16px / 0 0 6px` on the close): a text glow in the band's own ground color, so drifting leaves and flakes fade out behind letters instead of crossing them. Buttons and the Facebook pill opt out.

### Named Rules
**The Lift-What-You-Tap Rule.** Box shadows go on the primary action and the message card. Lists, sections and text blocks are flat.

**The Halo-Is-Ground Rule.** Text over a living canvas carries a halo in exactly its band's ground color, never a tint, a contrasting glow, or black. It exists for legibility over particles, not as decoration.

## Shapes

Soft and round where the hand goes, square everywhere else. The button and the Facebook pill are full pills (`rounded.pill`), the arrow on each job row is a circle (`rounded.circle`), the message card is a generous rounded rectangle (`rounded.card`) with a chat bubble inside (`rounded.bubble` with a `rounded.bubble-tail` corner), and the focus ring rounds to `rounded.focus`. Bands are hard full-bleed rectangles whose seams are broken by organic canvas silhouettes: tapered quadratic grass blades, sine-summed drift crests, two-curve leaves, and the mower built from rounded rectangles and circular wheels. Line icons are drawn at 2.2-2.4 stroke with round caps and joins, sized 20-30px; the Facebook mark is the one filled glyph. The favicon (`icon.svg`) is a pine rounded tile with paper "H" and orange "D" in the heading weight; there is no client logo.

## Components

### Buttons
One button, used alone: the orange text pill.
- **Shape:** full pill (`rounded.pill`), 58px tall, 26px side padding, 22px leading speech-bubble icon, 10px icon gap.
- **Primary:** "Text for a free estimate"; orange fill and 2px orange border, glove-ink label. Its href is an `sms:` link with a pre-filled body. It appears once in the hero and once in the close, never paired with a second pill.
- **Hover (hover-capable devices only):** hot glove with a 2px rise and deeper shadow. Active presses 1px down.
- **Focus:** the blue ring (see The Blue Focus Rule).
- **Layout:** full-width on phones; natural width from 561px.

### Service Rows
The job list is the menu and the form at once.
- **Structure:** each job is a single full-width link (the whole row is the `sms:` target, pre-filled with that job's name) holding the job name on the left and a 34px arrow-in-circle on the right.
- **Rules:** 1px hairline above each row and below the last, tinted from the band's text color.
- **Hover:** the name slides 8px right, the circle slides 4px left and fills orange with a glove-ink arrow.
- **Winter variant:** paper text, paper-tinted hairlines and circle on slate; two columns from 860px.
- **Group head:** a 30px moss line icon (frost icon on slate) beside an uppercase title.

### Navigation (header)
- Absolute over the hero, 68px tall: uppercase 900 wordmark "Handy **Dev**" (Dev in orange) left; right, a tap-to-call link with a 20px orange phone icon and the number in 800 16px paper, shown on every width, underlined on hover. No menu.

### Facebook Pill
- Under Dev's quote in the close: a 48px pill in paper at 10% on pine, 22px Facebook glyph in `facebook-glyph`, paper 800 label in Dev's voice ("See more of my work on Facebook"). Hover raises the fill to 18% and underlines the label. A plain footer "Facebook" link repeats it. It is a secondary link, so it never takes the orange.

### Message Preview Card
- Desktop only (960px+), right column of the hero. Paper card at 96%, 26px radius, tilted 1.5deg, held-card shadow; a pine avatar with orange "HD", a green chat bubble containing the exact pre-filled text the button sends, and a right-aligned caption saying so. It shows the action, not a testimonial.

### Steps
- Three numbered steps on snow: a moss numeral spanning title and copy, stacked on phones, three columns from 860px.

### Living Field (signature)
One canvas renderer, `Field(canvas, options)`, draws every seasonal ground. Canvases sit absolutely behind band content (`pointer-events: none`, `aria-hidden`).
- **Ground layers:** `grass` (array of layers, back to front, each with height range, blade width and color set) or `drift` (back and front crest heights, amplitude, two colors), plus an optional 3px `base` strip in the next band's color to seal the seam.
- **Particles:** `parts` of kind `leaf` (five autumn hues, bezier leaf with a shaded half, flips and rotates, can come to rest on the grass and be kicked loose) or `flake` (three pre-rendered radial sprites, settle into the drift surface). Counts differ for desk and phone.
- **Mower:** `mower: true` adds Dev's push mower to a grass field (hero only). It walks the lawn on its own, turning at the edges; once the pointer or a finger enters the canvas it follows it horizontally (speed-capped, eased), and resumes on its own after a few idle seconds. Blades under the deck are cut to about a quarter height and throw clippings in their own color that arc and fade; cut blades regrow steadily. Colors: orange deck with a darker orange skirt, glove-ink handle and wheels, dark engine block.
- **Seam doctrine:** the front grass layer or front drift is always the color of the band below, so the next section grows up out of the current one. The back drift of the sage-to-slate edge is a pale snowbank crest (#e3ebf1). Leaves draw between the back and front grass.
- **Interaction:** a shared loop tracks pointer and touch with velocity; blades are pushed and spring back with a wobble, the drift digs into a trench that slowly refills, particles are shoved and flung.
- **Tunables:** the `T` object at the top of the IIFE (`WIND_SPEED`, `BLADE_GAP`, `BLADE_GAP_PHONE`, `PUSH_RADIUS`, `PUSH_FORCE`, `SPRING`, `DAMP`, `LEAF_RADIUS`, `DRIFT_SPRING`, `DRIFT_DAMP`, and for the mower `MOW_SCALE`, `MOW_SCALE_PHONE`, `MOW_AUTO_SPEED`, `MOW_MAX_SPEED`, `MOW_FOLLOW`, `MOW_RESUME`, `MOW_CUT_TO`, `REGROW`, `CLIPPINGS_MAX`, `CLIPPINGS_MAX_PHONE`). Adjust feel there, not inside the step function.
- **Performance and motion:** frames run only while a canvas is within 80px of the viewport; DPR capped at 2; rebuilds on resize. With reduced motion, each field draws one still frame (the mower parked mid-lawn with a cut strip behind it) and never animates.
- **Instances:** hero (four grass layers ending in sage tufts, resting leaves, the mower), sage-to-slate edge (snowbank-crest drift ending in slate), winter (snowfall, drift ending in snow white), snow-to-pine edge (spring grass ending in pine), close (leaves only).

## Do's and Don'ts

### Do:
- **Do** write base CSS for the phone and add wider layouts with `min-width` queries only.
- **Do** keep work-glove orange for actions and the brand accent; put glove ink on top of it.
- **Do** use the blue focus ring: `focus` on dark grounds, `focus-light` on sage and snow.
- **Do** keep every ground in the pine, dusk, sage, slate, snow family; darkest is pine deep.
- **Do** join bands with a `Field` edge whose front layer is the next band's color.
- **Do** make the whole service row the link, ending in the arrow-in-circle, with a pre-filled `sms:` body naming the job.
- **Do** give each action spot one orange text pill and keep the phone number to the header and footer.
- **Do** halo text over a living canvas in its own ground color.
- **Do** write copy in Dev's first person.
- **Do** gate hover motion behind `(hover: hover)` and give every canvas a reduced-motion still frame.
- **Do** cap display type at 96px and keep headings uppercase 900.

### Don't:
- **Don't** use black or neutral-gray grounds, or pure-black shadows.
- **Don't** use orange as a section ground, decoration, focus ring, or text color outside the brand accent; the mower deck is the only orange in the canvas.
- **Don't** put a second pill or a Call button beside the text button.
- **Don't** put small uppercase kicker or eyebrow labels above headings.
- **Don't** add thin decorative highlight lines (glossy top-edge strokes, accent rules under headings, gradient hairlines). The only 1px lines are the structural list and section dividers tinted from the band's own text color.
- **Don't** add a contact form, icon-card grids, or stock photography; the text link and the living field carry the page.
