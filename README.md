# Drawing Guide for vivianx.com

This folder holds your hand-drawn art. Whatever you upload here automatically replaces the CSS/font version on the live site within 30 seconds.

**You don't have to do all of these at once.** Each drawing is independent. Skip any you don't want. The site uses the default font style for anything missing.

---

## How sizing works (important)

Each image has a **maximum width** set in the code. The **height auto-adjusts** based on your image's ratio.

In practice: draw whatever ratio feels natural to you. The site will scale it to fit. The only thing to keep in mind is the **aspect ratio** of what you draw — if it's too narrow or too wide, it might look strange on the page.

For each item below, I list the **recommended ratio** (width : height) so your drawing fits well. This is just a guide — small variations are fine.

---

## How to do this

1. Draw on white paper with a pen
2. Take a clear photo (or scan)
3. Remove the white background → save as transparent PNG
4. Upload to this `/art/` folder with the **exact file name** listed below
5. The site auto-updates within 30 seconds

If you don't like a drawing, upload a new version with the same name — it replaces the old one.

---

## Tools to remove background (pick one)

All free:

- **[remove.bg](https://www.remove.bg/)** — drag and drop, removes white background in 5 seconds. Best for line drawings.
- **iPhone Photos app** — long-press the drawing in a photo → "Copy Subject" → save as PNG.
- **Procreate (iPad)** — if drawing on iPad with Apple Pencil, export PNG with transparent background.

---

## Drawing recommendations

| Aspect | Recommendation |
|---|---|
| **Paper** | Plain white, A4 or letter, not lined |
| **Pen** | Brown or black fine-tip marker (Sharpie ultra-fine, Micron 03, brown gel pen). Avoid pencil (too light), thick markers (loses detail) |
| **Lighting** | Daylight, no shadow on paper. Or use a scanner |
| **Size** | Draw 2-3x bigger than you need. Larger = more detail when scaled down |
| **Imperfection** | Wobbles, uneven lines, smudges = good. That's the whole point. |

---

## File list — what to draw

Items grouped by where they appear and how important they are. **Tier 1** items have the biggest visual impact — do those first if you only do some.

---

### TIER 1 — Highest impact (5 files)

#### `num-01.png`, `num-02.png`, `num-03.png`, `num-04.png`
Hand-drawn numbers 01, 02, 03, 04.

- **Where:** Homepage, left side of "Things I'm making time for" list
- **Ratio:** ~1:1 (square) or slightly taller (3:4)
- **Site renders at:** max 80px wide
- **Tip:** Write each number 3-4 times on paper, pick your favorite

#### `signature.png`
Your signature "v." (just the letter) or "— v."

- **Where:** Bottom right of homepage footer
- **Ratio:** ~2:1 (wider than tall)
- **Site renders at:** ~64px wide
- **Tip:** Quick and casual, like how you'd sign a note

---

### TIER 2 — Headings and titles

These take more time because the text needs to be readable.

#### `kicker-intro.png`
The handwritten kicker text **"a small introduction —"** at the top of homepage.

- **Ratio:** ~6:1 (long and short)
- **Site renders at:** max 280px wide
- **Tip:** Cursive, casual handwriting — like a note in the margin of a book

#### `kicker-list.png`
The handwritten kicker **"a short list, on purpose —"** before the activity list.

- **Ratio:** ~6:1
- **Tip:** Same style as `kicker-intro.png` so they feel consistent

#### `title-short-version.png`
The chapter title **"The short version."** above the bio paragraph.

- **Ratio:** ~5:1
- **Tip:** Italic-looking script, slightly larger than the kickers

#### `title-snhs.png`
**"Science National Honor Society"** — activity 01 title.

- **Ratio:** ~8:1 (very wide), or **~4:1 on 2 lines** (recommended for readability)
- **Tip:** Try writing it on 2 lines: "Science National" / "Honor Society"

#### `title-college.png`
**"A college class, early"** — activity 02 title.

- **Ratio:** ~6:1
- **Tip:** "early" in italic-ish, slanted differently

#### `title-weekend.png`
**"Weekend shifts"** — activity 03 title.

- **Ratio:** ~5:1

#### `title-reading.png`
**"Reading, differently"** — activity 04 title.

- **Ratio:** ~5:1
- **Tip:** "differently" in italic-ish

#### `title-long-version.png`
**"The long version"** — link title to story page.

- **Ratio:** ~5:1
- **Tip:** "long version" with extra flourish since this is the "fancier" link

#### `title-fieldnotes.png`
**"Field notes"** — link title to notes page.

- **Ratio:** ~4:1
- **Tip:** Short and clean

#### `stamp-sophomore.png`
The badge **"Sophomore Year"** at top right of homepage.

- **Ratio:** ~3:1
- **Site renders at:** max 110px wide
- **Tip:** Draw it like a passport stamp or a sticker. Could be in a rectangle border, could be rotated.

---

### TIER 3 — Decorative (story and notes pages)

#### `signature-end.png`
Larger signature for the bottom of `/story` and `/notes` pages. Can include the date.

- **Ratio:** ~3:1 (like "— v., May '26")
- **Site renders at:** max ~140px wide

#### `arrow-curve.png`
A curvy arrow pointing right and slightly down. Replaces the SVG arrow icon next to "The long version".

- **Ratio:** ~1.6:1 (wider than tall)
- **Site renders at:** ~72px wide

#### `notebook.png`
Small notebook drawing. Replaces SVG notebook icon next to "Field notes".

- **Ratio:** ~1:1 (square)
- **Site renders at:** ~72px wide
- **Tip:** Spiral-bound notebook with a few horizontal lines inside

#### `ornament.png`
Decorative divider between sections on story and notes pages (replaces `· · ·`).

- **Ratio:** ~5:1 (long and short)
- **Site renders at:** ~80px wide
- **Tip:** Three dots, a tiny squiggle, a small star, a leaf. Anything simple.

---

## ⚠️ What I intentionally did NOT include

**"Things I'm making time for."** — Bean asked about this, but I left it as text on purpose.

It's the BIGGEST heading on the page. The font scales responsively — bigger on laptops, smaller on phones — automatically. An image can't scale text-smartly; on phones the heading would either get tiny (hard to read) or get cut off. The current responsive font handles every screen size cleanly.

If you really want to replace this later, it can be done — but it needs extra CSS to handle small screens correctly. Better to leave it as text for now.

---

## Upload steps on GitHub

1. Go to `github.com/vyanhle/vivian`
2. Click into the `art` folder
3. Click **Add file** → **Upload files**
4. Drag your PNG file (with the exact name from the list)
5. Click **Commit changes**
6. Wait 30-60 seconds
7. Refresh `vivianx.com` — your drawing is live

---

## A note on color

Use **brown or terracotta-colored ink** if you can. The site's accent color is `#B85423` (terracotta). Brown/red-brown ink blends naturally.

Black ink works too — just feels slightly heavier than the rest of the site.

Pencil is too light — it'll disappear when the image is scaled down. Use marker or pen.

---

## Tips that took me a while to figure out

- Draw each thing **2-3 times** on paper. Pick the best one.
- **Don't try to make it perfect.** Wobbles are good.
- Take photos in **bright daylight** — phone cameras need light to capture fine lines.
- Lines should be **thicker than you think** they need to be. Thin lines disappear when shrunk.
- If you don't like a drawing later, just upload a new file with the same name. The old one is replaced.

Good luck. Be a little messy.
