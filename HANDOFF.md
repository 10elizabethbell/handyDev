# Handy Dev — handoff

**Live:** https://10elizabethbell.github.io/handyDev/ · **Repo:** https://github.com/10elizabethbell/handyDev (public) · **Built:** 2026-10-08 from Muse brief (brief.md, revised by Muse 07:37 that morning) · **Finishing-rules pass:** 2026-10-17

## What's built
- One static `index.html` (inline CSS/JS, no frameworks, no tracking), plus `icon.svg`, `apple-touch-icon.png` and `og.png`. GitHub Pages serves `main`; every push is live in about a minute.
- **World:** a South Jersey yard through the seasons. Dusk-to-pine autumn hero, sage services band, slate winter band, snow-white "How it works", pine close. Work-glove orange is the action color and the brand accent.
- **Hero, "do the job":** a push mower mows the lawn along the bottom of the hero by itself, throwing clippings, and the grass grows back. Touch or mouse over the hero and it follows you. On phones, a drag in the lawn band mows in any direction instead of scrolling (`.mow-zone`, `touch-action: none`; the page turns off pull-to-refresh). Tunables: `MOW_*` and `REGROW` at the top of the `Field` IIFE.
- **Living page:** one canvas renderer (`Field`) used five times. Swaying grass whose front blades are the next section's color, falling leaves you can kick, snowfall and a drift you can dig through, and a snowbank edge into winter. One shared animation loop, paused off screen, still frame under reduced motion, fewer particles on phones. Text has a soft glow in its section's ground color so leaves and snow never cross it.
- **Copy:** Dev's own words lead. The headline is his tagline "Small jobs. Big impact.", followed by "If it needs fixing, cleaning, or maintaining, I can help." His flyer line closes the page, and his intro post is quoted in full. The rest is in his first-person voice and about how he treats people.
- **Contact:** the number appears once on the first screen, as a tap-to-call link in the header's top right. There's one orange "Text for a free estimate" button in the hero and one in the close. Every service row opens a pre-filled text naming that job. There are no Call buttons and no sticky bar. The number appears again only in the footer.
- **Facebook:** a "See more of my work on Facebook" pill under Dev's quote (the page's only proof), plus a footer link.

## Assumptions I made
- **Colors:** no logo or brand colors exist. Pine/sage/slate come from the yard world, and orange stands in for work gloves and fall leaves.
- **Favicon and home-screen icon** are the site's own "HD" lettering, because no logo exists.
- **Step copy** paraphrases his post in his voice: "You'll be dealing with me, Dev, from the first text to the last" assumes he works alone, which his post and his personal phone number suggest but don't say outright. "A photo helps" assumes he takes photos by text.
- **"Fix it. Mow it. Shovel it."** (the services heading) is my copy.
- **Facebook link** goes to his *personal* profile (profile.php?id=100055236912581), the only one in the brief. Non-friends may see little there. Confirm he wants it linked, or swap in a business page.
- **Service names** are the brief's: "trimming" and "edging" are merged into one row, and "Doors" texts "door repair".
- **Light-on-dark:** the dark hero was picked for a phone in hand at the end of the day.

## Placeholders and gaps
- No logo, no work photos, no before/afters, no reviews, no town list, no hours, no email (so no footer email).
- The flyer image sits behind a Facebook group login and couldn't be fetched.

## Questions for Ellie
- **Older audience?** Ocean County has a lot of retirees. If his customers skew 40+, the finishing rules say nothing should move: the mower, grass, leaves and snow would become a still picture. I left it animated because the brief doesn't say.

## Questions for the owner
- Which towns do you cover?
- Any photos of past jobs, especially before/after (yard cleanups, power washing, gutters)?
- Is it OK to link your personal Facebook, or is there a business page?
- Do you want texts with photos? Hours?
- Which jobs do you most want more of? They go first in each list.
- A logo or color you use (truck, shirt, flyer)? It would replace the "HD" icon.
- Is there an email you want in the footer?

## Ideas not built (yours to pick)
- **Runner-up world: a pegboard workshop.** Tools swing on their hooks when you sweep past.
- **Season-aware hero:** from December to March the mower becomes a snow shovel clearing a drift (same `Field`).
- Snow flying out of the trench when you dig the drift; kickable resting leaves on the services band.
- Before/after sliders and a work-photo strip (with the Facebook link moved directly under it) once real photos exist.

## Not verified
- Real-device touch: mowing, pushing grass and leaves, digging the drift. Headless tests confirmed the mower mows on its own and follows a simulated finger drag (up/down and sideways) in the lawn band.
- The real Facebook in-app browser, including the link preview using `og.png`.
- Real SMS handoff (`sms:+16094679972?&body=`) on iOS and Android.
- Frame rate on older phones.
