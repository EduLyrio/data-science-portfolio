# 03 · Market Basket Analysis (Regras de Associação)

Análise de cesta de compras em dados de e-commerce de supermercado, no estilo do dataset Instacart, para descobrir produtos frequentemente comprados juntos.

**Destaques:**

- Integração de 5 tabelas relacionais (pedidos, transações, produtos, corredores, departamentos)
- Análise exploratória: taxa de recompra (reorder) por corredor e departamento
- Regras de associação com o algoritmo Apriori (suporte, confiança e lift)

**Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, efficient-apriori

> **Nota sobre os dados:** os arquivos `pedidos.csv` (104 MB) e `transacoes.csv` (551 MB) excedem o limite do GitHub e não estão no repositório. Os arquivos menores estão em `datasets/`. O conjunto completo segue o formato do [Instacart Market Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis) (traduzido para PT-BR).
