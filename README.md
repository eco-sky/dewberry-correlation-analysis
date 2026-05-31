# Dewberry Correlation Analysis (Rubus caesius)

Simple R analysis exploring correlations between plant growth traits and environmental variables in European dewberry populations.

This analysis was completed as part of EVSC 445: Environmental Data Analysis.

## Project Description

European dewberry (*Rubus caesius*) is an invasive plant species used to study relationships between plant growth traits and environmental conditions. This analysis investigates correlations between flowering characteristics, leaf area, and environmental variables such as soil moisture, canopy cover, and dewberry density.

## Research Question

Which plant traits and environmental variables are significantly correlated in European dewberry populations?

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

## Key Findings

A moderate to strong positive correlation was observed between flowering branches and flowers per branch.  
Some environmental variables showed weak to moderate relationships with plant traits.  
Not all variable pairs were statistically significant.  
Approximately 37.5% of variation in flower production was explained by flowering branch number.  

<img width="1536" height="736" alt="image" src="https://github.com/user-attachments/assets/8d245b0f-ef70-4513-b6c5-08e295e35c5a" />

## Ecological Interpretation

Prior to analysis, it was expected that dewberry growth would be positively associated with reproductive traits such as flowers per branch, flowering branch number, and leaf area. These traits are typically associated with increased reproductive output and vegetative expansion, particularly in invasive species.

Environmental variables such as soil moisture were expected to support greater plant growth, while higher dewberry abundance was expected to reflect increased plant productivity and spread.

Results indicated that reproductive traits showed the strongest relationships, particularly between flowering branches and flowers per branch. This suggests that plants with greater reproductive structure tend to have higher reproductive output.

Weaker relationships were observed for some environmental variables, suggesting that local habitat conditions alone may not fully explain variation in dewberry abundance.

Importantly, correlation does not imply causation, and observed relationships may be influenced by other ecological factors such as plant health, disturbance, or competition.

## Conclusion

This analysis demonstrates that several plant reproductive traits are significantly correlated in European dewberry populations, while some environmental variables show weaker relationships.

Overall, reproductive structure appears to be a stronger predictor of variation in dewberry performance than environmental canopy conditions in this dataset.

However, these results are observational and do not establish causal relationships.

## Data and Code Availability

The full R script used for this analysis is included in this repository.  

The dataset (`dewberries.csv`) was provided as part of the EVSC 445: Environmental Data Analysis course and was distributed to all students for instructional purposes. I did not create or collect this dataset. I acknowledge its use as a shared class resource for this assignment.

## Notes

This is an exploratory statistical analysis completed for coursework.  
All analyses were conducted in R.  
Results are based on a single dataset and should be interpreted within the limitations of sampling and correlation-based methods.
