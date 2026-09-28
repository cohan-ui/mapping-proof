# Hume and Hovell Track: 3D map proof of concept

Scroll-driven 3D terrain and trail map built with MapLibre GL JS and GSAP ScrollTrigger.

## Run locally

Serve the folder (map tiles won't load reliably from `file://`):

```
npx serve .
```

Then open the local URL.

## Data sources

- Trail: `Hume_Hovell_Track.gpx`, full 426 km alignment from the Hume + Hovell Track site (NSW Crown Lands). Check terms of use before publishing.
- Imagery: NSW Spatial Services (CC BY 4.0). Esri World Imagery is included for comparison only and needs a licence for production.
- Elevation: AWS Terrain Tiles (Mapzen, terrarium encoding).

The free tile endpoints have no uptime guarantee. For production, self-host tiles or use a paid provider.
