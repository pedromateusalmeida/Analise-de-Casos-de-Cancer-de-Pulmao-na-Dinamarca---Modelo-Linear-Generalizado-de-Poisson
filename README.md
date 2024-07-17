# Análise de Casos de Câncer de Pulmão na Dinamarca - Modelo Linear Generalizado de Poisson

## Organização
**Instituto de Pesquisa em Saúde Dinamarquês**

## Descrição do Projeto
Este repositório contém um projeto de análise de dados e modelagem preditiva com o objetivo de ajustar um modelo linear generalizado de Poisson para prever o número de casos de câncer de pulmão em quatro cidades na Dinamarca, entre os anos de 1968 e 1971. Utilizamos dados do arquivo `danishlc.dat` que contém informações sobre número de casos, faixas etárias, população por faixas etárias e cidade.

## Base de Dados
O arquivo **danishlc.dat** contém as seguintes variáveis:
- **y**: Número de casos de câncer de pulmão.
- **Age**: Faixas etárias.
- **Population**: População por faixas etárias.
- **City**: Cidade.

## Objetivo do Projeto
O principal objetivo deste projeto é desenvolver um modelo linear generalizado de Poisson para estimar o número de casos de câncer de pulmão com base nas variáveis preditoras fornecidas no dataset, e identificar as faixas etárias e cidades com as maiores taxas da doença.

## Roteiro da Atividade

### Questão 2

1. **Informações Básicas do Dataset**
    - Print das 5 primeiras linhas
    - Tipo de dado em cada coluna
    - Descrição das colunas numéricas (contagem, média, mediana, desvio padrão)
2. **Análise Exploratória**
    - Dados missing
    - Distribuição da variável `y`
    - Scatter plot das variáveis numéricas com `y`
3. **Modelagem**
    - Correlação de Spearman
    - Teste de Shapiro-Wilk
    - Teste de Kruskal-Wallis
    - Teste Mann-Whitney U
    - Teste de qui-quadrado
4. **Treinamento do Modelo**
5. **Análise dos Resíduos**
6. **Conclusão**