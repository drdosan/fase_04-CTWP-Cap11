# FIAP - Faculdade de Informática e Administração Paulista 

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# SOLUÇÃO COMPLETA - CLASSIFICAÇÃO DE GRÃOS DE TRIGO COM MACHINE LEARNING


## Grupo 6

## 👨‍🎓 Integrantes: 
| Matrícula                 | Aluno               						        |
|---------------------------|---------------------------------------------|
|        RM 565150          | Andre de Oliveira Santos Burger			     |
|        RM 565497          | Vera Maria Chaves de Souza				        | 
|        RM 565286          | Diogo Rebello dos Santos					     |
|        RM 565555          | Marcos Vinícius dos Santos Fernandes		  |

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="#">Leonardo Ruiz Orabona</a>
### Coordenador(a)
- <a href="#">André Godoi Chiovato</a>



## 📜 Descrição

Este projeto apresenta uma solução completa de Machine Learning para a classificação de variedades de grãos de trigo (Kama, Rosa, Canadian) com base em suas características físicas. A metodologia CRISP-DM foi rigorosamente seguida para garantir um processo estruturado e eficaz, desde a compreensão dos dados até a otimização e interpretação dos modelos.


## 📁 Estrutura de pastas

```
src/
├── main.ipynb
├── seeds_dataset.txt
│
document/
├── Relatorio.pdf
│
├.gitignore
└ README.md
```

- main.ipynb - Solução completa do treinamento e geração dos modelos.
- seeds_data.txt - Data Sets utilizado para treinamento dos modelos.
- Relatorio.pdf - Relatório em pdf de todo o projeto.

## 🎯 Objetivo do Projeto

O objetivo principal deste projeto é desenvolver e implementar um sistema de classificação de grãos de trigo utilizando algoritmos de Machine Learning. A solução abrange todas as etapas essenciais de um projeto de ciência de dados, conforme a metodologia CRISP-DM, incluindo:

*   **Análise Exploratória de Dados (EDA) e Pré-processamento:** Compreensão aprofundada do dataset, tratamento de dados e preparação para modelagem.
*   **Implementação de Algoritmos de Machine Learning:** Aplicação de diversos modelos de classificação para identificar a variedade de grão.
*   **Otimização de Modelos:** Ajuste de hiperparâmetros para maximizar a performance dos modelos.
*   **Interpretação e Insights:** Análise dos resultados, importância das características e recomendações práticas.

---

## 🌾 Dataset Utilizado

O dataset empregado neste projeto contém 210 amostras de grãos de trigo, cada uma descrita por 7 características físicas distintas. As variedades de grãos a serem classificadas são Kama, Rosa e Canadian.

### Características dos Grãos:

*   **Área do grão:** Medida da área total do grão.
*   **Perímetro:** Medida do perímetro do grão.
*   **Compacidade:** Relação entre a área e o perímetro do grão, indicando sua forma.
*   **Comprimento do núcleo:** Medida do comprimento do núcleo do grão.
*   **Largura do núcleo:** Medida da largura do núcleo do grão.
*   **Coeficiente de assimetria:** Medida da assimetria da forma do grão.
*   **Comprimento do sulco do núcleo:** Medida do comprimento do sulco presente no núcleo do grão.
*   **Classe:** Variedade do grão (1=Kama, 2=Rosa, 3=Canadian).

---

## ⚙️ Etapas da Solução

O projeto foi estruturado nas seguintes etapas, seguindo a metodologia CRISP-DM:

### 1. Análise Exploratória e Pré-processamento

*   Carregamento e exploração inicial dos dados.
*   Geração de estatísticas descritivas completas para cada característica.
*   Criação de visualizações (histogramas, boxplots, gráficos de correlação, scatter plots) para entender a distribuição e relação entre as variáveis.
*   Verificação de valores ausentes e tratamento, se necessário.
*   Avaliação da necessidade de normalização ou padronização dos dados para otimizar o desempenho dos modelos.

### 2. Implementação de Algoritmos

*   Divisão do dataset em conjuntos de treino (70%) e teste (30%).
*   Implementação e treinamento de 5 algoritmos de classificação:
    *   K-Nearest Neighbors (KNN)
    *   Support Vector Machine (SVM)
    *   Random Forest
    *   Naive Bayes (GaussianNB)
    *   Regressão Logística
*   Avaliação detalhada de cada modelo utilizando métricas completas: acurácia, precisão, recall, F1-score e matriz de confusão.

### 3. Otimização

*   Aplicação de técnicas de otimização de hiperparâmetros, como Grid Search ou Randomized Search, para encontrar as melhores configurações para cada algoritmo.
*   Re-treinamento dos modelos com os hiperparâmetros otimizados.
*   Comparação da performance dos modelos antes e depois da otimização para demonstrar a melhoria.

### 4. Interpretação e Insights

*   Análise aprofundada dos resultados obtidos por cada modelo.
*   Identificação da importância das features (características) para a classificação.
*   Geração de recomendações para a aplicação prática da solução e possíveis melhorias futuras.

### 5. Geração de Gráficos e Relatório

*   Criação de gráficos e visualizações adicionais para ilustrar os resultados e insights.
*   Elaboração de um relatório detalhado contendo todas as análises, metodologias e conclusões do projeto.

### 6. Dashboard Resumo

*   Desenvolvimento de um dashboard interativo para apresentar um resumo visual dos principais resultados e métricas de desempenho dos modelos.


## 🗃 Histórico de lançamentos

* 0.1.0 - 19/06/2025
    *

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>


