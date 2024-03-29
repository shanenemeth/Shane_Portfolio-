# Shane Nemeth Portfolio
Data Science Portfolio. Headers are hyperlinks to the actual project github repository which include the R code used. 

# [Project 1: Cluster Analysis](https://github.com/shanenemeth/K--Means-Clustering-)
* Analyzed an iris dataset to segment different flower types into distinct clusters based on their attributes 
* Scaled the dataset in preperation for the algorithm
* Utilized the "Elbow Method" to determine the optimal number of "K" or clusters for the model
* Used the K-Means function to create the clusters
* Visualized the clusters using factoextra package 

## Elbow Plot
![](images/elbow%20plot.png)

## Clusters
![](images/K%20MEANS.png)

# [Project 2: Naive Bayes Classifier](https://github.com/shanenemeth/Naive-Bayes-Classifier-)
* Analyzed a college admissions dataset to predict the probability of whether a student was admitted to a school based off 3 independent variables - "GPA", "GRE", "RANK" and 1 response variable - "ADMIT"
* Converted "RANK" and  "ADMIT" variables to factors 
* Partitioned the data into testing and training subsets
* Used ggplot2 to create density and box plots of the two continuous variables 
* Utilized a Naive Bayes classification algorithm to predict probability of admission
* Accuracy of the model was .72 and sensitivity was .90
* [Packages used: "naivebayes", "dplyr", "caret", "ggplot2" and "e1071"]

![](images/box%20plot.png)

![](images/density%20plot.png) 

# [Project 3: Logit Regression to Predict Diabetes](https://github.com/shanenemeth/Logistic-Regression-)
* Analyzed a diabetes dataset with the goal of predicting a binary response variable - whether an observation has diabetes using logit regression 
* Split dataset into training and testing subsets 
* Utilized ROCR package to determine best threshold and performance for the model
* Created a ROC plot to determine the best probability threshold for the model and reduce the false positive rate 
* Identified .3 as the best threshold for the model to obtain the lowest false positive rate while maintaining the highest accuracy 
* Accuracy of the model was .76

### ROC Plot
 ![](images/Logistic.png)
 
# [Project 4: Multiple Linear Regression using Best Subset Selection](https://github.com/shanenemeth/Regfit)
* Analyzed dataset of MLB players with  observations of 20 variables to try and predict player Salary
* Cleansed data, ommiting missing values for Salary variable
* Used best subset selection regression technique to produce the best model for predicting player Salary 
* Plotted RSS and adjusted R2 for number of variables 
* Used max function to determine which combination of variables produced highest adjusted R2
* Identified model 11 as the best fit for the data, using adjusted R2 as the criteria 

 ![](images/regfit.png)
 
 
