# PACKSENSE-AI---FOOD-RECOMMENDATION-SYSTEM-
#  PackSense AI - Intelligent Food Packaging Recommendation System

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)

## 📖 About The Project

**PackSense AI** is an intelligent, AI-powered food packaging recommendation system designed to solve the critical problem of food spoilage due to incorrect packaging. Small-scale farmers and SMEs often lack access to packaging science, leading to massive food waste. 

PackSense AI democratizes this knowledge by providing zero-barrier access for farmers while offering laboratory-grade precision for industry users. It features dynamic climate-route adaptation, computer vision pack auditing, and support for 22+ Indian languages, making it the ultimate tool for sustainable food logistics.

*Built for the **Smart India Hackathon (SIH)**.*

---

## ✨ Key Features

### 🧠 Dual-Mode Intelligence
* **Farmer/SME Mode:** Simple dropdown selection that auto-fetches scientific parameters (pH, respiration rate, fat profile).
* **Industry/Lab Mode:** Manual calibration for OTR, WVTR, seal strength, and ASTM compliance validation.

### 🗺️ Dynamic Climate Adaptation Engine
* **Real-Time Satellite Maps:** Integrated with Leaflet.js and Esri World Imagery.
* **Live Weather API:** Fetches real-time data (Open-Meteo) for origin and destination cities (Temperature, Humidity, Dew Point, Precipitation).
* **Smart Barrier Adjustment:** Automatically upgrades WVTR/OTR specs based on live humidity and temperature risks (e.g., +40% WVTR for monsoon routes).
* **Vehicle Simulation:** Animated route tracking supporting multiple transport types (Mini Truck, Reefer Van, 20-Ton Container, Rail, etc.).

### 📸 AI Visual Pack Audit (Computer Vision)
* Upload a photo of current packaging.
* Canvas-based pixel analysis simulates CNN detection of film opacity, reflectivity, and seal integrity.
* Instant "Protection Score" (0-10) with specific, actionable upgrade recommendations.

### 🌍 22+ Indian Languages & Multilingual Chatbot
* Full UI dynamic translation across all major Indian languages (Hindi, Tamil, Telugu, Marathi, Bengali, Gujarati, etc.).
* Interactive "Tomato" AI Chatbot that answers packaging queries in the user's native language.

### ♻️ Sustainability Intelligence
* Side-by-side comparison of conventional plastics (PET, BOPP, LDPE) vs. biodegradable alternatives (PLA, PHA, Cellulose).
* Interactive Chart.js bubble graphs showing Carbon Footprint vs. Cost trade-offs.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Vanilla JavaScript, Tailwind CSS (via CDN)
* **Mapping & GIS:** Leaflet.js, OpenStreetMap, Esri Satellite Tiles
* **Weather API:** Open-Meteo API (Free, No API Key required, Real-time)
* **Data Visualization:** Chart.js
* **Computer Vision Logic:** HTML5 Canvas API Pixel Analysis (Simulated MobileNetV2)
* **Fonts:** Inter (Google Fonts)

---

## 🚀 Getting Started

No complex installation or backend required! This is a lightweight, fully functional frontend application.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shrey-as937/packsense-ai-food-recommendation.git
