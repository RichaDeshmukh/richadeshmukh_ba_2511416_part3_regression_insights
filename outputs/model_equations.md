# Regression Model Equations

## Simple Regression Model 1

Monthly Sales = 560777.35 + 2.1296 × Marketing Spend

### Interpretation

Marketing spend has a positive and statistically significant relationship with monthly sales. Every additional ₹1 spent on marketing is associated with an average increase of approximately ₹2.13 in monthly sales.

---

## Simple Regression Model 2

Monthly Sales = 446410.58 + 35.6780 × Footfall

### Interpretation

Footfall is strongly associated with monthly sales. Each additional customer visit is associated with an increase of approximately ₹35.68 in monthly sales.

---

## Multiple Regression Model

Monthly Sales =

89288.89

+ 1.2024 × Marketing Spend

+ 33.9843 × Footfall

+ 2887.04 × Inventory Availability

+ 11104.99 × Customer Rating

− 8661.45 × Region_East

+ 13316.41 × Region_South

+ 8380.77 × Region_West

---

## Coefficient Interpretation

### Marketing Spend

Positive and statistically significant.

### Footfall

Strongest predictor of monthly sales.

### Inventory Availability

Stores with better inventory availability generally generate higher monthly sales.

### Customer Rating

Higher customer ratings are associated with increased monthly sales.

### Region Dummy Variables

North was selected as the reference category.

The coefficients for East, South, and West represent the expected difference in monthly sales compared to North while holding all other variables constant.

Since the p-values for the regional dummy variables exceed 0.05, these regional differences should not be over-interpreted.

---

## Reference Category

North Region

---

## Final Model Selected

The multiple regression model was selected because it achieved the highest explanatory power (R² = 0.814) and included multiple statistically significant business variables.