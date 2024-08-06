# Implementação da Árvore de Decisão J48

## Descrição

Este projeto utiliza o dataset de diabetes disponível no Kaggle para implementar uma árvore de decisão J48. O objetivo é classificar pessoas como positivas ou negativas para diabetes com base em suas características.

## Instalação e Dependências

### Ferramentas Necessárias

- Google Colab
- Python 3.x

### Bibliotecas Utilizadas

- pandas
- seaborn
- scikit-learn (sklearn)
- scipy
- sqlite3
- matplotlib

### Como Instalar

1. Clone este repositório ou faça o download dos arquivos.
2. Acesse [este link](https://www.kaggle.com/datasets/mathchi/diabetes-data-set) e baixe o dataset do diabetes em formato `.arff` ou `.csv`.
3. Faça o upload do arquivo do dataset para o seu ambiente do Google Colab.
4. Instale as bibliotecas necessárias executando o seguinte comando no seu notebook:

    ```python
    !pip install pandas seaborn scikit-learn scipy sqlite3 matplotlib
    ```

## Dataset

O dataset utilizado contém informações de pacientes que testaram positivo ou negativo para diabetes. Algumas características do dataset incluem:

- **Número de Instâncias:** 768
- **Número de Atributos:** 9
- **Formato:** `.arff` ou `.csv`

### Carregamento do Dataset

O dataset é carregado no Colab e preparado para análise e modelagem. Certifique-se de que o arquivo do dataset esteja corretamente carregado no ambiente.

## Pré-processamento

As etapas de pré-processamento incluem:

1. **Tratamento de Valores Faltantes:** Substituição de valores ausentes.
2. **Normalização:** Normalização dos dados para melhorar a performance do modelo.
3. **Divisão dos Dados:** Separação dos dados em conjuntos de treinamento e teste.

## Implementação da Árvore de Decisão

O algoritmo J48 foi utilizado para a implementação da árvore de decisão. O processo incluiu:

- **Treinamento:** O modelo foi treinado com o conjunto de dados de treinamento.
- **Teste:** O modelo foi avaliado utilizando o conjunto de dados de teste.
- **Avaliação:** Métricas como acurácia, precisão, recall e F1-score foram usadas para avaliar o desempenho do modelo.

## Resultados

Os principais resultados obtidos com a implementação do J48 incluem:

- **Acurácia:** 0.76
- **Precisão:** 0.77
- **Recall:** 0.76
- **F1-Score:** 0.76

### Detalhes das Métricas

| Classe | Precision | Recall | F1-Score | Suporte |
|--------|-----------|--------|----------|---------|
| 0      | 0.71      | 0.81   | 0.75     | 74      |
| 1      | 0.82      | 0.71   | 0.76     | 87      |

- **Acurácia:** 0.76
- **Macro Avg:** 0.76 (Precision), 0.76 (Recall), 0.76 (F1-Score)
- **Weighted Avg:** 0.77 (Precision), 0.76 (Recall), 0.76 (F1-Score)

(Adicione qualquer visualização ou gráfico que você tenha gerado)

## Conclusão e Próximos Passos

As principais conclusões a partir dos resultados são:

- A árvore de decisão J48 mostrou uma acurácia razoável de 76%, com métricas de precisão e recall equilibradas entre as classes.

Os próximos passos ou melhorias futuras podem incluir:

- Experimentar com outros algoritmos de machine learning para comparar desempenho.
- Aplicar técnicas de feature engineering para melhorar a qualidade dos dados.
- Aumentar o conjunto de dados para potencialmente melhorar a performance do modelo.

## Contato

Para dúvidas ou colaborações, entre em contato:

- **Nome:** Michael Lopes Cachina
- **Email:** (maycomcachina306@gmail.com)
- **LinkedIn:** (https://www.linkedin.com/in/michaelcachina/)
