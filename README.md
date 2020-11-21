# Module 3 - Project 2 (ML) - Revenue | No Revenue

Álvaro Noriega, Ezequiel Hoffman, Lola López y Paula Iglesias
Data Analytics Part Time Couse | Barcelona June 2020

## Question
What if that possible to predict revenue on an online shop?

In this project we have analyze an e-commerce dataset to see if it was possible to predict which users are most likely to buy. 

## Content

- Project Description and Workflow
- Conclussions
- Organization
- Links 

### Project Description:

#### The Dataset: 
The dataset consists of feature vectors belonging to 12,330 sessions.The structure is the following: 
18 columns categorized that can be group between: 
+6 Type of page visit
+ 5 User behaviour
+3 Timeline
+2 Technology & Browser
+1 Demographics
+1 Conversion

To predict if a user would buy once they visit the webpage or not, this is the workflow we followed: 

1. Data Preparation

1.1 Data Wrangling

 - Explore Data to understand each variable and understand how is our dataset like. 
 - Clean Data, work with dtypes, NaNs and outliers. 
 - Transform Data to boolean types, numerical variables and categorical. 
 
1.2 Feature Selection: 

 - Delete not useful variables
 - Correlation    
 
1.3 Feature Engineering

 - PCA 
 - MinMaxScaler
 
Training Models (Machine Learning Classification Models)

 - LogisticRegression
 - SVM
 - Decision Trees
 - Random Forest

2. Fine-Tuning

### Conclusions: 

After completing our analysis, we discovered that the Random Forest model worked best with the dataset we cleaned applying knn and mean substitution. We achieved to get a 0.88 score in our model with a 95% of the non customers correctly classified and 76% of the customers correctly classified.

### Organization:
- We organized our workspace in a data folder where we placed every dataset we worked with and also, we enumerated our notebooks in order


### Original dataset (not the one in this PROJECT)
https://www.kaggle.com/roshansharma/online-shoppers-intention#online_shoppers_intention.csv
The dataset of this project has been changed for educational purposes.


