# IBO 2026 — Intelligent Building Operations Workshop

Site for the 2026 Intelligent Building Operations Workshop, held Sunday,
July 12, 2026 at Rawls Hall, Purdue University. Part of the Herrick
Conferences series. Coordinated by Kevin Kircher (Purdue) and Gregor Henze
(CU Boulder).

## Publishing this site

1. Push this repo's contents to `main` on
   `github.com/ibo-workshop/ibo-2026`.
2. In the repo, go to **Settings → Pages** and set the source to
   **Deploy from a branch → main → / (root)**.
3. Make sure the repo is **Public** — GitHub Pages does not publish free
   private-repo sites on the org's Free plan.
4. The site will be live at `https://ibo-workshop.github.io/ibo-2026/`
   within a few minutes.

## Editing content

Everything lives in a single `index.html` file (styles are inlined in a
`<style>` block, no build step required). To update:

- **Agenda** — edit the rows inside `<section id="agenda">`.
- **Speakers** — edit the cards inside `<section id="speakers">`.
- **Dates / venue** — update the `<span class="eyebrow">` in the hero and
  the `.meta-strip` items.

## For future years

Each year gets its own repo in the `ibo-workshop` org (e.g. `ibo-2027`),
named for the year rather than the host, since hosting may rotate between
Purdue and CU Boulder. The easiest way to start a new year:

1. Copy this repo (or use it as a GitHub template).
2. Update the hero, agenda, speakers, and location sections.
3. Publish via GitHub Pages as above.
4. Link the new year from the `ibo-workshop.github.io` landing repo once
   that exists.
