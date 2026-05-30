# DAPS_Final_Project_Piedmont_Triad_Real_Estate_Analysis
Booth Data Analysis final project: Identifying undervalued real estate investment opportunities in the Piedmont Triad, NC

## Project Summary

This project identifies undervalued residential real estate investment 
opportunities in the Piedmont Triad region of North Carolina (Greensboro 
and High Point) for small investors pursuing fix-and-flip or buy-to-rent 
strategies with acquisition budgets under USD 1 million.

The analysis combines three data sources: RentCast for active listings 
and market aggregates, U.S. Census ACS for zip-level demographics, and 
FRED for mortgage rate context. A heuristic Investor Opportunity Score 
ranks all 952 cleaned listings on five hand-weighted signals. Two 
statistical models then test whether those hand-picked weights hold up 
under regression: a linear regression predicting price (R² = 0.78) and 
a logistic regression classifying deal status (ROC-AUC = 0.69). 
Supplementary SQL analysis provides strategic market-level context.
