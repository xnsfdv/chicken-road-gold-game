# Chicken Road Gold game

[https://xnsfdv.github.io/chicken-road-gold-game/](https://xnsfdv.github.io/chicken-road-gold-game/)

Before `npm run build` not forget: `npm run lint -- --fix`

Requirements:
```
npm install @tweenjs/tween.js
npm install @pixi/sound
npm install solid-js
npm install -D vite-plugin-solid
npm install @esotericsoftware/spine-pixi-v8
```

#### In future:
- @pixi/sound use Audio Sprites base64.
- check switch to bun.
- Add an API to process requests from the server.

#### All images from source resizable and compressed:
- max 1280 height, because the level.
- export images from source to .webp(lighter size than .png), use compress, сompare quality and choose.

#### Alls audio used to convert from source to new .mp3 files or webm(check in ad service if support), prefer:
- Mono, quality 100%, or stereo if mono broke the sample from source.
- Sample rate, sound 11025 Hz, 22050 Hz(prefer) and more.
- 16 bit bit depth.
- export (Audition) Bitrate see options for your Sample rate, test and see how broke the sample from source.
- export (Audition) remove checkbox markers and metadata.
