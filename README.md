# 🏎️ FastF1 Telemetry & Lap-Time Analysis Toolkit

This repository contains a Jupyter Notebook built using the **FastF1** Python library to analyze Formula 1 race weekends.  
It includes functions for extracting telemetry, lap times, session details, driver comparisons, and generating high-quality visualizations.

---

## 📌 Features

### ✅ **1. Data Extraction**
- Load any F1 session (Practice, Qualifying, Race).
- Retrieve driver list, lap data, stint data, and weather information.
- Cache functionality for faster repeated access.

### ✅ **2. Helper & Utility Functions**
- Wrapper functions for:
  - Safe session loading  
  - Driver filtering  
  - Getting best laps  
  - Fetching telemetry & delta times  
  - Merging lap and telemetry data  

### ✅ **3. Telemetry Visualization**
- Speed traces  
- Throttle & brake overlays  
- Gear shifts  
- Racing lines  
- Delta time comparison  

### ✅ **4. GP & Season Setup**
- Predefined lists for:
  - Season races  
  - Drivers per season  
- Easy selection of: **year → GP → session → drivers**

