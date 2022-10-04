# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
 ground_clearance and vehicle_length provided non-random amount of variance to the mpg valuesin the dataset, and vehicle_weight also probably provided some variance, but not at a significant level. 
- Is the slope of the linear model considered to be zero? Why or why not?
Our p-value came out to 5.35e-11, making it smaller than a 0.05 significance level. Therefore, we believe the slope has a non-zero value. 
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
With a multiple r-squared value of 0.7149, we predict the model will know the mpg of Mechacar prototypes 71.49 percent of the time. This not an extremely effective model at only 71% but it should be enough to do a decent job. 

## Summary Statistics on Suspension Coils
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
1. Lots 1 and 2 are very similar. They had the exact same means and medians, and also managed to fall within design specifications required.
2. Lot 3 has a variance that is greater than the design specification.
3. When all the data is combined into one total set, our combined variance manages to fall within design specifications.

## T-Tests on Suspension Coils
- Briefly summarize your interpretation and findings for the t-test results.
1. Lots 1 and 2 have values not statistically different (alpha =0.05) from our population mean.
2. Lot 3 had a p-value of .041, meaning this had a value significantly different from our population mean.

## Study Design: MechaCar vs Competition
- What metric or metrics are you going to test?
Highway Fuel Efficiency
- What is the null hypothesis or alternative hypothesis?
We would want to test if the highway fuel efficency is significantly different from other vehicles from other manufacturers. So we would want an alternative hypothesis that highway fuel efficiency of MechaCar cars is significantly different from other manufacturers.
- What statistical test would you use to test the hypothesis? And why?
Most likely a one-sample t test because we're comparing similar vehicles and only doing one test based on efficiency points.
- What data is needed to run the statistical test?
We would need what type of car it is, and the highway fuel efficiency for each of those vehicles.
