# r3d drum

AI-generated band. Glitched Americana for the simulation era.

**Reference:** The Velvet Sundown — *"The memory of a time that never actually happened."*

**Influences:** Austin TV, Caballeros del Albedrio, Mogwai, post-metal, industrial, math-rock, shoegaze

---

## Sound

Dark instrumental post-rock/shoegaze with industrial noise textures and math-rock complexity. A minor, 100 BPM. Distorted guitar walls, relentless tension, cinematic builds.

**Tags:** post-metal, industrial, math-rock, shoegaze, dystopian, noise, drill rap aggression

---

## Tracks

| Song | Date | Type | Duration | Status |
|------|------|------|----------|--------|
| The Colors Are Gone | 2026-03-31 | Vocal | ~3:00 | [SoundCloud]() |
| haunted signal | 2026-04-18 | Instrumental | 1:51 | [MP3](track_01_haunted_signal.mp3) |
| postmetal dystopia | 2026-04-18 | Instrumental | 6:58 | [MP3](track_02_postmetal_dystopia.mp3) |

---

## Hooks (Generation Seeds)

Short guitar/synth phrases generated via Ace-Step cloud API with reference audio.

| Hook | Reference | Description |
|------|-----------|-------------|
| hook_01_no_reference | none | First guitar-only pass, clean arpeggios |
| hook_02_reference_15s | clip_05s.wav | From 5s mark — reverb depth + minor key |
| hook_03_reference_30s_aggressive | clip_30s.wav | From 30s mark — overdriven, aggressive |

**Reference clips:** `reference_clips/` — 5-second wav slices from track_02

**Workflow:**
1. Seed generation → Ace-Step cloud API (free)
2. GPU polish → RunPod Ace-Step local (SFT model) — *pending: SSH access resolved*
3. Final polish → Logic Pro + MIDI keyboard on MacBook (via SSH)

**MacBook access:** `tailscale ssh ulizzle@100.71.60.3` — files land in `~/r3d-drum/`

**Remote audio check:** `ssh macbook 'afplay ~/r3d-drum/hook_vX.mp3'`

---

## Platform

- **Seed generation:** Ace-Step cloud API (free tier)
- **GPU polishing:** RunPod Ace-Step local (SFT model + Lego mode)
- **DAW / MIDI:** Logic Pro + MIDI keyboard
- **Distribution:** SoundCloud, Spotify

---

## Band Members

- **Vocalist**
- **Drums**
- **Guitar / Synths**

*(Identities TBD — open GH issue #1)*

---

Repo: https://github.com/lux-sp4rk/the-r3d-drum
