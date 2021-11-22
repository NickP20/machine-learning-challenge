# Exploration of Exoplanets using Machine Learning
## Machine Learning Models to Categorize Exoplanets Candidates

![PlanetsImage](https://physicsworld.com/wp-content/uploads/2018/02/2018-02-13-trappist.jpg)

## Background
---
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. I sought to create machine learning models capable of classifying candidate exoplanets from the raw dataset.

## Analysis
---
I created 5 Machine learning models to evalute their accuracy. 

1. Deep Learning Model: Loss = 0.2514 Accuracy = 0.9062
2. KNN (K Nearest Neighbors) Model: Training Data Score = 0.83578 Testing Data Score = 0.83066 (k=13)
3. Logistic Regression Model: Training Data Score = 0.84665 Testing Data Score = 0.86384
4. Random Forests Model: Training Data Score = 1.0 Testing Data Score = 0.90904
5. Support Vector Machine: Training Data Score = 0.8863246233072668 Testing Data Score = 0.9016018306636155

All of the models I created have farily good accuracy with the Random Forest, Deep Learning and SVM models being all very similar in accuracy. Any of these models would be well utilized for further analysis. 
