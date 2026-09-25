# AI Trailblazers — editorial scrollytelling build

Static GitHub Pages-ready build. No build step required.

## Run locally

```bash
python -m http.server 8000 --directory .
```

Then open `http://localhost:8000`.

## Interaction rationale

Interactivity is only used where it adds understanding:

- **Profile explorer**: demonstrates that Trailblazer quality comes from the combination of five signals, not one score.
- **Identification scrollytelling**: shows three discovery routes converging, followed by profile fit and an organisational coverage lens.
- **Opportunity diagnostic**: lets the reader change the shape of a task and see the recommended intervention change.
- **Support map**: shows the three live connections around a Trailblazer and what moves through each.
- **Diffusion story**: shows adoption spreading through local networks and an emerging Trailblazer appearing.
- **Measurement explorer**: separates programme health from diffusion and value.
- **First-cycle route**: the horse moves through the implementation path as the reader progresses.

## Design research used

- Wolff Olins Lloyds identity / Cancara Philosophy
- Motion scroll-linked animation patterns
- Anime.js ScrollObserver and SVG motion-path capabilities
- Kokonut UI smooth tab patterns
- Untitled UI / React Aria interaction and accessibility patterns
- Aceternity Sticky Scroll Reveal / Timeline patterns
- Magic UI Animated Beam pattern
- React Bits scroll-stack / scroll-portal patterns

The build is intentionally bespoke rather than assembled from recognisable component-library sections.
