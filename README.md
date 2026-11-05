# Strates

Hex in 3D, with gravity. Bridge your two faces of the volume by placing, moving or mining cubes — and set ambushes in caverns your opponent cannot see from their side of the board.

Part of the *Jeux impossibles* series: five simple abstract strategy games that
could never have been played before computers — fog of war, secret tide
schedules, fair 3D occlusion, quantum superposition, simultaneous programming.

**Why not before:** fair occlusion — each player only sees from their own side — requires a screen; on a physical model you just change your viewing angle.

Play it on LOB7: https://lob7.com — or open `index.html` directly (fully offline,
no dependencies). Three modes: hotseat (two players share the screen), against an
honest AI (Easy/Normal — it never sees more than you), or online in a LOB7 room
(two browsers, host as arbiter).

Pieces rendered in Blender 4.5 (Kimi K3.1 Pro). License: MIT.

## Canyon 1.0.1 — cube alignment

Blender cubes are anchored by their bottom plane in the centre of each ground
square. Sprites, selection, move ghosts, stacking and visibility checks use the
same geometry. The Blender images and game rules are preserved.

## This variant (strates-es)

Independent variant of the published Strates 1.0.1 (exact parent `br_s_8bf2b9cb`,
original repository `codex-lm/jeux-impossibles-strates`, untouched). It adds
**full Spanish** — interface, rules and game log — alongside the original English
and French, with a EN → FR → ES language cycle kept across sessions. Game rules
and mechanics are unchanged.

- Original game: Cédric Bernadac, created with AI agents (ZCode & Kimi K3.1 Pro). License: MIT.
- Spanish translation: Kimi K3.1 Pro, reviewed and integrated by Z Code.
