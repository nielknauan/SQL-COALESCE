# SQL-COALESCE

SELECT *,
       COALESCE(column1, 'N/A') AS column1_coalesced,
       COALESCE(column2, 0) AS column2_coalesced
FROM table_name;

*Neste exemplo:

column1 e column2 são os nomes das colunas da tabela table_name.
COALESCE(column1, 'N/A') retorna o valor de column1, mas se for nulo, retorna 'N/A'.
COALESCE(column2, 0) retorna o valor de column2, mas se for nulo, retorna 0.
A cláusula SELECT * seleciona todas as colunas da tabela, enquanto COALESCE é usada para fornecer valores padrão para as colunas que podem ser nulas.
