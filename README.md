# IBO 2026 — Intelligent Building Operations Workshop

Site for the 2026 Intelligent Building Operations Workshop, held Sunday,
July 12, 2026 at Rawls Hall, Purdue University. Part of the Herrick
Conferences series. Coordinated by Kevin Kircher (Purdue) and Gregor Henze
(CU Boulder).

Live at: **https://ibo-2026.github.io/**

## Publishing this site

1. This repo must be named exactly `ibo-2026.github.io` inside the
   `ibo-2026` GitHub organization — that exact name is what gives it the
   clean root URL instead of a nested path.
2. Push this repo's contents to `main` on
   `github.com/ibo-2026/ibo-2026.github.io`.
3. In the repo, go to **Settings → Pages** and set the source to
   **Deploy from a branch → main → / (root)**.
4. Make sure the repo is **Public** — GitHub Pages does not publish free
   private-repo sites on the org's Free plan.
5. The site will be live at `https://ibo-2026.github.io/` within a few
   minutes.

## Editing content

Everything lives in a single `index.html` file (styles are inlined in a
`<style>` block, no build step required). To update:

- **Agenda** — edit the rows inside `<section id="agenda">`.
- **Speakers** — edit the cards inside `<section id="speakers">`.
- **Dates / venue** — update the `<span class="eyebrow">` in the hero and
  the `.meta-strip` items.

## For future years

This workshop uses a fresh, year-named GitHub organization each year
(e.g. `ibo-2027`) rather than one org holding every year, so each year's
repo can be named `<year>.github.io` and get a clean root URL like
`https://ibo-2027.github.io/`. To start a new year:

1. Create a new org named for that year (e.g. `ibo-2027`).
2. Inside it, create a repo named exactly `ibo-2027.github.io`.
3. Copy this repo's `index.html` as a starting point, update the hero,
   agenda, speakers, and location sections.
4. Publish via GitHub Pages as above.
5. Invite the workshop's coordinators (Kevin Kircher, Gregor Henze, or
   that year's host) as Owners so the org isn't tied to one person.
