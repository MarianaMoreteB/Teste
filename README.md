# Teste Engenharia de Dados
Repositório criado para armazenar o Teste de Engenharia de Dados

1. Para realização do teste foi utilizado um Database Type Ecommerce disponibilizado em https://uibakery.io/sql-playground.
2. Para melhor entendimendo do database, foi realizado um diagrama DBML, disponibilizado dentro desde repositório.
3. Foi criado um Notebook, no Databricks Community, disponibilizado neste repositório em formato .dbc,para a realização das demais atividades.
4. Inicialmente, foram setadas as credenciais para conexão JDBC com o Database, bem como os nomes das tabelas presentes. As quais, foram lidas e armazanadas, em primeiro momento, em dataframes.
5. As tabelas lidas foram armazenadas em formato parquet dentro do Databricks.
6. Foi criada uma logica Merge, para cada uma das tabelas, a fim de atualizá-las dentro do Databricks, a partir das tabelas JDBC lidas.
7. Foram realizadas análises a respeito dos dados disponibilizados. Sendo elas:
7.1. Qual país possui a maior quantidade de itens cancelados?
7.2. Qual o faturamento da linha de produto mais vendido, considere como os itens Shipped, cujo o pedido foi realizado no ano de 2005?
7.3. Nome, sobrenome e e-mail dos vendedores do Japão, o local-part do e-mail deve estar mascarado.
8. Por fim, os resultados das análises realizadas em 7. foram salvos em delta no Databricks.
