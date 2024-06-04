Desafio de modelagem de dados em star schema da DIO.

Para o desafio foi utilizado a planilha Financials fornecido pelo Power BI e criado um Star Schema.
O esquema para esta desafio consiste em, por meio da planilha principal, criar demais tabelas com assuntos específicos.
Sendo assim, conforme a orientação das aulas do desafio, foi criado uma tabela Fato de Vendas ligada a outras cinco tabelas Dimensão, sendo elas: Produtos Detalhes, Descontos, Calendário, Detalhes, Produtos

Para a ligação da tabela Fato com as demais foi realizado a criação de um ID para cada produto, sendo esta informação criada com a ferramente de Colunas condicionais.

Na tabela D_Produtos, foi utilizado as colunas de agregação, onde foi realizado os cálculos solicitados pelo desafio.

A tabela D_Calendário foi criada por meio da tabela Financials, aumentando a granularidade utilizando a ferramenta de transformação de dados e criando colunas a partir da coluna de data, fazendo as devidas formatações para pegar as informações solicitadas. 

A imagem demonstra como ficou a relação entre as tabelas em formato Star Schema.