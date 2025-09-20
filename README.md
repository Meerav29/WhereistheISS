# Satellite Pass Predictor

A lightweight, browser-based tool that tells you when selected satellites will be visible overhead from your current (or a default) location. Uses [satellite.js](https://github.com/shashwatak/satellite-js) for orbital calculations and Tailwind CSS for styling.

---

## 🛰️ Features

- **Automatic geolocation**: Detects your latitude, longitude, and altitude via the browser’s Geolocation API.
- **Fallback location**: Defaults to Park Forest Village, PA if geolocation is unavailable or denied.
- **Satellite selection**: Choose from International Space Station, Tiangong Space Station and Hubble Space Telescope.
- **Visible-pass calculation**: Finds passes where the satellite is above 10° elevation, in sunlight, while you are in darkness.
- **Clean, responsive UI**: Styled with Tailwind CSS and the Inter font; adapts to mobile and desktop.
- **Live TLE fetching with caching**: Retrieves fresh orbital elements from CelesTrak, caching them for 12 hours with graceful fallbacks if the network is unavailable.

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser with JavaScript enabled.
- Internet connection to load external scripts (Tailwind CSS, Google Fonts, satellite.js).
- Network access to [CelesTrak](https://celestrak.org/) to fetch current two-line element (TLE) data for the supported satellites. The app caches the results for 12 hours to avoid unnecessary refreshes.

### Installation

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/meerav29/whereistheiss.git
   cd whereistheiss
