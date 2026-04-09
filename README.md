# Estoque Inteligente

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Python](https://img.shields.io/badge/Python-3.12+-blue?logo=python)
![Plotly](https://img.shields.io/badge/Plotly-interativo-blueviolet?logo=plotly)

Analise de gestao de estoque aplicada a pequenos e medios negocios. O projeto demonstra como dados simples de entrada e saida de produtos geram insights que evitam ruptura de estoque, reduzem desperdicio e liberam capital parado.

## O Problema

Muitos pequenos empresarios ainda controlam o estoque no papel ou em planilhas sem historico. O resultado e previsivel: produto faltando no momento errado, dinheiro preso em item sem giro e reposicao feita no feeling. Dados resolvem isso.

## Analises

| Notebook | Descricao |
|---|---|
| `01_eda.ipynb` | Perfil do estoque: top produtos, categorias, lojas e distribuicao de valor |
| `02_abc_analysis.ipynb` | Curva ABC por valor de venda: quais 20% dos produtos geram 80% da receita |
| `03_reposicao_giro.ipynb` | Giro de estoque, ponto de reposicao e lead time de fornecedores |

## Principais Insights

- Classificacao ABC identifica produtos criticos vs. produtos que drenam capital
- Giro de estoque revela o que esta parado e gerando custo de oportunidade
- Ponto de reposicao calculado por produto evita ruptura sem superlotacao

## Stack

**Python 3.12** . Pandas . NumPy . Plotly . Jupyter

## Dataset

[Inventory Analysis Case Study — Kaggle](https://www.kaggle.com/datasets/bhanupratapbiswas/inventory-analysis-case-study)

Dados reais de distribuidora com 80 lojas, mais de 5.700 produtos e registro completo de vendas, compras e niveis de estoque.

## Autor

**Rodrigo Cruz dos Santos**
[LinkedIn](https://www.linkedin.com/in/rodrigopresidati) . [GitHub](https://github.com/RodrigoPresida)
