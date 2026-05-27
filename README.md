# Pathfinders Ventures LLC

The official website for [Pathfinders Ventures LLC](https://pathfindersventures.com) and **The Little Black Book on Leadership** by Brenen Morse.

## Structure

```
.
├── index.html                  # The full single-page site
├── vercel.json                 # Vercel config (PDF download headers, caching)
├── assets/
│   ├── logo.png                # Pathfinders Ventures logo
│   ├── book-cover.jpg          # Book cover image
│   └── brenen-morse.jpg        # Author photo
└── downloads/
    ├── leadership-rhythm-toolkit-complete.pdf   # All-in-one toolkit
    ├── leadership-self-assessment.pdf
    ├── employee-development-tracker.pdf
    ├── pre-shift-huddle-template.pdf
    ├── post-shift-after-action-review.pdf
    ├── difficult-conversation-guide.pdf
    └── hiring-interview-guide.pdf
```

## Local preview

This is a pure static site — no build step. Just open `index.html` in a browser, or run any static server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Auto-deployed via Vercel on every push to `main`. Pull requests get their own preview URLs.

## Updating the site

- **Edit copy or layout:** modify `index.html` directly. Everything is in one file (HTML, CSS, and a small reveal-on-scroll script).
- **Replace the book cover / logo / author photo:** drop the new image in `assets/` with the same filename.
- **Add a new downloadable resource:** put the PDF in `downloads/` and add a new `<a>` card in the Resources section of `index.html`.
- **Swap the Barnes & Noble link:** find-and-replace `barnesandnoble.com/s/little+black+book+on+leadership+brenen+morse` with the direct product URL (4 occurrences).

## Contact

brenenmorsecorp@gmail.com
