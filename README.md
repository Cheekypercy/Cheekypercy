# 🚀 Cosmic Dash

A pixel-art endless runner — a cool space-astronaut twist on the Chrome offline dino game.
Built as a **single `index.html`** with vanilla JS + Canvas. No build step, no dependencies,
mobile-first. Just open it and play.

![pixel art](https://img.shields.io/badge/style-pixel%20art-23e0ff) ![no deps](https://img.shields.io/badge/dependencies-none-ff7a2d)

## ▶️ Play

**Live link:** https://cheekypercy.github.io/cheekypercy/  *(after Pages is enabled — see below)*

Or run it locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## 🎮 How to play

| Action | Touch (phone) | Keyboard |
| --- | --- | --- |
| Jump | Tap anywhere | `Space` / `↑` / `W` |
| Higher jump | Hold the tap | Hold the key |
| Duck / fast-fall | Swipe down | `↓` / `S` |
| Start / Retry | Tap the screen | Any jump key |

- Jump over **asteroids**, duck under flying **satellites**.
- The longer you survive, the **faster** it gets.
- Your **high score** is saved on your device (`localStorage`).
- Tap **SND** (top-right) to mute/unmute the retro blips.

## ✨ Features

- Crunchy pixel-art rendering (low-res buffer upscaled with `image-rendering: pixelated`).
- Hand-drawn sprites: animated astronaut, asteroids, satellites.
- Parallax twinkling starfield, drifting ringed planet, slowly shifting nebula.
- Jetpack particle bursts, landing dust, CRT scanline overlay.
- Variable jump height, ramping difficulty, Web Audio sound effects.
- Retro **Press Start 2P** HUD font.

## 🌐 Enable the phone link (one-time)

GitHub Pages just needs to be switched on once:

1. Go to the repo on GitHub → **Settings** → **Pages**.
2. Under **Source**, choose **Deploy from a branch**.
3. Branch: `claude/session-TfyZL`, folder: `/ (root)` → **Save**.
4. Wait ~1 minute, then open **https://cheekypercy.github.io/cheekypercy/** on your phone.

> Prefer a permanent link? Merge this branch into your default branch and point Pages at that instead.
