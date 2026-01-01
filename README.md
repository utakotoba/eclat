### Éclat

Éclat is an immersive, muted color theme meticulously crafted for focused coding. By pairing a modern, clean palette with a background deeper than typical "eye-care" themes, Éclat minimizes visual fatigue while maintaining exceptional clarity and a seamless aesthetic across editors and terminals.

### Status

Currently, we have two reference implementations — a [Visual Studio Code Theme](https://github.com/utakotoba/vscode-theme-eclat) and a [Zed Theme](https://github.com/utakotoba/eclat-zed) — which showcase the initial aesthetic of the palette. While these themes perform well in most scenarios, their colors were primarily hand-picked based on visual intuition rather than precise calculation. As a result, they may not yet provide optimal performance or consistent accessibility across all environments.

To address this, I am currently refining the palette using the ~~OKLCH~~ (consider CAM16-UCS as for now) color space and APCA (Advanced Perceptual Contrast Algorithm) standards — the cutting edge of modern color theory. Transitioning to this scientific approach allows us to generate consistent color tokens for diverse use cases efficiently. Ultimately, this framework will serve as a tool to help you port and optimize your own themes using a data-driven, perceptually uniform methodology.

### License

This project is open-sourced under the MIT License. You are free to use, modify, and distribute the tools and colors provided here. If they help you build something good, a small credit note or a link to this repository would be greatly appreciated.
