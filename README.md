# [Project 1: Restaurant Reviews Classification](https://github.com/poronburman/Restaurant-Review-Classification)

1. This project uses Natural Language Processing and various Classification models to analyze and learn from the dataset consisting of past reviews of a restaurant. These reviews are classified as being positive or negative. The models can then be used to predict if any future review for that restaurant is a positive review or a negative one. 

2. The dataset consists of 1000 rows and 2 columns; where each row is a single review for a particular restaurant. The first column has the review and the second column classifies the review as either 0 or 1, 0 representing negative review and 1 representing positive review.

3. The data analysis for this project followed the following sequential steps:
* Remove punctuations and stop words from each review.    
* Convert all words to lowercase.    
* Create a sparse matrix of the dataset.    
* Divide the dataset into training and testing data.    
* Apply the Classification model.    
* Present the Data Analysis results: Confusion Matrix and Classification Report.    

4. Logistic Regression Classification model performed best in this project and can be used to classify any future reviews for this restaurant as positive or negative.   

5. Listed below are the Confusion Matrix and Classification Report of the various Classification models used in this project, arranged in order of decreasing accuracy:    

## Logistic Regression

**Confusion Matrix**    
![](images/rr_logistic_cm.png)    

**Classification Report**    
![](images/rr_logistic_classification_report.png)

## K Nearest Neighbors Classifier   

**Confusion Matrix**    
![](images/rr_knn_cm.png)

**Classification Report**    
![](images/rr_knn_classification_report.png)    

## Support Vector Machine    

**Confusion Matrix**    
![](images/rr_svm_cm.png)  

**Classification Report**    
![](images/rr_svm_classification_report.png)    

## Random Forest    

**Confusion Matrix**    
![](images/rr_random_forest_cm.png)  

**Classification Report**    
![](images/rr_andom_classification_report.png)    

## Kernel SVM    

**Confusion Matrix**    
![](images/rr_kernel.png)  

**Classification Report**    
![](images/rr_kernel_classification_report.png)    

## Decision Tree    

**Confusion Matrix**    
![](images/rr_decision_cm.png)  

**Classification Report**    
![](images/rr_decision_classification_report.png)    

## Naive Bayes    

**Confusion Matrix**    
![](images/rr_naive_cm.png)  

**Classification Report**    
![](images/rr_naive_classification_report.png)

# [Project 2: SUV Car Purchase Prediction](https://github.com/poronburman/SUV-Car-Purchase-Prediction)

1. This project uses data from customers who already bought a car from a dealership and uses various classification models to learn from the dataset, and to predict if any future customer will buy a SUV car from that dealership or not.  

2. K Nearest Neighbors, Artificial Neural Network, and Support Vector Machine classification models classified the data most accurately. These three classification models can be used to predict any future customers at this dealership, if they have more chances of buying a SUV or not.    

3. The data analysis for this project followed the following sequential steps:
* Split the dataset into training and testing data.    
* Scale the data.     
* Apply the classification model.    
* Predict the result.    
* Present the Data Analysis results: Confusion Matrix and Classification Report.    

3. Listed below are the Confusion Matrix and Classification Report of the various Classification models used in this project, arranged in order of decreasing accuracy:

## K Nearest Neighbor

**Confusion Matrix**    
![](images/cp_knn_cm.png)    

**Classification Report**    
![](images/cp_knn_classification_report.png)

## Artificial Neural Network   

**Confusion Matrix**    
![](images/cp_ann_cm.png)

**Classification Report**    
![](images/cp_ann_classification_report.png)    

## Kernel Support Vector Machine    

**Confusion Matrix**    
![](images/cp_kernel_svm_cm.png)  

**Classification Report**    
![](images/cp_kernel_classification_report.png)    

## Logistic Regression    

**Confusion Matrix**    
![](images/cp_logistic_cm.png)  

**Classification Report**    
![](images/cp_logistic_classification_report.png)    

## Naive Bayes    

**Confusion Matrix**    
![](images/cp_naive_cm.png)  

**Classification Report**    
![](images/cp_naive_classification_report.png)    

## Random    

**Confusion Matrix**    
![](images/cp_random_cm.png)  

**Classification Report**    
![](images/cp_random_classification_report.png)    

## Support Vector Nachine    

**Confusion Matrix**    
![](images/cp_svm_cm.png)  

**Classification Report**    
![](images/cp_svm_classification_report.png)

