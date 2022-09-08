Projeto de estudos de criação de diferentes modelos de Machine Learning para tentar prever a precificação dos preços das casas em Boston com suas features. O dataset é próprio do sklearn, e importado diretamente por ele, após isso foi criado o dataframe com as features e o target do nosso modelo, e então separado o modelo em treino e teste (80/20).

Após isso foi realizado a verificação e o tratamento dos outliers presentes, depois foram testadas 3 técnicas de regressão: <br>

1)Regressão Linear <br>
2)Support Vector Regression (SVR) <br>
3)Decision Tree Regresison (XGBoost) <br> 

Depois de avaliar os 3 modelos com as métricas de MSE (Mean Squared Error) e RMSE (Root Mean Squared Error), verificamos que o modelo que melhor perfomou foi o XGBoost, então foi realizada a otimização dos hiperparâmetros do modelo com o GridSearchCV