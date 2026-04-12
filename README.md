# Estoque Inteligente

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Python](https://img.shields.io/badge/Python-3.12+-blue?logo=python)
![Plotly](https://img.shields.io/badge/Plotly-interativo-blueviolet?logo=plotly)

Análise de gestão de estoque aplicada a pequenos e médios negócios. O projeto demonstra como dados simples de entrada e saída de produtos geram insights que evitam ruptura de estoque, reduzem desperdício e liberam capital parado.

## O Problema

Muitos pequenos empresários ainda controlam o estoque no papel ou em planilhas sem histórico. O resultado é previsível: produto faltando no momento errado, dinheiro preso em item sem giro e reposição feita no feeling. Dados resolvem isso.

## Análises

| Notebook | Descrição |
|---|---|
| `01_eda.ipynb` | Perfil do estoque: top produtos, categorias, lojas e distribuição de valor |
| `02_abc_analysis.ipynb` | Curva ABC por valor de venda: quais 20% dos produtos geram 80% da receita |
| `03_reposicao_giro.ipynb` | Giro de estoque, ponto de reposição e lead time de fornecedores |

## Principais Insights

- Classificação ABC identifica produtos críticos vs. produtos que drenam capital
- Giro de estoque revela o que está parado e gerando custo de oportunidade
- Ponto de reposição calculado por produto evita ruptura sem superlotação

## Stack

**Python 3.12** · Pandas · NumPy · Plotly · Jupyter

## Dataset

[Inventory Analysis Case Study — Kaggle](https://www.kaggle.com/datasets/bhanupratapbiswas/inventory-analysis-case-study)

Dados reais de distribuidora com 80 lojas, mais de 5.700 produtos e registro completo de vendas, compras e níveis de estoque.

## Autor

**Rodrigo Cruz dos Santos**
[LinkedIn](https://www.linkedin.com/in/rodrigopresidati) · [GitHub](https://github.com/RodrigoPresida)
