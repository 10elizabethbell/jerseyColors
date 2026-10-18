---
name: Jersey colors and floors LLC
description: Single-page phone-first site for a New Jersey painting and floors crew, built in the logo's colors around a house the visitor can paint.
colors:
  plum: "#33223f"
  plum-deep: "#271a31"
  orange-deep: "#b9520a"
  orange-text: "#a34606"
  gold: "#f2b322"
  teal: "#0e5a64"
  teal-ink: "#0b4b54"
  cream: "#fcebd7"
  paper: "#fff8ee"
  ink: "#2b1f33"
  ink-soft: "#5c4a63"
  on-plum-soft: "#e9d6e8"
  line: "rgba(51,34,63,.16)"
  field-border: "rgba(51,34,63,.28)"
  focus: "#0e5a64"
  paint-teal: "#3f8c91"
  paint-gold: "#e8b03a"
  paint-orange: "#d8703a"
  paint-cream: "#f3e4cc"
  floor-brown: "#8a5a35"
  arch-orange: "#dd6e14"
  roof-plum: "#3a2a40"
  trim-cream: "#f7ecdc"
  lawn: "#4f6a2c"
  step-orange: "#e9884a"
  step-teal: "#7fc1c0"
  quote-highlight: "#ffd36b"
  on-teal-soft: "#cfe3e2"
  on-plum-muted: "#c9b7c9"
  placeholder: "#7d6b80"
  error: "#9a2b0c"
  error-line: "#b33a12"
  paint-bead: "rgba(0,0,0,.2)"
  hint-shadow: "rgba(20,28,8,.8)"
typography:
  display:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "clamp(46px, 14vw, 104px)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "clamp(34px, 9vw, 60px)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  title:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "clamp(22px, 6.2vw, 32px)"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "-0.01em"
  quote:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "clamp(24px, 6.6vw, 40px)"
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: "-0.01em"
  body:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "16px"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "0.03em"
  button:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "17px"
    fontWeight: 900
    lineHeight: 1.12
    letterSpacing: "0.02em"
  display-close:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "clamp(38px, 11vw, 84px)"
    fontWeight: 900
    lineHeight: 0.98
  quote-desktop:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "clamp(24px, 3.6vw, 52px)"
    fontWeight: 800
    lineHeight: 1.15
  step-title:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "clamp(22px, 6vw, 28px)"
    fontWeight: 900
    lineHeight: 0.98
  promise:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.55
  wordmark:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "21px"
    fontWeight: 900
  wordmark-sub:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "10.5px"
    fontWeight: 800
  wordmark-sub-tablet:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "11px"
    fontWeight: 800
  phone-small:
    fontFamily: "ui-rounded, \"SF Pro Rounded\", system-ui, -apple-system, \"Segoe UI\", sans-serif"
    fontSize: "14px"
    fontWeight: 900
  small:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 700
  lead:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 400
rounded:
  pill: "999px"
  panel: "18px"
  field: "14px"
  mark: "10px"
  inner: "12px"
  focus: "6px"
spacing:
  gutter-phone: "16px"
  gutter-tablet: "28px"
  gutter-desktop: "40px"
  field-gap: "20px"
  tap: "44px"
  container: "1180px"
components:
  button-primary:
    backgroundColor: "{colors.orange-deep}"
    textColor: "{colors.paper}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "10px 24px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "#a24707"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.plum}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "10px 24px"
    height: "56px"
  button-ghost-hover:
    backgroundColor: "{colors.plum}"
    textColor: "{colors.cream}"
  button-facebook:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.teal-ink}"
    rounded: "{rounded.pill}"
    padding: "10px 22px"
    height: "60px"
  button-facebook-hover:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.plum}"
  input:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "14px 16px"
    height: "54px"
  chip:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.plum}"
    textColor: "{colors.cream}"
  service-row-arrow:
    backgroundColor: "rgba(51,34,63,.08)"
    textColor: "{colors.plum}"
    rounded: "{rounded.pill}"
    size: "44px"
  service-row-arrow-hover:
    backgroundColor: "{colors.orange-deep}"
    textColor: "{colors.paper}"
  step-number:
    textColor: "{colors.plum}"
    size: "56px"
  swatch:
    rounded: "{rounded.pill}"
    size: "44px"
---

# Design System: Jersey colors and floors LLC

## Overview

**Creative North Star: "The Logo's Own Street"**

Everything on the page comes out of the client's Facebook logo: a cream ground, a thick rounded plum roofline, a gold brush, orange/gold/teal rainbow arches, clapboard siding and a green lawn. The hero is that house drawn in canvas, and a visitor can paint it. Under the hero the page is a stack of flat full-bleed color bands (cream, plum, teal, cream, plum). Wet, ragged brush edges join the bands, never straight lines. Type is heavy, uppercase and rounded, the same weight as the logo's wordmark.

Single file (`index.html`), no framework, no webfonts, no tracking. It is built for a phone inside Facebook's in-app browser. Desktop keeps the same flow and puts the copy on the left with the house on the right.

**Key Characteristics:**
- Logo palette only. The page ground is never black.
- Heavy uppercase system display type (weight 900) over plain system body text.
- Flat color bands joined by generated brush seams.
- Pills and organic blobs. No square cards, no card grid.
- One live signature, the paintable house. Everything else is quiet.

## Colors

A warm, saturated logo palette on a cream ground. Plum carries text and the dark bands, and orange is the action color.

### Primary
- **Brushed Plum** (`plum`): headlines on cream, the "How a job goes" and closing bands, ghost-button stroke, selected chips. **Plum Deep** (`plum-deep`) is used only for the footer.
- **Burnt Orange** (`orange-deep`): the one filled action color (primary buttons, the hovered row arrow). **Orange Text** (`orange-text`) is the darker orange for orange type on cream (the second line of the headline, the wordmark subline, the header phone icon). Use it for any orange text. `orange-deep` is only for fills.

### Secondary
- **Arch Teal** (`teal`): the "Our work" band. It is also the focus color (`focus`) and the caret color. **Teal Ink** (`teal-ink`) is the text on the cream Facebook button.

### Tertiary
- **Brush Gold** (`gold`): text selection, the gold half of the closing headline on plum, Facebook-button hover, the first step number. On teal, the quote highlight uses a lighter gold (#ffd36b).

### Paint key (service colors)
A fixed color for each service, repeated as the row dot, the form chip dot and the hero swatch. Keep the mapping when you edit:
- Interior painting = `paint-teal`, Exterior painting = `paint-gold`, Siding & trim = `paint-orange`, Floors = `floor-brown`, Home remodeling = `plum`.
- Hero swatches: `paint-teal`, `paint-gold`, `paint-orange`, `paint-cream`.
- Step numbers: gold, #e9884a, #7fc1c0 (one each, in that order).

### Scene colors
Used only in the canvas and seams: `arch-orange` / `gold` / #1d6b74 for the arches, `roof-plum` for the roof, shutters, chimney and bristle base, `trim-cream` for trim, corner boards, frames and the vent ring, and `lawn` for the bottom of the lawn gradient (#93a95a to #6f8a3e to `lawn`). The first seam starts from `lawn`.

### Neutral
- **Logo Cream** (`cream`): page ground, the hero sky, the services and quote bands, and the theme-color. It is sampled from the logo.
- **Paper** (`paper`): input, chip and success-panel fills, and text on orange.
- **Ink** (`ink`) / **Ink Soft** (`ink-soft`): body text and secondary text on cream (promise, help, "(optional)").
- **On-plum Soft** (`on-plum-soft`): paragraph text on plum bands. On teal the cite uses #cfe3e2, and the footer body text is #c9b7c9.
- **Line** (`line`): hairlines between service rows. **Field Border** (`field-border`): resting stroke on inputs and chips.
- Errors: #9a2b0c for message text, #b33a12 for the invalid field border.

**The Logo Palette Rule.** Every new color has to come from the logo's plum, orange, gold, teal, cream or lawn, or be a tint or shade of one of them. No black ground, no gray UI chrome.

**The Two Oranges Rule.** `orange-deep` is for fills and `orange-text` is for type on cream. Don't put `arch-orange` behind text.

## Typography

**Display Font:** `ui-rounded` (SF Pro Rounded on Apple devices), falling back to the system heavy sans.
**Body Font:** system-ui stack (`-apple-system`, Segoe UI, Helvetica Neue, Arial).

**Character:** Rounded, very heavy uppercase that echoes the logo wordmark, set tight (line-height .98, -.02em) over a plain, readable system body.

### Hierarchy
- **Display** (900, clamp(46px,14vw,104px), .98, uppercase): the hero headline only. It breaks into two lines, plum then `orange-text`.
- **Closing display** (900, clamp(38px,11vw,84px)): the business name in the plum closing band, with its second half in gold.
- **Headline** (900, clamp(34px,9vw,60px), .98, uppercase): every section h2.
- **Title** (900, clamp(22px,6.2vw,32px), 1.05, uppercase): service row names. Step titles use clamp(22px,6vw,28px).
- **Quote** (800, clamp(24px,6.6vw,40px), 1.15, sentence case): the latest-post quote in the teal band. It grows to clamp(24px,3.6vw,52px) at 1024px and up.
- **Body** (400, 17px, 1.55): all running text. The hero promise uses clamp(17px,4.6vw,20px) at 34ch, step text 40ch, closing text 18px at 42ch.
- **Label** (800, 16px, 1.2, uppercase, .03em): form labels and the legend. "(optional)" drops to body 14px, not uppercase, in `ink-soft`.
- **Button** (900, 17px, 1.12, uppercase, .02em). The send button uses 18px.

**The System Font Rule (owner).** No webfonts, ever. Display type is `ui-rounded` with a system fallback. On non-Apple devices it falls back to plain system heavy. That is accepted, so don't add an `@font-face` to fix it.

**The Heavy Caps Rule.** Display, headline, title, label and button text are uppercase in the display stack at 800-900. Body and inputs stay in sentence case in the body stack.

## Layout

- **Container:** `.wrap` is 1180px max with side gutters of 16px (phone), 28px (600px and up) and 40px (1024px and up).
- **Breakpoints:** 600px (CTAs side by side, steps in 3 columns, seams 48px, the ES toggle reads "Español"), 1024px (two-pane hero, services in 2 columns, quote form in a 5fr/7fr grid), plus small-phone fallbacks at 380px and below (smaller hint) and 350px and below (no wordmark subline, no phone icon, no hint).
- **Band rhythm:** about 36-44px top padding and 52-60px bottom. Order is hero (cream sky, lawn at the bottom), services (cream), how (plum), work (teal), quote (cream), close (plum), footer (plum-deep).
- **Hero:** on a phone, the copy block stacks over the scene, which is clamp(340px,100vw,440px) tall. On desktop the hero is min(820px, 100svh - 64px) tall, the scene fills it from behind, and the copy sits left at max min(640px,44vw) on clear cream sky.
- **Tap targets:** 44px minimum everywhere (header items, footer links, swatches, row arrows). Buttons are 56px and chips 48px.
- **Form:** one column at max 560px, 20px between fields.

## Elevation & Depth

The bands are flat and depth lives in the illustration. UI shadows are soft and colored, always blurred with a negative spread and never offset hard.

### Shadow Vocabulary
- **Orange lift** (`0 8px 18px -10px rgba(185,82,10,.8)`): primary buttons only.
- **Dark lift** (`0 10px 22px -12px rgba(0,0,0,.6)`): the Facebook button on teal.
- **Swatch drop** (`0 4px 10px -4px rgba(20,12,24,.55)`). Selected adds a cream halo: `0 0 0 3px var(--cream), 0 6px 14px -4px rgba(20,12,24,.6)`.
- **Paint bead** (`inset 0 -2px 3px rgba(0,0,0,.18)`): row dots and chip dots read as drops of paint.
- **Focus glow** (`0 0 0 3px rgba(14,90,100,.22)`): inputs and chips on hover and focus.
- **Hint legibility** (`text-shadow: 0 1px 3px rgba(20,28,8,.8)`): cream "Drag to paint" text over the lawn.

**The Flat Bands Rule.** Section backgrounds never get gradients, textures or shadows. The canvas is the only rendered surface.

## Shapes

- **Pills** (`pill`) for every button, chip, swatch and row arrow.
- **Organic blobs:** row dots (`50% 46% 52% 48%`) and step numbers (`52% 48% 50% 46%`) are slightly uneven circles, like dabs of paint. Keep them uneven.
- **Soft rectangles:** fields at `field`, the success panel at `panel` (its message box at 12px), the brand mark at `mark`, and the focus ring outline at 6px.
- **Brush seams:** ragged horizontal edges between bands (see Components). Bands never meet on a straight line.
- **Strokes:** buttons 2.5px, fields and chips 2px, focus outline 3px with a 3px offset.

## Components

### Header
Not sticky (`position: relative`). On cream: brand mark (42px, `mark` radius) plus a two-line wordmark ("JERSEY" 900 21px/24px in `ink`, "COLORS AND FLOORS" 800 10.5px/11px in `orange-text`). Then the language toggle (800 14px, `ink-soft`, underlined, teal on hover, "ES" on phones and "Español" at 600px and up), then the tap-to-call number (900 15.5px, 18px on desktop, `plum`, phone icon in `orange-text`, orange on hover). The wordmark subline belongs to the logo lockup and is not a style for section labels.

### Buttons
- **Primary:** `button-primary` with a 2.5px border in its fill color, the orange lift shadow, and an optional 20px inline SVG icon. It moves down 1px on active.
- **Ghost:** transparent with a 2.5px plum stroke, filling plum with cream text on hover.
- **Facebook:** cream pill on teal with the Facebook glyph (24px). It fills gold with plum text on hover and becomes inline-flex at 1024px and up.
- **Hero CTAs:** stacked full width on phones, side by side at 600px and up. Get a quote is primary, Text us a photo is ghost.
- **Send:** a full-width primary button. On hover and focus it gets the 3px teal outline (form rule).
- Transitions: color properties .2s, transform .15s.

### Service rows
Full-width `sms:` links in a list with `line` hairlines (2 columns with a 60px gap at 1024px and up, each row with its own top rule). The row is a paint-key dot (16px), the uppercase title, and a 44px round arrow. Rows are 72px tall, 84px on desktop.
**The Arrow-Only Rule (owner).** Hover and focus never tint, outline or shadow the row. Only the arrow responds: it fills `orange-deep` with `paper` icon and moves `translateX(3px)`, and on keyboard focus the 3px teal outline goes on the arrow.

### Steps
A numbered list on plum, one column on phones (56px number spanning two rows next to the title and text) and three equal columns at 600px and up (number above). The number is a 56px organic blob in a step color with a 900 28px plum numeral. Titles are uppercase in cream, text in `on-plum-soft`.

### Chips and form
- **Inputs / select / textarea:** `input` with a 2px `field-border` stroke. The select uses a custom plum chevron at 20px, 14px from the right. The textarea is 110px minimum and resizes vertically. Placeholder is #7d6b80, caret teal.
- **Chips:** checkbox pills, with the real input visually hidden. Each has a 12px paint-key dot before the label (700 16px body). Checked is `chip-selected`.
- **The Outlined Controls Rule (owner).** Every form control (field, select, textarea, chip) shows the teal `focus` border plus the focus glow on **hover and on focus alike**. A checked chip keeps its plum fill and only swaps its border to teal. Never signal hover by changing the background.
- **Errors:** message text below the field (700 15px, #9a2b0c), hidden when empty. The invalid border is #b33a12.
- **Success panel:** `paper` panel, `panel` radius, 2px teal-tint border (rgba(14,90,100,.35)). It shows the composed message in a cream box with a small ghost "Copy message" button and an "Or call us" link.

### Seams (painted section edges)
Empty `div.seam` elements between bands, 34px tall (48px at 600px and up). Each one carries `data-from` (the band above) and `data-to` (the band below). JS builds an SVG with a 1200×48 viewBox and `preserveAspectRatio=none`, with an edge along y≈24 made of two sines (±5, ±2.5) plus seeded jitter (±2.5). Seams that are below the fold at load get brushed in left to right over 1100ms (expo-out) when 60% visible. When you add or reorder a band, update both data attributes to match the hex values of the neighboring backgrounds. Seeds are `97 + index×31`, so inserting a seam reshuffles the shape of every seam after it.

### Hero canvas scene (signature)
A single `<canvas>` drawn in **scene coordinates 800×640**, with the ground line at y 520. On phones the house is scaled by min(width/600, height/640) and centered. When the canvas is 1000px or wider it is scaled by min(height/670, width×0.42/560) and centered at 74.5% of the width. It is always bottom-aligned, with DPR capped at 1.75.

Layers, composited every frame in this order:
1. **Base** (offscreen, redrawn on resize): full-width lawn gradient, the three logo arches (`arch-orange`, `gold`, #1d6b74, radii 292/263/234, 29px stroke, soft drop shadow), the walkway, and the weathered gray siding (#c9bca6 with seeded blotches and peeling flecks).
2. **Paint** (offscreen, 2× scene resolution, in scene coordinates so resizes don't wipe it): bristle strokes clipped to the wall shape.
3. **Over** (offscreen): clapboard laps every 18px (shadow, lap line, highlight) that also shade the fresh paint, eave shadow, side shading, corner boards, two shuttered windows, the plum door with a gold knob, the attic vent, the roof as a 36px round-capped `roof-plum` stroke, the chimney, and the bushes.
4. **Brush** (on screen): gold handle, dark ferrule, and bristles dipped in the current color. It tilts with horizontal velocity and replaces the cursor (`cursor:none`).

Tunables (top of the hero script):
- `AUTO_SPEED` 560: autopilot brush speed in scene px/s.
- `ROW` 20: spacing between autopilot rows. Smaller means denser coats.
- `BRUSH_W` 32: stripe width. `BRISTLES` 22: bristle count. More bristles give a smoother, less streaky stripe.
- `IDLE_RESUME` 3200ms: how long after the visitor stops before autopilot takes over again.
- `PASS_PAUSE` 900ms: pause between coats. Each finished coat moves to the next swatch color.
- `STIFF` 260 / `DAMP` 26: the spring the brush follows its target on. Lower stiffness means more lag, and damping above about 2×√STIFF feels heavy.
- `PAINT_K` 2: paint layer resolution per scene px.
- `REWARD_AT` 2600: how many scene px the visitor paints before the hint changes to "Looking sharp." / "¡Quedó impecable!".
- `SW`/`SH` 800×640 and house geometry `G, L, R, T, PEAK, WIN, DOOR`. Moving any of these means redrawing all four layers.

Behavior: autopilot paints back-and-forth rows down the wall. With a mouse, hovering paints. With touch or a pen, painting happens while pressed (pointer capture, `touch-action:none` on the canvas only). The loop stops when the scene is off screen or the tab is hidden. Swatches are a radiogroup of 44px circles over the lawn (bottom left on phones, bottom right on desktop), scaling to 1.12 with a spring ease when selected.

### Brand mark and rasters (provenance)
- `assets/mark.webp`, `assets/favicon.png`, `assets/apple-touch-icon.png`: crops of the client's Facebook profile logo, fetched 2026-10-18 from facebook.com/profile.php?id=61584889347399 (og:image).
- `assets/og.jpg`: a headless-Chrome screenshot of this page's own hero at 1200×630.
- The site has no other rasters and no stock photography. Regenerate `og.jpg` whenever the hero changes.

## Do's and Don'ts

### Do:
- **Do** keep the phone number to **once per screen**: the header carries it, and the footer and success panel are the only other places. The hero gets no extra call button.
- **Do** keep the paint-key mapping (service to color) the same across row dots, chips and swatches.
- **Do** place a seam between every pair of differently colored bands, with `data-from`/`data-to` matching the neighbors.
- **Do** honor reduced motion as built: transitions drop to 0.01ms, smooth scroll turns off, the scene draws one finished coat with no autopilot brush (the visitor can still paint), and seams render complete.
- **Do** keep every tap target at 44px or more and every focus state visible in teal.

### Don't:
- **Don't** make the header (or any bar) sticky or fixed. That is an owner rule.
- **Don't** highlight a whole service row on hover or focus. Only the arrow responds.
- **Don't** show hover on form controls by any means other than the teal outline and glow.
- **Don't** publish an email address anywhere except the footer. None is known today, so none appears.
- **Don't** load webfonts or icon fonts. Icons are inline SVG at 16-24px.
- **Don't** add stock photos, review badges or a service-card grid. The painted house is the image.
- **Don't** use a black or gray ground. Dark bands are plum.
