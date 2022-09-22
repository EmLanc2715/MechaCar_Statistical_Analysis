# MechaCar_Statistical_Analysis
Software: R and RStudio
Data Tools: tidyverse, dplyr, ggplot2

## Linear Regression to Predict MPG

<b>Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?</b>

Vehicle length and vehicle ground clearance provided a non-random amount of variance due to the model. These two variables have a statistically significant impact on miles per gallon for the MechaCar prototype. 

<b>Is the slope of the linear model considered to be zero? Why or why not?</b>

 The screenshot below reveals that for this model, the p-Value = 5.35e-11. This value is much smaller than the assumed 0.05% significance level. This finding indicates that there is sufficient evidence to reject the null hypothesis. When the null hypothesis is rejected, that means the slope of the linear model is not zero.
  
<b>Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?</b>

The linear model has an r-Squared value of 0.7149, which roughly means that 72% of all mpg predictions can be determined by this model. In conclusion, this multiple regression model does predict mpg of MechaCar prototypes effectively.

![Deliverable1](https://user-images.githubusercontent.com/101427781/191613239-da5fee22-02cf-46ba-ae75-6e1c48c48128.png)

## Summary Statistics on Suspension Coils

#### total_summary image below

![total_summary_D2](https://user-images.githubusercontent.com/101427781/191632820-6190068e-edbc-4fb5-90dd-0f0fddb60384.png)

#### lot_summary image below 

![lot_summary_D2](https://user-images.githubusercontent.com/101427781/191632851-9f36e31c-9ab0-417d-86d5-1d4c09dc5afa.png)

<b>The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?</b>

The current manufacturing data indeed meets the design specification. In the above table, the variance of coils was calculated as 62.29 PSI, which is below the 100 PSI variance requirement.

## T-Tests on Suspension Coils

#### T-Test image

![T-Tests_D3](https://user-images.githubusercontent.com/101427781/191633560-28c31e94-70fd-4823-ac56-c29f81d49641.png)

### Summary of t-test Results

As shown above, the true mean of the population is 1498.78, which varies slightly from the presumed mean of 1500. The p-value is 0.06, which is higher than the average significance level of 0.05. In conclusion, there is not enough evidence to support rejecting the null hypothesis. To better explain, the mean of all three of the manfacturers lots is statistically similar to the presumed population mean of 1500.

Lot 1s ample actually had a true mean of 1500, and with a p-value of 1, the null hypothesis cannot be rejected. Meaning, there is no statistical difference between the observed sample mean and the presumed population mean.

Lot 2 sample has ery similar outcome to Lot 1. Lot 2s sample mean was 1500.02, and witha p-value of 0.04, again the null hypothesis cannot be rejected.

Lot 3s sample mean is 1496.14, and the p-value is 0.04. This p-value is lower than the standard significance level of 0.05. This indicates that the null hypothesis can be rejected, meaning that the sample mean and the presumed mean are significantly different.

## Study Design: MechaCar vs Competition

<b> 1. What metric or metrics are you going to test? </b>

 1. Miles Per Gallon
 2. Engine Type
 3. Safety Rating
 4. Price
 5. Average Cost of Maintenance

<b> 2. What is the null hypothesis or alternative hypothesis? </b>

The null hypothesis:
         MechaCar is priced accurately based on mpg, engine type, and safety rating.
         
Tehe alternative hypothesis:
         MechaCar is not priced accurately based on mpg, engine type, and safety rating.

<b> 3. What statistical test would you use to test the hypothesis? Why? </b>

I would used a multuple linear regression test to test this hypothesis because it will show the correlation between the price and all three of the tested metrics.
