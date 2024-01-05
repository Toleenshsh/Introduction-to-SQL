# Introduction-to-SQL
Introduction to SQL-project

overview:
"Investigate a Relational Database". In this project, you will be acting as an analyst and will be tasked with providing summary analyses of a rental transactions database.
project:
SELECT r.name region, s.name rep, a.name account
FROM sales_reps s
JOIN region r
ON s.region_id = r.id
JOIN accounts a
ON a.sales_rep_id = s.id
ORDER BY a.name;
