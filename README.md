<div style="display:inline_block">
    <img align="left" height="110" width="200" alt="PostgreSQL" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg">
</div>

# PostgreSQL
Sintaxe e características do sistema gerenciador de banco de dados PostgreSql.

<br>

## INTRODUÇÃO
* O PostgreSQL é sistema gerenciador de banco de dados relacional de código aberto.
* É banstante robusto e seguro, sendo totalmente transacional, o que possibilita a realização de mudanças estruturais com a garantia de restauração total e com segurança.
* Possui suporte a tipos variados de dados como: JSON, XML, objetos geométricos, hierarquias, tags e matrizes.
* Além disso é fácil de usar, é bastante confiável e rápido.

## TIPOS DE DADOS

> ### Tipo numerico

| TIPO | VALOR EM BYTES | MENOR VALOR | MAIOR VALOR |
|-------------|-------------|-------------|-------------|
| A (Ei)      | F (Éf)      | K (Kei)     | P (Pi)      | 
| B (Bi)      | G (Dji)     | L (Él)      | Q (Quiu)    | 
| C (Ci)      | H (Eitch)   | M (Em)      | R (Ár)      |  
| D (Di)      | I (Ai)      | N (En)      | S (És)      | 
| E (I)       | J (Djei)    | O (Ôu)      | T (Ti)      |  

> ### Tipo string

> ### Tipo boolean

> ### Tipo autoincremental

> ### Tipo data

> ### Tipo full text search
* São tipos de dados que auxiliam na através de coleções na linguagem do postgreSQL, procurando as semelhanças das consultas.

> ### Tipo xml

> ### Tipo json

> ### Tipo array
* Define um campo como forma de matriz multidimensional de tamanho variável. As matrizes podem ser de qualquer tipo onde se define o tamanho e qual tipo de dado a matriz armazena.
* Estrutura:
  - tipo [n] [n]

> ### Tipo composto
* Descreve a estrutura de uma linha ou registro, dessa forma um campo pode ser de um tipo de uma outra tabela inteira.

> ### Tipo personalizado
* Com o comando *create type* é possível criar tipos de dados personalizados, ou seja, um novo tipo de campo. Esse tipo pode ser composto por vários campos ou por uma lista de valores.