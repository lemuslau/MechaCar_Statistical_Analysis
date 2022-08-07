# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
-Through linear regression was able to idenitfy that vehicle length and the ground_clearance provided non random amounts of variance. The intercept was also statistically significant which indicates that there are possibly other factors that have a  impact on the MPG.
-The p-value was less than zero (5.35e-11), meaning the slope is not equal to zero
-The R squared value is 71.49% which implies that roughly 71% of the time the predictions will be correct using the linear model. The main indicator of whether the linear model predicts the mpg of the MechaCar is the r-squared value. This means that the model would be considered effective with that under consideration.
![Deliverable 1](https://user-images.githubusercontent.com/102635884/183274096-f1813fb8-91d2-442c-a09c-4956bb82f1db.PNG)

## Summary Statistics on Suspension Coils
Total Summary

![Deliverable 2 - Total Summary](https://user-images.githubusercontent.com/102635884/183274770-e90645c6-6112-40cd-8d1c-62eec6f46ea7.PNG)

Lot summary

![Deliverable 2 - Lot Summary](https://user-images.githubusercontent.com/102635884/183274756-9ab01b69-e748-492f-922a-6eacdc782ff0.PNG)

Under the total summary, the PSI is under 100 and meets the design speicifications. Looking at each lot indicudually, not all lots fit the speicifcations. Lot 1 and Lot 2 meet it, but lot 3 is signicatanly over the 100 PSI at 170.28 

## T-Tests on Suspension Coils
Suspension coils for all lots 

![D3 T-Test All Lots](https://user-images.githubusercontent.com/102635884/183275195-60696cbe-0ba9-46dc-8df4-5080b9c9e22a.PNG)

The P-values from single T-Test on PSI values for All Lots was .06028, and indicifually Lot 1 PSI= 1, Lot 2 PSI= 0.6072, and Lot 3 PSI= 0.04168.Standard significance value is p=.05. and becasue it was not defined for this analysis then only Lot 3 shows any kind of significant difference from the other 2 lots.  This could mean that Lot 3 might need to be re-evaluted. 

T-Test for Each lot individually 

![D3 T-Test Lot 1](https://user-images.githubusercontent.com/102635884/183275199-53d27d9e-c83b-4042-b12e-15e5d3e05b5a.PNG)
![D3 T-Test Lot 2](https://user-images.githubusercontent.com/102635884/183275218-e858324d-ad6e-47c6-a1b6-e8297af82ae9.PNG)
![D3 T-Test Lot 3](https://user-images.githubusercontent.com/102635884/183275219-d92095de-d159-486a-8d3a-5f03b9555968.PNG)


## Study Design: MechaCar vs Competition.

There are many factors that consumers take into consideration when evaluating a car to purchase. However, in a world where ridesharing is becoming more ubiquitous and it's easy and cheap to get around in other people's vehicles, customers looking to purchase a car are looking for more than just a conveyance. They will be looking to buy a car that is an economical means to regularly transport themselves and their items on a reliable, regular basis.

### Metrics to Test
Metrics to test could include city and highway fuel efficiencies as these are can differ in high cost factors depending on car type.

### Null and Alternate Hypothesis
Null Hypothesis is that cars in the same class type will have the same fuel efficiencies. Meanwhile the Alternative Hypothesis is that they are not all the same.

### Statistical Test Used
The best statistical test for this would to integrate an ANOVA test to compare the different fuel efficiencies.

### What data is needed
The data needed would include information of fuel efficiency data from a group of cars in order to get data for eaxh car class. 
