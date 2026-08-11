# 🫀 Key Indicators of Heart Disease in the US (2022)
### Exploratory Data Analysis (EDA) & Risk Factor Identification

🔗 **[🚀 Launch Interactive Notebook in Google Colab](https://colab.research.google.com/drive/1SjJ7u3CpDxfkcTjiT04h9J1KQ1VyX2_Q?usp=sharing)(https://colab.research.google.com/drive/1SjJ7u3CpDxfkcTjiT04h9J1KQ1VyX2_Q?usp=sharing)**

**Tech Stack:** `Python` | `Pandas` | `Plotly` | `Seaborn` | `Matplotlib`
---
---
---

## 📌 Executive Summary
This project delivers a comprehensive Exploratory Data Analysis (EDA) investigating the demographic, geographic, and lifestyle determinants associated with heart attack prevalence across the United States. 

By analyzing **246,022 individual health surveys** from the **2022 CDC Behavioral Risk Factor Surveillance System (BRFSS)**, this analysis uncovers critical spatial variations, age-specific risk elevations, and lifestyle correlations to help inform targeted public health interventions.

---

## 🔍 Key Insights & Findings

* **Geographic Disparities:** Southeastern states consistently demonstrate higher heart attack prevalence compared to West Coast states, highlighting potential regional socioeconomic and dietary pattern influences.
* **Young Adult Risk Clusters:** Identified distinct states where heart disease prevalence among young adults (<50 years old) disproportionately exceeds national baselines.
* **Ethnic Distribution:** Significant variance in racial/ethnic composition among early-onset heart disease cases across top-risk states, emphasizing the need for tailored community health initiatives.
* **Clinical Factors:** Strong positive correlation observed between Angina diagnosis and subsequent heart attack incidence.

---

## 🛠️ Dataset Overview

| Attribute | Details |
| :--- | :--- |
| **Data Source** | CDC BRFSS 2022 (via Kaggle) |
| **Sample Size** | 246,022 observations |
| **Features** | 40 variables (Demographics, Medical History, Lifestyle) |
| **Data Quality** | Fully cleaned dataset without missing values |

---

## 📊 Analytical Methodology & Pipeline

1. **Data Preprocessing & Transformation:**
   * Feature engineering (state abbreviation mapping, age category binning).
   * Filtering and cross-tabulation for subgroup populations (e.g., adults under 50 with positive heart attack records).
2. **Geographic & Choropleth Mapping:**
   * Interactive US state-level heatmaps built using `Plotly Express`.
   * Top/Bottom regional comparative bar charts.
3. **Cross-Sectional Subgroup Analysis:**
   * Proportion calculations of heart attack occurrences stratified by age categories, race/ethnicity, and medical history.

---

## 💻 Tech Stack & Libraries

* **Data Processing:** `Python`, `Pandas`, `NumPy`
* **Visualization:** `Plotly Express`, `Seaborn`, `Matplotlib`

---

## 👩‍💻 Author
**Chani Rosenbaum**  
*Data Analyst*  
[LinkedIn](https://www.linkedin.com/in/chani-rosenbaum-837172365/?skipRedirect=true)
