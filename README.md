## Mexican Real Estate Market Analysis: Size vs. Location

### Project Overview

Does property size determine real estate prices in Mexico, or does location play a more decisive role? This project explores residential property valuations across Mexican states using data science workflows.

Our analytical pipeline encompasses four core stages:
1. **Data Wrangling (L1):** Ingesting multi-file listings, handling missing values, standardizing currencies into USD, and structuring tidy datasets.
2. **Exploratory Analysis (L2):** Evaluating distribution shapes, identifying skewness, and visualizing outliers across property sizes and listing prices.
3. **Correlation Modeling (L3):** Quantifying size-price linear relationships via Pearson correlation, while uncovering regional nuances and Simpson's Paradox.
4. **Feature Engineering (L4):** Normalizing valuations through price per square meter (`price_per_m2`) and assessing variance across states and property types.

Through this workflow, we determine whether physical dimensions or geographical location serve as the primary driver of Mexican real estate prices.