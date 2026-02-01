<img align="center" width="100%" height="200" style="object-fit: cover" src="Gemini_Generated_Image_vp2kcvvp2kcvvp2k.png">

<h1 align="center">🌧️ Indian Rainfall Data Analysis</h1>

<p align="center">
  <strong>High-Fidelity Exploratory Data Analysis & Interactive Glassmorphism Dashboard</strong>
</p>

<div align="center">

![Jupyter](https://img.shields.io/badge/JUPYTER-NOTEBOOK-ffa726?style=for-the-badge&logo=jupyter&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML/CSS-DASHBOARD-0056b3?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JAVASCRIPT-INTERACTIVE-ffa726?style=for-the-badge&logo=javascript&logoColor=black)

</div>

---

## 🌟 Overview

This project presents a comprehensive, high-fidelity analysis of **64 years of Indian Rainfall data (1951-2014)**. It bridges the gap between deep statistical exploration in Python and premium, interactive web-based data visualization, providing a holistic view of climatic trends across 36 meteorological subdivisions.

### **Core Objectives:**

- 🔍 **Deep EDA:** Uncovering granular temporal and regional rainfall patterns.
- 📉 **Trend Forecasting:** Monitoring climate stability and shifts over decades.
- 🤖 **ML Insights:** Implementing regional clustering and trend-line prediction.
- 💻 **UI Excellence:** A premium, immersive dashboard built with modern design principles.

---

## 🚀 Live Dashboard

The interactive dashboard is live and can be accessed at the following link:

[![Live Site](https://img.shields.io/badge/Live-Dashboard-ffa726?style=for-the-badge&logo=github-pages&logoColor=white)](https://ajaygangwar945.github.io/Rainfall-Data-Analysis-Project/)

---

## 📊 Dataset Deep Dive

A curated dataset from the **Indian Meteorological Department (IMD)**:

| Feature | Details |
| :--- | :--- |
| **Time Frame** | 1951 - 2014 (64 continuous years) |
| **Regions** | 36 Meteorological Subdivisions of India |
| **Total Records** | ~2,300 high-integrity data points |
| **Variables** | Monthly, Seasonal, and Annual aggregates; Regional IDs |
| **Preprocessing** | Median imputation for gaps; Z-score outlier detection |

---

## 🛠️ Technical Implementation

### **1. Advanced Analysis (`Rainfall.ipynb`)**

A complete data science workflow leveraging the Python ecosystem:

- **Statistical Testing:** T-tests for period comparison and comprehensive correlation matrices.
- **Modeling:** Linear regression for predictive trends and K-means for regional intensity clustering.
- **Geospatial:**Folium-based mapping for regional intensity visualization.
- **Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`, `SciPy`.

### **2. Premium Dashboard (`index.html`)**

An immersive web experience focusing on aesthetics and performance:

- **Glassmorphism UI:** Translucent cards with 12px blur, adaptive borders, and responsive layouts.
- **Interactive Visuals:** Dynamic annual trends and seasonal charts using `Chart.js` and `Plotly.js`.
- **Theming:** Full synchronization between Light and Dark modes.
- **Micro-interactions:** Animated 3D rain background and CSS-driven hover effects.

---

## 📈 Analytical Highlights

> [!NOTE]
>
> ### Key Statistical Findings
>
> - **Mean Annual Rainfall:** 1,411.2 mm across India.
> - **Monsoon dominance:** June-September accounts for ~75% of annual precipitation.
> - **Extreme Events:** 13 major outlier events detected, primarily in coastal regions.
> - **Stability:** Statistical tests show no fundamental pattern shift pre/post 1980.

---

## 📂 Project Architecture

```bash
.
├── Rainfall.ipynb      # Advanced analysis & ML workbook
├── Rainfall.csv        # Raw dataset from IMD
├── index.html          # Dashboard entry point (Premium UI)
├── style.css           # Glassmorphism design system
├── rain_icon.svg       # Project branding & assets
└── README.md           # Documentation
```

---

## 🔧 Setup & Usage

### **Local Analysis**

```bash
pip install jupyter pandas numpy matplotlib seaborn scipy scikit-learn plotly folium
jupyter notebook Rainfall.ipynb
```

### **Dashboard Preview**

Open `index.html` in any modern browser, or serve via Python:

```bash
python -m http.server 8000
```

---

<div align="center">

**Developed by [Ajay Gangwar](https://github.com/ajaygangwar945)**  
*⭐️ If this project provided value, please consider a star on GitHub! ⭐️*

</div>
