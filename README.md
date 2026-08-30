# IRON CLASH

A complete, original 1-vs-1 Canvas fighting game. Choose between REX, KAI, and
ARJUN, then fight a tactical CPU opponent in a best-of-three underground match.

## Play

No build step or dependencies are required. Open `index.html` in a modern
browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Controls

| Action | Key |
| --- | --- |
| Move / dash | A / D (double-tap) |
| Jump / crouch | W / S |
| Light / heavy punch | J / K |
| Light / heavy kick | U / I |
| Guard | L |
| Signature attack / Rex's **BEAST RUSH** | O |
| Throw | J + U |
| Pause | Escape |

Touch controls appear automatically on mobile devices. All audio is synthesized
in the browser with the Web Audio API. Rex's in-game animations are transparent
runtime canvases cropped from the supplied character artwork using text-based
frame coordinates in `game.js`; no generated binary sprite assets are required.
