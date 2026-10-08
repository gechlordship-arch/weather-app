# 🌤️ Weather App

> **Live weather. Beautifully animated. Works anywhere.**

A modern, feature-rich weather app built with plain HTML, CSS, and JavaScript — no frameworks, no build tools, no dependencies. Just open it and it works.

---

## ✨ Features

### 🎯 Core Weather
- **Current conditions** — temperature, feels-like, humidity, wind speed
- **Live updates** — refreshes automatically every 10 minutes
- **Precise location** — powered by Open-Meteo's free global weather API
- **Local time zone** — everything in the city's own time, not yours

### 🔍 Search Any City
- **Instant autocomplete** — type 2+ letters, see suggestions
- **Worldwide coverage** — over 40,000 cities and towns
- **Country + region shown** — so you pick the right one
- **Keyboard shortcuts** — Enter to pick, Esc to close, arrow-Enter for first result

### 📅 Forecasts
- **⏰ 24-hour hourly forecast** — scroll horizontally through the day
- **📅 7-day forecast** — high/low temps and weather icons for the week
- **💧 Rain probability** — shown per hour when rain is possible
- **🌡️ Temperature trends** — see the day's shape at a glance

### 🎨 Animated Backgrounds
Every weather condition has its own living background:

| Weather | Animation |
|---------|-----------|
| ☀️ **Clear day** | Pulsing golden sun glow |
| 🌙 **Clear night** | 55 twinkling stars |
| 🌤️ **Partly cloudy** | 2 slow-drifting clouds + sun |
| ☁️ **Overcast** | 4 drifting clouds |
| 🌧️ **Rain** | 5 clouds + 110 falling rain streaks |
| ⛈️ **Thunderstorm** | 7 clouds + heavy rain |
| ❄️ **Snow** | 5 clouds + 70 wobbling snowflakes |

Every animation transitions **smoothly** when switching cities.

### ⭐ Favorites
- **Save any city** with one tap (☆ → ★)
- **Quick-switch chips** below the search box
- **Persistent** — survives browser restart
- **Remove with ✕** on any chip

### 🌧️ Rain Alerts
- **Smart detection** — scans next 12 hours for rain
- **In-app banner** — appears when rain is coming
- **Severity levels** — blue for rain, purple for thunderstorm
- **Optional notifications** — real browser notifications (once per event)
- **No spam** — alerts you once, not every refresh

### 🗺️ Weather Maps
- **Interactive map** — powered by Leaflet
- **Live rain radar** — the last 2 hours of precipitation
- **Animated playback** — play/pause the radar motion
- **Timeline scrubbing** — drag to any frame
- **Color legend** — light blue → green → yellow → red → purple
- **Keyless basemap** — works without any API key

### 📱 Responsive Design
- **Mobile-first** — perfect on phones and tablets
- **Desktop-friendly** — wide layout on big screens
- **Touch gestures** — pinch, swipe, and scroll work naturally
- **Reduced motion** — respects `prefers-reduced-motion` for accessibility

---

## 🚀 Quick Start

### Option 1 — Just open it (simplest)

1. Download or clone this folder
2. Double-click `index.html`
3. Done — the app opens in your browser

**No installation. No terminal. No build step.**

### Option 2 — Serve locally (for PWA features)

If you plan to add offline support or install it as an app, serve it locally:

```bash
# Using npx (recommended)
npx serve

# Or using Python
python -m http.server 8000

# Or using Node
npx http-server