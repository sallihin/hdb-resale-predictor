# hdb-resale-predictor
This HDB Resale Price Predictor uses Gradient Boosting Regressor to predict current and future price trends. The model uses HDB resale transactions dataset from the past 5 years, made available via [Data.gov.sg](https://data.gov.sg/). The model's accuracy is 96.59%. 

### Method
* The model uses the popular Ensemble Learning method, Gradient Boosting Regressor
* For hyperparameter tuning, I initially tested with GridSearchCV, which was unsuccessful
* Subsequently, I ran RandomSearchCV over 9 hours to achieve 96% accuracy
* The model is then exported into a PKL file for front-end integration

### Key Learnings 
* GridSearchCV took a very long time despite Colab Pro+ Subscription and exceeded 24 hours runtime limit.
* GPU Usage is restricted even with a Pro+ account. 

### Limitations
* Model does not factor in cooling measures implemented by Singapore Government on 16th December 2021.<br>[Ministry of National Development - Measures to Cool the Property Market](https://www.mnd.gov.sg/newsroom/press-releases/view/measures-to-cool-the-property-market)

### References
* [HDB Resale Prices Dataset](https://data.gov.sg/dataset/resale-flat-prices)
* [sklearn Gradient Boosting Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html)
* [sklearn GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
* [sklearn RandomSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html)
