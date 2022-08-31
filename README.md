# Churn

  Em serviços bancários ou de streaming, é interessante ter um modelo que possa prever os prováveis clientes que irão cancelar estes serviços. Desta forma, a empresa pode impedir que isso ocorra propondo melhores planos para os clientes, por exemplo. 
  Inicialmente, neste projeto foi realizado um pré-tratamento dos dados, a fim de que pudessem ser aplicados os modelos de Machine Learning. Foram testados os modelos de : 
  -Árvore de Decisão (com profundidade 3, 5 e 7);
  -Random Forest (n_estimators = 50 e 100 e profundidade = 5 e 7 ;
  -KNN (K=5, 15 e 25);
  -Bagging;
  -Regressão Logística.
  
 Foram avaliadas as métricas de acurácia, precisão, sensibilidade, eficiência e f1-score.
 O melhor modelo proposto para este conjunto de dados foi o de Árvore de Decisão com profundidade 7. 
