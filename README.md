# ⚡ Electric Vehicle Adoption Analysis in Washington State

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge) ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)

*A comprehensive data science project analyzing electric vehicle adoption trends and patterns across Washington State*

---

## ✨ Project Overview

This data analytics project, developed as part of a **personal portfolio initiative** on **September 14, 2025**, provides deep insights into the adoption patterns of electric vehicles (EVs) in Washington State. By analyzing the "Electric Vehicle Population Data" dataset containing **95,000+ EV registration records**, this project demonstrates expertise in:

- 📊 **Data Cleaning & Preprocessing**
- 🔍 **Exploratory Data Analysis (EDA)** 
- 📈 **Statistical Visualization**
- 💼 **Business Impact Simulation**
- 🎯 **Actionable Insights for Policy & Strategy**

### 🎯 Key Objectives

- 🔋 **Assess EV adoption trends** across model years and geographic regions
- 🚗 **Identify key drivers** including urban concentration and electric range capabilities  
- 📊 **Compare BEV vs. PHEV** adoption patterns
- 💡 **Simulate business value** with a 25% uplift in decision-making accuracy
- 🔄 **Create reusable analysis pipeline** for stakeholder review

---

## 📂 Dataset

### 🗂️ Data Source

**Dataset:** "Electric Vehicle Population Data" (CSV format)  
**Source:** Washington State public records  
**Records:** ~95,000 (after filtering)  
**Fields:** VIN, County, City, Model Year, Make, Model, EV Type, Electric Range, Base MSRP

### 🎯 Scope

Focused exclusively on **Washington State entries** to ensure data consistency and regional relevance.

---

## 🛠️ Technical Stack

### 💻 Programming & Environment

- **Language:** Python 3.x
- **Platform:** Jupyter Notebook / Google Colab
- **Version Control:** Git & GitHub

### 📚 Libraries & Tools

| Library | Purpose |
|---------|----------|
| **Pandas** | Data manipulation and wrangling |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization (bar charts, line plots) |
| **Seaborn** | Statistical visualization (heatmaps, distributions) |
| **SciPy** | Time series decomposition |
| **Statsmodels** | Statistical analysis |

### 🧪 Key Skills Demonstrated

- ✅ Data validation and integrity checks
- ✅ Outlier detection (Z-score method)
- ✅ Feature engineering
- ✅ Statistical summaries and correlations
- ✅ Dashboard-style reporting

---

## 📋 Analysis Process

### 1️⃣ Data Loading & Exploration

- Imported CSV and validated column integrity
- Filtered for Washington State entries only
- Examined data types, missing values, and distributions

### 2️⃣ Data Cleansing

- **Achieved 98% data completeness** by handling missing values
  - Median fill for Electric Range
  - Removed outliers (>3 standard deviations)

### 3️⃣ Feature Engineering

- Created **EV_Type_Short** (BEV/PHEV) for simplified analysis
- Added **Urban_County** flag (King County)
- Derived aggregated metrics for regional analysis

### 4️⃣ Exploratory Data Analysis

- **Statistical summaries:** Mean, median, mode, standard deviation
- **Correlation heatmaps:** Relationships between numeric variables
- **Time series decomposition:** Trend, seasonality, residuals

### 5️⃣ Visualization

- 📊 **Bar charts** - Top makes by registration count
- 📈 **Line plots** - Yearly growth trends  
- 🎯 **Scatter plots** - Range vs. MSRP with regression analysis
- 🗺️ **Geographic analysis** - County-level adoption patterns

### 6️⃣ Insight Simulation

- **Business Impact Model:** A/B comparison of urban vs. rural adoption
- **Quantified Results:** 25% improvement in decision-making accuracy

---

## 🔑 Key Findings

### 📈 Adoption Growth

- 🚀 Identified a **20% average annual growth** in BEV registrations
- 📊 Significant acceleration **post-2018**, driven by urban counties like **King County**

### 🏆 Market Dominance

- **Tesla leads** with over **50% of registrations**
- Premium EV market penetration reflects early adopter demographics

### 🔋 Range Analysis

- **BEVs:** Average range ~250 miles
- **PHEVs:** Average range ~30 miles
- Strong correlation between range and adoption rate

### 🏙️ Geographic Patterns

- **Urban concentration:** King County accounts for 60%+ of total EVs
- Rural areas show slower adoption due to infrastructure gaps

### 💰 Pricing Insights

- **MSRP trends:** Premium vehicles dominate, but mid-range options growing
- Price elasticity varies by region and vehicle type

---

## 📊 Visualizations

The notebook includes:

- 📊 Top 10 EV Makes (Bar Chart)
- 📈 Year-over-Year Registration Growth (Line Chart)  
- 🎯 Range vs. MSRP Scatter Plot with Regression
- 🗺️ County-Level Adoption Heatmap
- 📉 Time Series Decomposition
- 🔄 BEV vs. PHEV Comparative Analysis

---

## 💼 Business Applications

### 🎯 Use Cases

- **Policy Makers:** Infrastructure planning and incentive programs
- **Automakers:** Market segmentation and product positioning  
- **Energy Companies:** Charging station deployment strategies
- **Investors:** Market growth forecasting
- **Urban Planners:** Sustainability initiatives

### 📈 Value Proposition

This analysis provides a **reusable, scalable framework** for:

- ✅ Real-time EV market monitoring
- ✅ Predictive modeling for future adoption
- ✅ Stakeholder presentations and reports
- ✅ Data-driven policy recommendations

---

## 🚀 Getting Started

### 📥 Clone the Repository

```bash
git clone https://github.com/Rishisingh1999/Electric_Vehicle_Adoption_Analysis.git
cd Electric_Vehicle_Adoption_Analysis
```

### 📦 Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter
```

### ▶️ Run the Notebook

```bash
jupyter notebook "EV adoption in WA State using Python.ipynb"
```

**Or use Google Colab:**
- Upload the `.ipynb` file to Google Colab
- Upload the dataset CSV
- Run all cells

---

## 📁 Repository Structure

```
Electric_Vehicle_Adoption_Analysis/
├── EV adoption in WA State using Python.ipynb  # Main analysis notebook
├── README.md                                   # Project documentation  
└── data/                                       # Dataset (if included)
    └── Electric_Vehicle_Population_Data.csv
```

---

## 🎓 Skills Highlighted

This project demonstrates proficiency in:

- **Data Analytics:** End-to-end EDA pipeline
- **Python Programming:** Pandas, NumPy, visualization libraries  
- **Statistical Analysis:** Correlation, regression, time series
- **Data Visualization:** Matplotlib, Seaborn
- **Business Acumen:** Translating data into actionable insights
- **Documentation:** Clear, professional reporting

---

## 🔮 Future Enhancements

- 🤖 **Predictive Modeling:** ML algorithms for adoption forecasting
- 🗺️ **Interactive Dashboards:** Tableau/Power BI integration  
- 🌍 **Multi-State Comparison:** Expand analysis beyond Washington
- ⚡ **Real-Time Data:** API integration for live updates
- 📱 **Web App:** Deploy Streamlit/Dash interface

---

## 📧 Contact

**Hrushikesh Singh**

- 📧 Email: hrushisingh697@gmail.com
- 💼 LinkedIn: [linkedin.com/in/hrushikesh-singh](https://www.linkedin.com/in/hrushikesh-singh)
- 🐙 GitHub: [@Rishisingh1999](https://github.com/Rishisingh1999)  
- 🌐 Portfolio: [rishisingh1999.github.io/my-portfolio-website](https://rishisingh1999.github.io/my-portfolio-website/)

---

## 📄 License

This project is open source and available for educational purposes. Feel free to fork and adapt!

**Attribution appreciated** 🙏

---

## ⭐ Show Your Support

If you find this project useful, please give it a ⭐ on GitHub!

**Built with ❤️ for Data Analytics & Sustainability**

---

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=rishisingh1999.electric-vehicle-analysis)
