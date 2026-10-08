# Handy Dev — handoff at ~60%

**Live:** https://10elizabethbell.github.io/handyDev/ · **Repo:** https://github.com/10elizabethbell/handyDev (public) · **Built:** 2026-10-08 from Muse brief (brief.md, revised by Muse 07:37 that morning)

## What's built
- One static `index.html` (inline CSS/JS, no frameworks, no tracking, no external requests). Drop the file on Netlify Drop and it works.
- **World:** a South Jersey yard through the seasons. Dusk-to-pine autumn hero, sage services band, slate winter band, snow-white "How it works", pine close. Work-glove orange is the only action color.
- **Signature element:** one canvas renderer (`Field`) used five times. Swaying grass whose front blades are the next section's color, so each section grows up into the one above. Falling leaves that settle in the grass and get kicked loose by mouse or finger. Snowfall plus a snow drift you can dig a trench through (it fills back in). Blades part around the pointer and spring back with a wobble. One shared animation loop, paused off screen, still frame under reduced motion, fewer blades and particles on phones.
- **Sections:** hero (Dev's own tagline "Small jobs. Big impact.", the brief's "Handy Dev — Handyman & Property Maintenance", his "If it needs fixing, cleaning, or maintaining, I can help." and flyer line "Reliable work. Fair pricing. Free estimates."), services in three groups (Handyman / Outdoor & Yard / Winter), How it works (text or call → free estimate → job done right), service area (Ocean County, NJ), closing call with Dev's intro post quoted word for word, footer with "Demo one-pager — free sample."
- **Contact:** every service row is a text link with a pre-filled message naming the job ("…free estimate for gutter cleaning. Town: When:"). Hero/close buttons send a generic estimate request. Call buttons use `tel:+16094679972`. On phones a sticky "Text for a free estimate" bar shows only while the hero and closing buttons are off screen. On desktop, the hero's right column previews the exact text that gets sent.
- Tunables are named at the top of the `Field` IIFE (`WIND_SPEED`, `BLADE_GAP`, `PUSH_RADIUS`, `SPRING`, ...) and per band in the `Field(...)` calls at the bottom (blade heights, colors, leaf/flake counts).

## Assumptions I made
- **Colors:** no logo or brand colors exist. Pine/sage/slate come from the yard-and-seasons world. Orange stands in for work gloves, safety gear and fall leaves, and it's the one action color.
- **Headline and voice:** the headline, pitch line and closing quote are Dev's own words (intro post and flyer, 2026-10-05). "Fix it. Mow it. Shovel it." is my copy and heads the services list. The page mixes his first-person lines with "Text Dev" elsewhere; pick one voice if it bothers you.
- **"Past few years"** is his own claim, from his post.
- **Group sub-lines** ("Fix-ups and small jobs around the house", "When it snows, Dev clears it") and the step copy are mine, paraphrasing only the brief's facts. "A photo of the job helps" assumes he's happy to receive photos by text.
- **Service names** are the brief's, lightly regrouped: "trimming" and "edging" merged into one row, and "doors" shown as "Doors" with the SMS body saying "door repair".
- **Tone:** casual, first-name ("Text Dev"), since he introduced himself personally in a Facebook group.
- **Light-on-dark:** the hero is dark, picked for a phone in hand at the end of the day. Not based on anything Dev said.

## Placeholders and gaps
- No logo: "HANDY DEV" is set as a wordmark.
- No photos of his work at all. The page has no proof section; the motion and type carry it. **Photos wanted.**
- No town list, no hours, no reviews, no prices (correctly absent from the page).
- His Facebook is a personal profile (not viewable publicly), so there's no social link in the footer.
- The flyer image sits behind a Facebook group login and couldn't be fetched, so its colors are unknown.

## Questions for the owner
- Which towns do you cover, and how far will you drive? (A town list would beat the "Ocean County, NJ" blanket.)
- Any photos of past jobs, especially before/after (yard cleanups, power washing, gutters)? The before/after slider module is ready to add.
- Do you want texts with photos? Best times to reach you, and hours?
- Which jobs do you most want more of? They should go first in each list.
- Do you have a logo or a color you like (truck, shirt)?
- Is there a Facebook page to link?

## Ideas not built (yours to pick)
- **Runner-up world: a pegboard workshop.** Tools hang on hooks and swing on their pins when you sweep past them. It's more "handyman", less "property maintenance". The roll's pick, a sawdust workbench, was the other alternative.
- **Season-aware hero:** the hero swaps to snow + drift from December to March (same `Field`, different options).
- Leaves pushed hard enough could pile up against the services edge (Ellie's "break free" bonus in reverse).
- `book.html` booking-form page composing the same pre-filled text.
- Before/after sliders once real photos exist.
- A "power washing" proof strip: a grimy-to-clean wipe the visitor drags, but only with Dev's real photo.
- Review suggestions not built: snow flying out of the trench when you dig the drift, a few kickable resting leaves on the sage services band so the pointer does something there, and a white crest on the sage→slate edge so it reads as snow, not water.

## Not verified
- Real-device touch (finger pushing grass/leaves/drift) on iOS and Android. Only simulated mouse moves were tested headlessly. Pixels changed during the sweep, but wind moves them too, so the sweep doesn't prove the push effect on its own.
- The phone layout was designed and checked at 360/390px, including a 360×640 first screen (roughly Facebook's in-app browser height). Never opened in the real Facebook in-app browser.
- Real SMS handoff: `sms:+16094679972?&body=` should open Messages pre-filled on iOS and Android; not tested on a phone.
- Frame rate on older phones (the hero draws ~250 blades + 10 leaves per frame on phones).
- The sticky bar's show/hide on a real scroll.
