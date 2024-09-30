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
-- ex 7
-- criando uma tabela
create table funcionarios (
id int primary key
Nome varchar(20),
sobrenome varchar(100),
salario real 
);
-- alterar nome da coluna
alter table funcionarios rename column sobrenome to apelido;

````
````
--exer 8 
-- criando tabela 
create table clientes (
id_cliente int primary key,
nome_cliente varchar (100),email_cliente varchar(150),data_nascimento date,

);
````
````
-- ex 9 
criando tabela projeto
create table projeto (
codigo int primary key,
nome varchar (100)
);
-- adicionando um atributo a uma tabela existente 
alter table projeto add IDCliente varchar (100);
````
````
-- ex 10
create table endereco(
codigo primary key
rua varchar(50)
cidade varchar(50)
cep  int 
);
````
````
--ex 11
-- criando uma tabela
create table funcionarios (
id int primary key
Nome varchar(20),
sobrenome varchar(100),
salario real 
);
alter table funcionarios add IDEndereco int;
````
````
-- ex 12

-- criando tabela 
create table clientes (
id_cliente int primary key,
nome_cliente varchar (100),email_cliente varchar(150),data_nascimento date,

); 
-- alterando o nome do atributo na tabela 
alter table clientes rename column nome_cliente to NomeEmpresa;
`````
````
-- ex 13
-- criando uma tabela 
create table pedidos (
codigo int primary key,
dataPedido date
);
````
````
-- ex 14
-- criando uma tabela 
create table pedidos (
codigo int primary key,
dataPedido date
);
--adicionando um atributo a uma tabela existente
alter table pedidos add IDClientes int;
````
````
-- ex 15
-- criando uma tabela 
create table intenspedidos (
codigo primary key,
idPedidos int,
IDProduto int
);
````
````
-- ex 16
create table Produtos (
ID int,
NomeProduto Varchar(100),
QuantidadeProduto real,
ValorProduto decimal(100,100)
);
````
````
--ex 17 
-- criando uma tabela
create table produtos (
id_produtos int primary key,
nome_produto varchar (100),
preco_produto decimal(8,2)
);
-- Renomeando um atributo da tabela existente 
alter table produto rename column nome_produto to DescricaoProduto;
````
````
-- ex 18
-- criando uma tabela
create table estoques(
 ID_produtos int primary key,
 quantidade_produtos
 );
 ````
 ````
 --ex 19 
--criando uma tabela
create table estoques(
 ID_produtos int primary key,
 quantidade_produtos
 );
--adicionando um atributo a uma tabela existente 
alter table estoque add IDProduto int;
````
````
-- ex 20 
-- criando a tabela vendas
create table vendas (
codigo int primary key,
dataVendas date
);
````
````
-- ex 21
 -- criando a tabela vendas
create table vendas (
codigo int primary key,
dataVendas date
);

alter table vendas add IDCliente varchar (100)




