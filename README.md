# r3d drum

> AI-generated band. Glitched Americana for the simulation era.

**Reference:** The Velvet Sundown — *"The memory of a time that never actually happened."*

**Band members:** Vocalist · Drums · Guitar/Synths

---

## Sound

Dark instrumental post-rock/shoegaze with industrial noise textures and math-rock complexity. **A minor, 100 BPM.** Distorted guitar walls, relentless tension, cinematic builds.

**Tags:** post-metal, industrial, math-rock, shoegaze, dystopian, noise

**Confirmed tracks:** track_02 (postmetal dystopia, 6:58) = the reference sound

---

## Influences

- Austin TV / Caballeros del Albedrio — instrumental post-rock, cinematic builds, masks
- Mogwai — dynamic post-rock
- Hellblazer / Garth Ennis — sorcerous pulp energy
- Twin Peaks / The X-Files — lurking horror, open-ended dread
- The Ninth Gate — sorcerous subculture
- Lovecraft — *"Do not call up any that you cannot put down"*

---

## Band Members

| Role | Name | Status |
|------|------|--------|
| Vocalist | TBD | Open — see issue #1 |
| Drums | TBD | |
| Guitar / Synths | TBD | |

---

## Tracks

| Song | Date | Type | Duration | Status |
|------|------|------|----------|--------|
| The Colors Are Gone | 2026-03-31 | Vocal | ~3:00 | [SoundCloud]() |
| haunted signal | 2026-04-18 | Instrumental | 1:51 | [MP3](track_01_haunted_signal.mp3) |
| postmetal dystopia | 2026-04-18 | Instrumental | 6:58 | [MP3](track_02_postmetal_dystopia.mp3) |

---

## Generation Seeds (Hooks)

Short guitar/synth phrases generated via Ace-Step cloud API with reference audio from track_02.

See `hooks/` and `reference_clips/` directories.

---

## Workflow

```
Seed → Ace-Step cloud API (free, songwriting skill)
     ↓
Polish → MacBook Logic Pro + MIDI keyboard
     ↓
Vocals → Suno
     ↓
Distribute → SoundCloud, Spotify
```

**MacBook:** `tailscale ssh ulizzle@100.71.60.3` — files land in `~/r3d-drum/`
**Audio check:** `ssh macbook 'afplay ~/r3d-drum/hook_vX.mp3'`

---

## Open Issues

- #1 — Create vocalist persona
- #2 — Generate hooks with reference audio workflow
- #3 — Suno vocals for postmetal dystopia style
- #4 — Resolve RunPod SSH for Ace-Step SFT local

---

Repo: https://github.com/lux-sp4rk/the-r3d-drum
