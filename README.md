# City Size Comparison Tool - Geospatial Comparison Tool 2026

> **City Size Comparison Tool** is an interactive, browser-based map for examining real administrative boundaries at a consistent scale. The current build emphasizes visual size comparisons between supported locations, including New York City and Los Angeles.

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leon-lambert1992/city-boundary-size-compare?style=flat-square)](https://github.com/leon-lambert1992/city-boundary-size-compare)

---

<p align="center">
  <a href="https://leon-lambert1992.github.io/city-boundary-size-compare/">
    <img src="https://img.shields.io/badge/Download-City%20Size%20Comparison%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download City Size Comparison Tool">
  </a>
</p>

> **[Download City Size Comparison Tool Latest](https://leon-lambert1992.github.io/city-boundary-size-compare/)**

---

[Download Latest Build](https://leon-lambert1992.github.io/city-boundary-size-compare/)

---

## Explore City Size Comparison Tool

This tool places administrative boundary data on an interactive map, allowing users to see how the footprints of different cities compare. Because the overlays are rendered with scale-aware geometry, the result provides a more accurate visual reference than approximate silhouettes or basic city labels.

It is useful for learners studying urban planning, educators, geography and map enthusiasts, and anyone interested in data visualization. The map includes controls for moving and rotating one city over another, making it possible to examine their spatial relationship directly in a web browser.

---

## Capabilities

- Examine cities through real administrative boundary datasets
- Display GeoJSON boundaries as semi-transparent map layers
- Compare relative footprints using scale-aware geometry
- Rotate an overlay city to test alternate orientations
- Move an overlay around the map
- Adjust the movement increment for more precise positioning
- Restore the overlay's location and angle with reset controls
- Use the responsive interface on desktop and mobile devices
- Work with the currently supported New York City and Los Angeles datasets
- Navigate the map through a Leaflet-based view

---

## Getting Started

### Open the hosted version

Launch the current web build in a modern browser:

[Launch City Size Comparison Tool](https://leon-lambert1992.github.io/city-boundary-size-compare/)

### Set up a local copy

Download the repository and move into its directory:

```bash
git clone https://github.com/leon-lambert1992/city-boundary-size-compare.git
cd REPO
```

Open `index.html` in your browser afterward. When local file restrictions prevent the datasets from loading, start a basic local web server for the project directory and open the server address it supplies.

---

## How to Use the Map

1. Open the hosted application or start the local project.
2. Choose one of the available city boundary datasets.
3. Inspect the base city and the selected overlay on the map.
4. Reposition the overlay with the movement controls.
5. Select a different movement step when exact placement is required.
6. Rotate the overlay to view another alignment.
7. Reset the overlay to its starting position and rotation when needed.
8. Compare the cities through the semi-transparent boundary layers.

At present, the available datasets cover New York City and Los Angeles.

---

## Settings and Local Files

The page controls city selection, overlay translation, rotation, movement step size, and reset operations. Standard use does not require a separate configuration file.

When working locally, leave the project files and GeoJSON boundary assets in their expected repository paths. The browser relies on those locations to load the map and its datasets correctly.

---

## Requirements

To use the application, you need:

- A current desktop or mobile web browser
- JavaScript enabled in that browser
- Internet access for the hosted application and externally loaded map resources
- A local repository copy for development or offline use
- Enough browser memory and storage for interactive map layers

The tool does not need a native desktop installation.

---

## Frequently Asked Questions

### What cities can I compare?

The supplied boundary data currently includes New York City and Los Angeles.

### Does the overlay support movement and rotation?

Yes. You can translate and rotate the comparison layer, choose the movement increment, and restore its default state with the reset controls.

### Can I use it from a mobile phone?

The interface adapts to desktop and mobile screen sizes. The amount of available screen space and the browser's controls can influence how the map is viewed.

### Where can I find the newest build?

Open the [latest hosted build](https://leon-lambert1992.github.io/city-boundary-size-compare/). You can also track repository changes and releases through [GitHub](https://github.com/leon-lambert1992/city-boundary-size-compare).

### Why does the map fail when I open the local HTML file?

First verify that the clone completed successfully and that the GeoJSON files are still in their expected locations. Some browsers block local data requests, so serve the project with a local web server rather than opening the HTML file directly.

### Are application settings saved in a configuration file?

No separate user configuration file is needed for normal operation. Settings are applied through the controls within the web page.

---

## Planned Improvements

- Add more city boundary datasets
- Broaden comparison workflows to cover additional geographic areas
- Further tune the controls for desktop and mobile layouts
- Provide additional ways to visualize boundary-based comparisons

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
