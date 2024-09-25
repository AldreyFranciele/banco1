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

````
````
create table funcionarios ex 1 (
id int primary key,
nome varchar (20),
sobrenome varchar (100),
salario int
);

````
````
create table funcionarios ex 2(
id int primary key,
nome varchar (20),
sobrenome varchar (100),
salario int
);
alter table funcionarios add dataNascimento date; 

````
````
-- criando tabela departamemento ex 3
create table departamento (
codigo int primary key,
nome varchar (100)
);

````
````
ex 4
alter table funcionarios add IDDepartamento int;
````
````
-- criando tabela projeto ex 5
create table projeto (
codigo int primary key,
nome varchar (100)
);
````
````
create table alocacoes ex 6 (
codigo primary key 
);
````
````


