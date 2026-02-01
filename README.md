<img align="center" width="100%" height="250" style="object-fit: cover; " src="Gemini_Generated_Image_vp2kcvvp2kcvvp2k.png">

<h1 align="center">🌧️ Indian Rainfall Data Analysis</h1>

<p align="center">
  <strong>Comprehensive Exploratory Data Analysis & Interactive Dashboard</strong>
</p>

<div align="center">

[![Python](https://img.shields.io/badge/PYTHON-3.x-0288d1?style=flat&logo=python&logoColor=white)](https://www.python.org/)
![Jupyter](https://img.shields.io/badge/JUPYTER-NOTEBOOK-ffa726?style=flat&logo=jupyter&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML/CSS-DASHBOARD-0056b3?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JAVASCRIPT-INTERACTIVE-ffa726?style=flat&logo=javascript&logoColor=black)
![Design](https://img.shields.io/badge/DESIGN-GLASSMORPHISM-0056b3?style=flat)

</div>

---

## 🌟 Overview

This project presents a deep dive into **64 years of Indian Rainfall data (1951-2014)**. It combines rigorous statistical analysis in Python with a high-fidelity, interactive web dashboard for visualizing complex climatic patterns across 36 meteorological subdivisions.

### **Core Objectives:**

- 🔍 **EDA:** In-depth exploration of temporal and regional rainfall patterns.
- 📈 **Trend Analysis:** Identifying stable trends and shifts over decades.
- 🤖 **ML Insights:** Using K-means clustering and Linear Regression for categorization and forecasting.
- 💻 **Interactive Dashboard:** Premium web interface built with Glassmorphism design principles.

---

## 📊 Dataset Deep Dive

| Feature | Details |
|:--- |:--- |
| **Data Source** | Indian Meteorological Department (IMD) |
| **Time Frame** | 1951 - 2014 (64 continuous years) |
| **Granularity** | Monthly, Seasonal, and Annual aggregates |
| **Regions** | 36 Meteorological Subdivisions of India |
| **Total Records** | ~2,300 data points |
| **Key Variables** | SD_Name, Year, JAN-DEC, Annual, Seasonal Peaks |

---

## 🚀 Key Project Components

### **1. Advanced Analysis (`Rainfall.ipynb`)**

A complete data science workflow leveraging the Python ecosystem:

- **Preprocessing:** Median imputation for missing values and outlier detection.
- **Statistical Testing:** T-tests for period comparison and correlation matrices.
- **Modeling:** Linear regression for trend prediction and K-means for regional clustering.
- **Geospatial:** Folium maps for regional intensity visualization.

### **2. Premium Dashboard (`index.html`)**

An immersive, interactive experience featuring:

- **Glassmorphism UI:** Modern translucent cards with 20px blur and adaptive borders.
- **Dynamic Themes:** Full synchronization between Light/Dark modes and all charts.
- **Immersive Effects:** 3D animated rain background using Three.js and CSS ripples.
- **Chart.js & Plotly:** Interactive annual trends, seasonal heatmaps, and intensity distributions.

---

## 📈 Analysis Highlights

> [!NOTE]
>
> ### Statistical Summary
>
> - **Mean Annual Rainfall:** 1,411.2 mm
> - **Monsoon Impact:** June-September contributes ~75% of annual rainfall.
> - **Peak Event:** Coastal Karnataka recorded 5,554 mm in 1961.
> - **Climate Stability:** T-tests indicate no major shift in patterns pre/post 1980.

---

## 📂 Project Navigation

```bash
.
├── Rainfall.ipynb      # Main analysis & exploration notebook
├── Rainfall.csv        # Raw dataset from IMD
├── index.html          # Interactive dashboard entry point
├── style.css           # Premium Glassmorphism styling
├── rain_icon.svg       # Dashboard favicon & assets
└── README.md           # Project documentation
```

---

## 🔧 Installation & Usage

### **Prerequisites**

```bash
pip install jupyter pandas numpy matplotlib seaborn scipy scikit-learn plotly folium
```

### **Run Locally**

1. **Notebook:** Start Jupyter and open `Rainfall.ipynb`.
2. **Dashboard:** Open `index.html` directly in your browser, or serve via Python:

    ```bash
    python -m http.server 8000
    ```

---

<div align="center">

**Developed by [Ajay Gangwar](https://github.com/ajaygangwar945)**  
*⭐️ If you find this project useful, please consider giving it a star! ⭐️*

</div>
