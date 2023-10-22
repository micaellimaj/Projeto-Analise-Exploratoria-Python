# Análise Exploratória de Dados Socioecionônicos da População Global
Para a realização desse projeto foram utilizados diferentes conjuntos de dados. Podemos com os bancos de dados, gerar visualizações relevantes sobre o histórico de crescimento populacional, comparação entre os dados e entender como anda o funcionamento socioeconômico global, assim gerando conclusões interessantes a respeito dos dados. Além de utilizarmos técnicas de manipulação e tratamento dos dados para o formato ideal, que seria aquele em que podemo trabalhar e gerar bons resultados de acordo com o objetivo da análise. Nesse projeto, meu foco foi muito a parte visual e na geração de insights através da plotagem de diversos gráficos, com a realiação desse trabalho é possível notar que uma boa manipulação e tratamento dos dados faz toda diferenças no processo anterior a análise e geração de insights.

Os dados trabalhados nesse projeto podem ser encontrados nos seguintes links:

1. Primeiro Conjunto de dados:  https://www.kaggle.com/datasets/rajkumarpandey02/2023-world-population-by-country
2. Segundo Conjunto de dados: https://www.dadosmundiais.com/america/index.php
3. Terceiro Conjunto de dados:  https://pt.wikipedia.org/wiki/Demografia_do_Brasi
4. Quarto Conjunto de dados: https://pt.wikipedia.org/wiki/Demografia_do_Brasil;

## Tecnologias utilizadas:

* <img src="https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=yellow1" alt="icon python" > 
* <img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252" alt="icon colab">

## Atributos dos dados:

O **1ª conjunto de dados** possui os seguintes atributos:

*   **place**: número do lugar;
*   **pop1980**: população neste ano;
*   **pop2000**: população neste ano;
*   **pop2010**: população neste ano;
*   **pop2022**: população neste ano;
*   **pop2023**: população prevista para este ano;
*   **pop2030**: população prevista para este ano;
*   **pop2050**: população prevista para este ano;
*   **country**: Nome do país;
*   **area**: Área Por Km;
*   **landAreaKm**: Área do terreno por km;
*   **cca2**: valores únicos;
*   **cca3**: valores únicos;
*   **netChange**: Mudança de rede %;
*   **growthRate**: Taxa de crescimento;
*   **worldPercentage**: % de crescimento mundial;
*   **density**: Densidade por Km;
*   **densityMi**: densidade em milhas quadradas;
*   **rank**: Classificação do país.

O **2ª Conjunto de dados** possui os seguintes atributos:

*   **País**: nome do país correspondente;
*   **PBI(bi R$)**: O produto interno bruto representa a soma de todos os bens e serviços finais produzidos numa determinada região, durante um período determinado;
*   **Taxa de endividamento**: taxa de quanto o país está em dívida econômica;
*   **Taxa de desemprego**: se refere a desocupação oficial no país;
*   **Taxa de inflação**: é um aumento geral nos preços de bens e serviços em uma economia;
*   **Índice de corrupção**:A escala varia de 0 a 100, sendo que quanto maior a pontuação, mais massiva a corrupção.

O **3ª Conjunto de dados** possui os seguintes atributos:

*   **Região**: Refere-se as Regiões brasileiras, que são cinco: Norte, Nordeste, Centro-Oeste, Sudeste e Sul;
*   **Estados**: Refere-se aos Estados do país referentes a sua Região;
*   **Municípios**: Traz a quantidade de municípios por Região;
*   **População(2022)[5]**: Traz a quantidade total de pessoas por região em 2022.

O **4ª Conjunto de dados** possui os seguintes atributos:

*  **País**: refere-se a um pequeno grupo de países: Brasil, Reino Unido, México e Nigéria;
*   **Crianças(de 0 a 14 anos)**: Traz a porcentagem de valores da população de crianças de determinado país;
*   **Jovens(de 15 a 24 anos)**: Traz a porcentagem de valores da população jovem por país;
*   **Adultos(de 25 a 64 anos)**: Traz a porcantagem de valores de da população de adultos por país;
*   **Idosos(a partir de 65 anos)**: Traz a porcentagem de valores da população idosa de acordo com o país.

## Desenvolvimento

Foram aplicadas diversas técnicas de análise de dados para o desenvolvimento desse projeto, como:

* Importação, tratamento e manipulção de diferentes tipos de dados, como csv, json e excel.
* Resolução de problemas nos dados, como valores faltantes ou em formato incorreto.
* Separação dos dados para melhor visualização dos gráficos.
* Utilização de diversas gráficos como o de barras, setores, linhas e área.
* Uso de gráficos para análisar a dispersão dos valores, como gráfico de dispersão, box plot e mapa de calor.
* Utilização de visualizações gráficas interativas.
* Uso de mapas para mostrar os atributos referentes a cada país.
* Geração de insights relevantes com a análise de diferentes gráficos.

## Importações Python:

```
from IPython.display import Image, display
import json
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import numpy as np
import plotly.express as px
```




