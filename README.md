# 🤖 Projeto Python IA: Score de Crédito de Clientes

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue" alt="Python">
  <img src="https://img.shields.io/badge/pandas-✔️-green" alt="pandas">
  <img src="https://img.shields.io/badge/scikit--learn-✔️-orange" alt="scikit-learn">
</p>

> **Previsão automática do score de crédito de clientes bancários usando Machine Learning.**

---

## 📑 Sumário
- [Sobre o Projeto](#sobre-o-projeto)
- [Principais Tecnologias](#principais-tecnologias)
- [Estrutura dos Dados](#estrutura-dos-dados)
- [Como Rodar o Projeto](#como-rodar-o-projeto)
- [Fluxo de Trabalho](#fluxo-de-trabalho)
- [Observações](#observações)
- [Autor](#autor)

---

## 📝 Sobre o Projeto
Este projeto utiliza técnicas de Inteligência Artificial para prever o score de crédito de clientes de um banco, classificando-os como **Ruim**, **Ok** ou **Bom** a partir de dados históricos. O objetivo é automatizar a análise de risco de crédito, facilitando decisões financeiras.

---

## 🚀 Principais Tecnologias
- 🐼 **pandas** — Manipulação e análise de dados
- 🧪 **scikit-learn** — Pré-processamento, classificação (RandomForest, KNN), métricas
- 📓 **Jupyter Notebook** — Documentação e execução do fluxo

---

## 🗂️ Estrutura dos Dados
- `clientes.csv` — Base histórica de clientes (100.000 linhas, 25 colunas)
- `novos_clientes.csv` — Novos clientes para previsão

---

## 💻 Como Rodar o Projeto
1. **Pré-requisitos**
   - Python 3.8 ou superior
   - Jupyter Notebook (VSCode, JupyterLab, Google Colab, etc.)
2. **Instale as dependências:**
   ```bash
   pip install pandas scikit-learn
   ```
3. **Coloque os arquivos de dados** (`clientes.csv` e `novos_clientes.csv`) no mesmo diretório do notebook.
4. **Abra o arquivo** `inicial.ipynb` no Jupyter e execute as células na ordem:
   - 📥 Carregue e trate os dados
   - 🏷️ Faça o pré-processamento (LabelEncoder)
   - ✂️ Separe treino/teste (train_test_split)
   - 🌳 Treine modelos (Random Forest, KNN)
   - 📊 Avalie os resultados
   - 🔮 Faça previsões para novos clientes

---

## 🔄 Fluxo de Trabalho
```mermaid
graph TD;
    A[Leitura dos Dados] --> B[Pré-processamento]
    B --> C[Divisão Treino/Teste]
    C --> D[Modelagem (Random Forest/KNN)]
    D --> E[Avaliação dos Modelos]
    E --> F[Previsão para Novos Clientes]
```

---

## ⚡ Observações
- 📁 Os arquivos de dados devem estar no mesmo diretório do notebook.
- 💡 Projeto didático, sinta-se livre para expandir!
- 🔒 Os dados utilizados são fictícios e para fins educacionais.

---

## 👤 Autor
by **Rodolfo M. F. Abreu**
