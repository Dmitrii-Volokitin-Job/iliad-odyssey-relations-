# Iliad & Odyssey — Relationship Map

An interactive, fully self-contained HTML page (no build step, no CDN dependencies)
visualizing the characters and gods of Homer's *Iliad* and *Odyssey* as a force-directed
relationship graph, plus a separate world map of real and legendary locations.

Open `index.html` in a browser — internet access is only needed to load character photos
and Wikipedia links; the page itself works fully offline (`file://`).

## Features

- **Relationship graph** — 46 characters (gods, Achaeans, Trojans, nymphs/others), 78
  relations of five types (family, patronage, alliance, love/captivity, conflict), a
  hand-written force-directed layout on plain SVG/JS with no libraries, draggable nodes,
  zoom/pan, search, and group filters.
- **Hover cards** — hovering any character shows a small card with their photo, name, and
  epithet; hovering a relationship line shows what it means.
- **World map** — real Mycenaean-era locations (Troy, Mycenae, Sparta, Pylos, Argos, Crete,
  Ithaca, Olympus) styled like a classic "World of Homer" atlas — light-blue sea, pale-green
  coastlines, a compass rose, decorative frame, and a legend cartouche — plus Odysseus's
  legendary 12-stop route home, drawn as a red arrowed sailing line, per traditional (but
  disputed) identifications.
- **English / Russian** — every character bio, relationship label, and location description
  is fully bilingual; toggle with the language button in the top bar (defaults to English).
- **Wikipedia** — every character links to a *verified* (not guessed) article — both Russian
  and English Wikipedia titles were resolved and checked live against the Wikipedia API — and,
  where available, a photo pulled from the same article via the API.
- Light/dark theme, saved to `localStorage`.

## Credits / attribution

Character photos are pulled live from Wikimedia Commons via the Wikipedia API and linked
back to their source article — see the credit line under each tab's legend. The map's visual
style is inspired by classic "World of Homer" atlases (e.g. V. Bérard's route reconstructions);
coastlines here are schematic illustrations, not surveyed geography. All character/relationship
descriptions were written for this project, not copied from Wikipedia.

## Tech

Vanilla HTML/CSS/JS — no framework, no build step — following the convention of the other
educational sites in `learning/`.

## Screenshots

_Not yet added — this environment can't capture the rendered page. To add some: open
`index.html`, switch between the Graph and Map tabs, click a character/location to show the
side panel, then drop a few PNGs into a `screenshots/` folder and reference them here._
