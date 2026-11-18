# Projeto Pokémon - Análise Exploratória de Dados e Testes de Hipóteses

Projeto de **Análise de Dados** dividido em etapas, utilizando um dataset de Pokémon para praticar preparação de dados, análise exploratória (EDA) e validação de hipóteses estatísticas com Python.

## Descrição

O projeto parte de um dataset com dados de Pokémon (`pokemon_complete_stats.csv`) e conduz todo o fluxo de uma análise de dados: limpeza, análise exploratória e, em seguida, formulação e validação de hipóteses com testes estatísticos.

## Etapas

### Etapa 02 - Preparação, Limpeza e Análise Exploratória
- Carregamento do dataset (1351 registros × 20 colunas)
- Verificação e tratamento de valores nulos (ex.: `base_experience`, `type_2`, `abilities`)
- Verificação de duplicatas e inconsistências
- Detecção de outliers
- Análise das formas especiais de Pokémon (`id > 9000`, cerca de 24,1% dos registros)
- Geração de gráficos e visualizações dos dados

### Etapa 03 - Hipóteses e Validação Estatística
- Formulação de 5 hipóteses sobre os dados
- Testes estatísticos com nível de significância α = 0,05
- Testes aplicados: Mann-Whitney U / t de Welch, Kruskal-Wallis / ANOVA, Correlação de Pearson e Qui-Quadrado (χ²)
- Conclusões sobre atributos como `special_attack`, `speed`, peso, HP, shape e status de lendário

## Estrutura do Projeto

```
Projeto-etapa-2-e-3/
└── Etapas/
    ├── Etapa02_Nicholas_Knopp_Seferin_da_Silva.ipynb
    └── Etapa03_Nicholas_Knopp_Seferin_da_Silva (1).ipynb
```

## Tecnologias Utilizadas
- Python 3
- Jupyter Notebook
- pandas e NumPy
- Matplotlib e Seaborn
- SciPy (`scipy.stats`)

## Como Executar
1. Tenha o Python 3 e o Jupyter Notebook (ou Jupyter Lab) instalados.
2. Instale as dependências:

   ```
   pip install pandas numpy matplotlib seaborn scipy jupyter
   ```

3. Inicie o Jupyter e abra os notebooks:

   ```
   jupyter notebook
   ```

## Autor
Desenvolvido por **Nicholas Knopp Seferin da Silva**.
