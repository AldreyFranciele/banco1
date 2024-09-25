# banco1
````sql
require 'redcarpet'
markdown = Redcarpet.new("Hello word!")
puts markdown.to_html
````


````sql 
-- criando um banco de dados
create database trabalho;

````

```sql
-- usar banco de de dados
use trabalho;

````

````
-- criar tabela
create table cliente ex 1 (
id_cliente int primary key,
nome_cliente varchar(100),
email_cliente varchar(150),
data_nascimento date,
telefone_cliente varchar (15)
);

````
````
create table produto ex 2 (
id_produto int primary key,
nome_produto varchar (100),
preco_produto decimal (10,2)
);
````
````
create table faturas ex 3  (
id_fatura int primary key,
data_criacao date,
valor_fatura decimal (10,2)
);
