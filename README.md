### Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import panda module as pd
### Step2
Import linear model from sklearn
### Step3
Read the file cars.csv
### Step4
Assign the values for x and y as required
### Step5
Create the linearRegression model and predict the output

## Program:
```
#Developed by: Dhanusya .K
#Registration name: 23006651
import pandas as pd
from sklearn import linear_model
df=pd.read_csv('cars.csv')
a=df[['Weight', 'Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient",regr.coef_)
print("Intercept:", regr.intercept_)
print("Amount:", regr.predict([[3300,1300]]))





```
## Output:
![Screenshot 2024-01-03 091014](https://github.com/Dhanu654/Multivariate-Linear-Regression/assets/148514965/253dce1e-086e-4d91-a8b5-9220caccc1fa)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
