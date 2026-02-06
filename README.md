# 📊 Internet Access Inequality in Europe — Data Analysis Project

## 📊 Project Overview
While internet access in Europe is often viewed as near-universal, significant regional and socioeconomic disparities persist. This project investigates:

- Whether income or education serves as a stronger predictor of digital connectivity  
- Which countries deviate from expected patterns based on their economic capacity  
- Regional clustering and digital divide patterns across Europe  

---

## 🔍 Key Research Questions

- How does internet access vary across European countries in 2024?  
- Is internet access more strongly correlated with income levels or educational attainment?  
- Which countries overperform or underperform based on their economic capacity?  

---

## 📁 Data Sources & Methodology

### Datasets (Eurostat, 2024)

| Indicator | Source Code | Description |
|----------|-------------|-------------|
| Internet Access | tin00134 | Percentage of households with internet access |
| Income | ilc_di17 | Population-weighted mean equivalised net income (EUR) |
| Education | sdg_04_20 | Share of adults aged 30–34 with tertiary education (ISCED 5–8) |

### Methodology

- **Sample:** 29 European countries with complete 2024 data  
- **Excluded:** Albania, Switzerland, Iceland, North Macedonia (missing values)  
- **Approach:** Descriptive and exploratory analysis with OLS regression  
- **Limitations:** Correlational analysis only — not causal  

### Tools Used

- Data processing: pandas  
- Visualization: matplotlib, seaborn, plotly, Datawrapper  
- Statistical analysis: statsmodels (OLS regression)  
- AI assistance: Gemini, ChatGPT (coding & editing), Nano Banana (image generation)  

---

## 🎯 Key Findings

### 1. Income is the Primary Driver
Strong positive association between income and internet access. Higher-income countries tend to achieve higher connectivity rates.

### 2. Education’s Limited Role
Education correlates positively with internet access, but is a weaker and less stable predictor compared to income.

### 3. Regional Clustering

- **Nordic & Western Europe:** High income, near-universal access, higher tertiary attainment  
- **Southern Europe:** Relatively high access despite lower income levels  
- **Eastern Europe:** More dispersed outcomes with generally lower income  

### 4. Notable Deviations from Income-Predicted Access

**Higher access than expected:**

- 🇳🇱 Netherlands  
- 🇵🇱 Poland  
- 🇪🇸 Spain  

**Lower access than expected:**

- 🇬🇷 Greece  
- 🇭🇷 Croatia  
- 🇮🇪 Ireland  

---

## 📂 Repository Structure

```
.
├── data/                         # Raw or processed datasets
├── outputs/                      # Generated charts, tables, or analysis outputs
├── digital_divide_europe.ipynb   # Main analysis notebook
├── README.md                     # Project documentation
└── .DS_Store                     # System file (can be ignored)
```


---

## 📄 License
This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

---


## 🙏 Acknowledgments
Data provided by Eurostat. Visualizations created using Datawrapper, matplotlib, seaborn, and plotly.

---
