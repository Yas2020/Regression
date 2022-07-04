This notebook contains EDA and modeling details for housing price 
prediction on Ames Housing dataset with 79 explanatory variables 
describing (almost) every aspect of residential homes in Ames, Iowa. This 
dataset is an incredible alternative for a modernized and 
expanded version of the often cited Boston Housing dataset.
First data is downloaded from Kaggle, missing data is handled, 
categorical data is encoded and then, some features with very low 
variances are removed. Next, some basic new features are created or 
substituted old features. After that, more feature 
extraction is performed using supervised dimensionality reduction followed 
by a KNN to produce a new feature for the final XGBOOST model. To have a 
more stable final model, an forest XGBOOST (of 20 parallel trees at each 
boosting step) is trained and finally the predictions are submitted to 
Kaggle platform. At the time of submission, the ranking was in the top 4%.  
