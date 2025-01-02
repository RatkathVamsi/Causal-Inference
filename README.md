# Causal-Inference
Effect of being an international student on the flourishing of college students in the US

This was done as part of the course requirement for PUBH 7485- Methods Of Causal Inference, at the University Of Minnesota in Fall of 2024.

In this project, I have worked on the Healthy Minds Network dataset (2022-2023). I have performed data cleaning, processing where I handled missing values by imputation, converted multiple binary variables into single categorical variables. Additionally, for my specific analysis only a few covariates were considered which were selected based on prior research done in this field.

I would like to iterate that this was my first hands on experience working with survey type data and I faced quite a few challenges and had to change the treatment of interest due to huge missingness which could not be handled by me as imputating resulted in hevy bias in the model fitting and failed to produce meaningful results.

The final goal of the project was to estimate the average causal effect of being an international student on the flourishing(a scale for mental wellbeing). I have fitted multiple models and calculated the ATEs and plotted the findings in a forestplot.

The methods used were, Regression Adjustment, Propensity Score Regression, Propensity Score Stratification. Inverse Probability Weighting was done as a sensitivity Analysis. The ATEs were almost similar except in the case of IPW1 where the ATE indicated the opposite effect. I was unable to find out the cause for this.

A few limitations of this study were, being forced to convert Variables in likert scale to binary which will have resulted in loss of meaningful data. Another limitation was huge missingness in some important covariates which needed to be dropped due to modelling constraints.

This project helped me learn a lot of new things regarding data analysis, particularly when dealing with datasets with missingness and survey type datasets.
