# Medical-Data-Visualizer
Medical Data Visualizer This is the third project for the freeCodeCamp Data Analysis with Python certification. The objective of this project is to use Pandas, Seaborn, and Matplotlib to visualize and analyze medical examination data, exploring correlations between cardiac disease risk factors, body measurements, and lifestyle choices.
# Medical Data Visualizer

This is the third project for the **freeCodeCamp Data Analysis with Python** certification. The objective is to visualize and analyze medical examination data using Pandas, Seaborn, and Matplotlib to explore correlations between cardiac disease risk factors.

## Features & Visualizations
* **Data Preprocessing:** Calculates patient Body Mass Index (BMI) to label individuals as overweight and normalizes cholesterol and glucose values into binary indicators.
* **Categorical Plot (`draw_cat_plot`):** Generates a categorical bar chart displaying counts of good vs. bad lifestyle features (`active`, `alco`, `cholesterol`, `gluc`, `overweight`, `smoke`) split by cardiac disease presence (`cardio`).
* **Correlation Heatmap (`draw_heat_map`):** Cleans anomalous data (such as diastolic pressure exceeding systolic pressure and outlier body measurements) to generate a correlation matrix heatmap using Seaborn.

## How to Run Locally
1. Clone repository and ensure data file `medical_examination.csv` is present.
2. Install dependencies:
   ```bash
   pip install pandas seaborn matplotlib numpy
