# RockEmSockEm Ice Fury — Original 6

A retro arcade hockey game inspired by Blades of Steel, playable entirely in the browser — no install, no dependencies, single HTML file.

**[Play it](https://raw.githack.com/BroPilot-AI/RockEmSockEm/master/index.html)**

---

## Features

- **6 NHL teams** — Rangers, Bruins, Canadiens, Maple Leafs, Blackhawks, Red Wings
- **Full hockey rules** — 3 periods, penalties, power plays, face-offs
- **3v3 Overtime** — sudden death after regulation ties
- **Shootout** — 3 rounds + sudden death if OT doesn't decide it
- **Teams switch sides** each period
- **Fighting system** — challenge opponents with F; both sides must agree
- **Bodychecks** — X to check nearby opponents
- **Power-ups** — Speed, Power Shot, Freeze, Big Puck spawn on ice
- **Smart goalie AI** — lane-checks before passing; 5-second delay-of-game rule
- **Pixel-art sprites** — rotation-based skater and goalie sprites
- **Crowd** — animated spectators that wave and cheer on goals
- **Chiptune SFX** — Web Audio API sound effects

---

## Controls

| Key | Action |
|-----|--------|
| Arrows / WASD | Move |
| Space | Shoot |
| Z | Pass |
| X | Bodycheck |
| F | Challenge to fight |
| Tab | Cycle controlled player |
| P / Escape | Pause |

**During a fight:** Z = left punch, X = right punch

**During shootout:** Space = shoot, Arrows/WASD = skate

---

## How to Play

1. Open `index.html` in any modern browser
2. Select your team with Up/Down, confirm with Space
3. Score more goals than the opponent after 3 periods
4. If tied → 3v3 Overtime (sudden death)
5. If still tied → Shootout (3 rounds + sudden death)

---

## Tech

Single-file vanilla JS — HTML5 Canvas + Web Audio API, zero dependencies.
