# Children of Chaos — Wreckwood Ambush (visual playtest)

This is a **one-battle playable proof of concept**, NOT the complete Chapter One campaign. It uses the approved concept illustrations and extracted images, with a simple two-stage attack transition. All battle stats, combat decisions, movements, and HP are interactive; the cinematic attack illustrations are fixed stills with a two-stage zoom/flash animation.

## GitHub Pages
1. Extract the ZIP and upload the **contents** of this folder into a GitHub repository's root (including assets directory).
2. Under repository Settings → Pages choose `Deploy from a branch`, `main`, `/(root)`.
3. Open the new `https://<username>.github.io/<repository>/` link on iPhone Safari, then Share → Add to Home Screen.
4. Visit online once to cache the files for offline play. Progress is saved in that browser's local storage.

## Controls
- Tap allied hero to select.
- Tap highlighted blue square to move (once per turn).
- Choose Attack, then tap a nearby enemy (Duncan's range is 3; Alabor and Gwark's range is 1).
- Alabor may cast Healing Light on a nearby ally; anyone may use a shared potion.
- Wait ends a hero's turn; End Turn triggers AI.
- Win by defeating all foes.

## Art/technical limitations
- Sprites were **extracted from completed screenshots** and have imperfect edges; no complete frame-by-frame sprite sheets exist yet.
- Two-stage transitions use fixed illustration stills with brightness/scale changes, not individually animated limbs/characters.
- Some numbers shown *inside the artwork* are baked into the illustrations, while actual combat HP and damage are computed separately; the dynamic battle log and overlay caption show the actual values.
- Background removal uses inpainting, so some reconstructed terrain patches may be imperfect.
- Tested for static syntax and package structure, but not physically tested on iPhone.
