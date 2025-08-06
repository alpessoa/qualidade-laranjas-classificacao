<img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/aa68d2f1-8d0d-4455-94a2-3708eecada5e" />

# 🍊 Previsão da Qualidade de Laranjas

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Libraries](https://img.shields.io/badge/Libraries-Pandas%20%7C%20Scikit--learn%20%7C%20Seaborn-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Projeto de machine learning para prever a qualidade sensorial de laranjas com base em suas características físico-químicas. Desenvolvido durante o **Bootcamp de Ciência de Dados da Avantii**.

## 📖 Descrição do Projeto

Este projeto utiliza técnicas de Ciência de Dados para desenvolver um modelo de classificação capaz de prever a qualidade de laranjas. O objetivo é criar uma solução que possa auxiliar na automação e na objetividade do controle de qualidade na indústria agrícola, traduzindo dados brutos como doçura, acidez e peso em uma métrica de qualidade confiável.

## 🎯 Objetivos

* Realizar uma Análise Exploratória dos Dados (AED) para extrair insights e entender as correlações.
* Construir um pipeline de pré-processamento para tratar os dados de forma consistente.
* Treinar e validar cinco diferentes modelos de classificação.
* Comparar os modelos utilizando a métrica F1-Score Macro para identificar o de melhor desempenho.

## 🛠️ Tecnologias e Metodologia

O núcleo do projeto foi desenvolvido em Python, utilizando as seguintes ferramentas e técnicas:

* **Análise de Dados:** `Pandas`
* **Visualizações:** `Matplotlib`, `Seaborn`
* **Machine Learning:** `Scikit-learn`
* **Modelos Testados:** Regressão Logística, Árvore de Decisão, kNN, SVM e Random Forest.
* **Validação:** Validação Cruzada (K-Fold) para garantir a robustez dos resultados.
* **Métricas de Avaliação:** F1-Score Macro e Acurácia.

## 🏆 Resultado

Após a fase de modelagem e validação, o modelo de **Regressão Logística** apresentou o melhor desempenho geral, alcançando um **F1-Score Macro de 0.522**. Este resultado demonstrou que, para este problema, um modelo mais simples foi mais eficaz e generalizável do que algoritmos mais complexos.

## 🚀 Como Usar o Projeto

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/alpessoa/NOME-DO-SEU-REPOSITORIO.git](https://github.com/alpessoa/NOME-DO-SEU-REPOSITORIO.git)
    ```
2.  Navegue até o diretório do projeto e instale as dependências:
    ```bash
    cd NOME-DO-SEU-REPOSITORIO
    pip install -r requirements.txt
    ```
3.  Abra os notebooks na pasta `notebooks/` utilizando o Jupyter Notebook ou Google Colab.

## 📂 Estrutura do Repositório
```
├── notebooks/         # Contém a análise exploratória e a modelagem
├── data/              # Dados utilizados no projeto
├── imagens/           # Visualizações e gráficos gerados
├── requirements.txt   # Lista de bibliotecas e dependências
└── README.md          # Este arquivo :)
```

## 👤 Autores

**André Pessoa**

[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/andre-pessoaa)
[<img src="https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white" />](https://github.com/alpessoa)


**Carlos Augusto** 
**Juan Araújo**
---

## 📄 Licença

Este projeto está sob a licença MIT. É de uso educacional e livre para modificações e distribuição.
