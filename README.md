# HyperFrames Stop Motion

A paper stop-motion experiment, shot on a Fuji X-M5 and edited with HyperFrames and Grok 4.7.

[![A short preview of the film](media/preview.gif)](media/stopmotion-final.mp4)

[Watch or download the final video](media/stopmotion-final.mp4) · 55.5s · 1620 × 1080

## Behind the Scenes

<p>
  <img src="media/behind-the-scenes.jpeg" width="360" alt="The overhead camera and lighting setup">
  <img src="media/paper-interface.jpeg" width="360" alt="Moving a printed interface between shots">
</p>

## Development

Requires Node.js 22+ and FFmpeg.

```bash
npm run dev      # Start the preview
npm run check    # Validate the composition
npm run render   # Export at 24 fps
```

`index.html` mounts the photo sequence and curved credits in `compositions/`. All 231 source frames are in `assets/photos/`.

Music: *Last Train to London* — Electric Light Orchestra. [Asset credits and licenses](THIRD_PARTY_NOTICES.md).
