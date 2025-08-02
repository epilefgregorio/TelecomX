# 📊 Telecom X – Análise de Evasão de Clientes (Churn)

Este projeto faz parte do **Desafio de Data Science** do Programa ONE (Oracle Next Education), em parceria com a Alura. O objetivo principal é analisar os dados de uma empresa fictícia chamada **Telecom X**, que enfrenta alta taxa de evasão de clientes (churn), e gerar insights que possam contribuir para a retenção desses clientes.

---

## 📌 Objetivo

Investigar os principais fatores que influenciam o cancelamento dos serviços por parte dos clientes da Telecom X, utilizando as etapas do processo de **ETL (Extração, Transformação e Carga)** e **Análise Exploratória de Dados (EDA)** com Python.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- Python 3
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- JSON (estrutura dos dados)
- Git / GitHub

---

## 📁 Estrutura do Projeto

- `TelecomX_Data.json`: Dados brutos fornecidos pela empresa fictícia.
- `TelecomX_dicionario.md`: Dicionário de dados com descrição de cada coluna.
- `TelecomX_Analise_Churn.ipynb`: Notebook principal com todas as etapas do projeto.
- `README.md`: Este arquivo com as informações do repositório.

---

## 🔍 Etapas do Projeto

### ✅ 1. Extração (Extract)
- Importação dos dados em formato `.json`, simulando acesso a uma API.
- Normalização da estrutura aninhada para um DataFrame plano com o `pandas`.

### ✅ 2. Transformação (Transform)
- Limpeza e tratamento de dados:
  - Conversão de tipos.
  - Remoção de nulos e duplicatas.
  - Criação de nova variável `Contas_Diarias`.

### ✅ 3. Carga e Análise (Load & EDA)
- Análise descritiva das principais variáveis.
- Visualizações com `matplotlib` e `seaborn`.
- Comparações entre clientes que evadiram e os que permaneceram.

---

## 💡 Principais Insights

- Clientes com **contratos mensais** e **baixo tempo de permanência** têm maior tendência à evasão.
- Faturas **eletrônicas** e ausência de serviços adicionais estão associadas a maior churn.
- **Alto valor mensal**, mas **baixo total gasto**, sugere cancelamentos precoces.

---

## ✅ Recomendações

- Estimular contratos de longo prazo com benefícios.
- Incentivar adesão a serviços extras.
- Acompanhar clientes com padrão de risco nos primeiros meses.
- Rever opções de pagamento mais propensas à rotatividade.

---

## 📄 Licença

Este projeto é de caráter educacional, feito como parte do curso **Formação Cientista de Dados - Programa ONE / Alura**.

---

## 👤 Autor

Feito por Felipe Gregório como parte do desafio de dados do Programa ONE – Alura + Oracle.

[🔗 LinkedIn https://www.linkedin.com/in/felipe-fernandes01
