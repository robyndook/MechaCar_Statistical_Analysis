# MechaCar_Statistical_Analysis
Module 15: Statistics and R
## Linear Regression to Predict MPG

![image1](https://github.com/robyndook/MechaCar_Statistical_Analysis/blob/a217faf7a7d55c5ae754e162451d4adb2c369a8e/Images/2022-04-09_10-38-53.jpg)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
    - Vehicle length and ground clearance variables represent non-random amounts of variance as applied to the mpg values.
- Is the slope of the linear model considered to be zero? Why or why not?
    - The multiple linear regression formula results in a non-zero slope
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
    - R-square is 0.71 meaning 71% chance the model will predict mpg variations correctly. We can consider this linear model efficient to predict mpg of MechaCar prototypes given the current data set.
## Summary Statistics on Suspension Coils

total_summary
![image2](https://github.com/robyndook/MechaCar_Statistical_Analysis/blob/a217faf7a7d55c5ae754e162451d4adb2c369a8e/Images/2022-04-09_10-59-23.jpg)

lot_summary
![image3](https://github.com/robyndook/MechaCar_Statistical_Analysis/blob/a217faf7a7d55c5ae754e162451d4adb2c369a8e/Images/2022-04-09_10-59-46.jpg)

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
    - The design specs are respected for all manufacturing lots in total with a global variance of 62 psi < 100 within the expected design specifications of staying under 100 PSI. 
    - Lot 3 is a large contributing factor to the variance being high. Lot 3 variance of 170 > 100 and does not meet the design specifications.
## T-Tests on Suspension Coils

![image4](https://github.com/robyndook/MechaCar_Statistical_Analysis/blob/a217faf7a7d55c5ae754e162451d4adb2c369a8e/Images/2022-04-09_11-09-37.jpg)

- The p-value = 1 is above the significance level. We do not have sufficient evidence to reject the null hypothesis.

Lot 1
![image5](https://github.com/robyndook/MechaCar_Statistical_Analysis/blob/a217faf7a7d55c5ae754e162451d4adb2c369a8e/Images/2022-04-09_11-10-41.jpg)

- The p-value = 1.7 is above the significance level.

Lot 2
![image6](https://github.com/robyndook/MechaCar_Statistical_Analysis/blob/a217faf7a7d55c5ae754e162451d4adb2c369a8e/Images/2022-04-09_11-11-54.jpg)

- The p-value = .0006 is below the significance level.

Lot 3
![image7](https://github.com/robyndook/MechaCar_Statistical_Analysis/blob/a217faf7a7d55c5ae754e162451d4adb2c369a8e/Images/2022-04-09_11-12-45.jpg)

- The p-value = 1.6 is above the significance level.

## Study Design: MechaCar vs Competition

- What metric or metrics are you going to test?
    - Safety Ratings, Horsepower, City and Highway Fuel Efficiency, Maintenance Cost, and Price per Unit
- What is the null hypothesis or alternative hypothesis?
    - ???
- What statistical test would you use to test the hypothesis? And why?
    - Using a statistical summary would show how the variables impact the safety ratings for MechaCar and their competitors.
- What data is needed to run the statistical test?
    - A random sample from MechaCar and their competitor for Safety Ratings, Horsepower, City and Highway Fuel Efficiency, Maintenance Cost, and Price per Unit to analyize through RStudio.
