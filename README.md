# Crystal Vortex

Interactive particle art piece. Crystal shards drift across a black canvas, responding to mouse interaction in real time.

[Try Demo](https://crystal-vortex.vercel.app/)

This app is meant to be used as an input source for [Daydream Scope](https://github.com/daydreamlive/scope).

## Interactions

- **Hover** over the canvas to pull particles toward your cursor in a vortex spiral
- **Click** to blast particles away from the click point
- **Move cursor off** the canvas to release particles back into random wandering

## How to run

Open `index.html` in a browser. No dependencies, no build step.

## Details

- ~150 procedurally generated crystal shards in jewel tones (sapphire, emerald, ruby, amethyst, topaz)
- Canvas2D rendering at 60fps
- Noise-based wandering for organic default motion
- Gradient trails that fade behind each shard
- Touch support for mobile
