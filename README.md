# Housing Price Prediction

A multiple linear regression project predicting house sale prices 
using a 7,000-record dataset. Built as a team course project at UCLA 
(Winter 2026).

---

## My Contributions

- Feature engineering: created interaction terms (Qual x Liv) 
  and combined size features
- Applied log and Box-Cox transformations to meet MLR assumptions
- Removed 938 outliers (13.4%) based on distribution analysis
- Compared Best Subset, AIC Stepwise, and BIC Stepwise models

---

## Key Results

- Final model: BIC Stepwise (14 predictors)
- Adjusted R²: 0.9493
- Residual SE: 0.2076
- Validated assumptions: linearity, homoscedasticity, normality

---

## Tech Stack

| Tool | Usage |
|------|-------|
| R | Core language |
| ggplot2 | Visualizations |
| MASS | Stepwise regression |
| scatter matrix / correlation plots | Feature selection |

---

## Dataset

7,000 residential property records with 88 variables including 
size, quality, neighborhood, and sale price.

---

## Note

This was a team project. The modeling framework and report were 
developed collaboratively. My focus was on data preprocessing 
and feature engineering.
