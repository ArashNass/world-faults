# World Faults & Earthquakes

**Live tool:** https://arashnassirpour.com/world-faults/

An interactive global map of tectonic plate boundaries, named fault systems, and significant recent earthquakes.

## Features

- Plate boundaries colour-coded by tectonic mechanism.
- Twenty-two named fault systems.
- Significant earthquakes from the previous 30 days, retrieved live from USGS and shown by default, with an on/off switch, 24 h / 7 d / 30 d windows and a minimum-magnitude filter. A bundled snapshot is shown if the live feed is unreachable.
- Interactive map controls and event details.
- A statistics page at `/world-faults/stats/`: magnitude distribution, daily activity, depth breakdown, active swarms and notable volcanoes from the live USGS feed, with a map that offers Light, Dark, Satellite, Terrain, Street and NatGeo basemaps (all Esri, no API key).
- A Standard / Sentinel theme switch. The optional Sentinel mission-control theme is loaded on demand from `/sentinel/` in the main site repository (`arashnass.github.io`); when the page is opened locally the switch has no effect.
- A self-contained browser application with no build step.

Plate-boundary geometry is based on the Bird (2003) PB2002 model. Recent earthquake information is supplied by USGS and may be revised as events are reviewed.

The separate 3D Fault Mechanism application is available at https://arashnassirpour.com/earthquake-rupture/.

## Scope

This map is intended for learning and broad exploration. Displayed datasets are simplified, may be incomplete at local scale, and must not be used as a substitute for authoritative fault databases, site investigation, seismic-hazard analysis, or emergency information.

## Run locally

Open `index.html` in a modern browser or serve the repository with any static web server.

## Deployment

GitHub Pages publishes `main` at the live URL above.

## Licence

Copyright (C) 2026 Arash Nassirpour.

Licensed under the GNU Affero General Public License v3.0 only (`AGPL-3.0-only`). See [LICENSE](LICENSE).
