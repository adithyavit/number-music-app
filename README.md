# Number Music App

A public static web app that turns typed numbers into pentatonic music.

## What it does

- Multi-layer digit sequencer: type any digits, each digit becomes one beat
- Synthesized Web Audio instruments (Keys, Drums, Bells, Bass families)
- Tempo control (40-240 BPM), per-layer and full-mix playback
- Compact two-step sound picker (family, then sound)
- Session library: save layers as pieces, drag them back into any lane
- JSON import/export for portable sessions

## Run it

Open `index.html` in any modern browser, or serve the folder with any static server:

```sh
npx serve .
```

No build step, no dependencies, no backend. Entries are session-only on purpose:
nothing is persisted between visits.
