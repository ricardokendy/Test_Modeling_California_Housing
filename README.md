# Test Modeling California Housing
DATASET
Dataset disponível no site SKLearn: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html#sklearn.datasets.fetch_california_housing
Dataset apresenta 20640 dados
- MedInc        median income in block group
- HouseAge      median house age in block group
- AveRooms      average number of rooms per household
- AveBedrms     average number of bedrooms per household
- Population    block group population
- AveOccup      average number of household members
- Latitude      block group latitude
- Longitude     block group longitude

MODELING TECHNICS
- Regressão Linear do SKLEARN https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html#sklearn.linear_model.LinearRegression
- Suport Vector Regression do SKLEARN https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html#sklearn.svm.SVR
- Decision Tree Regression do XGBoost https://xgboost.readthedocs.io/en/stable/python/python_api.html

MODELING ASSUMPTIONS
- Apenas variáveis numéricas

TEST DESIGN
- Separação de Train/Test dataset padrão com 20% de massa para teste via método SKLEARN: https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html#sklearn.model_selection.train_test_split

MÉTRICA DE AVALIAÇÃO DO MODELO
- Validação da métrica: MSE(Mean Square Error) e RMSE(Root Mean Square Error) para penalizar grandes erros de previsão. Utilizando o método do SKLearn. https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html#sklearn.metrics.mean_squared_error
