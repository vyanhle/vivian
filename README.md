# Welcome to your website, Vivian.

This is your personal site at **vivianx.com**. You can change anything on it, anytime.

The whole site is 3 files of code, in this folder on GitHub:

- `index.html` — homepage (the front page people see first)
- `story.html` — your longer story at `vivianx.com/story`
- `notes.html` — your field notes journal at `vivianx.com/notes`

Plus:
- `/art/` — folder where you upload hand-drawn art (see `art/README.md` for that)

You don't need to know "how to code." You only need to learn how to **change text between two arrows**. That's 95% of what you'll ever do.

---

## How to edit your site (the fast way)

1. Go to **github.com/vyanhle/vivian**
2. Press the period key **`.`** on your keyboard — the page turns into a full code editor (called github.dev — it's free, runs in your browser)
3. Open `index.html`, `story.html`, or `notes.html` from the left sidebar
4. Press **Cmd+F** (Mac) or **Ctrl+F** (Windows) to search for the text you want to change
5. Change it → click the **Source Control** icon on the left (looks like a Y branch shape)
6. Type a quick note like "updated bio" → click **Commit & Push**
7. Wait 30 seconds → refresh `vivianx.com` → your change is live

If you mess something up, you can always come back and undo. Git keeps every version of every file.

---

## The one rule of editing HTML

**Only change the words. Don't touch the brackets `<` and `>`, or anything inside them.**

Example, from your `index.html`:

```html
<h3>Science National <em>Honor Society</em></h3>
```

To change to "Math Honor Society":

```html
<h3>Math National <em>Honor Society</em></h3>
```

Keep `<h3>`, `</h3>`, `<em>`, and `</em>` exactly the same. Just change the words.

The `<em>` wrapping makes a word terracotta-colored. You can move it to a different word if you want — just keep both `<em>` and `</em>` matched.

---

## What to change as you grow

### Things to update soon

| When | What to change |
|---|---|
| After June 2026 SAT/ACT | (Don't add scores — keep that out of the public site) |
| After summer 2026 | Update the `index.html` card "A college class, early" with what you actually did |
| Start of junior year (Sep 2026) | Update the homepage to say "junior" instead of "sophomore" |
| When you get into a real research lab | Add a new entry in `notes.html` |
| Whenever something interesting happens | Add a notes entry — small things are fine |

### Things to think about updating

`story.html` Chapter II ("Why bioengineering") — **right now it's mine, not yours.** I wrote a placeholder story about a grandmother counting pills. It's not your real memory. When you have time, replace it with your real moment — the actual thing that made you curious about bioengineering. Doesn't have to be dramatic. The smaller, the more real.

---

## Adding a new entry to `/notes`

Open `notes.html`. Near the top there's a comment that says "Để thêm 1 entry mới..." (instructions in Vietnamese — your dad set it up).

Basically: copy any `<article class="entry">...</article>` block, paste it above the newest one, change:

- `entry-date` (the month)
- `entry-number` (No. 04, No. 05, etc.)
- `entry-title` (your title)
- The `<p>` paragraphs (your text)

Each entry is independent. Just copy-paste-modify.

---

## Adding a new chapter to `/story`

Open `story.html`. Each chapter is a section with `§ I`, `§ II`, etc. Copy any chapter block, paste it before the closing signature, change:

- The chapter number (`§ V`)
- Section label (`Crossing`, `Now`, etc.)
- Chapter title (`<h2 class="chapter-title">`)
- The `<p>` paragraphs

---

## Things that are harder (just ask if you want them)

For these, send a message in the chat your dad uses with Claude:

- Adding a brand new page (like `/projects` or `/reading`)
- Changing colors or fonts of the whole site
- Adding photos, image galleries
- Anything involving the layout structure

These take some code knowledge. Easier to ask than struggle. Not worth your time when you can spend that time on actual schoolwork.

---

## Hand-drawn art (this is the fun one)

Look at `art/README.md` for the full guide. Short version:

The numbers (01, 02, 03, 04), the signature, the icons, even some headings — **you can replace all of them with your own hand-drawn versions.** Just draw on paper, take a photo, remove the background, upload to `/art/` folder with the right filename.

If you do that, your website will be one of *very few* sites with actual handwriting on it. Not a font. Not a template. Yours. That detail is rare and intentional — it's the kind of thing that catches attention without being loud.

You don't have to do all 18 drawings. Even 4 numbers + a signature would change the whole feeling of the site.

---

## Where to put this site's link

Use `vivianx.com` in:

- **Common App** — under "Personal website" in your application
- **Email signature** — when you email professors to ask about summer research
- **GitHub profile** — there's a website field in your profile settings
- **Anywhere you'd write your email** — having a personal site signals you're a person, not just a transcript

People who matter for college admissions look at 6-8 minutes per application. A real, personal website with handwriting and stories — they remember that. They don't remember another Notion template.

---

## A note from Claude (the AI helping build this)

I drafted this site with some words that feel right but are mostly guesses about you. Read through it. Anything that doesn't feel like *you* — change it.

The site grows with you over the next 2-3 years. The version you have now is the seed. By the time you apply to college, after you've added entries, hand-drawn numbers, a real chapter II, photos from places you've been, projects you've done — it'll be a small artifact of *who you became* during high school.

That's the part that matters.

— c.

---

## Quick reference

| Task | How long | Need help? |
|---|---|---|
| Change a sentence or paragraph | 2 minutes | No |
| Add a new notes entry | 5 minutes | No |
| Add a new story chapter | 5 minutes | No |
| Upload hand-drawn art to /art/ | 5 minutes per drawing | No (see art/README.md) |
| Update your bio for junior year | 5 minutes | No |
| Add a new page (like /projects) | 20 minutes | Yes — ask in chat |
| Change fonts or colors | 15 minutes | Yes — ask in chat |
| Major redesign | 1+ hour | Yes — definitely ask |

Take your time. The site doesn't go anywhere.
