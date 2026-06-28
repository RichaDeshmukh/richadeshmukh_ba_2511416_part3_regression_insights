# richadeshmukh_ba_2511416_part3_regression_insights

# Regression-Based Business Insights & Model Interpretation

## Business Problem

The leadership team of a retail chain wants to identify the key factors influencing monthly sales across stores. The objective is to understand which operational and business variables are most strongly associated with sales performance and to provide data-driven recommendations for improving revenue.

---

# Dataset Description

The dataset contains monthly operational information for 320 retail stores.

### Variables

## Dependent Variable

- monthly_sales

## Independent Variables

- marketing_spend
- footfall
- avg_discount_pct
- staff_count
- inventory_availability_pct
- competitor_distance_km
- holiday_flag
- customer_rating
- region (converted to dummy variables)

---

# Data Preparation

The following preprocessing steps were performed before building regression models.

- Original dataset preserved in a separate worksheet.
- No duplicate records were found.
- One missing value was identified in the customer_rating column.
- The missing value was replaced using the column mean (3.9).
- Region was converted into dummy variables.
- North was selected as the reference category.

---

# Regression Approach

Three regression models were developed.

### Model 1

Simple Regression

Dependent Variable

- Monthly Sales

Independent Variable

- Marketing Spend

---

### Model 2

Simple Regression

Dependent Variable

- Monthly Sales

Independent Variable

- Footfall

---

### Model 3

Multiple Regression

Dependent Variable

- Monthly Sales

Independent Variables

- Marketing Spend
- Footfall
- Inventory Availability
- Customer Rating
- Region Dummy Variables

---

# Model Comparison

| Model | R² |
|------|------|
| Marketing Spend | 0.167 |
| Footfall | 0.736 |
| Multiple Regression | 0.814 |

The multiple regression model provided the strongest explanatory power and was selected as the final model.

---

# Final Model Selected

The final model includes:

- Marketing Spend
- Footfall
- Inventory Availability
- Customer Rating
- Region Dummy Variables

Model Performance

- R² = 0.814
- Adjusted R² = 0.810

---

# Business Recommendation

The analysis indicates that footfall, inventory availability, marketing spend, and customer rating are significant drivers of monthly sales.

Leadership should prioritize increasing customer visits, maintaining inventory availability, investing efficiently in marketing campaigns, and improving customer satisfaction.

Regional differences were not statistically significant after controlling for operational variables.

---

# Assumptions and Limitations

- Linear relationships are assumed.
- Regression identifies association rather than causation.
- External factors such as seasonality, local events, and economic conditions were not included.

---

# Screenshots Included

- simple_regression_output.png
- multiple_regression_output.png
- residuals_preview.png
- model_comparison_preview.png
