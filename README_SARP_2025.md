
# 2025 NASA SARP Coding Mentorship Repository

Welcome to the official coding and project repository for the 2025 NASA Student Airborne Research Program (SARP). This repository collects all lectures, demo projects, final student projects, utilities, and supporting materials developed and used during the program's technical training and project phase.

---

## About the Program

NASA SARP provides undergraduate students the opportunity to engage in real-world Earth system science research using NASA data. This repository represents the technical backbone of the program’s coding component, which spanned:

- Week 1: Python fundamentals and data analysis
- Week 2: Sample projects across domains (Aerosols, Oceans, Land, Atmosphere)
- Week 3 onwards: Final student-led research projects and presentations

---

## Repository Structure

```
├── Lectures/           # Core Python and data lectures
├── SampleProjects/     # Instructor-built examples by theme
├── FinalProjects/      # Student-generated project notebooks
├── Utilities/          # Reusable tools and code (e.g., shapefiles, plotting, stats)
├── Matlab/             # MATLAB starter content for multi-language learners
```

---

## Lecture Highlights

The `Lectures/` folder contains a full series of instructional notebooks covering:

- **Python Essentials**: data types, control flow, functions
- **Data Science Tools**: pandas, NumPy, seaborn, matplotlib
- **Geospatial Analysis**: geopandas, shapefiles, folium
- **NASA Data Access**: using Earthaccess and xarray to retrieve and explore MODIS/VIIRS satellite data
- **Scientific Plotting**: time series, scatter maps, histograms, correlation plots

---

## Sample Projects

The `SampleProjects/` directory contains instructor-led end-to-end examples from domains including:

- **Aerosols**: Analyzing NO₂ concentrations and P-3 flight patterns
- **Oceans**: Visualizing chlorophyll-a using VIIRS satellite data
- **Land**: Exploring fire-prone zones using elevation and land use overlays

Each includes sample analysis steps, plots, and data exploration for students to follow and build upon.

---

## Final Projects

The `FinalProjects/` directory includes data simulated Jupyter Notebooks submitted during the final phase of the program. These projects reflect individual or group investigations using airborne data collected during the field campaign.

---

## Utilities

The `Utilities/` folder includes:

- Pre-made heatmaps (folium)
- File format conversion tools (CSV, Excel, Parquet)
- Shapefile intersection examples
- Reusable statistical analysis code

---

## MATLAB Support

The `Matlab/` folder contains the official MATLAB tutorial notebook provided to support students who preferred or supplemented with MATLAB during early sessions.

---

## Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/NASA-SARP/2025-NASA-SARP-CodingMentorship.git
cd 2025-NASA-SARP-CodingMentorship
```

2. **Install requirements (optional but recommended)**

Create a virtual environment and install basic Python packages:

```bash
python -m venv env
source env/bin/activate  # or 'env\Scripts\activate' on Windows
pip install pandas numpy matplotlib seaborn geopandas xarray netCDF4 earthaccess jupyter
```

3. **Launch notebooks**

```bash
jupyter lab
# or
jupyter notebook
```

---

## Acknowledgments

This repository was maintained by **Sufian Aldogom**, NASA SARP 2025 Coding Mentor. Special thanks to the NASA Earth Science Division, program faculty, and student participants for making this experience a success.

---

## License

For educational and public use. Please cite NASA SARP when reusing.

