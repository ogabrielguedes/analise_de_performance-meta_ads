# Análise de Performance de Campanhas Digitais do Meta Ads

## Visão Geral do Projeto

Este projeto tem como objetivo principal analisar um conjunto de dados de campanhas de anúncios digitais do Meta Ads (Facebook e Instagram) para identificar oportunidades de otimização de investimento. A análise focou em segmentar o público-alvo e avaliar métricas de performance para encontrar o segmento mais rentável.

## Perguntas de Negócio

A análise buscou responder às seguintes questões estratégicas:
1.  Qual público-alvo (gênero e faixa etária) é o mais eficiente para gerar conversões?
2.  Existe uma relação entre o custo por clique (CPC) e o custo por conversão (CPCon)?
3.  Quais são os principais gargalos no funil de anúncios que podemos otimizar?

## Análise e Metodologia

O projeto foi desenvolvido em Python e utilizou as seguintes bibliotecas:
-   **Pandas:** Para manipulação, limpeza e análise dos dados.
-   **NumPy:** Para cálculos numéricos eficientes, como a correção de divisão por zero.
-   **Matplotlib e Seaborn:** Para a criação de gráficos informativos.

As principais etapas da análise foram:
1.  **Limpeza de Dados:** Tratamento de valores ausentes e conversão de tipos de dados.
2.  **Cálculo de Métricas:** Criação de colunas para métricas essenciais como CPC, CPCon e CTR.
3.  **Segmentação e Análise:** Utilização do `groupby()` para analisar a performance dos anúncios por gênero e faixa etária.
4.  **Visualização:** Criação de gráficos para apresentar as descobertas de forma clara e visual.

## Resultados e Insights Chave

A análise revelou insights valiosos para a otimização das campanhas:

-   **O Público Mais Rentável:** O público **feminino** apresentou um custo por conversão (CPCon) significativamente menor do que o público masculino.
-   **A Oportunidade de Otimização:** O público de **mulheres entre 30 e 34 anos** demonstrou ser o segmento mais eficiente em gerar conversões.
-   **Gargalos de Performance:** O público masculino, especialmente nas faixas de idade de 35-39 e 40-44, apresentou um custo por conversão drasticamente mais alto, indicando uma necessidade de reavaliação da estratégia para este segmento.

## Visualizações

O gráfico abaixo resume as principais descobertas, comparando o custo por clique e o custo por conversão entre os diferentes segmentos de público.

Gráfico de Análise de Segmentação: [Cpc.png](https://github.com/ogabrielguedes/analise_de_performance-meta_ads/blob/main/CPC.png) [Cpcon.png](https://github.com/ogabrielguedes/analise_de_performance-meta_ads/blob/main/CPCon.png)

## Conclusão e Próximos Passos

O projeto demonstra que a otimização do investimento em anúncios pode ser alcançada com uma abordagem de análise de dados. As recomendações para a equipe de marketing incluem realocar o investimento para os segmentos mais eficientes e realizar testes com o público de menor performance para identificar novas oportunidades.
