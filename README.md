# SA-ARP — San Andreas Advanced Role-Play

![Version](https://img.shields.io/badge/version-3.2.1-blue)
![Status](https://img.shields.io/badge/status-active%20development-brightgreen)
![Platform](https://img.shields.io/badge/platform-SA--MP-orange)
![Since](https://img.shields.io/badge/running%20since-2006-lightgrey)

**A San Andreas Multiplayer gamemode built for realism.**
No arcade shortcuts, no invincible super-cops, no economy that runs itself — just a
persistent, faction-driven, player-run world with real physical limits.

---

## About

SA-ARP is a heavily customized [SA-MP](https://www.sa-mp.com/) gamemode that has been in
continuous development since 2006. It's built around two ideas: **factions** and
**economy**. Every player, every faction, and every transaction lives in a persistent
database — nothing resets, nothing is scripted to feel fair, everything is earned.

The codebase is written entirely in **Pawn**, organized as a core gamemode
(`SAarp.pwn`) plus a set of active filterscripts (anti-DDoS protection, vehicles,
doors, factions, administration, server restart handling) and a large shared library
of includes used across the whole project.

▶ **Website:** [www.sa-arp.net](https://www.sa-arp.net)
▶ **Connect in-game:** `sa-arp.net:7777`

## Highlights

- **Faction-based roleplay** — legal and illegal organizations with their own
  hierarchies, territory, and in-character politics.
- **Player-driven economy** — no free rides; income, property, and vehicles are earned
  and can be lost.
- **Realism-first design** — physical limits, consequence-driven mechanics, and
  moderation tuned to keep the world consistent rather than convenient.
- **Two decades of iteration** — a codebase that has grown, been rewritten, and been
  refined by one developer since age 15. Every system here has a history.

## Project Status

SA-ARP is at **v3.2.1** and under active, ongoing development. Development is tracked
entirely through GitHub Issues — this repository is the project's public record, even
though the live gamemode source lives in a private working copy.

Issue triage runs on a structured label system:

| Category | Purpose |
|---|---|
| `type:bug`, `type:enhancement`, `type:question`, `type:research` | What kind of issue this is |
| `impact:high` / `impact:medium` / `impact:low` | How much it affects story continuity |
| `state:needs-repro` → `state:ready` → `state:testing` | Where a fix is in its lifecycle |
| `effort:small` | Safe to release without a full test pass |
| `Map Editing`, `Mixing`, `IC Dev / CITYP`, `Anti-Cheat (Nex-AC)` | Which subsystem or team it belongs to |

Nothing is closed until it's been verified in-game — the **"Needs to be tested"**
milestone exists specifically to hold fixes until a human confirms they work on the
live server.

## Contributing

Found a bug or have an idea? Open an issue. Reports that include clear repro steps
move through triage fastest — vague reports get parked under `state:needs-repro`
until they're actionable.

## License

This repository documents an actively developed, privately maintained gamemode. No
open-source license is currently granted for reuse of the source.
