<h1 align="center">🌧️ Rainfall Data Analysis Project</h1>

<div align="center">

### Comprehensive Exploratory Data Analysis of Indian Rainfall Patterns (1951-2014)

![Status](https://img.shields.io/badge/Status-Completed-success?style=flat)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML/CSS-Dashboard-E34C26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Interactive-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Visualization-4C72B0?style=flat)
![Plotly](https://img.shields.io/badge/Plotly-Interactive_Charts-3F4F75?style=flat)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

</div>

---

## 📂 Project Structure & Files

| File Name | Type | Description | Purpose |
|----------|------|-------------|---------|
| `Rainfall.ipynb` | Jupyter Notebook | Complete data analysis workflow | Main analysis script with EDA, statistical tests, and visualizations |
| `Rainfall.csv` | CSV Dataset | Raw rainfall data | Source dataset containing 64 years of rainfall measurements |
| `Rainfall EDA Dashboard.html` | HTML Web Page | Interactive dashboard | Web-based visualization of analysis results |
| `README.md` | Markdown | Project documentation | This file - comprehensive project guide |
| `INT375ProjectReport.pdf` | PDF Document | Academic report | PDF version of the formal project report |
| `.gitignore` | Git Config | Version control | Git ignore file excluding large report files |

---

## 📊 Dataset Overview

### **Data Source:**
- **Origin:** Indian Meteorological Department (IMD)
- **Time Period:** 1951 - 2014 (64 years)
- **Geographic Coverage:** 36 Meteorological Subdivisions of India
- **Data Points:** 2,300 records
- **File Size:** ~250 KB

### **Data Structure:**
- **20 Columns:** SD NO., SD_Name, YEAR, JAN-DEC (monthly), ANNUAL, seasonal aggregates
- **Measurement Unit:** Millimeters (mm)
- **Data Type:** Time Series Data
- **Frequency:** Annual measurements with monthly breakdowns

### **Key Features:**
- Monthly rainfall data for all 12 months
- Seasonal aggregates (Winter, Pre-Monsoon, Monsoon, Post-Monsoon)
- Annual rainfall totals
- Geographic identifiers for 36 Indian regions

---

## 🚀 Project Components

### **1. Jupyter Notebook Analysis (`Rainfall.ipynb`)**
**Complete Data Analysis Pipeline:**
- **Data Loading & Inspection:** Import and initial data exploration
- **Data Cleaning:** Missing value handling, outlier detection
- **Descriptive Statistics:** Summary statistics, data distributions
- **Time Series Analysis:** Trend analysis, seasonal patterns
- **Statistical Tests:** T-tests, correlation analysis
- **Machine Learning:** Linear regression, K-means clustering
- **Advanced Visualizations:** Interactive plots, heatmaps, maps

**Key Libraries Used:**
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import scipy.stats as stats
from sklearn.linear_model import LinearRegression
from sklearn.cluster import KMeans
from sklearn.preprocessing import StandardScaler
import plotly.express as px
import folium
```

### **2. Interactive Web Dashboard (`Rainfall EDA Dashboard.html`)**
**Modern Web-Based Visualization:**
- **Responsive Design:** Bootstrap 5 based, mobile-friendly
- **Interactive Charts:** Chart.js, Plotly.js visualizations
- **Dataset Information:** Comprehensive data dictionary and metadata
- **Key Insights:** Statistical findings and interpretations
- **Methodology Section:** Analysis approach documentation
- **Professional Styling:** Modern UI with animations and transitions

**Dashboard Features:**
- Annual rainfall trend analysis
- Seasonal rainfall patterns
- Monthly distribution charts
- Correlation heatmaps
- Rainfall categorization
- Regional comparisons
- Outlier detection visualization

---

## 🛠 Installation & Setup

### **Prerequisites:**
```bash
# Python 3.x required
pip install jupyter pandas numpy matplotlib seaborn scipy scikit-learn plotly folium
```

### **For Jupyter Notebook:**
1. Clone or download the repository
2. Navigate to the project directory
3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `Rainfall.ipynb` and run cells sequentially

### **For Web Dashboard:**
1. **Option A - Direct Opening:**
   - Simply open `Rainfall EDA Dashboard.html` in any modern web browser

2. **Option B - Local Server (Recommended):**
   ```bash
   # Navigate to project directory
   cd "c:/Users/ajayg/College/SEM 4/INT 375/Project"
   
   # Start local server
   python -m http.server 8000
   
   # Open browser and navigate to:
   http://localhost:8000/Rainfall%20EDA%20Dashboard.html
   ```

---

## 📈 Analysis Highlights

### **Key Findings:**
- **Average Annual Rainfall:** 1,400 mm across India
- **Maximum Recorded:** 5,554 mm (Coastal Karnataka, 1961)
- **Minimum Recorded:** 86.5 mm
- **Monsoon Contribution:** ~75% of annual rainfall (June-September)
- **Outlier Events:** 13 extreme rainfall events identified
- **Regional Variations:** Significant differences across 36 subdivisions

### **Statistical Insights:**
- No significant difference in rainfall patterns before vs after 1980
- Strong correlation between monsoon months (Jun-Sep)
- K-means clustering identified 4 distinct rainfall patterns
- Linear regression shows stable long-term trends

### **Regional Analysis:**
- **Wettest Regions:** Coastal Karnataka, Arunachal Pradesh, Kerala
- **Driest Regions:** Rajasthan, Gujarat divisions
- **Seasonal Patterns:** Clear monsoon dominance in most regions

---

## 🎯 Project Objectives

1. **Data Exploration:** Comprehensive understanding of rainfall patterns
2. **Trend Analysis:** Identify long-term climate trends
3. **Regional Comparison:** Compare rainfall across different Indian regions
4. **Statistical Analysis:** Apply statistical methods for insights
5. **Visualization:** Create effective visual representations
6. **Web Dashboard:** Develop interactive web-based reporting
7. **Documentation:** Maintain comprehensive project documentation

---

## 🔧 Technical Implementation

### **Data Science Stack:**
- **Data Manipulation:** Pandas, NumPy
- **Statistical Analysis:** SciPy, Scikit-learn
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Machine Learning:** Linear Regression, K-means Clustering
- **Geospatial:** Folium for mapping

### **Web Technologies:**
- **Frontend:** HTML5, CSS3, JavaScript
- **Frameworks:** Bootstrap 5, Chart.js, Plotly.js
- **Icons:** Font Awesome
- **Design:** Responsive, modern UI with animations

---

## 📚 Usage Examples

### **Running the Analysis:**
```python
# Load the data
import pandas as pd
df = pd.read_csv("Rainfall.csv")

# Basic statistics
print(df.describe())

# Annual rainfall trend
import matplotlib.pyplot as plt
plt.figure(figsize=(12, 6))
sns.lineplot(data=df, x='YEAR', y='ANNUAL')
plt.show()
```

### **Accessing Dashboard:**
1. Open `Rainfall EDA Dashboard.html` in browser
2. Navigate through different sections:
   - Dataset Information
   - Statistical Visualizations
   - Key Insights
   - Methodology

---

## 🏆 Project Outcomes

1. **Comprehensive Analysis:** Complete EDA of 64 years of rainfall data
2. **Interactive Dashboard:** Professional web-based visualization platform
3. **Statistical Insights:** Data-driven understanding of rainfall patterns
4. **Regional Comparisons:** Detailed analysis of 36 Indian regions
5. **Academic Documentation:** Formal report and technical documentation
6. **Reusable Code:** Clean, documented analysis scripts

---

## 🤝 Contributing & Usage

### **For Academic Use:**
- This project serves as a complete reference for EDA projects
- Code can be adapted for similar time series analysis tasks
- Dashboard template can be reused for other datasets

### **For Learning:**
- Comprehensive example of data science workflow
- Integration of multiple visualization libraries
- Web development for data presentation

---

## 📄 License & Acknowledgments

- **License:** MIT License
- **Data Source:** Indian Meteorological Department (IMD)
- **Academic Purpose:** INT375 Data Science Course Project

---

## 📞 Contact & Support

For questions or issues regarding this project:
- Refer to the comprehensive documentation within the notebook
- Check the web dashboard for interactive explanations
- Review the academic report for detailed methodology

---

<div align="center">

**⭐ If you find this project helpful, consider giving it a star! ⭐**

</div>

