# Predição de Espécies de Pinguins

Este projeto utiliza técnicas de aprendizado de máquina para prever a espécie de pinguins com base em suas características físicas e localização.

## Visão Geral

O notebook Jupyter `trabalho v1.ipynb` contém uma análise completa do conjunto de dados de pinguins, incluindo:

1. Carregamento e exploração inicial dos dados
2. Análise exploratória de dados (EDA) com visualizações
3. Pré-processamento dos dados
4. Treinamento de um modelo de Random Forest
5. Avaliação do modelo e análise de importância das features

## Requisitos

Para executar este notebook, você precisará das seguintes bibliotecas Python:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Você pode instalar estas bibliotecas usando o comando:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Conjunto de Dados

O projeto utiliza o conjunto de dados "penguins.csv", que deve estar no mesmo diretório do notebook.

## Conteúdo do Notebook

1. Importação das bibliotecas necessárias
2. Carregamento e exploração inicial dos dados
3. Análise estatística descritiva
4. Visualizações:
   - Distribuição das espécies de pinguins
   - Relação entre comprimento e profundidade do bico
   - Distribuição da massa corporal por espécie
   - Matriz de correlação
5. Pré-processamento dos dados usando pipelines do scikit-learn
6. Treinamento de um modelo Random Forest
7. Avaliação do modelo:
   - Relatório de classificação
   - Matriz de confusão
8. Análise da importância das features

## Como Usar

1. Clone este repositório ou baixe o arquivo `trabalho v1.ipynb`
2. Certifique-se de que o arquivo "penguins.csv" está no mesmo diretório do notebook
3. Abra o notebook usando Jupyter Notebook ou JupyterLab
4. Execute as células em ordem

## Resultados

O notebook gera várias visualizações e métricas de avaliação do modelo. Os principais resultados incluem:

- Distribuição das espécies de pinguins
- Relações entre características físicas dos pinguins
- Desempenho do modelo de classificação
- Importância das features na previsão da espécie

## Exportação para HTML

O notebook inclui um comando para exportar o conteúdo para um arquivo HTML. Você pode executar esta célula para gerar uma versão estática do notebook.
