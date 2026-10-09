# Halo Design Notes

How the *Mission Python* "Escape" game maps onto the Master Chief Edition.
Phase 1 keeps the book's mechanics and only reskins names, text and art.
Phase 2 adds original Halo features.

## Theme mapping

| Book (Escape)                    | Master Chief Edition                               |
|----------------------------------|----------------------------------------------------|
| Mars space station               | UNSC *Pillar of Autumn* (or a Forerunner installation) |
| Astronaut player                 | Master Chief (Spartan-117)                         |
| Mission control / radio messages | Cortana                                            |
| Air supply running out           | MJOLNIR shield / armor power                       |
| Hazards (moving dangers)         | Sentinels / Covenant patrols                       |
| Objects and props                | Keycards, MA5B, plasma pistol, Cortana's data chip |
| Escape pod goal                  | Reach the Longsword / Warthog run                  |

## Asset rules

- Pygame Zero loads from `images/`, `sounds/` and `music/`. Filenames must be lowercase with no spaces.
- Start with the book's downloadable assets, then replace them gradually with original or fan-made Halo-style art.
- Don't commit ripped official Halo assets. This is a public fan project.

## Phase 2 backlog (after the book)

- [ ] Cortana dialogue system (dicts, JSON data files)
- [ ] Shield recharge mechanic (timers, `clock.schedule`)
- [ ] Covenant enemy AI (classes / OOP)
- [ ] Split `escape.py` into modules (imports, packages)
- [ ] Save / load (file I/O)
- [ ] Tests with `pytest`, linting with `ruff`
