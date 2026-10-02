# Royal Navy Motion

Remotion intro video: continuous-camera world map built with turf.js + world-atlas, SVG icons and charts.

## Run

1. Copy your narration to `public/Intro.mp3`
2. `npm install`
3. `npx remotion studio`
4. `npx remotion render Intro out/intro.mp4`

Video length follows the audio length automatically. Scene timings are defined on a 200 s base timeline in `src/Video.tsx` and scaled to the real audio duration.
