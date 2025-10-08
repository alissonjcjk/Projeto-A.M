# Projeto de Classificação de Proteínas de Levedura (Yeast)

## Descrição do Projeto

Este repositório contém o projeto de Machine Learning para a disciplina [Aprendizado de Máquina], cujo objetivo é classificar a localização de proteínas em células de levedura com base em atributos bioquímicos. O projeto explora e compara o desempenho de cinco algoritmos de classificação diferentes, com otimização de hiperparâmetros e análise de curvas de aprendizagem.

**Dataset:** [Yeast - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/110/yeast)

## Membros da Equipe

*   Alisson da Silva Bernadino
*   Alexsandro José da Silva
*   Alandrey André da Silva

## Objetivos

*   Realizar uma análise exploratória e pré-processamento do dataset Yeast.
*   Implementar, treinar e avaliar 5 modelos de classificação:
    *   Árvore de Decisão
    *   Naive Bayes Gaussiano
    *   Regressão Logística
    *   k-Nearest Neighbors (k-NN)
    *   Random Forest
*   Otimizar os hiperparâmetros de cada modelo usando Validação Cruzada (`GridSearchCV`).
*   Avaliar os modelos finais no conjunto de teste usando as métricas de Precisão, Cobertura (Recall) e F1-Score.
*   Gerar e analisar as curvas de aprendizagem para os modelos otimizados.

## Estrutura do Repositório

*   `yeast.data`: O dataset original utilizado no projeto.
*   `Projeto_AM.ipynb`: O notebook Jupyter/Google Colab contendo todo o código, desde a exploração dos dados até a avaliação final dos modelos e a geração dos gráficos.
*   `Relatorio_Projeto.pdf`: O relatório final do projeto detalhando a metodologia, resultados e conclusões.
*   `Apresentacao.pdf`: Os slides utilizados na apresentação do projeto.
*   `README.md`: Este arquivo.

## Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/alissonjcjk/Projeto-A.M.git)
    cd Projeto-A.M
    ```
    

3.  **Ambiente e Dependências:**
       O Projeto foi feito utilizando o ambiente do Google Colab onde todas as dependências
       são nativamente instaladas
    

5.  **Execução:**
    Abra o notebook `Projeto_AM.ipynb` em um ambiente como Jupyter Notebook, JupyterLab ou Google Colab e execute as células em ordem.

    [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seu-usuario/seu-repositorio/blob/main/Projeto_Yeast_Classificacao.ipynb)
    *(Dica: Substitua a URL acima pela URL do seu notebook no GitHub para que o botão "Abrir no Colab" funcione!)*

## Resumo dos Resultados


Após a otimização e avaliação, o modelo que apresentou o melhor desempenho geral no conjunto de teste foi o **----**, atingindo um F1-Score (weighted) de **----**. Os resultados detalhados para todos os modelos podem ser encontrados no relatório e no notebook.

---
