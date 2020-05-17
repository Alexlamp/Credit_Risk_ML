# Credit_Risk_ML

## Introduction
I was challenged with using Python to create and analyze machine learning models to predict credit risk using data from LendingClub. The methods that I utilized to achieve these outcomes included: <br>

- Creating training and test groups from a given data set. <br>
- Implementing the logistic regression, decision tree, random forest, and support vector machine algorithms. <br>
- Interpreting the results of the logistic regression, decision tree, random forest, and support vector machine algorithms. <br>
- Comparing the advantages and disadvantages of each supervised learning algorithm. <br>
- Determine which supervised learning algorithm is best used for a given data set or scenario. <br>
- Using ensemble and resampling techniques to improve model performance. <br>

## Goals
- Implement machine learning models.
- Use resampling to attempt to address class imbalance.
- Evaluate the performance of machine learning models.

## Materials
- Python 3 <br>
- Jupyter Notebok <br>
- LoanStats_2019Q1.csv <br>

## Analysis 
### Ensemble Analysis
#### Balanced Random Forest Classifier
Using the balanced random forest classifier I found that the balanced accuracy score was aproximately 77%. We can assume that the model can detect 77% of the credit risks correctly. I found that the high-risk recall score was 63%, meaning the model can predict true-positive, high-risks with 63% accuracy. 34% high-risks were actually low-risks. The low-risk recall score was 91%, meaning that the model can predict true-positive, low-risks with 91% accuracy. 9% low-risks were actually high-risks. I found that the high-risk precision score was 3%, meaning that out of all predicted high-risks, only 3% were actually high-risk. 97% were actually low-risk loans. I found that the low-risk precision score was 100%, meaning that all predicted low-risk loans were predicted with 100% accuracy.   
#### Easy Ensemble AdaBoost Classifier
Using the Easy Ensemble AdaBoost Classifier I found that the balanced accuracy score was aproximately 92%. We can assume that the model can detect 92% of the credit risks correctly. I found that the high-risk recall score was 88%, meaning the model can predict true-positive, high-risks with 88% accuracy. 12% high-risks were actually low-risks. The low-risk recall score was 95%, meaning that the model can predict true-positive, low-risks with 95% accuracy. 5% low-risks were actually high-risks. I found that the high-risk precision score was 8%, meaning that out of all predicted high-risks, only 8% were actually high-risk. 92% were actually low-risk loans. I found that the low-risk precision score was 100%, meaning that all predicted low-risk loans were predicted with 100% accuracy. 
#### Ensemble Recommendation
I recommend using the Easy Ensemble AdaBoost Classifier. This model was able detect true positives with 92% accuracy compared to the 77% accuaracy of the Balanced Random Forest Classifier model. The Easy Ensemble AdaBoost Classifier was able to identify high-risk loans with 88% accuracy. This is tremendously useful for a company to accurately identify people comsidered high-risk to avoid potentially losing money. 
