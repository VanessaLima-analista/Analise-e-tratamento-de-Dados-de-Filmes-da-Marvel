### Projeto 2: Análise e Tratamento de Dados de Filmes da Marvel

#### Visão Geral

Este projeto de análise de dados foca no tratamento e na exploração de um conjunto de dados sobre filmes da Marvel. O objetivo principal é demonstrar competências em limpeza de dados, operações matemáticas e estatísticas básicas, transformando dados brutos em informações úteis e prontas para visualização.

#### Objetivos do Projeto

* Aplicar conceitos de limpeza e formatação de dados.
* Realizar operações matemáticas e estatísticas básicas (média, mediana, moda, etc.).
* Preparar tabelas prontas para a geração de gráficos.

#### Metodologia

A metodologia seguiu os seguintes passos:

1.  **Limpeza de Dados:** Conversão da coluna de datas para o tipo `datetime` e criação de uma única coluna para os diretores.
2.  **Análise Estatística:** Cálculo de métricas estatísticas para as colunas de avaliação (`IMDb`, `Rotten Tomatoes`) e financeiras (`Budget`, `Worldwide Gross`).
3.  **Preparação para Gráficos:** Geração de tabelas de resumo para facilitar a criação de visualizações futuras.

#### Entregáveis

* Arquivo de dados limpo e tratado: `Marvel_Movies_Cleaned.csv`.
* Relatório de estatísticas básicas (média, mediana, moda, etc.).

#### Tabela de Estatísticas dos Filmes

| Estatística | IMDb | IMDB Metascore | Rotten Tomatoes - Critics | Rotten Tomatoes - Audience | Letterboxd | Budget | Domestic Gross | Worldwide Gross |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| **Média** | 7.24 | 65.97 | 80.88 | 84.21 | 3.24 | 229.52 | 365.86 | 918.56 |
| **Desvio Padrão** | 0.69 | 8.86 | 12.73 | 10.45 | 0.52 | 69.00 | 195.49 | 556.26 |
| **Mínimo** | 5.50 | 48.00 | 46.00 | 45.00 | 2.20 | 140.00 | 84.50 | 206.10 |
| **Máximo** | 8.40 | 88.00 | 96.00 | 98.00 | 4.00 | 400.00 | 858.40 | 2799.00 |
| **Mediana** | 7.30 | 67.00 | 83.50 | 86.50 | 3.35 | 200.00 | 333.95 | 809.50 |
| **Moda** | 6.90 | 57.00 | 79.00 | 87.00 | 3.70 | 200.00 | 84.50 | 206.10 |
