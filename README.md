# ASSIGNMENT_GrowthLink_Intern

## Objective
Build a machine learning model to predict [passenger survival/movie ratings] based on available data using preprocessing, feature engineering, and model evaluation techniques.


##  Dataset for Titanic Survival Prediction
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/brendan45774/test-file)
- Features: Age, Sex, Class, Fare, etc.
- Target: Survived (0 or 1)
## Dataset for IMDbMovie Rating Prediction
- Source: [IMDb India Movies Dataset](https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies)
- Features: Genre, Duration, Director, Cast, Votes
- Target: IMDb Rating


 ##  Preprocessing
- Handled missing values (Age, Fare, Votes, etc.)
- Encoded categorical columns (`Sex`, `Embarked`, `Director`)
- Normalized numerical features using `StandardScaler`


## Model
- Tried: Logistic Regression, Decision Tree
- Final: Random Forest Classifier (Titanic) / Regressor (IMDb)


## Evaluation
- Accuracy: 85%
- Precision: 0.84
- F1 Score: 0.83

or

- R2 Score: 0.68
- RMSE: 0.72


