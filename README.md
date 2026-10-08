# The Long Take

An independent review notebook by Marko. Film, TV, books, music and stage — not every reaction needs to be a 2,000-word essay.

**Live site:** https://marko-durasic.github.io/the-long-take/

## Editing reviews

All content lives in [reviews.json](./reviews.json). To add an entry, append an object with:

- slug: unique, URL-friendly identifier
- title: work title
- medium: film / television / book / music / stage
- year: original release year (or null if uncertain)
- score: your personal score out of 10; use null for first impressions
- status: First impression / Quick take / Full review
- date: date the note was published (YYYY-MM-DD)
- palette: moss / ink / clay / plum / blue / gold / forest / gray
- excerpt: honest 1–2 sentence takeaway
- body: array of paragraphs (no invented observations)
- tags: short array of topics
- featured: true for one recent spotlight (optional)

Publishing: commit to the default branch. GitHub Pages serves the static files from the repository root. No database, account, or subscription required.

## Editorial rules

1. Make a clear distinction between a **first impression** and a **finished review**.
2. Personal rating, not a claim of universal quality; a well-made show can still be only an 8/10 *for me*.
3. Don't manufacture details or reasons after the fact. A short truthful note beats invented analysis.
4. Judge plot, intelligence of characters, pacing, emotional impact and audiovisual craft separately when useful.
5. Prefer spoiler-free summaries; mark spoilers before detailed discussion.
6. Publish only deliberate personal notes. No private messages, contact details or personal data.

## Technical notes

Zero-build static HTML, CSS and JavaScript; filters and search run in the browser. The page renders from reviews.json. Basic social sharing tags and mobile layout are included.

### Roadmap

- Write a full review when finishing Spider-Man.
- Add books, music and stage reviews as they actually occur.
- Optionally use a tiny review submission form, RSS feed, or personalized domain later. No need yet.
