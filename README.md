# MechaCar Statistical Analysis

## Project Overview

Due to MechaCar's production troubles, AutosRU has called the data analytics team to review the production data to provide helpful and relevant information for the manufacturing team.



## Results

## Linear Regression to Predict MPG

![](https://github.com/EnoVaqari/MechaCar_Statistical_Analysis/blob/main/Images/1.png)

* Based on the results, vehicle length and vehicle ground clearance variables show non-random amounts of variance to the linear model. However, the vehicle weight, spoiler angle, and AWD variables show random amounts of variance to the linear model. Based on this, it is determined that vehicle length and vehicle ground clearance have an influence on miles per gallon.
* The P-value of 5.35e-11 is lower than the Normal Significance Level of 0.05, therefore the null hypothesis will be rejected. Also we come to the conclusion that the slope of the linear model is not zero.
* The R-squared of this linear model is 0.7149, which means that 71% of miles per gallon prediction will be based on this model. This linear model can be considered effectively to predict mgp of MechaCar prototypoes.

## Summary Statistics on Suspension Coils

![](https://github.com/EnoVaqari/MechaCar_Statistical_Analysis/blob/main/Images/2.png)
Total summary.
![](https://github.com/EnoVaqari/MechaCar_Statistical_Analysis/blob/main/Images/total_summary.png)
***
Lot summary.
![](https://github.com/EnoVaqari/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary.png)

* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The total summary for all manufacturing lots shows a variance of 62.3 psi, which does not exceed the 100 pounds per square inch specification. The specifications of lot sumarry for each manufacturing Lot show that Lot 1 and Lot 2 have variances of 0.98 and 7.5 psi respectively, which do not exceed the 100 pounds per square inch specification. Lot 3 has a variacne of 170.3 psi, which surpasses the 100 pounds per square inch specification.


## T-Tests on Suspension Coils
T-test results for all manufacturing lots
![](https://github.com/EnoVaqari/MechaCar_Statistical_Analysis/blob/main/Images/3.png)

* The P-Value is 0.06 and is larger than the Normal Significance Level of 0.5, which means that the null hypothesis cannot be rejected due to the fact that the P-value is not low enough. 

T-tests for each manufacturing lot (Lot 1, 2 and 3)

![](https://github.com/EnoVaqari/MechaCar_Statistical_Analysis/blob/main/Images/4.png)

Lot 1

* Lot 1 has a P-Value of 1 and cannot reject the null hypothesis, which states that there is no statistical difference between sample mean and population mean.

Lot 2

* Lot 2 has a P-value of 0.61 and sample mean of 1500.02. The sample mean and population mean have no statistical difference with each other. Also with a P-value of 0.61, the null hypothesis cannot be rejected.

Lot 3

*  Lot 3 has a P-value of 0.04 and a sample mean 1496.14. Since the P-value is lower than 0.05, the null hypothesis can be rejected since there is no staticial difference between sample mean and population mean.

## Study Design: MechaCar vs Competition

The goal of the company is to make MechaCar vehicles better in performance compare to market. The analysis included six different variables. However, for better and more accurate results, the company should have additional data such as the safety features, price, horsepower, engine type, and trip disctance information with MPG efficiency. Additionally, data about other veihcles in the market should be provided and analyzed for a more accurate comparison.


**What metric or metrics are you going to test?**

* Safety features
* Price
* Horsepower
* Engine type
* MPG efficiency

**What is the null hypothesis or alternative hypothesis?**

* Null Hypothesis (Ho) -  There is no statistical difference between the observables of MechaCar and the competition.
* Alternative Hypothesis (Ha) - MechaCar has statistical difference between the observables compared to the competition.

**What statistical test would you use to test the hypothesis? And why?**
One tailed T-test will be used to test the hypothesis. The statistical test will show MechaCar's position compared to the competition. 


**What data is needed to run the statistical test?**
To run the statistical test, safety features, price, horsepower, engine type, and MPG efficiency for MechaCar and competitors is needed.
