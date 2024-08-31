# K-Means Clustering com o Dataset Iris

Este projeto faz parte de uma atividade da matéria de **Inteligência Artificial Aplicada a Sistemas de Informação** do quarto período da Unimater. O objetivo da atividade é implementar o algoritmo de clustering K-Means utilizando o famoso dataset Iris, agrupando as amostras de flores em três clusters diferentes e comparando os resultados com as classes reais do dataset. 

## Descrição do Projeto

Utilizando o google Colab, o código realiza as seguintes etapas:

1. **Carregamento do Dataset**: O dataset Iris é carregado a partir de um arquivo CSV.
2. **Pré-processamento**: A coluna de classes (`variety`) é separada do restante do dataset e as classes são convertidas em valores inteiros para facilitar a avaliação posterior.
3. **Clustering com K-Means**: O algoritmo K-Means é aplicado ao dataset, agrupando as amostras em três clusters.
4. **Visualização dos Clusters**: Os clusters são visualizados em um gráfico de dispersão.
5. **Avaliação do Modelo**: Os clusters gerados pelo K-Means são comparados com as classes reais utilizando o relatório de classificação.
6. **Método Elbow**: O método Elbow é utilizado para determinar o número ideal de clusters.
