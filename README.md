Penguin Size Exploratory Data Analysis

This script performs EDA on the penguins_size.csv dataset. It loads the data and prints the first rows to understand the structure before cleaning.

Data cleaning steps include dropping rows with missing values, standardizing column names to lowercase with underscores, and converting species and sex to category types for efficient analysis.

Three visualizations are created: a count plot showing the distribution of penguin species, a scatterplot of culmen length vs culmen depth color-coded by species, and a boxplot comparing flipper length across species.

The script ends with a correlation heatmap of all numeric biometric measures to highlight relationships like how flipper length relates to body mass.

Business impact: EDA like this is the first step before any machine learning or reporting project. Cleaning and visualizing data prevents analysts from building models on bad inputs, which saves weeks of wasted work and budget. Clean, well-understood data leads to dashboards leadership can trust.

Real-world use: Wildlife researchers use these exact plots to study species differences and inform conservation policy. In business, the same workflow applies to customer segmentation, product analytics, or quality control — explore distributions, check relationships, and find outliers before making decisions.
