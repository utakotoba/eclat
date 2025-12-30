### Éclat

Éclat is an immersive, muted color theme meticulously crafted for focused coding. By pairing a modern, clean palette with a background deeper than typical "eye-care" themes, Éclat minimizes visual fatigue while maintaining exceptional clarity and a seamless aesthetic across editors and terminals.

### Status

Currently, we have two reference implementations — a [Visual Studio Code Theme](https://github.com/utakotoba/vscode-theme-eclat) and a [Zed Theme](https://github.com/utakotoba/eclat-zed) — which showcase the initial aesthetic of the palette. While these themes perform well in most scenarios, their colors were primarily hand-picked based on visual intuition rather than precise calculation. As a result, they may not yet provide optimal performance or consistent accessibility across all environments.

To address this, I am currently refining the palette using the OKLCH color space and APCA (Advanced Perceptual Contrast Algorithm) standards — the cutting edge of modern color theory. Transitioning to this scientific approach allows us to generate consistent color tokens for diverse use cases efficiently. Ultimately, this framework will serve as a tool to help you port and optimize your own themes using a data-driven, perceptually uniform methodology.

> ### Why OKLCH and APCA?
>
> Traditional color models like HSL often fall short when crafting a "peaceful" interface, as they fail to maintain consistent perceptual lightness across different hues. In my development, I found it nearly impossible to precisely calibrate the "visual depth" of colors against the same background using these models, leading to unintentional visual jarring. By adopting **OKLCH**, we can leverage a perceptually uniform color space that accurately maps how the human eye perceives brightness and chroma. This precision allows us to fine-tune the palette based on actual human sensitivity, ensuring every color sits at the exact visual height intended for a low-fatigue, immersive experience.
>
> While the legacy WCAG contrast standards are a common benchmark, they treat contrast as a symmetric calculation, ignoring color polarity (the fundamental difference between "light-on-dark" and "dark-on-light"). For a dark-themed coding environment, WCAG often suggests overly aggressive contrast levels that result in "visual blooming" or halos on self-emissive screens, creating unnecessary eye strain. **APCA (Advanced Perceptual Contrast Algorithm)**, however, is designed with modern displays and human physiology in mind. It accounts for the context of text size and background polarity, allowing us to achieve optimal readability without the harsh, high-pressure foregrounds typically produced by outdated standards.

### License

This project is open-sourced under the MIT License. You are free to use, modify, and distribute the tools and colors provided here. If they help you build something good, a small credit note or a link to this repository would be greatly appreciated.
