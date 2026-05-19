# Spatial Analytics & Environmental Monitoring Dashboard

An interactive web application built with Python and Streamlit designed to demonstrate independent spatial data visualization, metric distribution analysis, and modern dashboard prototyping.

## Tech Stack & Skills Displayed
* **Language:** Python
* **Framework:** Streamlit (Web UI)
* **Data Core:** Pandas, NumPy
* **Core Competencies:** Interactive coordinate mapping, slider-driven dataset filtering, multi-column dashboard design, and isolated system dependency handling.

## Repository Structure
```text
spatial-analytics-dashboard/
│
├── .gitignore          # Prevents heavy data caches from cluttering version history
├── README.md           # Project abstract, methodology, and execution guide
└── src/
    └── app.py          # Main entry point for the Streamlit dashboard layout
```

## Future Roadmap / Scalability Focus
To transition this layout into an enterprise-scale scientific utility, future iterations will implement:
* **GDAL/Rasterio Integration:** Direct I/O streaming of multi-band satellite raster images (`.tif`) instead of simulated coordinate matrices.
* **Spatial Query Optimization:** Integrating geopandas and shapely to process complex vector geometries (`.geojson`).
* **Cloud Storage Syncing:** Decoupling the data layer to fetch archives dynamically from cloud storage buckets or web processing services (WPS).

## How to Run Locally
1. Clone this repository.
2. Install dependencies: `pip install streamlit pandas numpy`
3. Launch the dashboard: `streamlit run src/app.py`

---
## Author
Developed by **Ganesh Kappavandla** – Master of Technology (M.Tech) in Computer Science and Engineering. Dedicated to building scalable spatial data products, advanced deep learning implementations, and production data pipelines.
