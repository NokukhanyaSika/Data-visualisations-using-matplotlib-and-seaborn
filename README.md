# Data-visualisations-using-matplotlib-and-seaborn

# Overview
The task required working with the UsArrests.csv dataset to:
Validate dataset structure and check for missing values
Analyze correlations between crime types (Murder, Assault, Rape)
Visualize arrest statistics across cities using stacked bar charts
Integrate urban population data into crime visualizations for deeper insights

# Implementation

The following libraries were used:
pandas for data loading, preprocessing, and reshaping
matplotlib for base plotting
seaborn for advanced statistical visualizations

# Key steps
1. Load and validate data
Inspect dataset structure with .info()
Check for missing values with .isna().sum()
2. Correlation analysis
Extract columns of interest (Murder, Assault, Rape)
Plot a heatmap correlation matrix to identify relationships between crime types
3. City‑level visualization
Create stacked horizontal bar charts showing arrests indexed by city
Build a numeric city index for consistent plotting
Combined visualization with population data
Reshape dataset using .melt() for crime type comparisons
Plot crime statistics as grouped bar charts
Overlay urban population percentages on a secondary axis for contextual analysis
