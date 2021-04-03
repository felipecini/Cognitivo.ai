# Desafio Cognitivo.ai

Questões a serem respondidas:

A estratégia utilizada para a modelagem foi definida com base no que eu pretendia prever (preço da estadia) e as variáveis que me foram fornecidas para poder fazer essa prediçao. Dessa forma, após análise exploratória dos dados foi possível escolher quais variáveis seriam descartas e quais dessas seriam mantidas. Ainda, foi necessário fazer a filtragem dos dados por conta de outliers e preenchimento de dados faltantes. Por conta de tentar prever o preço da estaia, foram utilizados modelos de regreção para serem testados. 

O modelo final selecionado foi o que obteve o melhor score para modelos de regressão, a raiz quadrada do MSE (mean squared error - média do erro quadrado) e que obtiveram bons valores de R quadrado. Sempre tomando cuidado para não fazer overfitting ou underfitting dos dados, isso foi feito utilizando o modelo de validação K-FOLD cross-validation. Esse modelo permite gerar diversos grupos testes e treinos, medir as métricas que avaliam a qualidade dos modelos e fazer uma média entre essas medições. Assim, é possīvel fazer uma avaliação das médias e desvio padrões dos modelos para escolher o mais adequado. Ainda, sempre é importante cumprir com todos as premissas necessárias para a aplicação dos modelos testados.

