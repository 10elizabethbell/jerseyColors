# Jersey colors and floors LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/jerseyColors/ · **Repo:** https://github.com/10elizabethbell/jerseyColors · **Built:** 2026-10-18 from Muse brief (run 2026-10-18, found via NJ contractor Facebook groups)

## What's built
- One page, `index.html`, phone-first, bilingual: an **EN/ES toggle** sits in the header. Spanish shows automatically for Spanish-language phones and with `?lang=es`, so you can send the owner a Spanish link.
- **World:** the logo's own world. Cream ground sampled from the logo, plum roofline, gold brush, orange/gold/teal arches, clapboard siding. Sections in plum and teal are joined by ragged wet-brush seams that brush in as you scroll.
- **Signature element:** the hero house paints itself, one coat per color: teal, then gold, orange and cream, on a loop. You can drag a finger in any direction (or move a mouse) to take the brush, and the four swatches change the color. After about 3 seconds idle the brush carries on. After a good amount of your own painting, the hint changes to "Looking sharp." ("¡Quedó impecable!"), echoing their post.
- **Sections:** header (logo mark + wordmark, ES, tap-to-call number top-right) → hero (headline, promise, **Get a quote** + outlined **Text us a photo**) → What we do (5 rows, each opens a pre-filled text for that service) → How a job goes (3 steps) → Our work (their latest post, then a big Facebook button right under it) → Get a quote form → closing name block → footer (name, phone, Facebook).
- **Quote form:** name, job chips, town, when, notes. It builds a pre-filled text to (732) 917-5197, and shows the message with a **Copy message** button and an "Or call us" link in case `sms:` is blocked.
- Icons (favicon, iPhone home-screen icon) are cut from the real logo. The og image (1200×630) is a shot of the hero mid-paint.

## Assumptions I made
- **Location is Long Branch, not Hammonton.** Their Facebook page (og meta, fetched 2026-10-18) says "Jersey colors and floors LLC | Long Branch NJ". The brief's Hammonton address, hours (daily 9–5) and phone came from an Instagram location pin named "Jersey colors painting company", which may be another listing. I left the address and hours off the page.
- **"Licensed and insured" is on the page.** The brief said not to claim it because nothing was published. But their own Facebook page says "Professional painting & flooring company serving New Jersey. Licensed and insured. High-quality work. HIC License:…", so the brief's reason no longer holds. It's one line in the closing section, easy to cut.
- **Phone (732) 917-5197** comes only from that Instagram pin. A web search found no other listing. The 732 area code fits Long Branch, so I used it.
- **"We / our"** voice, because they're an LLC crew and post as a company.
- **Copy I wrote and the owner should confirm:**
  - the promise ("We treat your house like it's our own: everything covered, every edge clean…")
  - step 2 ("We come take a look… give you a clear quote")
  - step 3 ("Floors and furniture covered… we clean up before we leave")
- **Services** are drawn from the Facebook ("painting & flooring"), the Instagram self-description ("remodelaciones de casa, pintura") and the latest post ("siding, trim"): interior painting, exterior painting, siding & trim, floors, home remodeling.
- **"Our work" quote** is their post caption, verbatim with the 🏠. The Spanish version is my translation and is labelled "(traducida)".
- **Font:** system stack with `ui-rounded`, so iPhones get SF Pro Rounded (close to the logo lettering) and Android gets the system heavy sans.

## Placeholders and gaps
- **No work photos.** The only group-post image (`src-assets/work-01.jpg`) shows a roof tear-off in progress with workers' faces visible. It doesn't match the "finished exterior" caption, and its upload ID is older than their page, so I couldn't confirm it's theirs and left it out. The second post's image was Facebook's stock group illustration. "Our work" is the caption plus the Facebook button for now. **Photos are the #1 thing to get.**
- No email (none found), so there's none in the footer.
- No HIC registration number: Facebook truncates it after "HIC License:". NJ expects it on contractor ads, websites included, so get it and add it to the closing line.
- No reviews, prices, owner name, or years in business, and nothing about them on the page.
- **Texting is unconfirmed.** "Text us a photo", the service rows and the form all open a text. The number in the header is the call path.
- No Google Maps listing.

## Questions for the owner
- Is (732) 917-5197 right, and does it take texts?
- What's the HIC registration number?
- Can we have 6–10 photos of finished jobs, plus any before/after pairs (same spot)? The Monmouth County exterior first.
- Is the Hammonton address/Instagram pin yours? Which towns do you want to work in?
- Do you come out to look before quoting, and is the quote free? I avoided saying "free".
- Which matters most to you: exterior painting, interiors, or floors?
- Do you want hours on the site?
- An email for the footer?
- What's your first name, so the page can say who they'll deal with?

## Ideas not built (yours to pick)
- **Floors have no visual presence** (finish reviewer's note): half the name and the headline's second line. Options:
  - a hardwood-plank ground for the quote section, with a sanding sweep that turns dull boards glossy as you drag (the runner-up world);
  - or a seam that's a floor edge instead of a brush edge.
- Once photos arrive, put them in "Our work" framed as paint-chip cards or inside the house's windows, with before/after sliders (plain divider) if pairs exist.
- **Overdrive:** when a coat finishes, shutters/door tint to the next swatch.
- **Delight:** a little "dip" wiggle of the brush when a swatch is tapped.
- Logo-style soft 3D on the arches (they're flat bands with a soft drop shadow now).
- Tunables are at the top of the hero script:
  - `AUTO_SPEED` (560)
  - `ROW` (20)
  - `BRUSH_W` (32)
  - `IDLE_RESUME` (3200 ms)
  - `PASS_PAUSE` (900 ms)
  - `REWARD_AT` (2600)
- Atkinson Hyperlegible or a self-hosted rounded face if you ever drop the system-font rule.

## Not verified
- Real-device touch (tested only with synthetic pointer events in headless Chrome at 320/360/390/430/1024/1440: vertical and sideways drags paint).
- The real SMS handoff on iOS and Android, and inside Facebook's in-app browser.
- Clipboard copy inside the FB in-app browser (it falls back to selecting the text).
- Frame rate on old Android phones (spring runs in fixed substeps, DPR capped at 1.75, loop pauses off-screen).
- WebKit/Safari rendering (only Chrome was run).
- Detector notes: Impeccable's detector ran in its normal (non-degraded) mode. Three findings were left standing as false positives or deliberate choices: the hint text over the lawn, the cream ground (the logo's own), and the hairline above the service rows.
- `.impeccable/config.json` (detector ignore notes) was in two early commits before I untracked it. It holds only lint-ignore reasons, no prospect notes, and `brief.md`, `src-assets/` and `.claude-claimed` were never committed.
