# Orbit Hopper

A one-tap arcade game built for YouTube Playables. Orbit a planet, tap to launch, and catch the orbit of the next one. Land perfect captures and collect stars for a high score.

**Play:** https://muharremozen04.github.io/Orbit-Hopper/

## Controls
Tap anywhere (or press Space) to launch.

## Tech
- Single-file HTML5 canvas game (`index.html`), no external assets
- Integrates the YouTube Playables SDK (`firstFrameReady`, `gameReady`, `saveData`/`loadData`, `onPause`/`onResume`, audio state)
- Outside YouTube the SDK is a no-op and progress is saved in `localStorage`
