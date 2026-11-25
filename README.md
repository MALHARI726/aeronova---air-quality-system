# VayuMitra – Intelligent Air Quality Monitoring & Investigation Platform

**VayuMitra – Beyond Air Quality Monitoring** is a multi-page environmental monitoring, pollution investigation, predictive analytics, clean-air routing, and community reporting platform built strictly with **HTML5, CSS3, Vanilla JavaScript, Chart.js, Leaflet.js, Python (Flask), and SQLite3**.

---

## Navigation & Core Modules

Every page shares a responsive 7-section navigation system (**Home**, **Insights**, **Routes**, **Alerts**, **Reports**, **Community**, **Profile**) with a **single global Indian city search bar** in the top navigation bar.

1. **Home – Intelligent Air Dashboard (`frontend/index.html`)**
   - Unblurred animated Indian city backgrounds (Mumbai, Delhi, Bengaluru, Kolkata, Chennai, and pan-India fallback) with ambient leaf drift and time-of-day greeting.
   - Live AQI card supporting **Indian NAQI (0–500)**, **US EPA (0–500)**, and **EU EAQI** standards cleanly separated across **6 semantic AQI levels** (`Good`, `Satisfactory`, `Moderate`, `Poor`, `Very Poor`, `Severe`).
   - Displays PM2.5, PM10, NO2, SO2, CO, O3, weather telemetry (temperature, humidity, wind speed), source attribution, and update timestamps.

2. **Insights – Pollution Intelligence (`frontend/insights.html`)**
   - **Likely Pollution Sources**: Analyzes pollutant ratios (PM2.5/PM10, NO2, SO2, CO, O3), meteorology, and a **Today vs. Past Average** table.
   - **AQI Forecast & 3-Day Outlook**: Combines Open-Meteo recent context (`past_days=3`) with `forecast_days=3` predictions, uncertainty bounds, and a 3-day outlook grid.
   - **Best Outdoor Windows**: Cleanest and highest-pollution hourly windows with practical guidance.
   - **What-If Simulator**: Interactive 5-slider scenario explorer with before/after Chart.js comparison.

3. **Routes – Clean Air Routes (`frontend/routes.html`)**
   - Interactive **Leaflet.js** map comparing **2 clear route ways**: **Ordinary Route** (fastest standard path) vs. **Safe Air Route** (cleanest / hotspot-avoiding corridor) with travel time (`min`), distance (`km`), average AQI, **Nearby Hotspots**, **Incident Updates**, and **Emergency Escape Mode** (`routes.html?escape=1`).

4. **Alerts – Alerts & Precautions (`frontend/alerts.html`)**
   - Location-based pollution advisories, custom AQI/PM2.5 thresholds, 6-level AQI guide (`Good` through `Severe`), quick Escape Route jump, and nearby hotspot/incident updates.

5. **Reports – Reports (`frontend/reports.html`)**
   - Streamlined Daily, Weekly, Monthly, and custom date-range summary with optional side-by-side **Compare City**, 4 key KPIs, AQI Trend & Pollutant Averages charts, Peak Pollution Hours, Print, and CSV download.

6. **Community – Air Guardian Community (`frontend/community.html`)**
   - Color-coded category feed (`Smoke and burning`, `Construction dust`, `Industrial emissions`, `Garbage burning`, `Vehicle-related pollution`, `Other environmental issues`), Guardian impact cards, GPS support, optional photo upload (`PNG/JPG/JPEG/WEBP <= 5 MB`), filters, and status tracking.

7. **Profile – Profile & Personal Air Twin (`frontend/profile.html`)**
   - Save frequent places with daily time spent (`hours/day`), manage daily routines, view weekly exposure & location charts, log Exposure Diary entries, export CSV, and manage concise Profile, AQI Standard, Alert, Privacy, and Password settings.

---
