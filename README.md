# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
<img width="525" alt="Screen Shot 2022-03-05 at 12 02 12 AM" src="https://user-images.githubusercontent.com/93438483/156868917-dd5cb2f7-d9be-4ad4-8448-d7a0ea6bb836.png">
According to the Pr(>|t|) value, the vehicle lenght and the vehicle ground clearance are the most likely to provide a non-random event.
The slope of the line is not zero because the p-value 5.35e-11 is much smaller than the significance level of 0.05%.
The R-squared is equal to 71% which is efficent enough to predict the mpf of MechaCar prototypes.

## Summary Statistics on Suspension Coils
**Total Summary**
<img width="634" alt="Screen Shot 2022-03-09 at 1 29 32 AM" src="https://user-images.githubusercontent.com/93438483/157386019-3cdf6228-42f3-4f22-a9d2-b423f68ee964.png">

**Lot Summary**
<img width="681" alt="Screen Shot 2022-03-09 at 1 30 30 AM" src="https://user-images.githubusercontent.com/93438483/157386067-54af8b92-b186-4b0c-8032-33945a913ecc.png">

Because the MechaCar suspension coils dictate that the variance of the suspension coils is not more that 100 psi, the tables show that Lot 3 failed the test. Even though all manufacturing lot table shows the variance to be 62.3 psi, the by lot table shows Lot 3 to be 170.3 psi while Lot 1 is 1.0 psi and Lot 2 is 7.5 psi.


## T-Tests on Suspension Coils
<img width="422" alt="Screen Shot 2022-03-09 at 1 32 24 AM" src="https://user-images.githubusercontent.com/93438483/157386122-634fe0f1-d24a-48f9-b26b-5657ce1bf293.png">
With a significance level of .05%, the global sample table is above it at 0.069. This means that we cannot reject the null hypothesis.

<img width="447" alt="Screen Shot 2022-03-09 at 1 33 32 AM" src="https://user-images.githubusercontent.com/93438483/157386142-9920c46a-919c-4851-ac17-da71425677ea.png">
Lot 1 has a p-value that is lower than the significance level. This means that we can reject the null hypothesis.

<img width="432" alt="Screen Shot 2022-03-09 at 1 33 57 AM" src="https://user-images.githubusercontent.com/93438483/157386186-6157f630-0036-41a3-940c-07e915970167.png">
Lot 2 has a p-value that is above the significance level. This means that we cannot reject the null hypothesis.

<img width="424" alt="Screen Shot 2022-03-09 at 1 34 22 AM" src="https://user-images.githubusercontent.com/93438483/157386207-a3bca4f0-71b7-4b3c-a542-3bca44f98937.png">
Lot 3 has a p-value that is above the significance level. This means that we cannot reject the null hypothesis.

## Study Design: MechaCar vs Competition

To compare MechaCar to competition, a few metrics that would be useful to a money conscious consumer are:

Price – compare the prices to similar cars
Null hypothesis would be there is no difference between the competitor and MechaCar.
ANOVA test would best test the differences between multiple samples.
I would need the prices for each car and the features to make sure they are similar

Fuel Efficiency – fuel price compared to competition for highway and city miles.
Null hypothesis would be there is no difference between the competitor and MechaCar.
ANOVA test would best test the differences between multiple samples.
I would need the mpg for each car based on highway and city miles.

Maintenance costs – the price of maintaining the vehicle should be considered.
Null hypothesis would be there is no difference between the competitor and MechaCar.
ANOVA test would best test the differences between multiple samples.
I would need the prices for popular maintenance costs for each car type.
![image](https://user-images.githubusercontent.com/93438483/157384843-4a222a07-6aeb-4f4c-8481-5d8acbc12b8b.png)
