# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import libraries & load dataset
2. Split data into Hours (X) and Scores (y)
3. Train Linear Regression model
4. Predict marks for given study hours (user input)
5.Display result

## Program:
```
/*
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
import numpy as np

raw_data = {
    'Hours': [12, 16, 18, 22, 24, 32, 37, 38, 40, 42],
    'Marks': [30, 37, 47, 54, 60, 63, 68, 78, 84, 92]
}
data = pd.DataFrame(raw_data)

# 2. Independent variable (X) and Dependent variable (y)
X = data[['Hours']]  # Features must be a 2D array/DataFrame
y = data['Marks']        # Target is a 1D Series

# 3. Create and Train the model
model = LinearRegression()
model.fit(X, y)

# 4. Predict values
y_pred = model.predict(X)

# 5. Display the Mathematical Equation
# Formula: y = mx + c
m = model.coef_[0]
c = model.intercept_

print(f"Slope (m): {m:.2f}")
print(f"Intercept (c): {c:.2f}")
print(f"Equation: Marks = {m:.2f} * Hours + {c:.2f}")

# 6. Plot the results
plt.figure(figsize=(10, 6))
plt.scatter(X, y, color='blue', label='Actual Data') # Scatter for original points
plt.plot(X, y_pred, color='red', linewidth=2, label='Regression Line') # Line for predictions
plt.xlabel("Hours Spent")
plt.ylabel("Marks Achieved")
plt.title("Simple Linear Regression: Hours vs Marks")
plt.legend()
plt.grid(True, linestyle='--', alpha=0.6)
plt.show()
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: ABDUL RAHMAN A R
RegisterNumber:25008775  
*/
```

## Output:
<img width="1203" height="771" alt="image" src="https://github.com/user-attachments/assets/fc39f25b-9c28-4b26-8666-54c0c44468b9" />



## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
