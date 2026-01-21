# Titanic Survival Analysis

Statistical and machine learning analysis of survival patterns in the Titanic disaster, exploring demographic factors and historical evacuation policies.

## Overview

This project uses classification models to analyze passenger survival on the Titanic and evaluate historical claims about evacuation priority, particularly the "women and children first" policy.

## Research Questions

- Is there evidence of a "women and children first" policy?
- What demographics were more likely to survive or perish?
- Do the results support portrayals in the 1997 film *Titanic*?
- What are the predicted survival probabilities for passengers like Rose and Jack?

## Technologies Used

- R
- dplyr
- ggplot2
- scales
- rpart
- rpart.plot

## Files

- `titanic_analysis.Rmd` - Main analysis with code and narrative
- `titanic_analysis.html` - Rendered output

## Key Findings

- **"Women and children first" policy was real but unevenly applied**: Women had 74% survival rate vs 19% for men, and children survived at higher rates than adults, but these advantages diminished sharply for third-class passengers
- **Class determined access to survival**: First-class women had 95% survival probability while third-class adult men had only 10% - survival disparities operated largely through unequal access to lifeboats and deck areas rather than class status alone
- **Film accuracy confirmed**: The classification tree model predicts Rose (first-class woman) at 95% survival probability and Jack (third-class adult man) at 10%, closely matching the movie's outcome
- **Sex was the primary determinant**: The decision tree identified sex as the strongest predictor, followed by passenger class and fare, with child status providing additional refinement

## How to Run

Open the .Rmd file in RStudio and knit to reproduce the analysis.
