# Profile assets

- `profile-scene.webp` is copied from `portfolio-v2/public/images/optimized/erdtree-ultrawide-1280.webp`. It is the approved portfolio scene without baked-in branding or copy.
- `profile-hero-base.svg` is the editable banner source; `profile-hero-base.webp` is its theme-safe raster render.
- `profile-hero.svg` layers the rasterized banner and animated AR GIF into one self-contained asset. Both sources are embedded so GitHub can animate it without loading nested files or intermittently dropping SVG text layers.
- `covent-icon.svg` is copied from the portfolio's approved Covent mark; its fill is fixed to gold so it remains visible in GitHub's light and dark themes.
- `metal-icon.svg` is copied from the portfolio's approved Metal mark.
- `ycombinator-logo.png` is a 96×96 derivative of Y Combinator's official site favicon.
- `a16z-mark.svg` reproduces the compact `a16z` text mark defined by the portfolio's `CompanyMark` component for GitHub's light and dark themes.
- `animated-ar-logo.gif` is a transparent 160×160, 10-second capture of the portfolio's live `AnimatedARLogoMark` component. It preserves the original outside-in power-up, hold, center-out drain, aura, and mote timing.
- `stack/*.svg` contains locally stored technology marks downloaded from the Simple Icons CDN and Devicon. `net-http.svg` reuses the Go mark because `net/http` is part of Go's standard library and has no separate brand mark.

The portfolio scene and animated AR logo are original project assets. Employer and investor marks remain the property of their respective companies and are used only for identification. Keep this directory limited to media used by the GitHub profile README.

The entire profile hero links to the portfolio. Individual navigation links remain immediately below it because GitHub strips positioning styles, background attributes, embedded objects, and forced new-tab attributes from README HTML.
