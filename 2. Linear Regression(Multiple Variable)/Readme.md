# Linear Regression (Multiple Variable)

Linear Regreesion with multiple variable is a type of **Linear Regression** with a **two or more independent variables** and **one variable that is dependent** on our independent variables.


In our case, **Area, bedrooms and age** will be independent and **Price** will be dependent on our independent variables.

| Area  | Bedrooms | Age | Price |
| ------------- |:-------------:|:-------------:|:-------------:|
| 2600      | 3.0    | 20    | 550000    |
| 3000      | 4.0    | 15    | 565000    |
| 3200      | NaN   | 18    | 610000    |
| 3600      | 3.0     | 30    | 595000    |
| 4000      | 5.0     | 8    | 760000    |
| 4100      | 6.0     | 8    | 810000    |

>Here, We can see that our data has one NaN entry that means, its value is not a number or undefined.
Here, we need to do some **Data Pre-Processing** as,we need numerical value for this to train our model.
There are multiple ways to assume that NaN value but here we are going to replace it with median of other values. For more details see the code.
# Behind the  Model (For multiple variable)
This model also uses **Linear Equation**, but for multiple variables, like

`y = m1*x1 + m2*x2 + m3*x3 + ... + mn*xn + b`

In our case, it will be used as follows,

![Linear Equation](equation.jpg)