# SATCOM Interference Introduction — "CW Easy"

A single-file, browser-based demo that introduces a new SATCOM operator to how to **detect, characterize, report, and work around** a continuous-wave (CW) interferer on a Ku-band transponder.

**Play it:** https://curtisarnold3.github.io/satcom-interference-intro/

## What's inside
- **Narrated opening story** (~2 min): a forward team brings up its terminal, how the uplink → satellite → downlink link works, where the interference comes in, and what it breaks.
- **Live spectrum analyzer + waterfall** with realistic swept-analyzer behavior (RBW/VBW, log-detected noise, Clear/Write, Max Hold, Average, markers, delta markers).
- **Scenario:** monitor → CW onset → characterize (frequency, bandwidth, type, level, behavior) → interference report → PACE decision → graded debrief.
- Guided tutorial, glossary, and overlays (toggleable).

## Run locally
Double-click `index.html`. No server, no build step, no network needed.

URL options: `?nointro=1` skips the intro, `?seed=N` picks a scenario variation.

## Disclaimer
All satellites, transponders, frequencies, units, and organizations are **fictional**. Unclassified demo.
