# GRIDSearchCV
Grid Search CV runs through all the different parameters that are fed into the parameter grid and produces the best combination of parameters, based on a scoring metric of your choice (accuracy, f1, etc). Obviously, nothing is perfect and GridSearchCV is no exception:
* “best parameters” results are limited
*  process is time-consuming
The “best” parameters that GridSearchCV identifies are technically the best that could be produced, but only by the parameters that you included in your parameter grid.

![alt text](https://github.com/shahriar-rahman/Netflix-Customer-Retention-using-GPR/blob/main/img/Grid_Search_example.png)

GridSearchCV is a useful tool to fine-tune the parameters of any model. Depending on the estimator being used, hyperparameters may need tuning even more than the ones (ex. K-Neighbors vs Random Forest). However, it is not expected the search to improve the overall generalizability of the model and accurate results greatly. It may be more efficient to go back and explore your selected features or find other relationships between features to improve the model performance.
