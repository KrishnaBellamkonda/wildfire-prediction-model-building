# wildfire-prediction-model-building

### Description
*This project is a machine learning project built with an aim of predicting the area of land lost to wildfire given the place's salient features. This model is inspired by a extended essay project by an IB student.*

### Aim 
The aim of this exercise was to build a linear machine learning model which can predict the land area lost to wildfires given the certain weather features of a given location. 

### Table of Contents 


### Methodology 
* 1) Exploration - Understanding the features and trends in the dataset
* 2) Processing - Selecting useful data features and processing them 
* 3) Model Building - Building a suitable model
* 4) Selecting the most optimum model 
* 5) Selecting the best configuration for the model 
* 6) Testing the model 
* 7) Using the model 

* The first notebook - 'WildFireDataExploration' contains the exploration process involved in the model building process. 
* The second notebook - 'WildFireModelbuilding' contains the process of building a linear model. 


### Assumptions
* 1) The fire can spread only to adjecent blocks of land through active fire places
* 2) Every active block of fire spreads to only one other block of fire
* 3) At the end of each turn, some blocks are put off due to the salient features in that area

### Tecchnology 
* Python 
* Jupyter Notebooks

### Modules 
* pandas
* numpy
* matplotlib
* seaborn
* sklearn 
* random


### Data Visualizations


### Final Equation
$ControlRate = 0.0005*(MaxTemperature) + 0.0019*(AvgTemperature) + -0.001*(MinTemperature) + -0.0005*(MaxDewPoint) + 0.0023*(AvgDewPoint) + 0.0044*(MinDewPoint) + -0.0011*(MaxHumidity) + 0.0008*(AvgHumidity) + -0.0028*(MinHumidity) + 0.0012*(MaxWindSpeed) + 0.2288$

### Sources
