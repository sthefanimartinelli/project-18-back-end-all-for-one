
# Projeto All for One

O objetivo deste projeto foi praticar o uso de queries na linguagem SQL, utilizando o banco de dados relacional MySQL.

Foi utilizado a base de dados presente no arquivo northwind.sql e optou-se por utilizar contêiners para subir a aplicação. Foram criados arquivos no formato deasfionN.sql, sendo que cada um representa uma query executada no banco. Os demais arquivos foram desenvolvidos pela Trybe. 

Também utilizou-se o Workbench para visualização das tabelas e queries.

### Para iniciar o projeto:
- git clone git@github.com:sthefanimartinelli/project-18-back-end-all-for-one.git
- docker compose up
- docker exec -it all_for_one bash
- npm install

### Observação: 
As credencias de acesso ao banco de dados estão definidas no arquivo docker-compose.yml.

### Requisitos do projeto:
| Requisito | Descrição |
|-----------|-----------|
| 01 | Exiba apenas os nomes dos produtos da tabela 'products' |
| 02 | Exiba os dados de todas as colunas da tabela 'products' |
| 03 | Escreva uma query que exiba os valores da coluna que contém a primary key da tabela 'products' |
| 04 | Conte quantos registros existem na coluna 'product_name' da tabela 'products' |
| 05 | Monte uma query que exiba os dados da tabela 'products' a partir do quarto registro até o décimo terceiro |
| 06 | Exiba os dados das colunas 'product_name' e 'id' da tabela 'products' de maneira que os resultados estejam em ordem alfabética dos nomes |
| 07 | Mostre apenas os ids dos 5 últimos registros da tabela 'products' ordenados por 'id' |
| 08 | Faça uma consulta na tabela `employees` que retorne o nome completo da pessoa colaboradora (colunas `first_name` e `last_name`) com o nome `full_name` e também a localização completa (colunas `city`, `state_province` e `address`) com o nome `location`. |
| 09 | Mostre todos os valores da coluna 'notes' da tabela 'purchase_orders' que não são nulos |
| 10 | Mostre todos os dados da tabela 'purchase_orders' em ordem decrescente ordenados por 'created_by' em que o 'created_by' é maior ou igual a 3 |
| 11 | Exiba os dados da coluna 'notes' da tabela 'purchase_orders' em que seu valor de 'Purchase generated based on Order' é maior ou igual a 30 e menor ou igual a 39 |
| 12 | Mostre os resultados da coluna 'submitted_date' da tabela 'purchase_orders' em que a 'submitted_date' é do dia 26 de abril de 2006 |
| 13 | Mostre o resultado da coluna 'supplier_id' da tabela 'purchase_orders' em que o 'supplier_id' seja 1 ou 3 |
| 14 | Mostre os resultados da coluna 'supplier_id' da tabela 'purchase_orders' em que o 'supplier_id' seja maior ou igual a 1 e menor ou igual 3 |
| 15 | Mostre somente as horas, sem os minutos e os segundos, da coluna 'submitted_date' de todos registros da tabela 'purchase_orders' |
| 16 | Exiba os resultados da coluna 'submitted_date' da tabela 'purchase_orders' que estão entre '2006-01-26 00:00:00' e '2006-03-31 23:59:59' |
| 17 | Mostre os registros das colunas 'id' e 'supplier_id' da tabela 'purchase_orders' em que os 'supplier_id' sejam tanto 1, ou 3, ou 5, ou 7 |
| 18 | Mostre todos os registros da tabela 'purchase_orders' que tem o valor na coluna 'supplier_id' igual a 3 e o valor na coluna 'status_id' igual a 2 |
| 19 | Mostre a quantidade de pedidos que foram feitos na tabela 'orders' pelo 'employee_id' igual a 5 ou 6, e que foram enviados através do método coluna 'shipper_id' igual a 2 |
| 20 | Adicione à tabela 'order_details' um registro com 'order_id': 69, 'product_id': 80, 'quantity': 15.0000, 'unit_price': 15.0000, 'discount': 0, 'status_id': 2, 'date_allocated': NULL, 'purchase_order_id': NULL e 'inventory_id': 129 |
| 21 | Adicione com um único 'INSERT', duas linhas à tabela 'order_details' com os mesmos dados do requisito 20 |
| 22 | Atualize todos os dados da coluna 'discount', na tabela 'order_details', para 15. |
| 23 | Atualize os dados da coluna 'discount' da tabela 'order_details' para 30, onde o valor na coluna 'unit_price' seja menor que 10.0000 |
| 24 | Atualize os dados da coluna 'discount' da tabela 'order_details' para 45, onde o valor na coluna 'unit_price' seja maior que 10.0000 e o id seja um número entre 30 e 40 |
| 25 | Delete todos os dados na coluna 'unit_price' da tabela 'order_details' em que o valor seja menor que 10.0000 |
| 26 | Delete todos os dados na coluna 'unit_price' da tabela 'order_details' em que o valor seja maior que 10.0000 |
| 27 |  Delete todos os dados da tabela 'order_details' |
