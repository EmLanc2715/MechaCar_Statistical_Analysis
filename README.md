# MechaCar_Statistical_Analysis
Software: R and RStudio
Data Tools: tidyverse, dplyr, ggplot2

## Linear Regression to Predict MPG

<b>Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?</b>

Vehicle length and vehicle ground clearance provided a non-random amount of variance due to the model. These two variables have a statistically significant impact on miles per gallon for the MechaCar prototype. 

<b>Is the slope of the linear model considered to be zero? Why or why not?</>

 The screenshot below reveals that for this model, the p-Value = 5.35e-11. This value is much smaller than the assumed 0.05% significance level. This finding indicates that there is sufficient evidence to reject the null hypothesis. When the null hypothesis is rejected, that means the slope of the linear model is not zero.
  
<b>Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?</b>

The linear model has an r-Squared value of 0.7149, which roughly means that 72% of all mpg predictions can be determined by this model. In conclusion, this multiple regression model does predict mpg of MechaCar prototypes effectively.

![Deliverable1](https://user-images.githubusercontent.com/101427781/191613239-da5fee22-02cf-46ba-ae75-6e1c48c48128.png)

## Summary Statistics on Suspension Coils

<b>The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?</b>

total_summary screenshot here

lot_summary screenshot here 

## T-Tests on Suspension Coils

screenshot of t-test here

### Summary of t-test Results

## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:

What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?
