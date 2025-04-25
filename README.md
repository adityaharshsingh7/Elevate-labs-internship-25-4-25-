 Elevate-labs-internship-25-4-25-
Task 2: Exploratory Data Analysis (EDA)
---
Tools Used
- Pandas: Data manipulation and summary statistics
- Matplotlib / Seaborn: Visualizations (histograms, boxplots, correlation matrix, etc.)
- Plotly (optional): For interactive charts (not used in this run but applicable)
---
1.Generate Summary Statistics
- Used `df.describe()` and `df.info()` to explore data types, missing values, and distribution.
- Identified missing data in `Age`, `Cabin`, and `Embarked`.

2.Visualize Numeric Features
- Created histograms for numerical columns (e.g., Age, Fare, SibSp, Parch).
- Created boxplots to identify outliers (especially in Fare and Age).

3.Correlation & Feature Relationships
- Generated a correlation heatmap to examine numeric feature relationships.
- Created a pairplot to visualize feature interactions.

4. Identify Patterns & Anomalies
- Visualized survival vs:
  - Age (`histplot`)
  - Fare (`boxplot`)
  - Pclass (`barplot`)
  - Sex (`barplot`)
- Found outliers in `Fare` and `SibSp`.

5.Inferences from Visuals
- Females and 1st class passengers had higher survival.
- Higher fares and younger age were loosely associated with higher survival chances.
- Most passengers traveled alone.

---

 ✅ Summary

This EDA provided a foundation for understanding the Titanic dataset and prepared it for further steps like feature engineering or machine learning modeling.

