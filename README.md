# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Read the csv file
<br>

### Step2
Get the value of X and y variables
<br>

### Step3
Create the linear regression model and fit
<br>

### Step4
Predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm cube.
<br>

### Step5
Print the predicted output.
<br>

## Program:
```

Developed by: Prakash C
Reg.No: 212223240122

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
print("Account",regr.predict([[3300,1300]]))


```
## Output:

![Screenshot 2024-05-15 224700](https://github.com/Prakash-Chandran/Multivariate-Linear-Regression/assets/147120899/848dc8a3-4955-468c-9866-52745b058f43)

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
