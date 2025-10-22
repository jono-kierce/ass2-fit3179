# FIT3179 Assignment 2 — AFL Club Membership Geography (2024)

A lightweight, static repo for DV2 showing where AFL club memberships are concentrated (2024 season). Includes:
- Proportional-symbol map of club home grounds (size = membership).
- Leaderboard bar chart by club.
- State breakdown chart.

## Quick start
- Open `src/index.html` in a browser (no build step needed).
- OR serve locally (e.g. `python -m http.server` from repo root).

## Data
- `data/afl_memberships_2024.csv`: club, membership_2024.
- `data/afl_club_homegrounds.csv`: club, ground, lat, lon, state.
- Run `python scripts/prepare_data.py` to produce `data/afl_clubs_2024_geo.csv`.

## Vega-Lite specifications
- All chart specs live in `specs/` and are prettified for accessibility/compliance.
- `specs/map.json` — proportional symbol map with inset.
- `specs/leaderboard.json` — club membership leaderboard.
- `specs/state.json` — membership totals by state.
- `specs/per-capita.json` — membership per 1,000 residents.

## Sources (human-readable)
- 2024 AFL club membership totals: Official AFL season release (2024).
- Stadium coordinates: public stadium pages (MCG, Marvel, Adelaide Oval, Optus, SCG, Gabba, GMHBA, Heritage Bank Stadium, Sydney Showground).
> Note: This repo keeps data small (<1 MB). CSVs are included for reproducibility.

## License
MIT — see `LICENSE`.
