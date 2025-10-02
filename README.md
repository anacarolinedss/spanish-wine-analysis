# Análise e Predição da Qualidade de Vinhos Espanhóis🍷

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## Bibliotecas Usadas
### Manipulação de Dados
- `pandas` – análise e manipulação de DataFrames  
- `numpy` – operações numéricas  

### Visualização
- `matplotlib` – gráficos e visualizações básicas  
- `seaborn` – gráficos estatísticos avançados  

### Modelagem e Pré-processamento
- `scikit-learn` (`sklearn`) – modelos de regressão, métricas, KNNImputer, StandardScaler, train_test_split, OneHotEncoder, OrdinalEncoder, Cross-Validation  

### Outras (opcionais)
- `missingno` – visualização de valores ausentes  
- `plotly` – gráficos interativos
  
---

## Sobre o Projeto
O projeto **Spanish Wine Analysis** foi desenvolvido durante o Bootcamp de Ciências de Dados **Atlântico Avanti** em grupo. O objetivo consistiu em explorar, limpar e analisar dados de vinhos espanhóis premium, além de comparar diferentes modelos preditivos para prever a qualidade (rating) dos vinhos.

---

## Dataset
- Fonte: [Kaggle - Spanish Wine Quality Dataset](https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset)
- 7.500 registros de vinhos espanhóis com 11 atributos:
  - `winery`, `wine`, `year`, `rating`, `num_reviews`, `country`, `region`, `price`, `type`, `body`, `acidity`
- Tarefas possíveis: regressão (preço)

---

## Etapas do Projeto
1. **Importação de Bibliotecas**: pandas, numpy, matplotlib, seaborn, scikit-learn  
2. **Carregamento e Inspeção dos Dados**: verificação de tipos, valores ausentes e primeiras impressões  
3. **Análise Exploratória**: histogramas, gráficos de contagem, scatterplots e heatmaps de correlação  
4. **Tratamento de Valores Ausentes**: KNNImputer para numéricos e remoção de linhas críticas em variáveis categóricas  
5. **Pré-processamento de Variáveis Categóricas**: agrupamento de categorias, remoção de colunas irrelevantes, One-Hot Encoding e Ordinal Encoding  
6. **Separação Treino/Teste e Padronização**: StandardScaler para features  
7. **Comparação de Modelos Preditivos**: Linear Regression, Decision Tree, kNN, Dummy Regressor; avaliação com MAE e RMSE usando K-Fold Cross-Validation  
8. **Visualização de Resultados**: tabelas e gráficos de barras para comparar desempenho dos modelos

---

## Conclusões Preliminares
- A análise exploratória revelou padrões importantes sobre ratings, preços, popularidade e características sensoriais  
- O pré-processamento preparou os dados para modelagem  
- O modelo kNN apresentou melhor desempenho na previsão de ratings  
- Próximos passos: otimização de hiperparâmetros, engenharia de features e exploração de outros modelos

---

## Como Rodar o Projeto
1. Clone o repositório:
```bash
git clone https://github.com/anacarolinedss/spanish-wine-analysis.git
