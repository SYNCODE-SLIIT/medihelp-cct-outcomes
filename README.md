# Medihelp CCT Outcomes

Static web page for capturing measurable outcomes across the Medihelp CCT framework (Care, Convenience, Time) by hospital area.

- Import outcomes from a CSV or JSON file (see `sample-outcomes.csv` for the format)
- Edit outcomes, targets, current figures and status per box
- Export everything back to CSV

## Run locally
Open `index.html` in a browser.

## Deploy
Import the repo into Vercel as a static site (no build command, no output directory).

## Storage note
Outside claude.ai, edits are saved in the visitor's own browser (localStorage). They are not shared between people until a backend is added.
