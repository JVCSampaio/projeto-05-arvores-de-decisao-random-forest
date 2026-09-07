# Projeto 5 — Árvores de Decisão e Random Forest

Árvores de decisão visualizadas com Graphviz, Random Forest com GridSearchCV (melhor: max_depth=9, n_estimators=200, AUC médio 0.776) e importância das variáveis — PAY_1 domina (0.44).

**Livro:** *Projetos de Ciência de Dados com Python* — Stephen Klosterman (Novatec Editora, 2020)

## Conteúdo

- `projeto.ipynb` — notebook completo, já executado (com todas as saídas e gráficos)
- `Data/` — datasets usados (UCI Credit Card: 5.333 registros, 23 variáveis)

## Como executar

```bash
pip install pandas scikit-learn numpy matplotlib seaborn xlrd
jupyter notebook projeto.ipynb
```

Para as visualizações de árvores (Projeto 5), instale o binário Graphviz (`dot`).
