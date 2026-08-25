# Portfolio animation assets

- `portfolio-retro-sequence.gif` — optimized for GitHub READMEs, documentation and places that accept animated images.
- `portfolio-retro-sequence.mp4` — higher-quality and smaller alternative for websites and social platforms that support video.

## Reuse

In Markdown:

```md
![Portfolio preview](./portfolio-retro-sequence.gif)
```

In HTML:

```html
<img src="./portfolio-retro-sequence.gif" alt="Animated portfolio preview" width="560">
```

For websites, prefer the MP4 because it usually loads faster and looks sharper:

```html
<video autoplay muted loop playsinline width="560">
  <source src="./portfolio-retro-sequence.mp4" type="video/mp4">
</video>
```
