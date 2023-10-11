# Boston_Housing_for_model_selection
Case de seleção do melhor modelo de regressão entre a Regressão Linear do SKLEARN, o Support Vector Regression também do SKLEARN e o Decision Tree Regression do XGBoost para determinar o preço de uma casa a partir dos dados disponíveis. O dataset utilizado foi o Boston Housing e o método de avaliação foram as métricas MSE e RMSE do SKLEARN, com o intuito de penalizar grandes erros de previsão.

Cada um dos modelos foi treinado e testado com as métricas desejadas e o modelo selecionado foi o Decision Tree Regression do XGBoost.

Com o modelo selecionado, o próximo passo foi refiná-lo através dos parâmetros do GridSearchCV. Apesar disso, a conclusão final é que o modelo default do Decision Tree Regression funcionou melhor do que o modelo refinado, por apresentar um RMSE menor.

------------------------------------------------------------------------------------------------------------------------------

In this case, the objective was to determine which regression model works the best to predict housing prices given the data we had. Three models were tested: the Linear Regression and de Support Vector Regression. both from the SKLEARN and the XGBoost's Decision Tree Regression. The Boston Housing was the used dataset for these tests. The choosing criteria was the SKLEARN's MSE and RMSE, since the point was to penalize bigger errors in the predicition.

Each model was trained e tested with the predetermined criteria and the XGBoost's Decision Tree Regression came out as the winner, having the lowest RMSE between the three models.

Given the selected model, the next step was to refine the regression by using the GridSearchCv parameters. Despite that, the final conclusion was that the default Decision Tree Regression model was a best fit for the data we had, since it presented a lower RMSE compared to the refined one (2.62 < 2.88).
