# HousingMrktPred

Procudure:
![image](https://github.com/manofword5/HousingMrktPred/assets/100426500/86958d74-a3e1-4627-abaf-74376e4ca20b)

Introduction:
We strive to obtain the median house value for the California district, as median prices are a useful tool for understanding the price changes of properties that have transacted in a market. Furthermore, the median is more accurate than the average because it is less affected by a few unusually high or low sale prices.


Procedure:
1.	Problem definition — The given model is one of supervised learning, where we are going to use regression, since we have to find a numerical quantity.
2.	Data — California Housing Dataset https://scikit- learn.org/stable/modules/generated/sklearn.datasets.fetch_california_h ousing.html
3.	Evaluation — Evaluation using coefficient of determination(r^2),cross validation score and mean absolute error.
4.	Features — 8 numeric, predictive attributes and the target
5.	Modelling — We use both the Ridge Regressor and the RandomForestRegressor, with the latter having the highest score.
6.	Experimentation — What else could we try? Does our deployed model
do as we expected? How do the other steps change based on what
we’ve found?


Note:The target variable is the median house value for California districts, expressed in hundreds of thousands of dollars ($100,000).
