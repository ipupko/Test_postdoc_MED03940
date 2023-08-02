
Call:
lm(formula = variables2[[q]] ~ Sex + BMI + age, data = original_dataset)

Residuals:
       Min         1Q     Median         3Q        Max 
-7.791e-13 -1.182e-14  2.780e-15  2.384e-14  1.976e-13 

Coefficients:
              Estimate Std. Error    t value Pr(>|t|)    
(Intercept)  4.800e+00  1.988e-13  2.414e+13   <2e-16 ***
Sexmale     -1.000e-01  1.812e-14 -5.520e+12   <2e-16 ***
BMI          2.170e+01  6.672e-15  3.253e+15   <2e-16 ***
age         -8.435e-15  6.179e-15 -1.365e+00    0.175    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 8.729e-14 on 96 degrees of freedom
Multiple R-squared:      1,	Adjusted R-squared:      1 
F-statistic: 3.554e+30 on 3 and 96 DF,  p-value: < 2.2e-16

