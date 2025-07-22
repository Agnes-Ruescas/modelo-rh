#  HR Analytics: Predição de Rotatividade de Funcionários

Este projeto foi desenvolvido como trabalho final da disciplina **Data Science Experience** do MBA em Engenharia de Dados da Universidade Presbiteriana Mackenzie. O objetivo principal é prever a **probabilidade de um colaborador sair da empresa** (attrition), a partir de dados históricos, por meio de um pipeline completo de ciência de dados.

---

##  Problema

A **alta rotatividade de funcionários** impacta diretamente os custos, clima organizacional e a produtividade. Antecipar quais colaboradores estão mais propensos a pedir desligamento é essencial para ações de **retenção estratégica**.

---

##  Solução Proposta

Utilizamos um conjunto de dados com informações demográficas, contratuais e comportamentais dos colaboradores. O pipeline envolve:

-  Análise Exploratória (EDA)
-  Criação de novas variáveis (Feature Engineering)
-  Modelagem com 4 algoritmos (Logistic Regression, KNN, Decision Tree e Random Forest)
-  Balanceamento de classes com SMOTE
-  Avaliação com métricas (Recall, F1-Score, Lift, Matriz de Confusão)

---

##  Estrutura dos Notebooks

- [`EDA_Projeto_Final_MBA.ipynb`](./notebooks/EDA_Projeto_Final_MBA.ipynb): Análise estatística, visualizações e principais insights do dataset.
- [`Feature_Engineering_MBA.ipynb`](./notebooks/Feature_Engineering_MBA.ipynb): Criação de variáveis com hipóteses de negócio e codificação de variáveis categóricas.
- [`Modelo_MBA.ipynb`](./notebooks/Modelo_MBA.ipynb): Treinamento, avaliação e comparação dos modelos preditivos com foco em Recall e Lift.

---

##  Principais Resultados

- O modelo **Random Forest** foi o que obteve **melhor performance geral**:
  - F1-score classe 1: 0.47
  - Recall classe 1: 0.45
  - Lift: 2.8 no 1º decil
- As variáveis mais influentes indicam que **baixa satisfação, alta carga de trabalho e distância de casa** são importantes fatores de risco.
- Recomendação: **Monitoramento proativo dos 20% com maior risco predito de saída**.

---

##  Tecnologias Utilizadas

- Python (Pandas, Seaborn, Scikit-Learn, Imbalanced-learn)
- Jupyter Notebook
- Streamlit (para futura interface de uso)
- Git e GitHub

---

##  Próximos Passos

- Criação de dashboard interativo com Streamlit
- Testes com modelos avançados (XGBoost, LightGBM)
- Explicabilidade com SHAP
- Monitoramento contínuo do modelo com novos dados

---

##  Autor

**Agnes Ruescas**  
MBA em Engenharia de Dados — Universidade Presbiteriana Mackenzie  
[LinkedIn](https://www.linkedin.com/in/agnesruescas/) 

