```sql 
require 'redcarpet' 
markdown = 
Redcarpet.new("Hello World!")
puts markdown.to_html
```

```sql
-- criando um banco de dados
create database trabalho;
```

```sql
-- usar o banco de dados 
use trabalho;
```


```sql
--Exercicios de 1 a 3 
--Exercicio 1
-- criar tabela 
create table clientes (
id_cliente int primary key,
nome_cliente varchar (100),email_cliente varchar(150),data_nascimento date,
telefone_cliente varchar (15)
);
```
```sql
--exercicio 2
-- criar tabela
create table produtos (
id_produtos int primary key,
nome_produto varchar (100),
preco_produto decimal(8,2)
);
```
```sql
--exercicio 3
-- criar tabela 
create table fatura (
id_fatura int primary key,
data_criacao date,
vaalor_fatura decimal (10,2)
);
```
```sql
--exercicos de 1 a 20
-- exercicio 1
-- criando uma tabela 
create table funcionaario (
id int primary key
Nome varchar(20),
sobrenome varchar(100),
salario real 
);

````
````sql
-- ex 2
-- criando uma tabela
create table funcionarios (
id int primary key
Nome varchar(20),
sobrenome varchar(100),
salario real 
);
-- -- incluir um atributo em uma tabela existente
alter table funcionarios add dataNacimento date;
````
````sql
-- ex 3
create table departamentos (
codigo int  primary key
nome varchar (100)
);
````
```sql
-- ex 4
-- criando uma tabela 
create table funcionario (
id int primary key
Nome varchar(20),
sobrenome varchar(100),
salario real 
);
-- adicionando um atributo a uma tabela existente
alter table funcionario add IDDepartamento date;
```
```sql
-- exer 5 
 -- criando tabela projeto
create table projeto (
codigo int primary key,
nome varchar (100)
);

```

```sql
-- ex 6
create table alocacoes (
codigo primary key 
); 
```
```sql
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
```
```sql
--exer 8 
-- criando tabela 
create table clientes (
id_cliente int primary key,
nome_cliente varchar (100),email_cliente varchar(150),data_nascimento date,

); 
```
```sql
-- ex 9 
criando tabela projeto
create table projeto (
codigo int primary key,
nome varchar (100)
);
-- adicionando um atributo a uma tabela existente 
alter table projeto add IDCliente varchar (100);
```
````sql
-- ex 10
create table endereco(
codigo primary key
rua varchar(50)
cidade varchar(50)
cep  int 
);

```
````
````sql
--ex 11
-- criando uma tabela
create table funcionarios (
id int primary key
Nome varchar(20),
sobrenome varchar(100),
salario real 
);
alter table funcionarios add IDEndereco int;
`````

````sql
-- ex 12

-- criando tabela 
create table clientes (
id_cliente int primary key,
nome_cliente varchar (100),email_cliente varchar(150),data_nascimento date,

); 
-- alterando o nome do atributo na tabela 
alter table clientes rename column nome_cliente to NomeEmpresa;

````
````sql
-- ex 13
-- criando uma tabela 
create table pedidos (
codigo int primary key,
dataPedido date
);
`````
````sql
-- ex 14
-- criando uma tabela 
create table pedidos (
codigo int primary key,
dataPedido date
);
--adicionando um atributo a uma tabela existente
alter table pedidos add IDClientes int;

`````
````sql
-- ex 15
-- criando uma tabela 
create table intenspedidos (
codigo primary key,
idPedidos int,
IDProduto int
); 


````
````sql
-- ex 16
create table Produtos (
ID int,
NomeProduto Varchar(100),
QuantidadeProduto real,
ValorProduto decimal(100,100)
);
````
````sql
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
````sql
-- ex 18
-- criando uma tabela
create table estoques(
 ID_produtos int primary key,
 quantidade_produtos
 );


````
````sql
--ex 19 
--criando uma tabela
create table estoques(
 ID_produtos int primary key,
 quantidade_produtos
 );
--adicionando um atributo a uma tabela existente 
alter table estoque add IDProduto int;

````
````sql
-- ex 20 
-- criando a tabela vendas
create table vendas (
codigo int primary key,
dataVendas date
);
````
````sql
-- ex 21
 -- criando a tabela vendas
create table vendas (
codigo int primary key,
dataVendas date
);

alter table vendas add IDCliente varchar (100)
````

