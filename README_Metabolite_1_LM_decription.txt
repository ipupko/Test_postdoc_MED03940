
Call:
lm(formula = variables2[[q]] ~ Sex + BMI + age, data = original_dataset)

Residuals:
      Min        1Q    Median        3Q       Max 
-0.159585 -0.058972  0.007439  0.059884  0.152066 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  1.35758    0.18951   7.164  1.6e-10 ***
Sexmale     -0.02717    0.01727  -1.573    0.119    
BMI          1.99794    0.00636 314.158  < 2e-16 ***
age         -0.29148    0.00589 -49.487  < 2e-16 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.0832 on 96 degrees of freedom
Multiple R-squared:  0.999,	Adjusted R-squared:  0.999 
F-statistic: 3.324e+04 on 3 and 96 DF,  p-value: < 2.2e-16

