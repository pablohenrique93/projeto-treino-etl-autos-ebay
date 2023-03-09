# Projeto Treino


#### A base de dados 
O dataset utilizado na realização deste projeto foi feito através de um “scraping” em 2016 a partir do ebay-Kleinanzeigan (Alemanha). O dataset contém 21 colunas com mais de 37 mil linhas de carros usados para venda.


## Processos realizados


#### Nível Infra
- O Arquivo tratado final foi salvo no MongoDB atlas

#### Nível Pandas
- Extração para um dataframe;
- Verificação de inconsistências;
- Drop de colunas;
- Renomeação e tradução de colunas;
- Renomeação e tradução dos dados dentro das colunas;
- Verificação de valores nulos presentes no dataframe;
- Realização de insights, utilizando filtros e Group By com auxílio de plots(Data Visualization)

#### Nível PySpark
- Montagem da estrutura do DataFrame utilizando StructType;
- Conversão do dataframe de Pandas para PySpark;
- Contagem de linhas totais do dataset assim como a dropagem das linhas duplicadas;
- Padronização de valores dentro das colunas;
- Conversão dos tipos das colunas;
- Concatenação de colunas;
- Drop de colunas;
- Reordenação de colunas;
- Análises utilizando Group By e filtros;
- Desenvolvimento de insights utilizando SparkSQL
