# Flow of AI/ML/Data Science Projects from hands-on perspective

1. Import libraries
    - import pandas as pd
    - import numpy as np
2. Import dataset
    - df = pd.read_csv('Data.csv')
3. visualize data
    - df.head()
    - df.tail()
    - df.describe()
    - df.info()
    - df.isnull().sum()
    - df.isnull().sum()/df.shape[0]
    - df.columns
4. Data preprocessing (clean,imputation etc.)
5. Split dataset into training and test set
6. Feature scaling if required
7. Create model, Train it
8. Test model
9. Predict from model

df = pd.read_csv('filename.csv')


Independent variables: variable/feature/columns in data that is not dependent on other variables. 
    - X


Dependent variables: variable/feature/columns in data that is dependent on other variables.


Numerical variables: Values will be in numbers. 
Categorical variables: Values will be in text.
