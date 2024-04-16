# Exemplo-Data-Warehouse-e-Data-Lake

<h2>Data Warehouse</h2>

O código gera e analisa dados simulados de vendas de produtos. Ele começa criando informações fictícias sobre produtos e vendas, como nomes, categorias, datas e valores de vendas. Esses dados são combinados em um único conjunto, simulando um armazém de dados.
Ao analisar as vendas por produto e por categoria, é possível entender o desempenho de diferentes tipos de produtos e identificar as categorias mais lucrativas. Isso ajuda na tomada de decisões sobre quais produtos priorizar ou em quais áreas investir mais recursos.
Além disso, ao examinar as tendências temporais das vendas, é possível identificar padrões sazonais, picos de demanda ou períodos de baixo desempenho. Essas informações são cruciais para o planejamento estratégico, permitindo ajustes na oferta de produtos e nas estratégias de marketing para maximizar as vendas.
Por fim, ao calcular o desempenho de cada produto, somando o valor total das vendas, é possível identificar os produtos mais rentáveis e aqueles que talvez necessitem de mais atenção ou promoção.

![imagem 1](https://github.com/Testorugo/Exemplo-Data-Warehouse-e-Data-Lake/assets/114782204/3196a42b-a294-476b-9aa5-29b8ae0f9917)
![imagem 2](https://github.com/Testorugo/Exemplo-Data-Warehouse-e-Data-Lake/assets/114782204/dbf87d7b-62ad-4849-b9ec-b0137fc24d8f)
![imagem 3](https://github.com/Testorugo/Exemplo-Data-Warehouse-e-Data-Lake/assets/114782204/970eeccd-8550-412b-b117-6048bed194f9)
![imagem 4](https://github.com/Testorugo/Exemplo-Data-Warehouse-e-Data-Lake/assets/114782204/eaf6810f-878f-4d4d-858e-2ed6a47b9e81)

<h2>Data Lake</h2>

O script do Data Lake realiza várias operações relacionadas à geração de dados aleatórios, armazenamento desses dados em arquivos CSV, e análise exploratória dos dados usando bibliotecas como pandas, matplotlib e seaborn.

Geração de Dados:
O primeiro trecho de código cria uma pasta chamada 'data_lake' se ela ainda não existir.
Define o número de arquivos a serem criados (num_files) e o número de linhas por arquivo (num_rows_per_file).
Em seguida, um loop cria dados aleatórios para três colunas (coluna1, coluna2, coluna3) e os armazena em dataframes do pandas.
Cada dataframe é então salvo como um arquivo CSV na pasta 'data_lake', e uma lista de tuplas contendo o nome do arquivo e o dataframe correspondente é mantida para referência posterior.

Análise dos Dados:
Após a geração dos dados, o script continua com a análise exploratória.
Cria uma conexão com um banco de dados SQLite usando SQLAlchemy.
Exibe as primeiras linhas do último dataframe gerado, que foi usado para inspeção inicial dos dados.
Fornece informações sobre o dataframe, como tipos de dados de cada coluna e a presença de valores nulos.
Mostra um resumo estatístico das colunas numéricas do dataframe, incluindo média, desvio padrão, mínimos e máximos.
Cria visualizações gráficas usando seaborn e matplotlib:
Um gráfico de dispersão entre coluna1 e coluna2.
Um histograma para a coluna1 com uma curva de densidade estimada (KDE).
Um boxplot para visualizar a distribuição da coluna1 agrupada por valores da coluna3.

![imagem 1](https://github.com/Testorugo/Exemplo-Data-Warehouse-e-Data-Lake/assets/114782204/226beacf-9cc6-4aba-a04c-28698fd44ea9)
![imagem 2](https://github.com/Testorugo/Exemplo-Data-Warehouse-e-Data-Lake/assets/114782204/49a19509-5772-479d-bbb6-a8a8035304e1)
![imagem 3](https://github.com/Testorugo/Exemplo-Data-Warehouse-e-Data-Lake/assets/114782204/a13e2b71-b4ae-433a-ac5d-433ce6693501)
![imagem 4](https://github.com/Testorugo/Exemplo-Data-Warehouse-e-Data-Lake/assets/114782204/69a58666-d86c-48e5-a9da-e1ee3924e0f0)
![imagem 5](https://github.com/Testorugo/Exemplo-Data-Warehouse-e-Data-Lake/assets/114782204/1b618871-f423-4685-a1d7-573cbb40fd01)
![imagem 6](https://github.com/Testorugo/Exemplo-Data-Warehouse-e-Data-Lake/assets/114782204/3389a162-3e4b-459b-9506-2550ca898a6f)





