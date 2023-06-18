# Projeto_12

Obs: No projeto usei gráficos interativos gerados pelo Plotly Express como eles não são exibidos corretamente, transformei os gráficos em estáticos para conseguir visualizá-los aqui.

Analisar os dados dos clientes de uma acadêmia e verificar os motivos da alta taxa de cancelamentos.

Estrutura:
- análise exploratória dos dados (AED).
- histogramas de barra e distribuições.
- matriz de correlação e a exiba.
- modelo para predizer a rotatividade de clientes.
- modelo de classificação binária para clientes onde a variável objetivo é a saída de usuários do próximo mês.
- treinamento e validação em dois conjuntos usando a função train_test_split().

Métodos:
- regressão logística.
- floresta aleatória.

-Avaliação de acurácia, precisão e sensibilidade.
-R2.
-RSME.

Agrupamentos de clientes:
- padronização dos dados.
- função linkage() para construir a matriz das distâncias baseada na matriz de características padronizada.
- dendrograma. 
- Treine o modelo de agrupamento com o algoritmo K-means e preveja agrupamentos de clientes. 
- distribuições de características para os agrupamentos. 

