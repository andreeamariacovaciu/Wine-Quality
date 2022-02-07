## Wine-Quality
The purpose of this project is to classify the wine by its quality considering some features like alcohol, sulphates, volatile acidity, total sulfur dioxide and others.
To do that I used the Random Forest Classifier algorithm from scikit-learn library.  
For the model evaluation I used the accuracy score metrics. GridSearchCV helps evaluate all combinations of parameters I defined (n_estimators, max_depth and criterion) to find out the best ones, then I re-fitted the model with the new parameters, so the accuracy score increases.
