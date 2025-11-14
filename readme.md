# 📊 Seaborn Visualization Plots — Complete Definitions

Seaborn provides a wide range of statistical and beautiful visualisation tools.
Here are all major Seaborn plots with simple, clear definitions.

## 🔹 1. Distribution Plots
1. histplot()

Plots a histogram to show the frequency distribution of a numeric variable.

2. kdeplot()

Plots a smoothed density curve to estimate the probability distribution.

3. distplot() (Deprecated)

Old function combining histogram + KDE.

4. ecdfplot()

Plots the Empirical Cumulative Distribution Function (ECDF) showing proportion of data ≤ x.

5. rugplot()

Adds small vertical lines to show individual data points along an axis.

## 🔹 2. Relationship Plots
6. scatterplot()

Displays the relationship between two numerical variables, optionally with grouping via hue.

7. lineplot()

Shows trends over time or continuous values.

8. regplot()

Scatterplot with a linear regression line.

9. lmplot()

Higher-level regression plot supporting multiple facets.

10. residplot()

Plots regression residuals to check model quality.

## 🔹 3. Categorical Plots
11. barplot()

Shows mean values of categories with confidence intervals.

12. countplot()

Displays the count/frequency of each category.

13. boxplot()

Shows median, quartiles, and outliers of distributions across categories.

14. violinplot()

Combines KDE + boxplot, showing distribution shape and statistics.

15. stripplot()

Shows individual data points for each category with jitter.

16. swarmplot()

Like stripplot but ensures no overlapping points.

17. pointplot()

Shows mean values of categories with connected points.

## 🔹 4. Matrix & Heatmap Plots
18. heatmap()

Displays color-coded matrix or correlation values.

19. clustermap()

Heatmap combined with hierarchical clustering, groups similar rows/columns.

## 🔹 5. Distribution + Category Combination Plots
20. jointplot()

Shows combined distribution + relationship (scatter/hist/KDE) between two variables.

21. pairplot()

Plots all pairwise relationships between numerical variables in a dataset.

22. pairgrid()

Customizable version of pairplot for more control.

23. jointgrid()

More flexible version of jointplot.

## 🔹 6. Faceting Plots
24. FacetGrid()

Creates a grid of subplots based on category splits.

25. catplot()

A high-level function for categorical plots (bar, box, violin, etc.) with faceting options.

26. relplot()

High-level interface for relationship plots like scatter & line with faceting.

## 🔹 7. Distribution (Legacy)
27. displot()

# ✔️ Summary Table (for GitHub)

| Plot        | Purpose                             |
|-------------|-------------------------------------|
| histplot    | Histogram (frequency)                |
| kdeplot     | Density estimation                   |
| ecdfplot    | Cumulative distribution              |
| rugplot     | Individual data marks               |
| scatterplot | Relationship between 2 variables     |
| lineplot    | Trend analysis                       |
| regplot     | Regression line                      |
| lmplot      | Regression with facets               |
| residplot   | Regression residuals                 |
| barplot     | Category + mean                      |
| countplot   | Count of categories                  |
| boxplot     | Distribution stats                   |
| violinplot  | Distribution + density               |
| stripplot   | Raw points                           |
| swarmplot   | Non-overlapping points              |
| pointplot   | Category + mean (points)             |
| heatmap     | Matrix / correlation visualization   |
| clustermap  | Heatmap + clustering                 |
| jointplot   | Relationship + distribution          |
| pairplot    | Pairwise relationships               |
| FacetGrid   | Multi-plot grid                      |
| catplot     | Categorical faceted plots            |
| relplot     | Relationship plots with facets       |
| displot     | Figure-level distribution plot       |
