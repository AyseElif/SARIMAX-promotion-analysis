# Promotion Bump Analysis

## Overview
This project examines the impact of promotional campaigns on sales within a retail environment. By analyzing data from 2015, the project identifies how promotions influence sales volumes and categorizes items and stores based on their performance.

## Data Description
- `Assignment4.1a.csv`: Daily sales data for selected items across various stores. This file also marks the periods when promotions were active.
- `Promotiondates.csv`: Lists the start and end dates for six promotional campaigns in 2015.
- `Assignment4.1b.csv`: Continuation of daily sales data post-initial study period, used to assess the predictive accuracy of the models.

## Methodology
The project employs clustering (K-means) to categorize products and stores into three groups each (Fast, Medium, Slow) based on sales performance. The impact of promotions on these categories is then analyzed. For predictive analysis, a SARIMAX model is used to forecast sales during new promotional periods.

### Analysis Steps
1. **Clustering of Items and Stores**: Using K-means clustering based on average weekly sales to identify Fast, Medium, and Slow groups.
2. **Promotion Impact Analysis**: Comparing sales during promotional and non-promotional periods to gauge the effect of promotions.
3. **Predictive Modeling**: Employing a SARIMAX time series model to forecast the impact of future promotions, validated against actual sales data.

## Results
Key findings include:
- Promotions significantly increase sales, particularly for items classified as Fast.
- Some stores show a higher response to promotions than others, with store number 92 showing the most significant increase during promotions.
- The SARIMAX model provided reasonably accurate forecasts with a MAE of 2217 units and a MAPE of 69.15%, indicating potential areas for model improvement.
