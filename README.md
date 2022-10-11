# kibet
Import libraries
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression

We can Fit a linear regression model using the longitude feature 'long' and 
caculate the R^2.

X = df[['long']]
Y = df['price']
lm = LinearRegression()
lm
lm.fit(X,Y)
lm.score(X, Y)


	floors
1.0	10680
2.0	8241
1.5	1910
3.0	613
2.5	161
3.5	8

