# Telecom X-2

Projeto de **Data Science** desenvolvido como parte do **Desafio Final da Especialização em Data Science** da **Oracle One Next Education em parceria com a Alura**.

---

## Objetivo

Identificar **clientes com maior risco de evasão (churn)** em uma empresa de telecomunicações, analisando quais variáveis mais influenciam esse comportamento e propondo ações para reduzir a perda de clientes.

---

##  Dados Utilizados

- **Fonte:** Dataset tratado a partir da etapa 1 do projeto Telecom X.
- Inclui informações de:
  - Perfil do cliente
  - Serviços contratados
  - Cobranças
  - Tempo de contrato
  - Variável alvo: `Churn` (evasão)

---

##  Tecnologias e Ferramentas

- **Linguagem:** Python
- **Bibliotecas principais:** 
  - `pandas`, `numpy` para tratamento de dados
  - `scikit-learn` para modelos preditivos
  - `seaborn`, `matplotlib` para visualizações
- **Jupyter Notebook** para análise e documentação.
- **Git e GitHub** para versionamento.
- **Trello** para gestão das etapas do desafio.

---

##  Etapas Realizadas

1. **Preparação de Dados**
   - Carregamento do dataset tratado
   - Limpeza de dados inconsistentes e colunas irrelevantes
   - Transformação de variáveis categóricas

2. **Análise Exploratória de Dados (EDA)**
   - Visualização de distribuição de churn
   - Análise de correlação entre variáveis

3. **Modelagem Preditiva**
   - Modelos aplicados: **Random Forest** e **Regressão Logística**
   - Divisão em dados de treino e teste
   - Avaliação de métricas: Accuracy, Recall, Precision, F1-Score, AUC

4. **Interpretação**
   - Identificação das variáveis mais relevantes
   - Recomendações para retenção de clientes

---

##  Principais Resultados

- Variáveis como **`Contract`**, **`tenure`** e **`MonthlyCharges`** foram as mais relevantes para prever o churn.
- Clientes com contratos mensais e altas cobranças têm maior risco de evasão.
- Recomenda-se ações de fidelização e ofertas personalizadas para este perfil.

---

##  Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/ajtoriani/telecomx-2

2. Crie um ambiente virtual e instale as dependências:
   ```bash
   pip install -r requirements.txt
   
3. Execute o notebook TelecomX2.ipynb no Jupyter ou Google Colab.


🏷️ Observações
Este projeto faz parte da trilha de formação em Data Science do programa Oracle One Next Education com a Alura.

Para uma análise reprodutível, o dataset tratado deve ser incluído no repositório ou disponibilizado via link.

📚 Créditos
Oracle Next Education — Alura
