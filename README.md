# [Project 1: Restaurant Reviews Classification](https://github.com/poronburman/Restaurant-Review-Classification)

1. This project uses Natural Language Processing and various Classification models to analyze and learn from the dataset consisting of past reviews of a restaurant. These reviews are classified as being positive or negative. The models can then be used to predict if any future review for that restaurant is a positive review or a negative one. 

2. The dataset consists of 1000 rows and 2 columns; where each row is a single review for a particular restaurant. The first column has the review and the second column classifies the review as either 0 or 1, 0 representing negative review and 1 representing positive review.

3. The data analysis for this project followed the following sequential steps:
* Remove punctuations and stop words from each review.    
* Convert all words to lowercase.    
* Created a sparse matrix of the dataset.    
* Divided the dataset into training and testing data.    
* Applied the Classification model.    
* Presented the Data Analysis results: Confusion Matrix and Classification Report.    

4. Logistic Regression Classification model performed best in this project and can be used to classify any future reviews for this restaurant as positive or negative.   

5. Listed below are the Confusion Matrix and Classification Report of the various Classification models used in this project, arranged in order of decreasing accuracy:    

## Logistic Regression

**Confusion Matrix**    
![](images/logistic_cm.png)    

**Classification Report**    
![](images/logistic_classification_report.png)

## K Nearest Neighbors Classifier   

**Confusion Matrix**    
![](images/knn_cm.png)

**Classification Report**    
![](images/knn_classification_report.png)    

## Support Vector Machine    

**Confusion Matrix**    
![](images/svm_cm.png)  

**Classification Report**    
![](images/svm_classification_report.png)    

## Random Forest    

**Confusion Matrix**    
![](images/random_forest_cm.png)  

**Classification Report**    
![](images/random_classification_report.png)    

## Kernel SVM    

**Confusion Matrix**    
![](images/kernel.png)  

**Classification Report**    
![](images/kernel_classification_report.png)    

## Decision Tree    

**Confusion Matrix**    
![](images/decision_cm.png)  

**Classification Report**    
![](images/decision_classification_report.png)    

## Naive Bayes    

**Confusion Matrix**    
![](images/naive_cm.png)  

**Classification Report**    
![](images/naive_classification_report.png)
