# Flappy Bird

A feature-rich Flappy Bird clone in a single HTML file. No dependencies, just open and play.

## Features

- **3 Difficulty Levels**: Easy, Medium, Hard — each with tuned speed, gravity, and pipe gap
- **Procedural Audio**: Flap, score, coin, hit, and swoosh sounds via Web Audio API — no audio files needed
- **Visual Effects**: Parallax hills background, wing flap animation, particle feathers, screen shake, floating score popups, collectible coins with bob animation
- **Medal System**: Try Again → Bronze → Silver → Gold → Platinum based on score
- **11 Achievements**: First flight, coin hoarder, medalist, difficulty wins, and more
- **Progressive Difficulty**: Pipe speed gradually ramps up during a session
- **Near-Miss Bonus**: +2 points for tight squeezes beside pipes
- **Stats Tracking**: Games played, total score, coins collected, per-difficulty wins (persisted in localStorage)
- **Pause / Resume**: Esc or P key, or the pause button
- **Responsive Canvas**: Scales to fit any screen, fullscreen button included
- **Mobile Support**: Touch events, viewport-optimized

## Controls

| Action | Desktop | Mobile |
|--------|---------|--------|
| Flap | Space / Click | Tap |
| Pause | Esc / P | — |

## How to Play

1. Select a difficulty (Easy, Medium, Hard)
2. Press **Play** or hit Space
3. Tap/click to flap — avoid the pipes and ground
4. Collect coins for bonus points; squeeze close to pipes for near-miss bonuses

## Files

- `flappy.html` — the entire game
