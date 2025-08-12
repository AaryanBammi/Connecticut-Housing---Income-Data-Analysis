# Connecticut Housing & Income Analysis

## Overview
This repository investigates the influence of income, population growth, taxation and location on housing prices and affordability in Connecticut between 2010 and 2022. It consolidates housing and economic data from state and county sources, and explores how demographic and economic factors correlate with real estate prices.

## Data
- **Housing Data:** Median house prices and counts by county from the Connecticut Department of Economic and Community Development (2010–2022).
- **Income & Demographics:** Median household income, population counts, and tax rates by county for the same period.

## Methodology
1. **Data cleaning & merging:** Combine housing, income, population and tax datasets; handle missing values and align yearly ranges.
2. **Exploratory analysis:** Visualize trends over time and geographic differences using line charts, bar plots, and correlation heatmaps.
3. **Statistical modelling:** Fit linear regression models to study relationships between income, taxes, population and housing prices.

## Key Findings
- Median home prices increased steadily between 2010 and 2022, with higher growth in Fairfield and New Haven counties.
- Income growth positively correlated with housing prices (Pearson r≈0.65), while higher tax rates showed a negative relationship.
- Population growth had limited effect on housing prices compared with income and taxes.

## How to Run
1. Clone this repository and ensure you have Python 3.10+ installed.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter notebook:

   ```bash
   jupyter notebook connecticut_housing_income_analysis.ipynb
   ```

4. Follow the notebook cells to reproduce the analysis and plots.

## Next Steps
- Integrate more recent housing and economic data to extend the analysis beyond 2022.
- Explore additional modelling techniques such as random forests or gradient boosting.
- Build an interactive dashboard (e.g., with Streamlit) to allow users to explore county‑level trends.

## Contributors
- Aaryan Bammi
- Pushpraj Sandhu
- BeiSu
- Haojiang Wu
- Yixi Yu
- Zeran Huang
