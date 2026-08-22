# ♟ Ferz Chess

Chess application with a built-in **aggressive, human-style engine** (~2250 ELO), 3D board view, tournament mode, and more.

**⬇ [Download Latest Release](https://github.com/nkralev76-hue/ferz-chess/releases/download/v1.0.6/Ferz_SFX.exe)**

**🌐 [Website](https://nkralev76-hue.github.io/ferz-chess/)**

---

## About the Engine

The built-in **Ferz engine** is designed to play in an **aggressive, human-like style** at approximately **2250 ELO**. It doesn't just find the strongest move — it fights for the initiative, launches kingside attacks, sacrifices material for activity, and creates the kind of tactical complications that make chess exciting.

Whether you're training for tournament play or just want a challenging opponent that plays like a strong human, Ferz delivers sharp, fighting games every time.

### Engine Details

| | |
|---|---|
| **Name** | Ferz Engine |
| **Style** | Aggressive / Human-like |
| **Approximate ELO** | ~2250 |
| **Evaluation** | Handcrafted (HCE) |
| **Protocol** | UCI |

## Features

- **Aggressive Built-in Engine** — Plays attacking chess with a human-like style. Sacrifices, kingside attacks, tactical complications.
- **2D & 3D Board Views** — Classic 2D or immersive 3D perspective view with smooth animated transitions.
- **Dark Mode** — Clean dark theme throughout the entire application.
- **PGN Database & Explorer** — Built-in PGN database with game explorer, move-by-move statistics, import/export.
- **Computer Tournaments** — Round-robin and knockout tournaments with real-time statistics and detailed summaries.
- **Game Analysis** — Evaluation graphs, per-move eval bars, and detailed move commentary.
- **Full Console Control** — Built-in console (`Ctrl+` `) with 40+ commands: game control, engine management, book/database, UI tweaks, screenshots, raw UCI forwarding. TAB autocomplete, command history, session log.
- **Chess960 (Fischer Random)** — Randomized starting positions for more variety.
- **Opening Books & Tablebases** — Support for opening books and Syzygy tablebase probing (local files + online lookup).

## System Requirements

| Requirement | Minimum |
|------------|---------|
| OS | Windows 10 / 11 (64-bit) |
| RAM | 2 GB |
| Disk Space | ~150 MB after extraction |
| Processor | x86-64 compatible |

## How to Install

1. Download [`Ferz_SFX.exe`](https://github.com/nkralev76-hue/ferz-chess/releases/download/v1.0.6/Ferz_SFX.exe) from the [Releases](https://github.com/nkralev76-hue/ferz-chess/releases) page
2. Run the self-extracting archive
3. Choose an extraction folder (e.g. `C:\Ferz`)
4. Launch `Ferz.exe` — no installation required

## Changelog

### v1.0.6 (August 22, 2026)
- NEW: Analysis Report window — per-move evals with inaccuracy/mistake/blunder detection, opens automatically after whole-game analysis
- Whole-game analysis now caches an eval for every move (regardless of engine color)
- Analysis reliably stops when it finishes — pending engine searches can no longer restart after stop
- Rich hover info on every analyzed move: White-perspective eval, depth and best line

### v1.0.5 (August 22, 2026)
- Fixed engine best-move arrows missing in every color-swapped Engine vs Engine game
- Premoves fixed: queue a move while the engine thinks and it plays automatically after the reply
- Legal-move dots & capture highlights now shown in the 2D view too

### v1.0.4 (August 21, 2026)
- 3D view now switches pieces to the 3D Staunton plastic set on first toggle
- Dedicated 2D/3D piece-set settings — pick a set in each view independently
- Improved stop responsiveness — UI no longer freezes when stopping parallel/tournament games
- Added "Stopping engines..." status message in the status bar

### v1.0.3 (August 20, 2026)
- Optimized SFX archive size (71 MB down from 146 MB)
- Improved tournament functionality
- UI improvements in TournamentDialog

### v1.0.2 (August 15, 2026)
- Game analysis improvements
- Stability fixes

### v1.0.1 (August 10, 2026)
- Added 3D board view
- Parallel games and tournaments
- Opening book improvements

### v1.0.0 (August 7, 2026)
- First public release
- Ferz engine with aggressive human-style play
- 2D board with dark mode
- PGN database and explorer
- UCI engine support
- Opening book + tablebase support
- Chess960 (Fischer Random)
- Qt6 Fusion UI

## License

Ferz Chess © 2026
