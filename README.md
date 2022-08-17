# TED-Talks-VIews-Prediction

A TED talk is a recorded public-speaking presentation that was originally given at the main TED (technology, entertainment and design) annual event or one of its many satellite events around the world. TED is a nonprofit devoted to spreading ideas, usually in the form of short, powerful talks, often called "TED talks." TED is dedicated to researching and sharing knowledge that matters through short talks and presentations. Their goal is to inform and educate global audiences in an accessible way.

We have Started with data loading and we have done EDA ,feature engineering,data cleaning, target encoding feature selection and then model building.
So we have used this models:

●	Ridge Regressor

●	Lasso Regressor

●	KNearestNeighbors Regressor

●	Gradient Boosting Regressor

●	Random Forest Regressor

●	Extra Tree Regressor

●	XGB Regressor


As we know, RMSE is more influenced by outliers MAE doesn't increase with outliers.
MAE is linear and RMSE is quadratically increasing.So, We choosed MAE as a deciding factor for our model.
We used some sklearn libraries and performed python coding on the data.
On the basis of MAE, The best performing regression model is Random Forest Regressor.
