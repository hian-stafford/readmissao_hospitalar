# Análise e Previsão de Demanda em Hospitais

## Descrição

Este repositório contém o projeto de **Análise e Previsão de Demanda em Hospitais**. O objetivo principal é aplicar técnicas de aprendizado de máquina para prever a demanda hospitalar com base em dados históricos.
---

## Ferramentas e Tecnologias Utilizadas

### 1. **Dados**  
- **hospital_readmissions.csv**:  
  - O dataset contém informações de admissões hospitalares, incluindo dados sobre pacientes, condições médicas, e características clínicas.  
  - **Importância**: Esses dados serviram como a base para o projeto, permitindo a análise e a extração de padrões e insights relacionados à demanda hospitalar.

### 2. **Jupyter Notebooks (`hospital_readmissions.ipynb`)**  
- **Descrição**:  
  - O notebook fornece um passo-a-passo para análise exploratória e modelagem. Contém desde a leitura dos dados até a visualização, limpeza e preparação para o treinamento de modelos.  
- **Importância**:  
  - **Análise Exploratória**: Permitiu entender a estrutura dos dados, identificar padrões, outliers e variáveis relevantes.  
  - **Visualizações**: Criou gráficos e tabelas para ajudar na compreensão dos dados e na identificação de tendências importantes para previsões.  
  - **Modelagem**: Utilizou o pandas e bibliotecas de visualização para manipular e analisar os dados, além de importar os modelos de machine learning.  

### 3. **Modelos de Machine Learning**  

- **Descrição**:  
  - Inclui o treinamento de modelos como Regressão Logística, Random Forest, Árvore de Decisão e MLP (Multilayer Perceptron).  
- **Importância**:  
  - **Modelos Utilizados**:  
    - **Regressão Logística**: Utilizada para prever se um paciente será readmitido ou não, baseada em variáveis preditoras.  
    - **Árvore de Decisão**: Permitiu entender como as variáveis influenciam a previsão e criar decisões baseadas em critérios específicos.  
    - **Random Forest**: Melhorou a robustez da modelagem ao reduzir o overfitting e fornecer previsões mais precisas.  
    - **MLP (Multilayer Perceptron)**: Utilizado para explorar modelos mais complexos que capturam não-linearidades e melhoram a precisão nas previsões.  

---

## Dados

- O dataset utilizado é `hospital_readmissions.csv`, contendo informações de admissões hospitalares.  
- Os dados foram pré-processados para análise e modelagem.

---

## Modelos

- Foram utilizados modelos de machine learning como Regressão Logística, Random Forest, Árvore de Decisão e MLP para prever a demanda hospitalar.  
- O desempenho dos modelos pode ser analisado no notebook `hospital_readmissions.ipynb`.  
- A validação cruzada foi aplicada para garantir a robustez dos modelos e evitar overfitting.

---

## Contato

- **Autor**: Hian Stafford  
- **Email**: hian-stafford@gmail.com
