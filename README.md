# Alcohol Consumption & Life Expectancy in South and Southeast Asia

**Econometrics · University of Massachusetts Amherst · Akanksha Sharma**

## Question
Does alcohol consumption explain differences in life expectancy across South and Southeast Asia, once income and region are taken into account?

## Data
WHO life expectancy panel (via Kaggle), South and Southeast Asian countries, 2000–2015. Key variables: life expectancy, log GDP, alcohol (litres of pure alcohol per capita), development status, and region.

## Model
Life expectancy regressed on log GDP, alcohol consumption, region, and their interaction terms. The log transformation captures diminishing returns to income; interactions test whether effects differ by region. Countries were also split into low (≤ 1.0 L) and high (> 1.0 L) consumption groups.

## Results
- **GDP** is the strongest predictor, with a larger effect in Southeast Asia than in South Asia
- **Low-consumption group:** no relationship (slope 1.78, p = 0.94, R² ≈ 0.00007)
- **High-consumption group:** weak negative slope (−0.65 years per litre), not significant at 5% (p = 0.069, R² = 0.027)
- Countries such as Singapore and Thailand combine moderate drinking with high life expectancy, pointing to healthcare access and income as the bigger drivers

## Limitations
Small sample, few controls, and possible data-quality issues. Healthcare spending and pollution measures would strengthen future work.

## Files
- `Project_Econometrics.pdf` — research poster

**Methods & tools:** R / RStudio · ggplot2 · OLS regression · Interaction terms · Log transformation
