
# Ensaio de Machine Learning
# Problema de Negócio
## Descrição
A Data Money é uma empresa especializada em prestar serviços de consultoria em Análise e Ciência de Dados com resultados que proporcionam ganhos significativos aos seus clientes, brasileiros e estrangeiros. Estes resultados são fruto da principal expertise da empresa em treinar e realizar ajustes finos nos algoritmos de Machine Learning. Como cientista novato o seu papel é se integrar o mais rápido possível ao time a garantir o nível de excelência.
## Objetivos
Realizar três ensaios de Machine Learning utilizando algoritmos de classificação, regressão e clusterização, a fim de obter aprendizados sobre as performances obtidas com base nos cenários apresentados. Cenários estes, que serão alterados à medida que os parâmetros de controle de overfitting e underfitting são modificados. Com isso, incorporar os conhecimentos extraídos e repassar ao time, para que assim o novo cientista de dados acompanhe o ritmo dos colegas.
# Planejamento da Solução
## Produto Final
O produto final será a apresentação de 7 tabelas contendo os algoritmos utilizados e valores das respectivas métricas para os datasets envolvidos. Com isso podemos comparar a performance de cada algoritmo.
##Algoritmos Ensaiados
### Classificação:
Algoritmos: KNN, Decision Tree, Random Forest e Logistic Regression
Métricas de performance: Accuracy, Precision, Recall e F1-Score
### Regressão:
Algoritmos: Linear Regression, Decision Tree Regressor, Random Forest Regressor, Polinomial
Regression, Linear Regression Lasso, Linear Regression Ridge, Linear Regression Elastic Net,
Polinomial Regression Lasso, Polinomial Regression Ridge e Polinomial Regression Elastic Net
Métricas de performance: R2, MSE, RMSE, MAE e MAPE
### Clusterização:
Algoritmos: K-Means e Affinity Propagation
Métricas de performance: Silhouette Score
## Ferramentas utilizadas:
Python 3.8 e Scikit-learn
# Desenvolvimento
## Estratégia da solução
Para o objetivo de ensaiar os algoritmos de Machine Learning, eu vou escrever os códigos utilizando a linguagem Python, para treinar cada um dos algoritmos e vou variar seus principais parâmetros de ajuste de overfitting e observar a métrica final.
O conjunto de valores que fizerem os algoritmos alcançarem a melhor performance, serão aqueles escolhidos para o treinamento final do algoritmo.
### O passo a passo
Passo 1: Divisão dos dados em treino, teste e validação.
Passo 2: Treinamento dos algoritmos com os dados de treinamento, utilizando os parâmetros “default”.
Passo 3: Medir a performance dos algoritmos treinados com o parâmetro default, utilizando o conjunto de dados de treinamento.
Passo 4: Medir a performance dos algoritmos treinados com o parâmetro “default”, utilizando o conjunto de dados de validação.
Passo 5: Alternar os valores dos principais parâmetros que controlam o overfitting do algoritmo até encontrar o conjunto de parâmetros apresente a melhor performance dos algoritmos.
Passo 6: Unir os dados de treinamento e validação.
Passo 7: Retreinar o algoritmo com a união dos dados de treinamento e validação, utilizando os melhores valores para os parâmetros de controle do algoritmo.
Passo 8: Medir a performance dos algoritmos treinados com os melhores parâmetro, utilizando o conjunto de dados de teste.
Passo 9: Avaliar os ensaios e anotar os 3 principais Insights que se destacaram.
# Os top 3 Insights
## Insight Top 1
Os algoritmos baseados em árvores possuem uma performance melhores em todas as métricas, quando aplicados sobre os dados de teste, no ensaio de Classificação.
## Insight Top 2
A performance dos algoritmos de classificação sobre os dados de validação ficou bem próxima da performance sobre os dados de teste.
## Insight Top 3
Todos os algoritmos de regressão não apresentaram boas métricas de performance, o que mostra uma necessidade de uma seleção de atributos e uma preparação melhor das variáveis independentes do conjunto de dados.
# Resultados
### Ensaio de Classificação:
Sobre os dados de treinamento
 
Sobre os dados de validação
 
Sobre os dados de teste
 

### Ensaio de Regressão:
Sobre os dados de treinamento
 
Sobre os dados de validação
 
Sobre os dados de teste
 
### Ensaio de Clusterização:
6.7 Sobre os dados de treinamento
 
# Conclusões
Com o ensaio foi possível praticar a manipulação dos parâmetros a fim de encontrar os limiares dos algoritmos para os estados de underfitting e overfitting, conseguindo assim aproximar a experiência de trabalho diário no uso de machine learning pelos cientistas de dados.
Dentre os parâmetros que podemos controlar para evitar o estado de overfitting, temos que a profundidade do numero de árvores na floretas, para os algoritmos baseados em árvores, afetam sua performance podendo overfitar. Portanto, analisar este comportamento é imprescindível para a escolha da profundidade.
Na regressão, os algoritmos utilizados demonstraram que o parâmetro que mais afeta os resultados e assim podendo levar ao estado de underfitting e overfitting, é o grau do polinômio. Quanto maior o grau do polinômio, maior a chance de acompanhar ponto a ponto da linha do gráfico, demonstrado a tendência do overfitting.
Esse ensaio de Machine Learning foi muito importante para aprofundar o entendimento sobre o funcionamento de diversos algoritmos de classificação, regressão e clusterização e quais os principais parâmetros de controle entre os estados de underfitting e overfitting.
# Próximos passos
Como próximos passos desse ensaio, pretendo ensaiar novos algoritmos de Machine Learning e usar diferentes conjuntos de dados para aumentar o conhecimento sobre os algoritmos e quais cenários são mais favoráveis para o aumento da performance dos mesmos.
