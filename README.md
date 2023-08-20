# Análise de Dados e Predição de Retorno de Investimento sobre Diferentes Canais de Marketing

Este repositório contém um projeto desenvolvido como desafio de projeto do curso de Formação em Dados da Escola DNC. O projeto envolve a análise de um dataset contendo informações sobre valores investidos em três canais de marketing e o respectivo retorno em vendas.

## Dataset

O dataset utilizado neste projeto contém as seguintes informações sobre as propriedades:

- Valor investido no Youtube.
- Valor investido no Facebook.
- Valor investido em Newspaper.
- Valor de vendas (retorno dos investimentos).

## Etapas do Projeto

### Exploração e Limpeza dos Dados

Inicialmente, realizamos uma exploração detalhada dos dados, identificando valores ausentes ou inconsistentes. Utilizamos técnicas estatísticas, como média e desvio padrão, para compreender a distribuição dos dados.

### Análise de Correlações

Utilizando a biblioteca Seaborn, plotamos gráficos de distribuição e dispersão para analisar possíveis correlações lineares entre as variáveis. Posteriormente, criamos um mapa de calor para visualizar as correlações entre o valor investido em cada canal e o respectivo retorno em vendas, identificando, assim, o canal com maior retorno sobre o investimento.

### Desenvolvimento do Modelo de Regressão Linear

O desafio consistia em construir um modelo de regressão linear que pudesse estimar o retorno em vendas a partir de um determinado investimento em um ou mais canais de marketing. Para isso, foi implementado um modelo simples de regressão linear utilizando a biblioteca scikit-learn. Foi utilizado o coeficiente de determinação R² como métrica de avaliação do desempenho do modelo. Além disso, plotamos um gráfico de linhas para comparar os valores de teste x resultados de treino.
