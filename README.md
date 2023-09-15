# PEL 309 - Ciência de Dados - Entrega das Atividades de Sala

## Para executar os notebooks

1. Utilize a versão correta do Python (3.11.2)
2. Instale as dependências utilizando o `pip`:
```bash
pip install -r requirements.txt
```
3. Execute o Jupyter Notebook

**Nota:** Os notebooks já estão com os dados de execução, portanto, não é necessário executá-los novamente. Se desejar é possível analisar os notebooks desse repositório diretamente no GitHub.

## Organização do repositório.

1. Notebooks com as atividades:
   1. Se encontram na pasta [notebooks](./notebooks/)
   2. Estão numerados de forma sequencial e separados por aula da seguinte forma: `<numero_sequencia>_<descricao>_aula_<numero_aula>.ipynb`
2. Arquivos adicionais:
   1. Arquivos de Dados: [police dataset](./data/police.csv)
   2. Script de ETL desenvolvido durante a [primeira atividade](./notebooks/1_etl_aulas_2_e_3.ipynb) e utilizado em outras atividades: [etl script](./notebooks/etl/main.py)
   3. Infográfico utilizado na [atividade de visualização](./notebooks/4_visualizacao_aula_6.ipynb): [infografico](./visualizacao_aula_5_ifografico.png).

### Organização das Atividades

| Atividade | Notebook                                                               |
| --------- | ---------------------------------------------------------------------- |
| Aulas 2 e 3         | [1_etl_aulas_2_e_3.ipynb](./notebooks/1_etl_aulas_2_e_3.ipynb)         |
| Aula 4         | [2_etl_aula_4.ipynb](./notebooks/2_etl_aula_4.ipynb)           |
| Aula 5         | [3_analise_descritiva_aula_5.ipynb](./notebooks/3_analise_descritiva_aula_5.ipynb)           |
| Aula 6         | [4_visualizacao_aula_6.ipynb](./notebooks/4_visualizacao_aula_6.ipynb) |
| Aulas 7 e 8         | [5_modelos_de_aprendizado_aula_7_e_8.ipynb](./notebooks/5_modelos_de_aprendizado_aula_7_e_8.ipynb) |



## Técnicas não vistas em aula

Para realizar algumas análises propostas pelas atividades utilizei adicionalmente duas técnicas que não foram vistas em aula, sendo elas:

1. Mutual Information Score
   - Utilizada na [atividade 1](./notebooks/1_etl_aulas_2_e_3.ipynb)
   - Com a finalidade de encontra correlações não lineares
   - [mutual information - artigo Kaggle](https://www.kaggle.com/code/ryanholbrook/mutual-information)
2. Análise de Coeficientes de Regressão Linear
   - Utilizada também na [atividade 1](./notebooks/1_etl_aulas_2_e_3.ipynb)
   - Com a finalidade de entender os atributos mais relevantes que definem a predição do nível do resultado da parada.  
3. Análise de Topologia da Árvore de Decisão
   - Utilizada também na [atividade 1](./notebooks/1_etl_aulas_2_e_3.ipynb)
   - Com a finalidade de entender os atributos mais relevantes que definem a predição se uma pessoa vai ser presa ou não.