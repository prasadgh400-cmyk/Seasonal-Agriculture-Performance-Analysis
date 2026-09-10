# Seasonal Agriculture Performance Analysis

**VOIS AICTE Batch 1 — Major Project 2026–2027**

## Project objective
Analyze agricultural performance across Kharif, Rabi, and Zaid seasons, with emphasis on yield, environmental conditions, resource usage, water efficiency, disease/pest risk, and economic outcomes.

## Dataset
- 4,000 farm records
- 28 original variables
- 3 seasons: Kharif, Rabi, Zaid
- 8 crops
- 8 states

## Main cleaning performed
- Rainfall and soil-moisture missing values filled using season medians.
- 32 missing yield values reconstructed from Production_Tonnes / Farm_Area_Hectares.
- No exact duplicate rows were found.

## Selected findings
- Kharif average yield: **5.63 t/ha**
- Kharif average profit: **₹178,915**
- Zaid average profit: **₹-24,805**
- Yield vs water efficiency correlation: **r=0.916**
- Yield vs profit correlation: **r=0.490**
- Seasonal differences in yield, profit, water efficiency, and pest/disease risk are significant under Kruskal–Wallis tests.

## Files
- `Seasonal_Agriculture_Performance_Analysis.ipynb` — complete executed analysis
- `Seasonal_Agriculture_Performance_Analysis.pptx` — VOIS presentation
- `seasonal_agriculture_performance_dataset.csv` — original dataset
- `seasonal_agriculture_performance_cleaned.csv` — cleaned dataset
- `seasonal_summary.csv` — seasonal summary table
- `crop_season_summary.csv` — crop × season summary
- `irrigation_summary.csv` — irrigation summary
- `statistical_tests.csv` — Kruskal–Wallis test results
- `charts/` — presentation-ready charts

## Technology
Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, SciPy, GitHub, Microsoft PowerPoint.

## Before submission
Replace `[Student Name]`, `[College Name]`, and `[AICTE STU ID]` in the notebook and PPT. Add your GitHub repository URL to slide 12 and insert your VOIS Data Visualization course certificate on slide 13.
