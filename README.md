# Finance

Notebooks de estudo de finanças quantitativas e simulação, feitos originalmente no Google Colab.

## Conteúdo

| Notebook | Descrição |
|---|---|
| `Balanceador_de_investimentos.ipynb` | Balanceamento de carteira de ações da B3 com CAPM, modelo histórico e Black-Litterman, integrando dados fundamentalistas e quantitativos. |
| `Marketanalysis.ipynb` | Análise de mercado usando `finpie` (dados do Yahoo Finance) e R (`BatchGetSymbols`) para listas de ações do S&P 500 e brasileiras. |
| `Overshoot_sim.ipynb` | Simulação em R de uma dinâmica de *overshoot* de consumo. |
| `Untitled2.ipynb` | Algoritmo genético para o problema do caixeiro-viajante (classes `City` e `Fitness`). |

## Como usar

Cada notebook tem um botão "Open In Colab" na primeira célula. Para rodar localmente:

```bash
pip install finpie rpy2 tabulate numpy pandas matplotlib seaborn jupyter
jupyter notebook
```

`Balanceador_de_investimentos` e `Marketanalysis` usam `rpy2`, então precisam do R instalado. O `finpie` busca dados online e pode ficar lento por causa de limites de requisição.
