# -Happy Customer

Predicting  if a customer is happy or not based on the answers they give to questions asked  in the logistics and delivery domain.

Data Description:

Y = target attribute (Y) with values indicating 0 (unhappy) and 1 (happy) customers
X1 = my order was delivered on time
X2 = contents of my order was as I expected
X3 = I ordered everything I wanted to order
X4 = I paid a good price for my order
X5 = I am satisfied with my courier
X6 = the app makes ordering easy for me

Attributes X1 to X6 indicate the responses for each question and have values from 1 to 5 where the smaller number indicates less and the higher number indicates more towards the answer.


Approach-Trained several models which included :'Support Vector Machines', 'KNN', 'Logistic Regression', 'Random Forest', 'Naive Bayes', 'Perceptron', 'Stochastic Gradient Decent', 'Decision Tree','Gradient Boosting'.Desion Tree classifier produced  the best results of  65.38%.
I used  cross validation check how they perform and then performed a feature selection.The performance increased to 76%.

My conclusion: the best model in predicting the happiness of the customer is Decision Tree Classifier and the most important features are X1, X5, and X3.

