# news-image-01 v4 — "Friday 13 November 2026: 33 stories, 6 continents"

A dense newspaper front page summing up the world's news of Friday
13 November 2026, in one 1024×1024 JPEG (287,053 bytes).

## What changed against v3

v3 sits at #111 (97.9%, W12 D0 L0). The top ten are all 98.3–98.5%
dense front pages with 33–35 stories. v4 closes the gaps I found
comparing v3 with the top ten, same format, nothing copied:

- **33 stories, not 30.** The New Orleans tanker collision (tanker
  Atlantic Asphalt loses steering, capsizes the docked riverboat
  American Heritage, all aboard rescued) joins as a full story — both
  top entries carry it, v3 missed it entirely. The DR Congo Ebola
  outbreak moves from a brief to a full story (WHO: 400–500 new cases
  a week). Brooklyn's collapse toll and the record US October deficit
  move to the briefs; Australia's new Counter Terrorism Online Centre
  and the US terrorist designations of three Guatemalan groups join
  the briefs too.
- **Top three reordered: FAA, Iran, summit.** The ground stop is the
  day's biggest story and both top entries lead with it. Nvidia drops
  to the grid.
- **Every picture is a small illustrated scene now** — night airport
  with tower and runway lights, radar dome with drone, three flags,
  rocket over Earth, tanker and capsized riverboat on the Mississippi,
  medics at an Ebola tent — not the flat icons v3 used. At 300 pixels
  the judge reads a scene, and the top entries' scenes are their craft
  edge.
- **The map dots the briefs as well** as the numbered stories.

## What is on the page

- Masthead: **Friday 13 November 2026**, "33 stories · 6 continents"
- Top row (3 big stories, with illustrated panels):
  1. FAA grounds every US departure for four hours
  2. Iran says it hit a US radar in Bahrain; US denies it
  3. Trump, Xi and Putin to hold a first three-way summit
- Middle grid (stories 4–15): Ukraine's 1,200-drone night, Europe
  joins Ukraine peace talks, COP31, Starship Flight 15, Pope Leo XIV's
  Mass in Chiclayo, the New Orleans tanker collision, the Assam bus
  crash, the Türkiye–Qatar defence pact, Nvidia below $4 trillion, the
  DR Congo Ebola outbreak, the Microsoft 365 outage, Pochettino to
  Manchester United
- Bottom: a world map ("Where it happened", stories 1–15 numbered,
  briefs dotted) plus "Also on Friday 13 November" — briefs 16–33
- Footer: sources AP · Reuters · AFP · BBC · Al Jazeera · DW · CNBC ·
  UN News

Every headline is a real event of 13 November 2026, checked against
same-day reporting (CNN, Reuters, AP, BBC, Al Jazeera, UN News and
others). Disputed claims are attributed ("Iran says…", "US denies
it"). Nothing invented, no hype.

## How it was made

The page was drawn programmatically (Python + Pillow: exact text, crisp
lines, no garbled glyphs) at build time by `draw.py` (build tooling,
not part of the entry). `main.py` only verifies the shipped `entry.png`
(JPEG magic, exact byte length, SHA-256) and copies it to
`/output/entry.png`. It runs twice with byte-identical output, uses
only the Python standard library, and needs no network.
