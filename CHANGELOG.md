# Filter Bloom — Changelog

All notable changes to Filter Bloom are listed here. Download the latest at
[phonomenon.crypticartslab.com/downloads](https://phonomenon.crypticartslab.com/downloads).

## 0.1.3 — 2026-06-14

- Refined the spacing of the per-band controls in the right-hand panel for a cleaner, more compact layout.

Maintenance release — the audio engine is unchanged and your saved projects load exactly as before.

## 0.1.2 — 2026-06-14

- The Cryptic Arts Laboratory logo now lives permanently in the top-right header.
- "Open User Guide" now opens the online guide at phonomenon.crypticartslab.com/docs (and still falls back to the built-in guide when you're offline).
- Cleaned up tooltip text that could show stray characters on some systems.
- More breathing room between the per-band detail controls.
- Corrected the support link in the licence to point at this public tracker.

## 0.1.1 — 2026-06-07

First official release — signed and notarized for macOS, so it opens cleanly on any Mac with no Gatekeeper warnings.

- **Envelopes survive copy/paste** — per-step Frequency, Q, Detune and Resonance curves are preserved when you copy the plug-in between tracks.
- **Saved projects reload exactly as you left them** — loading no longer overwrites drawn envelopes with the band's main knob values.
- **Three bands by default** (down from four), with a new "− Remove" button next to "+ Add" so you can collapse the band strip down to a single band.

If you're on the 0.1.0 beta, please update: sessions saved with 0.1.0 can lose drawn envelopes on reload.

## 0.1.0 — 2026-05-28

The original public beta of Filter Bloom — a graduated multi-step filter sequencer for AU and VST3.

- Up to **8 parallel filter bands**, each with its own envelope drawn across the step grid.
- **16 / 32 / 64 / 128 steps** spanning 1 to 64 host bars, phase-locked to the DAW transport.
- Per-step envelopes for **Magnitude, Amplitude, Frequency, Q, Resonance and Detune**.
- Per-band **Filter Type** (Low-Pass / Band-Pass / High-Pass / Notch / Low Shelf / High Shelf / Peak), plus **Drive, Timbre, Gain, Wet/Dry and Level**.
- **Safe Low Cut** on Low-Pass bands, loop-boundary **Hard Reset** or **Gradual Fade**, automatable Master and per-band Levels, and an in-plug-in update check.
