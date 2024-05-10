# SQL-COALESCE

SELECT *,
       COALESCE(column1, 'N/A') AS column1_coalesced,
       COALESCE(column2, 0) AS column2_coalesced
FROM table_name;
