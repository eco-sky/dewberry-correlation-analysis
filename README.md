# Dewberry Correlation Analysis (Rubus caesius)

Simple R analysis exploring correlations between plant growth traits and environmental variables in European dewberry populations.

This project was completed as part of EVSC 445: Environmental Data Analysis.


## Project Description

European dewberry (*Rubus caesius*) is an invasive plant species used to study relationships between plant growth traits and environmental conditions. This analysis investigates correlations between flowering characteristics, leaf area, and environmental variables such as soil moisture, canopy cover, and dewberry density.

The dataset used in this project was provided in the EVSC 445 course.


## Research Question

Which plant traits and environmental variables are significantly correlated in European dewberry populations?


## Methods

  Data source: Dewberry dataset (`dewberries.csv`) provided in EVSC 445  
  Software: R  
  Response variables: Branches with flowers, flowers per branch, leaf area  
  Environmental variables: Soil moisture, canopy cover, dewberry cover  
  
## Analytical approach  

  Summary statistics using `summary()`
  Pairwise visualization using `pairs()`
  Correlation testing using `cor.test()`
  Pairwise correlation matrix using `cor()`
  Coefficient of determination calculated from correlation values
  99% confidence interval estimation for key correlations

## Assumptions

Relationships between variables are approximately linear  
Observations are independent  
Pearson correlation is appropriate for continuous variables  

