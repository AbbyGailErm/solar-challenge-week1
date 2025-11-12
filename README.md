Project Description:
This repository contains the Solar Data Discovery Challenge, which analyzes solar farm data from Benin, Sierra Leone, and Togo to identify high-potential regions for solar energy deployment. The project includes data profiling, cleaning, exploratory data analysis (EDA), and cross-country comparison of key metrics such as solar irradiance, temperature, humidity, and wind. An optional interactive Streamlit dashboard allows dynamic visualization of trends and top-performing regions. Insights generated aim to support MoonLight Energy Solutions in making data-driven decisions for sustainable and efficient solar energy investments.

Methodology

The analysis follows a structured workflow to ensure reproducibility, accuracy, and actionable insights:

Data Collection & Setup

Solar datasets for each country are loaded and stored in a structured directory.

Python environment is configured with required libraries and CI/CD workflow is implemented for reproducibility.

Data Profiling & Cleaning

Examine datasets for missing values, outliers, and inconsistencies.

Apply imputation strategies (median/fill) and outlier detection (Z-scores, IQR).

Standardize timestamps and sensor measurements for consistency.

Exploratory Data Analysis (EDA)

Visualize temporal patterns of GHI, DNI, DHI and temperature trends.

Examine relationships between environmental factors (temperature, humidity, wind) and module readings (ModA, ModB).

Assess impact of cleaning events on module performance.

Cross-Country Comparison

Compare solar potential metrics across Benin, Sierra Leone, and Togo using summary statistics, boxplots, and optional statistical tests (ANOVA/Kruskal-Wallis).

Identify regions with highest and most reliable solar irradiance.

Optional Interactive Dashboard

Create a Streamlit dashboard to explore country-wise solar trends.

Enable interactive selection of countries and visualization of top-performing regions.

Insights & Recommendations

Translate EDA findings into actionable insights for strategic solar farm deployment.

Highlight regions and conditions optimal for long-term sustainable solar energy investments.
