# Bivariate Map
# 🗺️ Greensboro, NC Public Schools by Council District (2023)

This interactive map visualizes the public school locations and Greensboro City Council districts in 2023 using Leaflet.js and GeoJSON data. It highlights a **bivariate relationship** between council districts and public school types, making it easier to understand their spatial distribution across the city.

---

## 📌 Key Features

- 🟩 **Color-coded council districts** with hover functionality displaying district numbers.
- 🏫 **Public school icons** styled by school type:
  - Elementary School
  - Middle School
  - High School
  - K–12
  - Early College
- 🧭 **Legend** showing both district colors and school type icons.
- ⚙️ Built using:
  - Leaflet.js
  - Chroma.js (for color scales)
  - jQuery
  - Font Awesome
  - Google Fonts

---
## 📂 Project Structure

```bash
.
├── index.html              # Main HTML page with interactive map
├── assets/
│   ├── publicschools.geojson     # GeoJSON with public school locations and types
│   └── councildistricts.geojson  # GeoJSON with district polygons
└── README.md               # You're here!
