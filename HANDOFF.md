# Jersey colors and floors LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/jerseyColors/ · **Repo:** https://github.com/10elizabethbell/jerseyColors · **Built:** 2026-10-18 from Muse brief (run 2026-10-18, found via NJ contractor Facebook groups) · **Revamped:** 2026-10-19 to the calm band style

## Revamp (2026-10-19): what changed
The business hadn't been contacted yet, so the site was rebuilt end to end under the new house default, the calm band style from lpmr.co.uk (`calm-photo-style.md`). It started from DPG's `index.html`.
- **Look:** the old cream "paint the house" world is gone. The page is now:
  - warm paper (#faf6f1) and the logo's cream (#fbead6) for the light bands
  - mid plum (#45305c) for the hero and closing band, and deep plum (#271a32) with the faint line texture for "How a job goes" and the footer
  - brush gold (#f2b322) as the only accent, used as a fill; #7f5300 when it has to be text on light
  - teal (#0e6470) only for form hover and focus
  - Cal Sans headings, system body text, 24px cards, pill buttons
- **Motion:**
  - The hero H1 bounces in letter by letter and is put back as plain text after about 1.7s.
  - Everything below the first screen does one quiet 12px fade-up.
  - The service rows stagger by 40ms each.
  - A 60px gold text circle appears after the hero and hides while the form is on screen.
  - There's no canvas any more and nothing loops. All of it shows at once under reduced motion and without JS.
- **Structure:**
  - Header: logo mark and wordmark, ES toggle, phone top right.
  - Hero, on plain plum because there are no usable photos: eyebrow "Painting and flooring", H1 "Fresh color and solid floors in Long Branch.", the promise line, then **Get a quote** and an outlined **Text us a photo**. Desktop also shows the full logo on a card.
  - What we do: 5 rows. Tapping one jumps to the form with that job ticked, and the chip gets a brief gold ring.
  - How a job goes: 3 steps.
  - Our work: the latest post's caption on a card, then the big "See more of our work on Facebook" row.
  - Get a quote: the form card on cream.
  - Closing band: the name, "Licensed and insured" plus the area, and the big number.
  - Footer: name, area, phone, Facebook.
- **Form:**
  - Fields: job chips (ticked chips get a check mark), name, town, and optional notes.
  - The submit button is "Text us this request" and it builds the pre-written text.
  - If the messages app doesn't open, the send button is replaced by the message plus **Open in Messages**, **Copy message** and "Or call us at (732) 917-5197". The send button disappears so two send buttons never show together.
- **Spanish:** same EN/ES toggle and `?lang=es` link as before, and the page title now switches too.
- **Truth fixes found in the review:**
  - "Licensed and insured" is no longer the hero eyebrow or in the meta and og descriptions. It's now one clause in the closing band. See Assumptions.
  - Step 2 no longer promises a site visit nobody confirmed. It was "We come take a look… We walk it with you" and is now "We give you a clear quote."
- **og image:** a new 1200×630 shot of the plum hero.

## What's built
One page, `index.html`, single file. The only external resource is Cal Sans from Google Fonts. Phone first: checked at 320, 360, 390 and 430 wide, 844×390 landscape, and 1440, in Chrome and WebKit. There's no sideways scroll, every tap target is at least 44px, and the first screen shows the header number, the H1 and both buttons. All contact goes through `CONFIG.PHONE` (+17329175197). There is no email anywhere because none was found.

## Assumptions I made
- **"Licensed and insured" stays, but quietly.** Muse's brief said don't claim it, because Muse found nothing published. The business's own Facebook page description says "Professional painting & flooring company serving New Jersey. Licensed and insured. High-quality work. HIC License:…" (re-checked 2026-10-19 with the crawler fetch). Their own words make it fair to repeat. But the HIC number is cut off, and NJ expects the HIC number on contractor advertising, websites included. So the claim is one clause in the closing band only, not up top. **Get the HIC number before this goes to the owner**, then add it next to the claim (or move the claim back into the hero eyebrow).
- **Location is Long Branch** (Facebook title "Jersey colors and floors LLC | Long Branch NJ"). The brief's Hammonton address and daily 9–5 hours come from an Instagram pin named "Jersey colors painting company" and may belong to another listing, so neither is shown.
- **Phone (732) 917-5197** comes only from that Instagram pin. The 732 area code fits Long Branch.
- **"We / our" voice**, because they're an LLC crew.
- **Copy the owner should confirm** (written by me, not theirs):
  - the promise line
  - step 2 ("We listen to what you want and tell you plainly what it takes")
  - step 3 ("Floors and furniture covered, clean lines, and we tidy up before we go")
  - the "Big job or small" eyebrow
- **Services** are drawn from Facebook ("painting & flooring"), Instagram ("remodelaciones de casa, pintura") and the latest post ("siding, trim").
- **The Spanish caption** of their post is my translation, labelled "(traducida)".
- **Colours:** the logo's plum, gold and cream mapped onto the calm roles. The logo's orange and teal arches aren't used as page colours (the calm style allows one accent), except teal for form focus.

## Placeholders and gaps
- **No work photos, so no photo hero.** The only group-post image (`src-assets/work-01.jpg`) shows a roof tear-off in progress with workers' faces. It doesn't match the "finished exterior" caption and can't be confirmed as theirs. The other image is Facebook's stock group art. So the hero is the plain textured plum band, which is the calm style's no-photo rule. **Photos are the #1 thing to get.** A wide finished exterior would go straight into the hero under a plum overlay, and the rest into 4:5 work cards above the Facebook row.
- No email, so there's none in the footer.
- No HIC number (see above).
- No reviews, prices, owner name, years in business or hours on the page.
- **Texting is unconfirmed.** "Text us a photo", the circle and the form all open a text. The header number and the closing band are the call path.

## Questions for the owner
- Is (732) 917-5197 right, and does it take texts?
- What's the HIC registration number?
- Can we have 6–10 photos of finished jobs, plus any before/after pairs (same spot)? The Monmouth County exterior first.
- Do you come out to see the job before quoting? Is the quote free? (The page says neither.)
- Is the Hammonton address and Instagram pin yours? Which towns do you want to work in?
- Hours on the site? An email for the footer? Your first name, so the page can say who customers will deal with?
- Which matters most: exterior painting, interiors, or floors?

## Ideas not built (yours to pick)
- **Runner-up signature (opt-in): the paint-the-house hero.** In the original build (git `dd2c66a`), the hero house painted itself coat by coat and you could drag to paint it. It could come back as the hero art on desktop, or below the hero, if you want a living element.
- Other worlds from their trade:
  - hardwood planks that a sanding sweep turns glossy (would give floors a visual presence)
  - a paint-chip fan for the services
  - a wet-brush seam between bands
- **Impeccable findings kept by house rule:**
  - The craft floor bans eyebrows; there are three quiet ones (hero, services, quote).
  - The detector flags the band texture as "repeating stripes" and the warm paper and cream as a "cream palette".
  - The H1 bounce-in, the floating circle and Cal Sans are also house features.
  - The detector ignores are recorded in `.impeccable/config.json` (not committed).
- **From the review, not done:**
  - **Self-host Cal Sans** (it's OFL licensed). That would avoid a render-blocking Google request and a font swap mid-bounce. The skill says Cal Sans comes from Google Fonts, so I left it.
  - **Sticky header with a scroll shadow** (calm kit item 1). DPG doesn't do it either.
  - **Hide the floating circle while the service rows are in view.** It overlaps a row arrow as it passes, but the whole row is the link.
  - Service rows on a plum band (the kit's version) instead of on paper.
  - A View Transition that carries a tapped service row into its form chip.
  - A scroll-driven gold fill on the step numbers.
  - A before/after slider once pairs exist.
- **Desktop logo card:** the finish reviewer called it the weakest part of the desktop first screen (it repeats the header mark). It goes once a hero photo exists.
- Atkinson Hyperlegible for body text, if you ever want it.

## Not verified
- Real-device touch, and the real SMS handoff on iOS and Android, including inside Facebook's in-app browser.
- Clipboard copy inside the FB in-app browser. It falls back to selecting the text and says "Selected, now copy it".
- Form fields are a filled #ebdfd2 on a white card, about 1.2:1. That's the same compromise as DPG; the visible labels identify the fields.
- `.impeccable/config.json` (detector ignore notes) was in two early commits from the first build. It holds only lint reasons, nothing private. `brief.md`, `src-assets/` and `.claude-claimed` were never committed (re-checked 2026-10-19).
