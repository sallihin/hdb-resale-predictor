# hdb-resale-predictor
HDB Resale Price Predictor using Gradient Boosting Regressor

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
