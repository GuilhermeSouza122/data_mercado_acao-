# Segmentação de Clientes com K-Means

**Análise exploratória e agrupamento de carteiras de investimentos.**

Estudo de aprendizado não supervisionado organizado em um notebook: entendimento do problema, exploração da base, preparação das variáveis e segmentação de clientes com K-Means.

## O que você encontra

- Estatísticas descritivas e distribuição das variáveis.
- Exploração da alocação por classe de ativo e das correlações.
- Análise de outliers e comparação entre perfil declarado e comportamento da carteira.
- Padronização de variáveis com `StandardScaler`.
- Agrupamento com `KMeans` e exploração com `PCA`.
- Avaliação de agrupamentos com silhouette e índice Davies–Bouldin.

## Arquivos

- [`analise_clustering_vertice.ipynb`](analise_clustering_vertice.ipynb) — análise e visualizações.
- [`carteiras_clientes.csv`](carteiras_clientes.csv) — base utilizada pelo notebook.

## Stack

Python · pandas · NumPy · scikit-learn · matplotlib · seaborn · Jupyter

## Como explorar

Abra o notebook no GitHub para consultar a análise. Para executar localmente, mantenha o CSV junto ao notebook, instale as bibliotecas importadas e rode as células em ordem em um ambiente Jupyter.

Os agrupamentos são resultados exploratórios sobre a base analisada. O foco do projeto é estudar padrões nos dados e comparar perfis de clientes.
