# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step1
import panda as pd

### Step2
import linear model from sk learn

### Step3
read the csv file

### Step4
find the multivariate regression

### Step5
display the output

## Program:
```
Developed by:T.KAVINAJAI
Register no:212223100020

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))
```
## Output:

![image](https://github.com/Kavin1311/Multivariate-Linear-Regression/assets/145695724/7439800b-8a2f-4ebd-90ac-5eb4ea9f587d)



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
