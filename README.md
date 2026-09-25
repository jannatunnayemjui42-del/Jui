# Jannatun Nayem Jui — Interactive Portfolio

A single-file, interactive recreation of your portfolio deck. It renders every slide from the original document as a swipeable/clickable presentation instead of a static PDF, with the same cream-and-botanical look (dark green headings, olive info boxes, hand-drawn accents).

## Files

- `index.html` — the entire site (HTML, CSS, and JavaScript in one file). Open it directly in any browser — no build step, no server required.

## How to view it

1. Double-click `index.html`, or right-click → **Open with** → your browser.
2. That's it — it works fully offline except for loading two Google Fonts (Caveat, Baloo 2) on first view.

## Controls

| Action | How |
|---|---|
| Next slide | Click the `›` button, press the **Right Arrow** key, or swipe left on mobile |
| Previous slide | Click the `‹` button, press the **Left Arrow** key, or swipe right on mobile |
| Jump to a slide | Click any dot in the dot row at the bottom |

## Slides included

1. Title — Jannatun Nayem Jui
2. A Little About My Journey + Areas of Interest
3. Learning Through Study & Practice
4. Waste to Wealth — Ongoing Course Research Project
5. Exploring Plants Beyond the Lab
6. Beyond Classroom to Explore Myself
7. My Current Toolkit
8. My Journey of Learning & Becoming
9. Still Learning. Still Growing.
10. Thank You

## Customizing

Everything lives in `index.html`, organized top to bottom:

- **`<style>` block** — color variables are defined once at the top under `:root` (e.g. `--cream`, `--green-dark`, `--olive`). Change a variable there to re-theme the whole deck.
- **`<body>` section** — each slide is a `<section class="slide" id="sN">`. Edit the text directly inside the matching section to update content.
- **`<script>` block** — controls slide navigation (buttons, keyboard arrows, dot indicators, swipe). You shouldn't need to touch this unless you want to change how navigation behaves (e.g. auto-advance, different transition style).

### Adding a new slide

1. Copy an existing `<section class="slide" id="sN">...</section>` block, give it a new unique `id`, and edit its content.
2. Place it wherever you want it to appear in the sequence — order in the HTML is the slide order.
3. No JavaScript changes needed — the script automatically detects all `.slide` elements and builds the dots/counter for you.

## Hosting it online

Since it's a single static HTML file, you can publish it anywhere for free:
- **GitHub Pages** — push this folder to a repo and enable Pages.
- **Netlify / Vercel** — drag-and-drop the folder into their dashboard.
- Or simply email/share the `index.html` file — it opens the same way anywhere.
