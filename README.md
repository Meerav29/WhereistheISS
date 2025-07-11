# Satellite Pass Predictor

A lightweight, browser-based tool that tells you when selected satellites will be visible overhead from your current (or a default) location. Uses [satellite.js](https://github.com/shashwatak/satellite-js) for orbital calculations and Tailwind CSS for styling.

---

## 🛰️ Features

- **Automatic geolocation**: Detects your latitude, longitude, and altitude via the browser’s Geolocation API.
- **Fallback location**: Defaults to Park Forest Village, PA if geolocation is unavailable or denied.
- **Satellite selection**: Choose from International Space Station, Tiangong Space Station and Hubble Space Telescope.
- **Visible-pass calculation**: Finds passes where the satellite is above 10° elevation, in sunlight, while you are in darkness.
- **Clean, responsive UI**: Styled with Tailwind CSS and the Inter font; adapts to mobile and desktop.

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser with JavaScript enabled.
- Internet connection to load external scripts (Tailwind CSS, Google Fonts, satellite.js).

### Installation

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/meerav29/whereistheiss.git
   cd whereistheiss
