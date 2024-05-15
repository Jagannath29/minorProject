## Business Understanding: Problem Statement

- According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally.
- Stroke is responsible for approximately 11% of total deaths in the world
- The dataset is provided to predict whether a patient is likely to get stroke or not on the basis of given input parameters
- Each row in the data provides relavant information about the patient.
- After going through the context of datasets, we can say that it is a binary classification problem
- We have to make prediction on the target variable STROKE
- Finally, we have to build a model to get the best prediction on the stroke variable



## Exploratory Data Analysis and Data Cleaning

### Exploratory Data Analysis (EDA)

- EDA is an approach of analyzing data sets to summarize their main characteristics

### Data Cleaning

- Data cleaning is the process of detecting and correcting corrupt or inaccurate records from a record set, table, or database and refers to identifying incomplete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or deleting the dirty or coarse data.

### Missing Data

- In programming we refer to missing values as a null value.

- We can use the following functions to identify missing values:

   - isnull()
   - notnull()

### Replacing missing values
- We need to replace various missing values (such as empty string, ?, null, etc) with python's default missing value marker i.e. NaN, so that it will be easier to handle the missing values of a dataset later. Let's see two different approach to convert missing values to python's default missing value marker.

  
## Data Preparation and Feature Engineering
### Categorical Encoding

### Categorical Encoding

- Encoding categorical data is a process of converting categorical data into integer format so that the data with converted categorical values can be provided to the different models.

- There are two most widely used encoding techniques:

  -  Label Encoding
  -  One-Hot Encoding

### Label Encoding

- Label Encoding is a popular encoding technique for handling categorical variables. In this technique, each label is assigned a unique integer based on alphabetical ordering.



### One-Hot Encoding

- One-Hot Encoding is another popular technique for treating categorical variables. It simply creates additional features based on the number of unique values in the categorical feature. Every unique value in the category will be added as a feature. One-Hot Encoding is the process of creating dummy variables.


## Model Training
### Logistic Regression

- Logistic regression is a classification machine learning algorithm(supervised) used in binary or multi-class classification. It tries to estimate the class of input features using S-shaped sigmoid function/curve which indicates the likelihood of something. The value from sigmoid function always ranges [0,1] (probablistic value)

- Logistic regression is one of the most popular classification Machine Learning algorithms, which comes under the Supervised Learning technique. It is used for predicting the categorical dependent variable using a given set of independent variables.

-    Logistic regression predicts the output of a categorical dependent variable. Therefore the outcome must be a categorical or discrete value. It can be either Yes or No, 0 or 1, true or False, etc. but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and 1.



### To run this project, Type below commant in your terminal
- git clone https://github.com/Jagannath29/minorProject.git
- pip install -r requirements.txt
