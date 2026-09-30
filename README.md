# Hume and Hovell Track: 3D map proof of concept

- `index.html`: section picker with a 3D terrain block per section (three.js), elevation profile, and per-section GPX downloads. Deep link with `?section=1` to `5` or `?section=all`.
- `concept-1/`: earlier full-screen, scroll-driven version (MapLibre GL JS + GSAP), served at `/concept-1/`.

## Run locally

```
npx serve .
```

Or enable GitHub Pages on `main`.

## Data sources

- Trail: `Hume_Hovell_Track.gpx`, full 426 km alignment from NSW Crown Lands. Section files in `gpx/` are split from it at the official section boundaries. Check terms of use before publishing.
- Section distances, times and grades: humeandhovelltrack.com.au.
- Imagery: NSW Spatial Services (CC BY 4.0). Esri World Imagery is a fallback for comparison and needs a licence for production.
- Elevation: AWS Terrain Tiles (Mapzen, terrarium encoding).
