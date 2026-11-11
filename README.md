# 🥁 Beat Maker

A lightweight step-sequencer drum machine for your PC. Single HTML file, zero
dependencies, zero samples — every sound is synthesised live with the
Web Audio API.

## Run it

Double-click **`start.bat`** (or just open `index.html` in any browser).
Works fully offline.

## What's in v1 (kept light on purpose)

- **16-step grid × 6 tracks** — Kick, Snare, Clap, Hat, Open hat, Tom
- **Click or drag** to place hits, **right-click** to erase
- **Play/Stop**, **BPM** 60–200, **swing**, **master volume**
- Per-track **volume** and **mute**
- **Random** (musically weighted starter patterns) and **Clear**
- **Auto-save** — the pattern, levels and tempo live in your browser's
  storage; `Save` gives an explicit confirmation
- Keyboard: `Space` play/stop · `R` random · `C` clear · `1`–`6` mute tracks

## Roadmap (the "move up as we go" part)

- Per-step velocity & note length
- More sounds + pitch controls, per-track pan
- Multiple patterns / song mode (chain patterns)
- Record to WAV export
- Keyboard piano / melodic tracks

## Files

| File | Role |
|---|---|
| `index.html` | the whole app (UI + synthesis + scheduler) |
| `start.bat` | opens it in your default browser |
