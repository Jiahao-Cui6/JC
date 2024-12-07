# Optimal study design for GLS estimator under hierarchical model: A Simulation Study

### Abstract
 In this project, we provide a theatrical insight for the simple hierarchical linear model with
 binary covariate. We point out that the GLS estimator of 𝛽 is the same as OLS , no matter
 the 𝛾2,𝜎2 is known or unknown. Therefore, for unknown scenario, the empirical variance of
 the estimator will closer to the true variance as the number of simulation increases. And for
 optimal study design, we derive a closed form for the target function which is a integer non
linear programming. Instead of optimization for minimal variance of the estimator we show
 it is the same as using grid searching for the lowest empirical variance. We also derive the
 distribution of 𝒳 (inflated), marginal variance of estimatorVar(𝛽) and the lower bound of the
 variance of the estimator. We also provide a simulation study for the unknown variance case
 which can further explain the theatrical part of aim1 and aim2. We use ADEMP framework
 to do the simulation study for non-linear case(poisson).

## Files

optimal_results.csv
results_df_optimal.csv
results_df_pois.csv

### report
`project_3.Rmd`: The Rmarkdown version of the Simulation study, which includes both written text interpretations and raw code used in the Simulation. 

`project_3.pdf`: The PDF version of the Simulation study, which includes both written text interpretations and a Code Applendix with the raw code used in the analysis. 


## Dependencies

The following packages were used in this analysis: 

library(dplyr)
library(ggplot2)
library(tidyr)
library(kableExtra)
library(e1071)
library(MASS)

