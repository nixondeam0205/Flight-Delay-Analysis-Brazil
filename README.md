# ✈️ Flight Delay Analysis Brazil

Análise exploratória e modelagem preditiva de atrasos em voos domésticos e internacionais no Brasil utilizando dados da ANAC (VRA 2025).

## 📌 Objetivo

Este projeto tem como objetivo analisar os fatores associados aos atrasos de voos no Brasil e desenvolver um modelo de Machine Learning capaz de prever se um voo sofrerá atraso com base em informações operacionais.

Durante o projeto foram realizadas as etapas de limpeza, preparação dos dados, análise exploratória (EDA) e construção de um modelo de classificação utilizando Random Forest.

---

## 📂 Dataset

Base de dados:

- **VRA (Voo Regular Ativo)** disponibilizada pela Agência Nacional de Aviação Civil (ANAC)
- Ano analisado: **2025**

Após o tratamento dos dados foram analisados aproximadamente **978 mil voos realizados**.

---

## 🛠 Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Etapas do projeto

### 1. Preparação dos dados

- União dos arquivos mensais
- Remoção de colunas desnecessárias
- Tratamento de datas
- Criação de novas variáveis
- Mapeamento de companhias aéreas
- Mapeamento de aeroportos
- Tratamento de valores inconsistentes

---

### 2. Análise Exploratória dos Dados (EDA)

Foram investigados diversos fatores relacionados aos atrasos, incluindo:

- Companhias aéreas
- Aeroportos de origem e destino
- Horário dos voos
- Dia da semana
- Sazonalidade (mês)

Também foram produzidos gráficos para facilitar a interpretação dos resultados.

---

### 3. Machine Learning

Foi desenvolvido um modelo de classificação utilizando:

- Random Forest Classifier

Variáveis utilizadas:

- Companhia aérea
- Aeroporto de origem
- Aeroporto de destino
- Hora do voo
- Dia da semana
- Mês

---

## 📈 Resultados

O modelo apresentou aproximadamente:

- **Acurácia:** 65,7%

As variáveis mais importantes para a previsão foram:

- Mês
- Hora
- Aeroporto de origem
- Dia da semana
- Companhia aérea

Os resultados demonstram que fatores temporais possuem maior influência na previsão de atrasos do que a companhia aérea.

---

## 📁 Estrutura do projeto

```
Flight-Delay-Analysis-Brazil/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── analise_voos_2025.ipynb
│
├── images/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Como executar

Clone o repositório:

```bash
git clone https://github.com/nixondeam0205/Flight-Delay-Analysis-Brazil
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Abra o notebook:

```
notebooks/analise_voos_2025.ipynb
```

---

## 📌 Possíveis melhorias

- Inclusão de dados meteorológicos
- Teste de outros algoritmos de classificação
- Ajuste de hiperparâmetros
- Desenvolvimento de dashboard interativo

---

## 👤 Autor

**Nixon Deam**

Projeto desenvolvido para fins de estudo e composição de portfólio em Ciência de Dados.