# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
 Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. Both variables that had the most amount of random variance are ground_clearance and vehicle_length.
- Is the slope of the linear model considered to be zero? Why or why not? 
The slope is not zero just by looking at the p-value, which is less than 0.05.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The R-squared value is 71%, which means roughly ~71% of the time the model will predict mpg values correctly. There are probably other factors that were not captured in the datasaet that contribute to the mpg variability of the MechaCar prototypes.

- Model summary

![Model Summary](https://user-images.githubusercontent.com/92067596/171857042-a15d068e-a669-41b1-8050-6d0fba9c3ee9.png)

## Summary Statistics on Suspension Coils
- Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
Lot 1 and Lot 2 are both within design specifications and have the same exact mean and median. Lot 3 shows the most variance and exceeds the manufacturers specs.

![Lot summary](https://user-images.githubusercontent.com/92067596/171860240-c1b85ed2-50ca-40c7-b1ed-925f7dc019cb.png)


## T-Tests on Suspension Coils


![sample 1](https://user-images.githubusercontent.com/92067596/171861436-e07979fd-ad04-45ce-b9ac-312a33d9df7c.png)

![Sample 2](https://user-images.githubusercontent.com/92067596/171861446-78db8804-bc2b-4739-8777-05e1ac3efc2c.png)

![sample 3](https://user-images.githubusercontent.com/92067596/171861460-884a4d68-4bc4-4260-8932-313c1319195c.png)

![Sample 4](https://user-images.githubusercontent.com/92067596/171861466-5142a9e7-4c2b-4020-b7ff-a210d19e03b6.png)


## Study Design: MechaCar vs Competition
### Comparisson Metrics:
### Hypothesis: Null and Alternative
### Statistical Tests
