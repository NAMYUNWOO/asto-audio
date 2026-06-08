# 어스토니시아 사운드 · Astonishia Audio

A themed in-browser **BGM jukebox** for *Astonishia Story* (어스토니시아 스토리),
built with [LÖVE2D](https://love2d.org/) and compiled to the web with
[love.js](https://github.com/Davidobot/love.js).

**▶ Play: https://namyunwoo.github.io/asto-audio/**

- Plays the 41 converted `event_stream` music tracks (looping, seek, volume).
- Re-skinned with original Astonishia sprite art — ornate title frame, an
  animated character (Lloyd / 로이드), retro numeric glyphs, and the neodgm
  (네오둥근모) pixel font.
- PC and mobile friendly: responsive landscape / portrait layout, touch
  controls, and a "tap to start" gate for browser audio.

## Controls

| | |
|---|---|
| Select track | ↑ / ↓ or tap a row |
| Play / pause | Enter / Space or the ▶ button (double-tap a row to play) |
| Stop | `S` or ■ |
| Seek | ← / → or tap the progress bar |
| Loop | `L` or the loop button |
| Search | `/` (desktop) |

## Build

This site is generated from the `asto_audios/` project in the
[astonishiastory-love2d](https://github.com/NAMYUNWOO/astonishiastory-love2d)
repo via `asto_audios/build_dist.sh` (love.js `-c` compatibility mode — no
COOP/COEP headers required, so it runs on GitHub Pages and mobile browsers).

All audio and art are converted from the original game data; nothing here is a
runtime read of the original copyrighted resource files.
