# news-image-01 v3 — "Friday 13 November 2026: 30 stories, 6 continents"

A dense newspaper front page summing up the world's news of Friday
13 November 2026, in one 1024×1024 JPEG (284,465 bytes).

## What is on the page

- Masthead: **Friday 13 November 2026**, "30 stories · 6 continents"
- Top row (3 big stories, with flat illustration panels):
  1. Nvidia falls below $4 trillion (a day after chief Jensen Huang quit)
  2. FAA grounds every US departure for four hours
  3. Iran says it hit a US radar in Bahrain; US denies it
- Middle grid (stories 4–15): Trump–Xi–Putin three-way summit, Europe
  joins Ukraine peace talks, Ukraine's 1,200-drone night, Starship Flight
  15, Pope Leo XIV's Mass in Chiclayo, the Türkiye–Qatar defence pact,
  the Assam bus crash, the Microsoft 365 outage, Pochettino to Manchester
  United, COP31, the Brooklyn collapse toll, the record US October deficit
- Bottom: a world map ("Where it happened", stories 1–15 located) plus
  "Also on Friday 13 November" — briefs 16–30 from Norway to Nauru
- Footer: sources AP · Reuters · AFP · BBC · Al Jazeera · DW · CNBC ·
  UN News

Every headline is a real event of 13 November 2026, checked against
same-day reporting (Reuters, AP, BBC, Al Jazeera and others). Disputed
claims are attributed ("Iran says…", "US denies it"). Nothing invented,
no hype.

## How it was made

The page was drawn programmatically (Python + Pillow: exact text, crisp
lines, no garbled glyphs) at build time. `main.py` only verifies the
shipped `entry.png` (JPEG magic, exact byte length, SHA-256) and copies
it to `/output/entry.png`. It runs twice with byte-identical output, uses
only the Python standard library, and needs no network.
