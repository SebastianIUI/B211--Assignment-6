# B211--Assignment-6

PART 2: EXPLANATION: The forest regressor model seemed to have the best preformance out of all of the models used for this program. It has the lowest mean squared error meaning its predictions were closer to the actual progression values. It also had the highest R2 score which shows that it explains more of the variation in the dataset compared to the other models. Linear regression performed reasonably well but due to its strictly linear nature it lowered the accuracy of its results. The decision tree model performed the worst since trees often overfit the training data.

README FILE:

Purpose: The purpose of this assignment is to start performing machine learning regression using python and the Scikit Learn module, using real world data.

Class Design/Implementation:

X(Features): Numerical measurements describing the chaaracteristics of each patient such as age, blood pressure, etc
Y(Target): A value representing the progression of diabetes after a year.
train_test_split: Divides dataset into training and testing data.
LinearRegression: A regression model that predicts the target using a lineaar relationship between features and outcomes

