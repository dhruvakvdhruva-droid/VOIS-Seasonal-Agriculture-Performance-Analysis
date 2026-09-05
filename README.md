# Seasonal Agriculture Performance Analysis

## VOIS AICTE Batch 1 — 2026–2027 Major Project

This project analyzes seasonal agricultural performance using a dataset of 4,000 farm records and 28 variables.

### Objectives
- Clean and prepare agricultural data.
- Compare Kharif, Rabi and Zaid seasons.
- Analyze crop, state and irrigation performance.
- Examine yield, revenue, cost, profit, water efficiency and disease/pest risk.
- Identify relationships and unusual patterns using statistics and visualization.
- Develop evidence-based recommendations for seasonal planning.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

## Key Findings
- Kharif has the highest descriptive average yield: **5.64 tonnes/ha**.
- Kharif has the highest descriptive average profit: **₹178,914.65**.
- Zaid has a negative descriptive average profit: **−₹24,804.82**.
- Sugarcane and Chilli show the strongest average profitability among the crops.
- Drip irrigation has the highest average yield and profit among the listed irrigation methods.
- Punjab has the highest average state-level yield: **6.12 tonnes/ha**.
- Yield and water-efficiency are strongly correlated (**r ≈ 0.915**), but the efficiency metric is mathematically derived from production/yield and water use, so this should not be interpreted as independent causal evidence.
- One-way ANOVA for yield by season gives **F = 1.458, p = 0.233**. Therefore, the observed seasonal yield differences are descriptive and are not statistically significant at the 5% level.

## Project Structure

```text
VOIS_Seasonal_Agriculture_Project/
├── VOIS_Seasonal_Agriculture_Performance_Analysis.ipynb
├── seasonal_agriculture_cleaned.csv
├── results_charts/
│   ├── 01_seasonal_yield.png
│   ├── 02_seasonal_profit.png
│   ├── 03_crop_profitability.png
│   ├── 04_irrigation_yield.png
│   ├── 05_state_yield.png
│   ├── 06_yield_water_efficiency.png
│   └── 07_seasonal_risk.png
└── README.md
```

## How to Run

1. Download/clone the repository.
2. Open `VOIS_Seasonal_Agriculture_Performance_Analysis.ipynb` in Jupyter Notebook or JupyterLab.
3. Keep the CSV in the same project folder.
4. Run the notebook cells from top to bottom.

## Future Scope
- Predictive yield and profit models.
- Multi-year agricultural time-series analysis.
- Integration of weather and market forecasts.
- Interactive dashboards.
- More detailed field/experimental studies for causal analysis.

## Author
**[Student Name]**  
**[College Name]**  
**AICTE STU ID: [Enter ID]**
