# Projeto Python IA: Score de Crédito de Clientes

Este projeto utiliza técnicas de Inteligência Artificial para prever o score de crédito de clientes de um banco, classificando-os como Ruim, Ok ou Bom, a partir de dados históricos.

## Principais Bibliotecas Utilizadas
- **pandas**: Manipulação e análise de dados tabulares.
- **scikit-learn**: Pré-processamento, divisão de dados, classificação (RandomForestClassifier, KNeighborsClassifier) e métricas.

## Padrões e Boas Práticas
- **Notebook Jupyter**: Todo o fluxo está documentado no arquivo `inicial.ipynb`.
- **Pré-processamento**: Utilização de `LabelEncoder` para transformar variáveis categóricas em numéricas.
- **Divisão de dados**: Separação em treino e teste com `train_test_split`.
- **Modelos**: Treinamento e avaliação de dois modelos: Random Forest e KNN.

## Estrutura dos Dados
- `clientes.csv`: Base histórica de clientes (100.000 linhas, 25 colunas).
- `novos_clientes.csv`: Novos clientes para previsão.

## Instruções de Setup
1. **Pré-requisitos**:
   - Python 3.8+
   - Instale as bibliotecas necessárias:
     ```bash
     pip install pandas scikit-learn
     ```
2. **Execução**:
   - Abra o arquivo `inicial.ipynb` em um ambiente Jupyter Notebook (ex: VSCode, JupyterLab, Google Colab).
   - Execute as células sequencialmente para:
     - Carregar e pré-processar os dados
     - Treinar e avaliar os modelos
     - Realizar previsões para novos clientes

## Observações
- Os arquivos de dados devem estar no mesmo diretório do notebook.
- O projeto é didático e pode ser expandido para outros algoritmos ou métricas.

by Rodolfo M. F. Abreu
