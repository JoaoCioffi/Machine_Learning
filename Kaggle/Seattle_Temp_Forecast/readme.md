COLAB DIRECT LINK: https://colab.research.google.com/drive/1eCwMbdf0AA6agy0YR8wRxuK_556msyal?usp=sharing


# Introdução ao Problema:

> Neste estudo de caso faremos a modelagem para prever a máxima temperatura para o dia seguinte na cidade de Seattle-WA utilizando a base de dados NOAA (https://www.ncdc.noaa.gov/cdo-web/). Neste aspecto temos acesso ao histórico das temperaturas máximas registradas ao longo dos anos (série temporal), as temperaturas registradas nos últimos dois dias e uma variável estimada através de previsões de tempo comuns.

> O caso em questão será modelado através de um algoritmo supervisionado (problema de regressão), pois temos o histórico tanto das features quanto do target (temperaturas) que precisamos prever. Além disso, esta é uma tarefa de regressão devido ao fato de os valores para o nosso target são numéricos contínuos (isto é, não são números inteiros que designam classes distintas como em problemas de classificação).

> Roadmap
>> Antes de irmos direto à programação, devemos estabelecer um breve guia para nos manter no caminho certo. As etapas a seguir formam a base para qualquer workflow de machine learning assim que tivermos um problema e um modelo em mente:
1. Declarar a pergunta do problema e determinar os dados necessários;
2. Adquirir os dados em um formato acessível;
3. Identificar e corrijir os pontos/anomalias de dados ausentes conforme necessário;
4. Preparar os dados para o modelo;
5. Estabelecer um baseline model que você pretende superar;
6. Treinar o modelo nos dados de treinamento;
7. Fazer previsões sobre os dados de teste;
8. Comparar as previsões com as metas conhecidas do conjunto de testes e calcular as métricas de desempenho;
9. Se o desempenho não for satisfatório, ajustar o modelo, adquirir ou criar mais dados (feature engineering) ou ainda tentar uma técnica de modelagem diferente;
10. Interpretar o modelo e relatar os resultados visualmente e/ou numericamente;

> Aquisição dos dados:
>> Para usar um exemplo realista, tomaremos como base dados meteorológicos registrados em Seattle de 2011~2017 através do NOAA Climate Data Online. Geralmente, cerca de 80% do tempo gasto na análise de dados é para limpar e recuperar dados, mas essa carga de trabalho pode ser reduzida ao encontrar fontes de dados de alta qualidade. A ferramenta NOAA é surpreendentemente fácil de usar e os dados de temperatura podem ser baixados como arquivos csv limpos que podem ser analisados em linguagens como Python ou R. O arquivo de dados completo está disponível para download para aqueles que desejam acompanhar: https://drive.google.com/file/d/1pko9oRmCllAxipZoa3aoztGZfPAD2iwj/view


---
# Main Libraries
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

<div style="display: inline_block"><br> 
    
</div>

---
