# Model Comparison

## Model 1: Marketing Spend

Dependent Variable

- Monthly Sales

Independent Variable

- Marketing Spend

R² = 0.167

Marketing spend is statistically significant (p < 0.001) but explains only 16.7% of the variation in monthly sales.

---

## Model 2: Footfall

Dependent Variable

- Monthly Sales

Independent Variable

- Footfall

R² = 0.736

Footfall is a highly significant predictor and explains approximately 73.6% of the variation in monthly sales.

---

## Model 3: Multiple Regression

Variables Included

- Marketing Spend
- Footfall
- Inventory Availability
- Customer Rating
- Region Dummy Variables

R² = 0.814

Adjusted R² = 0.810

Significant Variables

- Marketing Spend
- Footfall
- Inventory Availability
- Customer Rating

Statistically Weak Variables

- Region_East
- Region_South
- Region_West

---

## Comparison Summary

| Model | Variables Used | R² | Business Usefulness |
|------|----------------|------|----------------|
| Simple Regression 1 | Marketing Spend | 0.167 | Moderate |
| Simple Regression 2 | Footfall | 0.736 | Strong |
| Multiple Regression | Marketing + Footfall + Inventory + Customer Rating + Region | 0.814 | Excellent |

---

## Final Model

The multiple regression model was selected because it explains approximately 81.4% of the variation in monthly sales while considering multiple operational factors simultaneously.

---

## Limitations

- Regression measures association, not causation.
- The model excludes external influences such as weather, economic conditions, competitor promotions, and seasonal demand.