# Lead-Score-ML: Logistic Regression
**Problem Statement:** 
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.  X Education has appointed you to help them select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%

**Business Objective**
Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

**Steps Involved:**
1. Importing Libraries
2. Loading and Analysing the DATA
3. Data Cleaning & Manipulation
4. Handling Outliers
5. Handling Null Values
6. Exploratory Data Analysis (EDA): Univariate and Bivariate Analysis 
7. Splitting the Data into Training and Testing Sets
8. Scalling:  MinMaxScaler()
9. Building a Linear Model
10. Making Predictions
11. Model Evaluation

**Libraries Used:**
1. NumPy as np
2. Pandas as pd
3. Matplotlib.pyplot as plt
4. Seaborn as sns
5. statsmodels.api as sm 
6. RFE from sklearn
7. Variance_inflation_factor (VIF)

**Inferences:** Our Model has below provided metrics from the Precision and Recall view with the cutoff of 0.44 probability on the test set.
1. Confusion Matrix: 
          Predicted     not_churn    churn
 Actual
 not_churn                2550      492
 churn                    748       1560  

2. Accuracy= 0.7682242990654206
3. Sensitivity:  TP/(TP+FN)= 0.6759098786828422
4. Specificity: TN/(TN+FP)= 0.8382642998027613
5. ROC Curve Area= 0.85
6. Precision: TP / TP + FP= 0.7602339181286549
7. Recall: TP / TP + FN= 0.6759098786828422

**Credit:** Kshitiz Thakur

![image](https://user-images.githubusercontent.com/90130378/161400231-e853d49f-79a6-4174-bf2b-134867119d53.png)
![image](https://user-images.githubusercontent.com/90130378/161400248-6b366350-0a4f-48c0-93a9-d3c42009cc57.png)


