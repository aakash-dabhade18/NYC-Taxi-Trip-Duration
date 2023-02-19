
# NYC-Taxi-Trip-Duration

## 📋 Problem Description : 
Task is to build a model that predicts the total ride duration of taxi trips in New York City. Primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.

## 💾 Project Files Description :
 - This repository includes 1 colab notebook (.ipynb) file.
 - 1 pdf file of project presentation.
 - Dataset.
 - Problem-Statement (Pdf)
 - Requirements.txt

 ## 📋Objective :
Build a model that predicts the total trip duration of taxi trips in New York City.

## 📋 Summary : 
The given dataset conatins more than 14 lac records and 11 columns. The main goal of this project to predict the trip duration. To get more insights about the dataset, performed Exploratory data analysis to understand the main characteristics of various features. Using existing features, created new features for model building and to interpret data more easily. After analyzing the dataset, it’s found that there is a some inconsistency in some recorded data. The passenger count was high like 7 to 9 passengers in taxi. The travelled distance is very less but trip duration is quite high. There were many outliers in many columns and after analyzing the data, those outliers removed and dataset prepared for model building. Various algorithms apllied on prepared dataset after train and test split of dataset. 

## Conclusion :
Linear Regression algorithm performed very poorly on given dataset. Decision Tree perform much better.

## References :

Linear Regression
Link: https://towardsdatascience.com/linear-regression-using-python-b136c91bf0a2

Decision Tree
Link: https://towardsdatascience.com/the-complete-guide-to-decision-trees-28a4e3c7be14

Random Forest Link: https://www.analyticsvidhya.com/blog/2021/10/an-introduction-to-random-forest-algorithm-for-beginners/
