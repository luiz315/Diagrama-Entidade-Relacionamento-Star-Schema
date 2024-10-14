# Diagrama de Entidade e Relacionamento Star Schema

## Projeto 

O projeto consiste em criar um modelo de "Banco de dados" 
sem necessariamente os dados, visando apresentar o modelo Star Schema a partir do exemplo abaixo. 

<img src="/Imagens/projeto.jpg">

Como podemos ver a estrutra acima utiliza o modelo 3NF que permite relacionamentos mais complexos e é muito utilizado para processamento transacional, quando se trata de processamento analítico onde você precisa  além de armazenar e recuperar esses dados rapidamente,mas também categorizar e separar esses dados,o modelo mais recomendado e utilizado é o modelo Star Schema ou Esquema Estrela.

## Star Schema
o Star Schema foi desenvolvido em 1996 pelo professor e pesquisador de dados Ralph Kimball,
ele surgiu pela necessidade de analisar abundância de dados que vinham crescendo vertiginosamente na década de noventa.

#### Características 
- Custo 
- Desempenho 
- simplicidade

#### Custo
Na década de noventa não existia o conceito de armazenamento na nuvem como tem hoje em dia
então o fato de trabalhar com menos dados e de forma mais eficiente impulsionaram a popularidade do modelo.

#### Desempenho

Como já foi dito acima,
 o fato de trabalhar com uma menor quantidade de dados aumentava o desempenho, trazendo uma visão muito positiva para o esquema na época.

#### Simplicidade 

A simplicidade do modelo se dá ao fato de poder fazer consultas muito poderosas usando conceitos mais simples dá, Ciências de Dados como os famosos "Joins" das linguagens mais utilizadas pelos SGBD.

##  Como funciona 

O Star Schema consiste em criar uma tabela principal,chamada tabela fato onde vamos montar nossa base de dados 
utilizando essa tabela fato como o centro do nosso esquema,onde as outras tabelas se relacionam apenas com a tabela fato
e não se relacionam entre si essas tabelas são chamadas de tabela dimensão.

## Demonstração 

Abaixo podemos ver a demonstração do nosso Star Schema.

<img src="/Imagens/Star_Schema_DIo_Project.jpg">

Como conseguimos ver acima existe uma tabela central chamada Professor que se relaciona comtodas as outras tabelas deixando as informações do nosso banco dados sem redundâncias.