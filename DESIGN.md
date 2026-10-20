---
name: Handy Dev
description: One local handyman in calm full-bleed bands of paper and pine; every surface ends in a text to Dev.
colors:
  field-fill: "#e7ece4"
  work-glove-orange: "#f28c28"
  work-glove-orange-hot: "#ff9d3a"
  orange-ink: "#9a4a00"
  pine: "#1f4a33"
  deep-pine: "#13301f"
  pine-ink: "#13301f"
  body-pine: "#2a3a30"
  soft-pine: "#4d5c52"
  paper: "#f5f6f2"
  card-white: "#ffffff"
  on-dark: "#f4f7f3"
  on-dark-soft: "#cfe0d4"
  focus-pine: "#1f4a33"
  error-red: "#b3261e"
  line-on-light: "rgba(19,48,31,.12)"
  line-on-dark: "rgba(255,255,255,.14)"
  tint-on-light: "rgba(19,48,31,.06)"
  arrow-tint-on-light: "rgba(19,48,31,.07)"
  tint-on-dark: "rgba(255,255,255,.12)"
  arrow-tint-on-dark: "rgba(255,255,255,.1)"
  ghost-outline: "rgba(244,247,243,.7)"
  texture-line: "rgba(255,255,255,.035)"
  facebook-blue: "#1877f2"
typography:
  display:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  display-phone:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(30px, 9vw, 52px)"
    fontWeight: 400
    lineHeight: 1
  headline:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(22px, 6vw, 26px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  claim:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "clamp(20px, 5.4vw, 24px)"
    fontWeight: 400
    lineHeight: 1.15
  title-small:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1.2
  label:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.2
  wordmark:
    fontFamily: "\"Cal Sans\", \"Avenir Next\", \"Segoe UI\", system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.01em"
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(17px, 4.7vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  body-large:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.3
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  eyebrow:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.02em"
rounded:
  field: "10px"
  card: "24px"
  pill: "999px"
  circle: "50%"
spacing:
  stack-tight: "12px"
  stack: "20px"
  block: "28px"
  group: "40px"
  column: "64px"
  gutter-phone: "20px"
  gutter-desktop: "40px"
  section-phone: "64px"
  section-desktop: "96px"
  container: "1160px"
components:
  button-primary:
    backgroundColor: "{colors.work-glove-orange}"
    textColor: "{colors.pine-ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.work-glove-orange-hot}"
    textColor: "{colors.pine-ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.pine-ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    height: "56px"
  eyebrow:
    backgroundColor: "{colors.tint-on-light}"
    textColor: "{colors.pine-ink}"
    typography: "{typography.eyebrow}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  eyebrow-on-dark:
    backgroundColor: "{colors.tint-on-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.eyebrow}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  card-form:
    backgroundColor: "{colors.card-white}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  input:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.pine-ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.pine-ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.pine-ink}"
    textColor: "{colors.card-white}"
  arrow-disc:
    backgroundColor: "{colors.arrow-tint-on-light}"
    textColor: "{colors.pine-ink}"
    rounded: "{rounded.circle}"
    size: "44px"
  arrow-disc-active:
    backgroundColor: "{colors.work-glove-orange}"
    textColor: "{colors.pine-ink}"
  step-marker:
    backgroundColor: "{colors.work-glove-orange}"
    textColor: "{colors.pine-ink}"
    rounded: "{rounded.circle}"
    size: "44px"
  float-circle:
    backgroundColor: "{colors.work-glove-orange}"
    textColor: "{colors.pine-ink}"
    rounded: "{rounded.circle}"
    size: "60px"
---

# Design System: Handy Dev

<!-- Recorded from the shipped index.html after the 2026-10-19 revamp into Ellie's house calm band style. The previous seasonal-yard world (mower canvas hero, grass, leaves, snow, sage and slate bands, system weight-900 headings) lives in git history at commit 9a51e2d. -->

## Overview

**Creative North Star: "The Calm Work Truck"**

A plain, orderly page for one young handyman: full-bleed bands that alternate off-white paper with pine and deep pine, one work-glove orange that only ever fills things, and Cal Sans headings sitting on a quiet system-font body. Nothing on the page is busy. The order does the work: who he is, his promise, his list of jobs, a short form, his number.

Density is low and the rhythm is generous (64px bands on phones, 96px on desktop). Every action surface is a text to Dev: the hero button, each service row, the form, and the floating circle. The one flourish is the hero H1 bouncing in letter by letter on load; everything after it settles with a single 12px fade-up.

This is Ellie's house calm band style (learned from lpmr.co.uk), applied with pine in place of the style's navies and orange in place of its gold, both carried over from Dev's first build. There are no photos, no logo and no brand colors; the bands and the type carry the identity.

**Key Characteristics:**
- Full-bleed bands: paper, pine, deep pine with a faint 135° line texture.
- One warm accent, used as a fill; orange text on light uses the darker orange ink.
- Cal Sans at weight 400 for headings, buttons, labels and the phone number; the system stack for running text.
- Soft, borderless shapes: 24px cards, 10px fields on a tinted fill, full pills.
- Motion: one letter bounce-in on the hero H1, one fade-up for content below the first screen, one sliding text circle.

## Colors

Paper and pine with one work-glove orange: a restrained palette where the accent appears as fills on buttons, markers, the eyebrow dot and the floating circle, and as the last phrase of headings on dark bands.

### Primary
- **Work-Glove Orange** (`work-glove-orange`): the one accent. Fills the primary pill button, step numbers, the floating text circle, the eyebrow dot, hovered/focused arrow discs and the text-selection highlight. On pine and deep pine it is also the color of accent text (the hero's "Ocean County.", "Shovel it.", "Dev" in the close) and of group icons and the big phone glyph. Text on it is always Pine Ink.
- **Hot Orange** (`work-glove-orange-hot`): the primary button's hover fill, nothing else.
- **Orange Ink** (`orange-ink`): orange when it has to be text or an icon on a light ground (wordmark "Dev", header phone glyph and hover, claim icons, accent phrases on paper). Measured 5.8:1 on paper.

### Secondary
- **Pine** (`pine`): the mid band. Grounds the hero and the close.
- **Deep Pine** (`deep-pine`): the darkest band. Grounds the services list and the footer, always with the line texture.

### Neutral
- **Paper** (`paper`): the page ground, the header, the light bands, and the tinted fill inside inputs and chips. Also the browser theme color.
- **Card White** (`card-white`): the form card and the Facebook row; also the hero H1 and selected-chip text.
- **Pine Ink** (`pine-ink`): headings on light, text on orange, selected chip fill, outlined button. Same value as Deep Pine; the two names mark two roles.
- **Body Pine** (`body-pine`): running text on light.
- **Soft Pine** (`soft-pine`): ledes, step details, helper text, placeholders, the wordmark's descriptor.
- **On Dark** (`on-dark`): headings, rows and links on pine and deep pine.
- **On Dark Soft** (`on-dark-soft`): running text on dark bands (7.3:1 on pine; a pine-tinted soft, not a gray).
- **Lines** (`line-on-light`, `line-on-dark`): 1px dividers between claims and between service rows.
- **Tints** (`tint-on-light`, `arrow-tint-on-light`, `tint-on-dark`, `arrow-tint-on-dark`): quiet fills for the eyebrow pill and the resting arrow discs.
- **Ghost Outline** (`ghost-outline`): the 2px outline of the ghost button on pine.
- **Focus Pine** (`focus-pine`): focus rings and field hover/focus borders on light grounds. On dark grounds the ring switches to Work-Glove Orange.
- **Error Red** (`error-red`): field error text and the invalid field border.
- **Facebook Blue** (`facebook-blue`): the Facebook mark inside the Facebook row only. A third-party brand mark, not a palette color.

### Named Rules
**The Fill-Only Orange Rule.** Work-Glove Orange is a fill on any light ground. Where orange must read as text or an icon on paper or white, use Orange Ink. Text placed on an orange fill is Pine Ink, never white.

**The Accent Tail Rule.** A heading's last phrase may take the accent color, set in a span. On dark bands that is Work-Glove Orange; on paper it is Orange Ink.

**The Never-Black Rule.** The darkest surface is Deep Pine. No black grounds, no gray text; soft text is always pine-tinted.

## Typography

**Display Font:** Cal Sans (Google Fonts, `display=swap`, preconnected), falling back to "Avenir Next", "Segoe UI", system-ui, sans-serif.
**Body Font:** the system stack: -apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Arial, sans-serif.

**Character:** a rounded, friendly geometric display at its single weight (400) over a native body that reads like a text message. All headings are balanced (`text-wrap: balance`) with a slight negative track.

### Hierarchy
- **Display** (400, clamp 42–80px, 1.02): the hero H1 only, white, max 12ch.
- **Display Phone** (400, clamp 30–52px, 1): the big tap-to-call number in the close.
- **Headline** (400, clamp 30–48px, 1.08): section H2s.
- **Title** (400, clamp 22–26px, 1.08): service group H3s, each with a 28px orange line icon.
- **Claim** (400, clamp 20–24px, 1.15): the three trust claims.
- **Title Small** (400, 20px, 1.2): step titles; the Facebook row label runs at clamp 18–20px.
- **Label** (400, 18px, 1.2): form labels and legends; buttons and the header phone use it at line-height 1 (header phone 20px from 760px).
- **Wordmark** (400, 21px, 24px from 760px, +0.01em): "Handy Dev" with "Dev" in Orange Ink.
- **Lead** (system 400, clamp 17–20px, 1.5): the hero promise and the close's intro; ledes run clamp 17–20px at 1.7, capped near 38ch.
- **Body Large** (system 400, 18px, 1.3): service rows and the "ask me anyway" line.
- **Body** (system 400, 16px, 1.7): running text, inputs, chips, helper and error text, footer. Nothing interactive drops below 16px.
- **Eyebrow** (system 500, 14px, +0.02em): the eyebrow pill only. Field "(optional)" hints use 14px system at 400.

### Named Rules
**The Display-Is-Cal-Sans, Body-Is-System Rule.** Only headings and heading-like voices (buttons, labels, claims, step titles, phone numbers, wordmark) use Cal Sans. Running text, inputs, chips and the eyebrow use the system stack. No second webfont.

**The One-Weight Rule.** Cal Sans is always weight 400; hierarchy comes from size alone. Never fake-bold it.

**The Sixteen Floor Rule.** Inputs and body text are 16px or larger so iOS never zooms and helper text stays legible.

## Layout

A single centered column (max 1160px) with a 20px phone gutter that becomes 40px from 760px. Sections are full-bleed bands with 64px vertical padding on phones and 96px from 760px; the hero runs 56/72px on phones and 96/112px on desktop.

Band order: paper header, pine hero (textured), paper trust, deep-pine services (textured), paper estimate, pine close, deep-pine footer (textured). Light and dark alternate so each new section is obvious.

Phone first; two breakpoints:
- **760px:** wider gutter and band padding, header grows to 76px, hero buttons sit side by side (min 240px each).
- **1024px:** the trust band splits into two columns (heading and Facebook row left, claims right, 64px gap); service groups go to three columns (48px gap); the estimate band becomes a 1fr / 1.2fr grid with the heading and steps sticky at 40px; the close puts the copy left and the big number right, bottom-aligned.

Rhythm inside sections: 16px between eyebrow, heading and lede; 20px between hero items, steps and form fields; 28px before claims, the Facebook row and the big number; 40px between service groups on phones.

### Named Rules
**The Hover-Needs-A-Pointer Rule.** Every hover style lives inside `(hover: hover)`, so taps never leave a stuck state. Focus styles are always on.

## Elevation & Depth

Mostly flat. Depth comes from the band contrast and the line texture; only three things lift, all with soft pine-tinted shadows, never hard offsets.

### Shadow Vocabulary
- **Row lift** (`box-shadow: 0 6px 18px rgba(19,48,31,.06)`): the white Facebook row on paper.
- **Card lift** (`box-shadow: 0 10px 30px rgba(19,48,31,.07)`): the estimate form card.
- **Float lift** (`box-shadow: 0 10px 28px rgba(8,30,18,.3)`): the floating text circle, which sits over every band.

### The Band Texture
Deep-pine bands, the hero and the footer carry `repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`: a 1px white line every 23px at 3.5% opacity. Ellie's call from the calm band style; it stays at about 4% white or fainter so it never reads as lines through text.

### Named Rules
**The Soft Lift Rule.** Shadows are wide, low-opacity and pine-tinted. Nothing gets a border-plus-shadow or a hard offset.

## Shapes

Soft and borderless. Cards are 24px, fields 10px on a tinted fill with no visible border at rest (a transparent 2px border that takes color on hover, focus and error), buttons, chips and the eyebrow are full pills, and arrow discs, step markers and the floating button are circles. Icons are 2.2–2.6px round-capped line drawings in `currentColor`.

## Components

### Header
- Paper ground, 64px tall (76px from 760px), safe-area aware.
- Wordmark left: "Handy Dev" in Wordmark type over "OCEAN COUNTY, NJ" (system 600, 11px, uppercase, +0.08em, Soft Pine).
- Tap-to-call number right in Cal Sans with an Orange Ink phone glyph; turns Orange Ink on hover. No navigation menu.

### Hero
- Pine band with the line texture. Eyebrow, white Display H1 ending in an orange accent phrase, one promise line in Lead (On Dark Soft, the name bolded in On Dark), then at most two pill buttons: primary "Get a free estimate" and ghost "Text Dev". No call button; the number stays in the header.
- **Bounce-in:** JS splits the H1 into letters inside nowrap word wrappers; each letter slides from 50px right and fades in over 1s on `cubic-bezier(.34,1.56,.64,1)` (the overshoot is the bounce), 20ms apart. The H1 carries an `aria-label` while split; when the last letter lands the plain heading is restored. Hero H1 only.

### Eyebrow Pill
- System 500 14px in a pill (9px 14px) on a 6% pine tint (12% white on dark bands), with a 7px orange dot. Marked up as a `<p>`, never a heading.
- Used sparingly: above the hero H1 and a few key section headings (three on this page), not every section. No arrow, no hover, no shadow, never a full orange fill, so it can't pass for a button.

### Buttons
- **Shape:** full pill (999px), 56px tall, 0 26px padding, Label type, 20px leading icon when present, 2px border.
- **Primary:** Work-Glove Orange fill and border, Pine Ink text. Hover: Hot Orange.
- **Ghost (on pine):** transparent with a 2px Ghost Outline border and On Dark text. Hover: white border and a 10% white wash.
- **Line (on light):** transparent with a 2px Pine Ink border; used for "Copy message".
- **All:** press scales to 0.98; color transitions 0.2s. Inside the form the primary is full-width and its hover/focus adds a 2px Focus Pine outline at 2px offset.

### Claims List
- Three rows, each a 40px Orange Ink line icon and a Claim-size Cal Sans phrase in Pine Ink, 16px vertical padding, 1px light dividers between rows. No cards.

### Facebook Row
- White row, 24px radius (card), min 72px tall, Row lift, max 440px. Facebook Blue 28px mark plus label left; a 44px arrow disc right.
- Hover/focus changes only the arrow disc (to orange); focus rings the disc, not the row.

### Service Rows
- On deep pine, grouped under three Title headings with orange icons. Each row is a full-width link, min 64px, Body Large in On Dark, 1px dark dividers, with a 44px arrow disc on a 10% white tint.
- **Only the arrow changes on hover:** the disc fills orange with Pine Ink arrow; the row itself gets no background, underline or shadow. Focus rings the disc in orange.
- Each row opens a pre-filled text naming its job. A closing line ("Don't see your job? Ask me anyway.") underlines in orange and turns orange on hover.

### Steps
- Numbered list beside the estimate heading: a 44px orange circle with a Cal Sans 19px numeral, a Title Small line in Pine Ink, and a Soft Pine detail line below.

### Estimate Form
- White card, 24px radius, clamp 20–32px padding, 20px gaps, Card lift, max 600px.
- **Labels:** Label type in Pine Ink; "(optional)" in 14px Soft Pine.
- **Inputs:** Field Fill (#e7ece4, pine-tinted; paper was 1.08:1 on the white card), 10px radius, 2px transparent border, 52px min (textarea 120px, vertical resize), 16px system text, Orange Ink caret, Soft Pine placeholder. Hover and focus color the border Focus Pine.
- **Chips:** single-choice radios styled as 48px pills on Paper with a 2px transparent border; hover or keyboard focus colors the border Focus Pine; selected fills Pine Ink with white text. Padding tightens from 18px to 14px under 380px.
- **Errors:** inline Error Red text under the field and an Error Red border; focus jumps to the first bad field; the error clears as soon as the field has text.
- **Submit and fallback:** the full-width primary composes a text and opens messages. If nothing opens after 900ms, a status block (Pine Ink, 600) offers the number and a Line "Copy message" button; if the clipboard is blocked, the message appears selected in a readonly textarea.

### Close
- Pine band: Headline "Handy Dev" with an orange "Dev", a Lead intro, the service-area line, then the Display Phone number with an orange glyph. The number turns orange on hover.

### Footer
- Deep pine with the line texture; On Dark Soft 16px. Name, descriptor, area and number, plus a Facebook link (44px tap target, On Dark, orange on hover). Bottom padding leaves 96px plus the safe area so the floating circle never covers it.

### Floating Text Circle (signature)
- One 60px orange circle with a Pine Ink chat icon, fixed 16px from the bottom-right (safe-area aware), Float lift.
- Slides up from 120px below on `cubic-bezier(.2,.8,.2,1)` over 0.35s once the hero is scrolled away; slides back out while the service rows or the form are on screen, where every row and the form already text Dev. When hidden it is `tabIndex=-1` and `aria-hidden`.
- Removed entirely without IntersectionObserver or with `CONFIG.FLOAT = false`. Never a bottom bar.

### Motion and Fallbacks
- **Fade-up:** content marked to rise moves up 12px and fades in over 0.4s ease-out as it enters (IntersectionObserver, -8% bottom margin). Only elements that start below the first screen are hidden first; everything is visible at rest, without JS, and under reduced motion.
- **Reduced motion:** no smooth scroll, no bounce-in (the H1 is never split), no fade-up, no float slide or button transitions.
- **No JS:** the plain H1 shows, nothing waits at opacity 0, text links keep their bare `sms:` href, and the floating circle shows only once its script runs.

## Do's and Don'ts

### Do:
- **Do** alternate full-bleed bands light and dark: paper, pine, deep pine with the 135° texture at 3.5% white.
- **Do** use Work-Glove Orange as a fill with Pine Ink text on it, and Orange Ink when orange must be text on light.
- **Do** set headings, buttons, labels and phone numbers in Cal Sans 400, and everything else in the system stack at 16px/1.7.
- **Do** keep cards at 24px, fields at 10px on the Field Fill with no visible border at rest, and buttons, chips and eyebrows as full pills.
- **Do** make every action a text or call to Dev; give list items a 44px arrow disc that alone changes on hover.
- **Do** gate hover styles behind `(hover: hover)` and keep tap targets at 44px or more.
- **Do** keep the bounce-in to the hero H1 and keep everything visible without JS and under reduced motion.

### Don't:
- **Don't** put white text on orange or orange text on paper.
- **Don't** add a second webfont, bold Cal Sans, or set body copy in Cal Sans.
- **Don't** use black grounds, gray text, hard offset shadows or border-plus-shadow cards.
- **Don't** put an eyebrow above every section, give it a hover state or arrow, or mark it up as a heading.
- **Don't** add a bottom contact bar or a second floating control; the one circle hides wherever another text control is on screen.
- **Don't** let the line texture get stronger than about 4% white.
- **Don't** apply the bounce-in to any heading other than the hero H1.
