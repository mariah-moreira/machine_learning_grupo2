# Repositório - Projeto Machine Learning I - Santander Coders 2023

__Equipe:__
Ingrid Guimarães
Maria Gabrielly A. Santana
Desiree Gomes
Lucas Cruz
Mariah Moreira

O objetivo do projeto foi desenvolver um estudo baseado em um conjunto de dados (dataset) do [Kaggle](https://www.kaggle.com/).

O dataset optado foi:
- [Análise de crédito](https://www.kaggle.com/datasets/rohitudageri/credit-card-details?select=Credit_card_label.csv)

O qual possui como problema a ser trabalhado: classificação.

Para auxiliar no desenvolvimento do projeto, vamos separar em algumas seções, conforme descrito abaixo:

- __Preparação dos Dados e Verificação de Consistência__: Neste tópico foi feita a verificação da consistência dos dados e caso necessário efetuada eventuais modificações na base de dados. Alguns dos procedimentos que podemos fazer aqui são: Remoção e/ou tratamento de valores faltantes, remoção de duplicatas, ajustes dos tipos de variáveis, análise de _outliers_ entre outras;

- __Análise Exploratória dos Dados__: Nesta parte do projeto desenvolvemos análises e gráficos a respeito dos dados que estão utilizando. Tentando tirar ao máximo informações sobre as variáveis em si e suas relações com as demais;

- **Modelagem dos dados**: Nessa parte, foi definido o tipo de problema (classificação/regressão).

Escolhemos os seguintes modelos para análise de performance:

Decision Tree
Random Forest
AdaBoost
Gradient Boosting
XGBoost
LightGBM

Para comparar esses modelos utilizamos as seguintes metricas:
Acurácia
Precisão
Recall
F1-Score
ROC-AUC;

- __Otimização do Modelo__: A partir do modelo escolhido no tópico anterior, vamos tentar aprimorar e garantir um melhor desempenho no modelo, seja fazendo validação cruzada, otimização de parâmetros com _GridSearchCV_ ou _RandomizedSearchCV_ e até mesmo testar diferentes _thresholds_ (ao invés de utilizar a função _predict_ do modelo, utilize a função _predict_proba_ do modelo e a partir das probabilidades determinar qual vai ser o limiar onde será considerado um caso positivo ou negativo);

- __Conclusões sobre o Projeto__: Para finalizar, descrevemos as conclusões sobre o desenvolvimento do modelo e os resultados obtidos.
