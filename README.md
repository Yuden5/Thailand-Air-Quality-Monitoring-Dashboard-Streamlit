# Thailand Air Quality IoT Monitoring Dashboard

![Welcome GIF](https://i.pinimg.com/originals/7d/01/2e/7d012e426a845a849bf0c017819916b0.gif)

**Course:** DSA-441 Cloud Computing  
**Live Application:** [https://thailand-air-quality-monitoring-dashboard.streamlit.app](https://thailand-air-quality-monitoring-dashboard.streamlit.app)

## Project Overview
This project implements a responsive multi-district IoT air quality monitoring dashboard for Thailand. Built to transition from a static prototype to an interactive web application, it integrates real-time telemetry ingestion with secure cloud secrets management and a modern, bright UI aesthetic.

---

## Key Features & Architecture
1. **Real-Time Data Integration:** Connects live to the **World Air Quality Index (AQI / WAQI) REST API** to stream live pollutant data (AQI, PM2.5, PM10, $O_3$) and meteorological metrics (Temperature, Humidity) across major Thai provinces and districts.
2. **Interactive Hoverable Sidebar Filtering:** Features a custom CSS-styled interactive district list that allows users to instantly filter regional metrics, map focuses, and analytics.
3. **Dynamic KPI Cards & Visualizations:** Instant metric updates including regional AQI status badges (`NORMAL`, `WARNING`, `ALERT`), pollutant breakdown bar charts, historical progress trend lines, and live Leaflet map overlays with AQICN tile layers.
4. **Cloud Security:** Credentials and API tokens are completely decoupled from source control using Streamlit's built-in `st.secrets` management.
5. **Production Hosting:** Deployed and hosted securely on **Streamlit Community Cloud** via automated GitHub synchronization.

---

## Tech Stack
* **Frontend / UI:** Python, Streamlit, Custom CSS (`style.css`), Markdown
* **Data Manipulation & APIs:** Pandas, Requests
* **Mapping & GIS:** Folium, Streamlit-Folium, AQICN Map Tile API
* **Cloud & DevOps:** Git, GitHub, Streamlit Community Cloud Secrets

---

## Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Yuden5/Thailand-Air-Quality-Monitoring-Dashboard-Streamlit.git](https://github.com/Yuden5/Thailand-Air-Quality-Monitoring-Dashboard-Streamlit.git)
   cd Thailand-Air-Quality-Monitoring-Dashboard-Streamlit
