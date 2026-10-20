# Handy Dev — handoff at ~60%

**Live:** https://10elizabethbell.github.io/handyDev/ · **Repo:** https://github.com/10elizabethbell/handyDev (public) · **Built:** 2026-10-08 from Muse brief (brief.md, 2026-10-08) · **Finishing-rules pass:** 2026-10-17 · **Calm-style revamp:** 2026-10-19

## What changed in the 2026-10-19 revamp
The site was rebuilt end to end under the new house default, the calm band style learned from lpmr.co.uk (`calm-photo-style.md`), starting from DPG Home Improvement's page. Dev hasn't been contacted, so nothing from the old look was kept for continuity's sake.
- **Gone:** the seasonal-yard canvas world. That was the mower hero you could drive, swaying grass, kickable leaves, the snow band with a drift to dig through, and the snowbank dividers, about 400 lines of canvas code. The old build is commit `9a51e2d` if you want any of it back.
- **Look:** paper, pine and deep-pine bands alternate down the page, with the faint diagonal line texture on the dark ones. Work-glove orange is the one accent and is used as a fill; text on it is deep pine. Headings are Cal Sans, body is the system stack at 16/1.7, buttons are pills, and the form is a 24px card.
- **Hero:** a plain textured pine band (no photos exist). Its contents are an eyebrow pill ("Handyman & property maintenance"), the H1 "Small jobs, big impact in Ocean County." (his tagline with the place in it) bouncing in letter by letter, "I'm Dev. If it needs fixing, cleaning, or maintaining, I can help.", and two buttons: **Get a free estimate** (orange, jumps to the form) and **Text Dev** (outlined, opens a pre-filled text).
- **New structure:** hero, then "I leave it better than I found it." with his flyer's three promises and the Facebook row, then all 17 services as rows on deep pine in three groups, then the estimate form with "How it works" as three steps beside it, then a pine close with his own intro line and the big number, then the footer.
- **New: estimate form.** It asks for name, the job, town (optional) and when (optional). It turns them into a text to Dev and shows "Didn't open your messages? Call or text me at…" in case nothing opens. Inline errors are written as plain sentences.
- **New: floating text circle** at the bottom right. It appears after the hero and hides while the form is on screen.
- **Motion:** the H1 bounce-in, a 12px fade-up for things below the first screen, and the circle's slide. Everything shows at once with reduced motion on or JS off.
- **Unchanged facts and wiring:** the same phone number, the same per-service pre-filled texts (each row names its job), the same Facebook profile link, and no email.
- **Icons:** the favicon, home-screen icon and og image were redrawn in the new palette. The og image is the hero line on pine with the number.

## What's built
- One static `index.html` (inline CSS/JS, about 30KB, no frameworks, no tracking), plus `icon.svg`, `apple-touch-icon.png` and `og.png`. GitHub Pages serves `main`.
- **Contact:** the number appears once on the first screen, as a tap-to-call link in the header's top right. There's no Call button in the hero. The close section and footer repeat the number. Text paths are the hero "Text Dev" button, every service row, the form, and the floating circle; the circle never shows beside the form.
- **Facebook:** a white "See more of my work on Facebook" row under his promises, which stand in for proof since there are no photos or reviews, plus a footer link.
- Tunables: `CONFIG.PHONE` and `CONFIG.FLOAT` at the top of the script; colors are tokens in `:root`.

## Assumptions I made
- **Colors:** there's no logo or brand color. Pine (#1f4a33, deep #13301f) takes the calm style's "navy" role and work-glove orange (#f28c28) is the accent, both carried over from the first build so the "HD" icon stays recognizable. Orange as text on light uses #9a4a00 (5.8:1).
- **Audience is not treated as 40+.** The brief doesn't say who his customers are. Ocean County has many retirees, though, so this is the top open question (below).
- **The H1 is his tagline reworked** to "Small jobs, big impact in Ocean County." so the place is in it.
- **Copy that's mine, built from his words:** "I leave it better than I found it." and its lede paraphrase his post. "Fix it. Mow it. Shovel it." is my services heading. The group names ("Around the house", "Yard and outside", "Snow and storms") and the three steps are mine. "You deal with me, Dev, from the first text to the last" assumes he works alone, which his post and personal number suggest but don't say outright.
- **The form's town placeholder** is "e.g. Toms River", a real Ocean County town used only as an example. It doesn't claim he works there.
- **Facebook** links his *personal* profile (profile.php?id=100055236912581), the only one in the brief.

## Placeholders and gaps
- No logo, work photos, before/afters, reviews, town list, hours or email, so there's no footer email and no photo cards.
- The flyer image sits behind a Facebook group login and couldn't be fetched.

## Questions for Ellie
- **Older audience?** If his customers skew 40+, `older-audience.md` says to drop the bounce-in and fade-up (two deletions in the script) and raise body text to 18–20px. I kept the calm-style motion because the brief doesn't say.
- **Desktop hero right side is empty** (as on DPG). It could hold a photo of Dev or his work once he sends one.

## Questions for the owner
- Which towns do you cover?
- Any photos of past jobs, especially before/after (yard cleanups, power washing, gutters)? A photo of you?
- Is it OK to link your personal Facebook, or is there a business page?
- Hours? Do you want texts with photos?
- Which jobs do you most want more of? They go first in each list.
- A logo or color you use (truck, shirt, flyer)? It would replace the pine/orange and the "HD" icon.
- Is there an email you want in the footer?

## Ideas not built (yours to pick)
- **Signature motion, opt-in:** the old mower hero (commit `9a51e2d`) could come back as the hero's living element. Runner-up world: a pegboard workshop whose tools swing when you sweep past.
- Season-aware ordering: from December to March, put "Snow and storms" first.
- Photo cards (4:5 with gradient and title) with the Facebook row under them, once real photos exist.
- Impeccable findings kept against its advice because Ellie chose them: eyebrow pills, the H1 letter bounce-in, the floating circle, Cal Sans, the band texture.

## Not verified
- Real SMS handoff (`sms:+16094679972?&body=`) on iOS and Android, and in Facebook's in-app browser. Playwright confirmed the composed bodies decode correctly.
- The Facebook link preview using `og.png`.
- Real-device touch. Headless Chromium and WebKit at 360/390/430 checked layout, overflow, the bounce-in, the circle and the form flow.
