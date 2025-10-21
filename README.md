# FIT3179 Assignment 2 — AFL Club Membership Geography (2024)

A lightweight, static repo for DV2 showing where AFL club memberships are concentrated (2024 season). Includes:
- Proportional-symbol map of club home grounds (size = membership).
- Leaderboard bar chart by club.
- State breakdown chart.

## Data
- `data/afl_memberships_2024.csv`: club, membership_2024.
- `data/afl_club_homegrounds.csv`: club, ground, lat, lon, state.
- Run `python scripts/prepare_data.py` to produce `data/afl_clubs_2024_geo.csv`.

## Sources (human-readable)
- 2024 AFL club membership totals: Official AFL season release (2024).
- Stadium coordinates: public stadium pages (MCG, Marvel, Adelaide Oval, Optus, SCG, Gabba, GMHBA, Heritage Bank Stadium, Sydney Showground).

## License
MIT — see `LICENSE`.
