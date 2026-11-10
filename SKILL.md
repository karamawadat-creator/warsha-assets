---
name: warsha-sounds
description: Karam's two standard Warsha Sport sound files (Whoosh_01.wav and Transition.wav). Use in EVERY Warsha Sport motion-graphics video or frame build, before mixing any audio.
---

# Warsha Sport standard sounds

This folder contains his two original sound files, byte-exact:

- `Whoosh_01.wav` (about 2.6 s, 44.1 kHz stereo): play it every time an element enters from the bottom or moves left/right (cutout rising, square or crest sliding in, newspaper sliding up, halves splitting). Gain about 0.8, starts at the start of the movement.
- `Transition.wav` (about 0.7 s, 48 kHz stereo): the black-band photo-to-photo transition sound, starting about 0.36 s before the cut.

Rules: never replace them with synthetic sounds; never continue without them. If a file is missing, say so plainly.

How to use: copy both files from this skill's folder (the folder that contains this SKILL.md) into the working directory's `sounds/` folder, for example `mkdir -p sounds && cp <this skill folder>/*.wav sounds/`, then check with ffprobe that both durations match the numbers above.
