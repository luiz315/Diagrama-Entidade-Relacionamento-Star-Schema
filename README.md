
# Diagrama de Entidade e Relacionamento Star Schema

## Projeto

O Projeto consiste em criar um modelo de "Banco de dados", Visando apresentar o modelo Star Schema a partir do exemplo abaixo 

<img src="imagens/projeto.jpg" alt = "Imagens do projeto">

Como podemos ver a estrutura acima utiliza o modelo 3NF que permite relacionamentos mais complexos e é muito utilizado para processamento transacional, quando se trata de processamento analítico onde você precisa além de armazenar e recuperar esses dados rapidamente, mas também categorizar e separar esses dados, o modelo mais recomendado e utilizado é o modelo Star Schema ou Esquema Estrela.

## Star Schema
O Star Schema foi desenvolvido em 1996 pelo professor e pesquisador Ralph Kimball, ele surgiu pela necessidade de analisar a abundância de dados que vinham crescendo vertiginosamente na década de noventa.

#### Características
- Custo
- Desempenho
- Simplicidade
#### Custo 
Na década de noventa não existia o conceito de armazenamento na nuvem como se tem hoje em dia então o fato de trabalhar com menos dados e de forma mais eficiente impulsionaram a popularidade do modelo.

#### Desempenho 
Como já foi dito acima, o fato de se trabalhar com uma menor quantidade de dados aumentava o desempenho, trazendo uma visão muito positiva para o esquema na época.

#### Simplicidade

A simplicidade do modelo se dá ao fato de poder fazer consultas muito poderosas usando conceitos mais simples dá, Ciências de Dados como os famosos "Joins" das linguagens mais utilizadas pelos SGBDs.

## Como Funciona 

O star Schema consiste em criar uma tabela principal, chamada tabela fato onde vamos mostrar nossa base de dados utilizando essa tabela fato como centro do nosso esquema, onde as outras tabelas se relacionam apenas com a tabela fato e não se relacionam entre si, essas tabelas são chamadas de tabela dimensão.

## Demonstração 

Abaixo podemos ver a demonstração do nosso Star Schema. 

<img src="imagens/Star_Schema_Dio_Project.jpg" alt = "Star Schema">

Como conseguimos ver acima existe uma tabela central chamada professor que se relaciona com todas as outras tabelas deixando as informações do nosso banco de dados sem redundâncias.


