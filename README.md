# Gender Inequality & Human Development: A Cross-Country OLS Analysis

## Overview
This project investigates whether higher gender inequality (GII) is associated with lower 
human development (HDI) across 187 countries, using UNDP 2023 data.

## Methodology
- **Tool:** STATA
- Conducted OLS regression (Model 1: HDI on GII only; Model 2: full multivariate model with 
controls for income, female education, labor force participation, and political representation)
- Tested classical OLS assumptions: linearity, random sampling, no perfect multicollinearity, 
zero conditional mean, normality of residuals
- Detected heteroskedasticity via Breusch-Pagan and White tests; corrected using 
Huber-White robust standard errors

## Key Findings
- Model 1: HDI = 0.975 − 0.699(GII), R² = 0.836
- Model 2 (full model): R² = 0.963 — GII remained negative and highly significant (p < 0.001) 
even after controlling for income, education, and labor participation
- Female secondary education and log GNI per capita were also significant predictors

## Files
- `Gender_Inequality_HDI_Presentation.pdf` — Full project writeup with visualizations, 
diagnostics, and policy implications

## Tools Used
STATA, OLS regression, robust standard errors, correlation analysis, residual diagnostics
