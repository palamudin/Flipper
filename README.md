# Split-Flap Board From Hell

Because apparently making an old airport board in HTML/CSS/JS was not suffering enough already, this repo exists.

It flips.  
It animates.  
It collapses the config bar.  
It pretends to be classy.  
It absolutely did not come into being through calm, balanced engineering decisions.

## What this thing is

A single-file split-flap board showcase with:

- old-school mechanical flip animation
- arrivals / departures presets
- random status generation
- collapsible nav/config section
- no external CSS
- no external JS
- no dependency circus
- no framework cult membership required

It is one HTML file because sometimes the correct architectural decision is:
“shove the whole cursed machine into one place and make it work.”

## Why this exists

Because standard UI is boring.

Because airport boards have more soul than 90% of modern dashboards.

Because turning text into a flapping electro-mechanical-looking display is objectively better than another washed-out card layout pretending to be enterprise innovation.

Because pain builds character.

## Features

- Split-flap style character rendering
- Per-character flip animation
- Manual text input in `TIME|FLIGHT|DESTINATION|STATUS` format
- Quick actions for:
  - Render board
  - Randomize status
  - Load arrivals
  - Load departures
- Collapsible top nav so the config junk can get out of the way
- Same-size fields across rows when configured properly, like a real board should have been from the start

## Format

Input rows use this format:

```text
08:15|JU214|LONDON|BOARDING
09:05|LH1739|MUNICH|ON TIME
09:50|OS738|VIENNA|DELAYED
