# Segmentação de Clientes e Previsão de Rotura (Churn)

## Objetivo do Projeto
Analisar o perfil e o comportamento de utilização dos clientes de uma rede de ginásios para identificar os principais fatores associados ao cancelamento (churn), segmentar a base de utilizadores e propor estratégias práticas de retenção.

## Ferramentas e Bibliotecas
* **Linguagem:** Python
* **Manipulação e Análise de Dados:** Pandas, NumPy
* **Visualização de Dados:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (Regressão Logística, Random Forest, StandardScaler, K-Means, métricas de classificação)

## Metodologia
1. **Análise Exploratória de Dados (EDA):** Verificação de valores ausentes, distribuição das variáveis e comparação entre clientes ativos e clientes em churn.
2. **Modelação Preditiva:** Treino e comparação de modelos de classificação (Regressão Logística e Random Forest) avaliados por acurácia, precisão (*precision*) e sensibilidade (*recall*).
3. **Clusterização de Clientes:** Padronização dos dados, construção de dendrograma para definição do número ideal de grupos ($K=5$) e aplicação do algoritmo **K-Means** para caracterizar cada perfil de cliente.

## Principais Conclusões e Recomendações
* Identificação dos grupos com maior taxa de rotura (clientes com contratos mais curtos, menor frequência semanal e menor interação em grupo).
* Recomendações orientadas ao negócio para ações preventivas de retenção direcionadas aos clusters de maior risco.

