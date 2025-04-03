# Credit Scoring com PyCaret e Streamlit

Este projeto é uma aplicação interativa construída com Streamlit para realizar **escoragem de crédito** usando um modelo de machine learning treinado com a biblioteca PyCaret.

## Etapas do Projeto

### 1. Notebook de Treinamento: `credit_scoring_pycaret.ipynb`

O notebook contém as seguintes etapas:

- **Importação e exploração dos dados**
- **Pré-processamento com PyCaret**
- **Criação e comparação de modelos de machine learning**
- **Escolha do melhor modelo**
- **Salvamento do modelo final com `save_model()`**

O modelo final é salvo no arquivo `model_final.pkl`, que será utilizado na aplicação Streamlit para escoragem.

---

### 2. Aplicação com Streamlit: `app_pycaret.py`


A aplicação feita com Streamlit permite que o usuário:

- Faça o upload de uma base de dados (`.csv` ou `.ftr`)
- Utilize o modelo treinado para escorar a base
- Veja as previsões diretamente na tela
- Faça o **download do resultado** em formato Excel

---
No projeto, usamos Streamlit para:

- Criar interface de upload de dados
- Aplicar o modelo treinado nos dados do usuário
- Exibir os resultados
- Oferecer botão de download do arquivo com as previsões

---

Este projeto faz parte do módulo final do curso de Ciência de Dados da EBAC.
