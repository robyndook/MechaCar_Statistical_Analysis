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

- The _p_ = 1
- "A p-value higher than 0.05 (> 0.05) is not statistically significant and indicates strong evidence for the null hypothesis. This means we retain the null hypothesis and reject the alternative hypothesis. You should note that you cannot accept the null hypothesis, we can only reject the null or fail to reject it." [Source](https://www.simplypsychology.org/p-value.html)
![image4](https://github.com/robyndook/MechaCar_Statistical_Analysis/blob/a217faf7a7d55c5ae754e162451d4adb2c369a8e/Images/2022-04-09_11-09-37.jpg)



Lot 1
- The _p_ = 1.568e-11
- "A p-value higher than 0.05 (> 0.05) is not statistically significant and indicates strong evidence for the null hypothesis. This means we retain the null hypothesis and reject the alternative hypothesis. You should note that you cannot accept the null hypothesis, we can only reject the null or fail to reject it." [Source](https://www.simplypsychology.org/p-value.html)
![image5](https://github.com/robyndook/MechaCar_Statistical_Analysis/blob/a217faf7a7d55c5ae754e162451d4adb2c369a8e/Images/2022-04-09_11-10-41.jpg)



Lot 2
- The _p_ = .0006
- "A p-value less than 0.05 (typically ≤ 0.05) is statistically significant. It indicates strong evidence against the null hypothesis, as there is less than a 5% probability the null is correct (and the results are random). Therefore, we reject the null hypothesis, and accept the alternative hypothesis."[Source](https://www.simplypsychology.org/p-value.html)
![image6](https://github.com/robyndook/MechaCar_Statistical_Analysis/blob/a217faf7a7d55c5ae754e162451d4adb2c369a8e/Images/2022-04-09_11-11-54.jpg)



Lot 3
- The _p_ = 1.6
- "A p-value higher than 0.05 (> 0.05) is not statistically significant and indicates strong evidence for the null hypothesis. This means we retain the null hypothesis and reject the alternative hypothesis. You should note that you cannot accept the null hypothesis, we can only reject the null or fail to reject it." [Source](https://www.simplypsychology.org/p-value.html)
![image7](https://github.com/robyndook/MechaCar_Statistical_Analysis/blob/a217faf7a7d55c5ae754e162451d4adb2c369a8e/Images/2022-04-09_11-12-45.jpg)



## Study Design: MechaCar vs Competition

- What metric or metrics are you going to test?
    - Safety Ratings, Horsepower, City and Highway Fuel Efficiency, Maintenance Cost, and Price per Unit
- What is the null hypothesis or alternative hypothesis?
    - Null Hypothesis = The MEAN of the safety rating _is_ zero. 
    - Alternative Hypothesis = The MEAN of the safety rating is _not_ zero.
- What statistical test would you use to test the hypothesis? And why?
    - Using a statistical summary would show how the variables impact the safety ratings for MechaCar and their competitors.
- What data is needed to run the statistical test?
    - A random sample from MechaCar and their competitor for Safety Ratings, Horsepower, City and Highway Fuel Efficiency, Maintenance Cost, and Price per Unit to analyize through RStudio.
