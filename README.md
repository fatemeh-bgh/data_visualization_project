📊 Project Overview

While internet access in Europe is often viewed as near-universal, significant regional and socioeconomic disparities persist. This project investigates:


Whether income or education serves as a stronger predictor of digital connectivity
Which countries deviate from expected patterns based on their economic capacity
Regional clustering and digital divide patterns across Europe


🔍 Key Research Questions


How does internet access vary across European countries in 2024?
Is internet access more strongly correlated with income levels or educational attainment?
Which countries "overperform" or "underperform" based on their economic capacity?



📁 Data Sources & Methodology
Datasets (Eurostat, 2024)
IndicatorSourceDescriptionInternet Accesstin00134Percentage of households with internet accessIncomeilc_di17Population-weighted mean equivalised net income (EUR)Educationsdg_04_20Share of adults aged 30-34 with tertiary education (ISCED 5-8)
Methodology


Sample: 29 European countries with complete 2024 data

Excluded: 4 countries due to missing values (Albania, Switzerland, Iceland, North Macedonia)

Approach: Descriptive and exploratory analysis with OLS regression

Limitations: Correlational only—not causal

Tools Used

Data Processing: pandas

Visualization: matplotlib, seaborn, plotly, Datawrapper

Statistical Analysis: statsmodels (OLS Regression)

AI Assistance: Gemini, ChatGPT (coding & text editing), Nano Banana (image generation)


🎯 Key Findings

1. Income is the Primary Driver
2. Strong positive association between mean income and internet access. Higher-income countries generally achieve higher connectivity rates.

4. Education's Limited Role While positively correlated, tertiary education is a weaker and less stable predictor than income. Countries with similar education levels show wide variation in access rates.

6. Regional Clustering

Nordic & Western Europe: High income, near-universal access, higher tertiary attainment

Southern Europe: Relatively high access at lower income levels, variable education

Eastern Europe: More dispersed, generally lower income, heterogeneous outcomes

4. Notable Deviations from Income-Predicted Access
Positive Residuals (Higher access than expected):

🇳🇱 Netherlands

🇵🇱 Poland

🇪🇸 Spain

Negative Residuals (Lower access than expected):

🇬🇷 Greece

🇭🇷 Croatia

🇮🇪 Ireland


📂 Repository Structure

.
├── Baghchei_data_visualization.pdf    # Full visual analysis (maps, charts, regression)

├── README.md                           # This file

└── [data/]                            # (Optional) Raw/processed datasets

📄 License

This project is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.



🙏 Acknowledgments
Data provided by Eurostat. Visualizations created with Datawrapper, matplotlib, seaborn, and plotly.
