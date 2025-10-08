# Projeto de Classificação de Proteínas de Levedura (Yeast)

## Descrição do Projeto

Este repositório contém o projeto de Machine Learning para a disciplina [Nome da Disciplina], cujo objetivo é classificar a localização de proteínas em células de levedura com base em atributos bioquímicos. O projeto explora e compara o desempenho de cinco algoritmos de classificação diferentes, com otimização de hiperparâmetros e análise de curvas de aprendizagem.

**Dataset:** [Yeast - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/110/yeast)

## Membros da Equipe

*   Nome Completo do Membro 1
*   Nome Completo do Membro 2
*   Nome Completo do Membro 3

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
*   `Projeto_Yeast_Classificacao.ipynb`: O notebook Jupyter/Google Colab contendo todo o código, desde a exploração dos dados até a avaliação final dos modelos e a geração dos gráficos.
*   `Relatorio_Projeto.pdf`: O relatório final do projeto detalhando a metodologia, resultados e conclusões.
*   `Apresentacao.pdf`: Os slides utilizados na apresentação do projeto.
*   `README.md`: Este arquivo.

## Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```

2.  **Ambiente e Dependências:**
    O projeto foi desenvolvido em Python 3. As bibliotecas necessárias estão listadas abaixo. Para recriar o ambiente, você pode instalar as dependências usando `pip`:
    ```bash
    pip install numpy pandas scikit-learn matplotlib seaborn
    ```

3.  **Execução:**
    Abra o notebook `Projeto_Yeast_Classificacao.ipynb` em um ambiente como Jupyter Notebook, JupyterLab ou Google Colab e execute as células em ordem.

    [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seu-usuario/seu-repositorio/blob/main/Projeto_Yeast_Classificacao.ipynb)
    *(Dica: Substitua a URL acima pela URL do seu notebook no GitHub para que o botão "Abrir no Colab" funcione!)*

## Resumo dos Resultados

*AQUI VOCÊ PODE ADICIONAR UMA BREVE CONCLUSÃO APÓS TERMINAR O PROJETO*

Após a otimização e avaliação, o modelo que apresentou o melhor desempenho geral no conjunto de teste foi o **Random Forest**, atingindo um F1-Score (weighted) de **XX.X%**. Os resultados detalhados para todos os modelos podem ser encontrados no relatório e no notebook.

---
