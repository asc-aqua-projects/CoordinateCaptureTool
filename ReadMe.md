# CoordinateCaptureTool
This code is not intended for reuse. Please do not redistribute or fork.

# ASC Map Viewer

This is a simple interactive web map built with [OpenLayers](https://openlayers.org/), using Esri’s World Imagery basemap. Click anywhere on the map to drop a custom pin and instantly get the latitude and longitude.

## Features

- Drop a pin by clicking the map
- Copy coordinates in plain text format (e.g., `Lat = ..., Lon = ...`)
- Generate a shareable link that opens the map with your pin and zoom level

## How to Use

1. Open the map in your browser.
2. Click anywhere — a teal pin will appear.
3. Use the **“Copy Coords”** button to copy plain text coordinates.
4. Use the **“Share”** button to copy a URL with the current location and zoom level.
   - You can share that link, and the map will open with the same view and marker.

## Credits

- **OpenLayers** – This map uses [OpenLayers](https://openlayers.org/) for all mapping and interaction features.
- **Esri World Imagery** – The satellite imagery comes from [Esri’s World Imagery service](https://www.arcgis.com/home/item.html?id=10df2279f9684e4a9f6a7f08febac2a9), accessed via  public tile API.
- **ASC Branding** – Styling, color scheme (`#00B3A9`), and logo are based on ASC’s official visual identity.
- **Clipboard API** – The “Share” and “Copy Coords” buttons use the [Clipboard API](https://developer.mozilla.org/en-US/docs/Web/API/Clipboard_API).
