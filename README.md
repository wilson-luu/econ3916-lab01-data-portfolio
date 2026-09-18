# The Data Portfolio — Big Mac Index Analysis
## Objective
To empirically evaluate the validity of Purchasing Power Parity (PPP) and structural currency valuation disparities across 57 global economies using a panel dataset of local consumer pricing.
## Methodology
- Data Integration: Loaded and standardized the Big Mac Index panel dataset (57 countries, 45 periods spanning 2000-04 to 2026-07) from The Economist's repository.
- Metric Engineering: Computed implied Purchasing Power Parity (PPP) exchange rates and calculated percentage valuations against the US Dollar benchmark for cross-sectional analysis.
- Structural Diagnosis: Differentiated the dataset into cross-sectional, time-series, and panel structures to test distinct economic hypotheses.
- Missing Data Classification: Systematically identified incomplete panels and diagnosed missingness mechanisms, successfully classifying attrition events (e.g., Russia's market exit) as Missing Not At Random (MNAR) to identify potential survivorship bias.
- Data Visualization: Developed comprehensive visualizations, including cross-sectional bar charts of global valuations and multi-country time-series comparisons to track historical currency repricing.
## Key Findings
- Structural Overvaluation: The Swiss Franc demonstrates severe, persistent overvaluation (+41.8% in the July 2024 cross-section), driven heavily by high localized costs for non-tradeable inputs (rent, wages).
- Persistent Undervaluation: Conversely, the Japanese Yen exhibits chronic undervaluation across the measured timeline, persisting on average through every decade of the series.
- Data Bias Risk: Removing countries with incomplete panels creates a significant survivorship bias within global valuation calculations, as these absences are often driven by structural economic crises or geopolitical events rather than random omission.
