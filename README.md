# Final-Project
Using Linear Regression and Decision Tree to determine wine quality by chemical makeup

## Introduction
The purpose of this project was to create a machine learning model that could help wine makers and wine sellers classify wine quality based on a variety of chemical variables, such as Citric Acid level, Sulphates, and Alcohol Percentage. This would allow wine makers determine what the ideal chemical qualities of a good red or white wine are, in order produce wines that will be most highly rated by experts. Determining quality of wine will also help wine sellers decide how much to charge for certain wines without having to have an expensive professional wine tasting. We created two models to try and better understand what variables will have the most influence on wine quality, one Linear Regression Model and one Decision Tree Model. We also ran a correlation matric to determine how correlated the variables were with each other before creating our machine learning models. 
## Data Sets
We had two different data sets for this project, one that consisted all of Portuguese Red Wines and the other consisting of Portuguese White Wines. The White Wine data set had 4898 different wines listed, while the Red Wines list had 1599 wines listed. Each data set has twelve variables: Fixed Acidity, Volatile Acidity, Citric Acid, Residual Sugar, Chlorides, Free Sulfur Dioxide, Total Sulfur Dioxide Density, pH, Sulphates, Alcohol Percentage and Quality. The values for all variables besides Quality are determined by testing the chemical properties of the wine, while Quality was dewtermined by the ratings between 1 and 10 given to each wine by professional wine tasters. 
#### Histogram Showing Quality Ratings for Red Wines
<img src="redwinehisto.PNG">

#### Histogram Showing Quality Ratings for White Wines
<img src="whitewinehisto.PNG">

## Trained Models & Visualizations 

### Correlation Matrix

#### Red Wine Process and Result
<img src="corr_matrix_process_rw.PNG">
<img src="corr_matrix_rw.PNG">

#### White Wine Process and Result
<img src="corr_matrix_process_ww.PNG">
<img src="corr_matrix_ww.PNG">

### Linear Regression Models

#### Red Wine Linear Regression Process and Result
<img src="linear_reg_process_rw.PNG">
<img src="linear_reg_rw.PNG">
