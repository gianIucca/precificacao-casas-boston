Projeto de estudos de criação de diferentes modelos de Machine Learning para tentar prever a precificação dos preços das casas em Boston com suas features. O dataset é próprio do sklearn, e importado diretamente por ele, após isso foi criado o dataframe com as features e o target do nosso modelo, e então foi realizado a verificação e o tratamento dos outliers presentes, após isso o modelo foi separado entre treino e teste (80/20) e foram normalizados os dados com a biblioteca StandardScaler do Scikit-Learn

Após isso foi realizado a verificação e o tratamento dos outliers presentes, depois foram testadas 5 técnicas de regressão: <br>

1)Regressão Linear <br>
2)Support Vector Regression (SVR) <br>
3)XBoost Regressor <br> 
4)Redes Neurais Scikit-Learn (MLP) <br>
5)Stochastic Gradient Descent (SGD) <br>

Depois de avaliar os diferentes modelos com as métricas de MSE (Mean Squared Error) , RMSE (Root Mean Squared Error) e MAE (Mean Absolute Error), verificamos que o modelo que melhor perfomou foi o XGBoost, então foi realizada a otimização dos hiperparâmetros do modelo.
