# Study project on the course “Data Science Specialist” from Yandex Practicum
This is my study project completed as part of the Data Science Specialist course from Yandex Practicum.

## Project Description
The goal of the project is to help the client company optimize HR management by predicting the level of employee satisfaction and the likelihood of employee departure. This will allow the company to better control staff attrition and minimize financial losses.

## Results
- **Best model for predicting satisfaction**: `DecisionTreeRegressor` 
 - **SMAPE on test sample**: **13.49** (requirement ≤ 15)
- **Best model for predicting quit**: `LogisticRegression` 
 - **ROC-AUC on test sample**: **0.91** (requirement ≥ 0.91)
 - **Recall**: **0.90** (low false negative predictions)
- **Conclusions and Recommendations**:
  - Satisfaction level directly affects the likelihood of quitting.
  - Junes with little seniority and low salary are at risk.
  - Businesses are recommended to work with motivation of young professionals.

## Technology Stack
- **Python**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **Data Preprocessing**: OneHotEncoder, OrdinalEncoder, StandardScaler
- **Data Analysis**: Matplotlib, Seaborn, Phik
- **Feature Importance**: SHAP
- **Models**: DecisionTreeRegressor, LogisticRegression, SVC, KNeighborsClassifier
- **Model Evaluation**: SMAPE, ROC-AUC, Recall, GridSearchCV, RandomizedSearchCV

## Link to the project notebook

You can view the project notebook [here](https://github.com/donatorex/hr_analytics/blob/main/hr_analytics.ipynb) (in Russian).
