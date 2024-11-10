# **Physical Activity Predictor**
### Project Report
https://github.com/1minute99/physical-activity-predictor/blob/main/main.ipynb

### Objective
Building a Supervised Machine Learning Model that can predict various physical activity using the time series data.

### Outcome
The machine learning model was successfully built with near-perfect accuracy (99.96%) by applying square root of sum of squares and temporal abstraction feature engineering, utilizing the Random Forest algorithm.

### About the data

The collected dataset comprises body motion and vital signs recordings for ten volunteers of diverse profile while performing 12 physical activities. Shimmer2 wearable sensors were used for the recordings. The sensors were respectively placed on the subject's chest, right wrist and left ankle and attached by using elastic straps.

The physical activities(label) are the following:
- `Standing still (1 min)` 
- `Sitting and relaxing (1 min)`
- `Lying down (1 min) `
- `Walking (1 min)`
- `Climbing stairs (1 min)`
- `Waist bends forward (20x)`
- `Frontal elevation of arms (20x)`
- `Knees bending (crouching) (20x)`
- `Cycling (1 min)`
- `Jogging (1 min)`
- `Running (1 min)`
- `Jump front & back (20x)`

The dataset contains the features:
- `acceleration from the chest sensor (X axis)`
- `acceleration from the chest sensor (Y axis)`
- `acceleration from the chest sensor (Z axis)`
- `electrocardiogram signal (lead 1)` 
- `electrocardiogram signal (lead 2)`
- `acceleration from the left-ankle sensor (X axis)`
- `acceleration from the left-ankle sensor (Y axis)`
- `acceleration from the left-ankle sensor (Z axis)`
- `gyro from the left-ankle sensor (X axis)`
- `gyro from the left-ankle sensor (Y axis)`
- `gyro from the left-ankle sensor (Z axis)`
- `magnetometer from the left-ankle sensor (X axis)`
- `magnetometer from the left-ankle sensor (Y axis)`
- `magnetometer from the left-ankle sensor (Z axis)`
- `acceleration from the right-lower-arm sensor (X axis)`
- `acceleration from the right-lower-arm sensor (Y axis)`
- `acceleration from the right-lower-arm sensor (Z axis)`
- `gyro from the right-lower-arm sensor (X axis)`
- `gyro from the right-lower-arm sensor (Y axis)`
- `gyro from the right-lower-arm sensor (Z axis)`
- `magnetometer from the right-lower-arm sensor (X axis)`
- `magnetometer from the right-lower-arm sensor (Y axis)`
- `magnetometer from the right-lower-arm sensor (Z axis)`

### Data Source
- Banos, O., Garcia, R., Holgado-Terriza, J.A., Damas, M., Pomares, H., Rojas, I., Saez, A., Villalonga, C.: 
mHealthDroid: a novel framework for agile development of mobile health applications. 
In: Proceedings of the 6th International Work-conference on Ambient Assisted Living an Active Ageing (IWAAL 2014), Belfast, United Kingdom, December 2-5 (2014)
- [UC Irvine Machine Learning Repository - MHEALTH](https://archive.ics.uci.edu/dataset/319/mhealth+dataset)
 
