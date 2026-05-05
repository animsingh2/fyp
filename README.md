# Hong Kong Climate Risk Web Map

An interactive web map for visualising climate risk across Hong Kong districts, built as a Final Year Project.

## Overview

The map displays four spatial indices across Hong Kong's 18 districts:

- **Hazard Index** — flood, landslide, and urban heat island scores
- **Vulnerability Index** — population and income vulnerability
- **Resilience Index** — economic, social, and environmental resilience
- **Risk Index** — combined risk score per district

## Features

- Toggle layers on/off via the layer control panel
- Filter districts by index score using range sliders
- Click any point to view detailed attribute data
- Search districts by name
- Locate your current position on the map

## Usage

Open `index.html` in a browser. No server or build step required — all data is loaded locally from the `data/` folder.

## Stack

- [Leaflet.js](https://leafletjs.com/) — interactive maps
- [qgis2web](https://github.com/tomchadwin/qgis2web) — QGIS to web export
- CartoDB Positron — base tile layer

## Project Structure

```
├── index.html        # Main application
├── data/             # GeoJSON data for each index layer
├── css/              # Leaflet and custom styles
├── js/               # Leaflet plugins and scripts
├── legend/           # Legend images for each layer
└── images/           # Additional assets
```

## License

GPL-3.0
