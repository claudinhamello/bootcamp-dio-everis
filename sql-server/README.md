# SQL SERVER - Criando as suas primeiras consultas

## O que são SGBDs?

*Software que padroniza os bancos de dados.*

Diferente do Excel, o SGBD, ao proteger seus dados você consegue adicionar vários usuários para diferentes tarefas. Exemplo: Um usuário que seleciona, outro que exclui, outro que insere dados.

## Tipos de bancos de Dados

*Relacionais* - são sistemas que necessitam de grande confiabilidade dos dados. Exemplos: Controle de estoque; Controle de Vendas...

- SQL Server
- Oracle
- MySQL

*NoSQL* - São bancos para uma melhor performance, armazenam grande quantidade de dados com qualidade como por exemplo Big Data. Armazenam vídeos, imagens, geolocalização, links. Já possuem ferramentas prontas para consumir esse banco de dados. 

- MongoDB
- Neo4J
- Firebase

## Representações de um banco de dados relacional e consistência de dados

*E-comerce*

Produtos >>> Vendas <<< Clientes

Clientes:

- id: int
- Nome: varchar
- CPF: char
- Ativo: bit

Uma tabela num banco de dados é como o excel, possui linhas e colunas. As linhas são os registros e as colunas são as informações daquele registro. Como no exemplo acima, um cliente teria uma coluna id, outra coluna nome, e assim continuamente. Pra saber se o cliente está ativo ou não. O tipo da coluna seria o int, varchar, char. bit. Indicam qual informação será inserida ali.

int: inteiro

varchar: Caracteres alfanuméricos

char: são alfanuméricos

bit: informação que aceita apenas 0 ou 1, False or True.

## Atomicidade (nos sistemas relacionais)

Garante que todos os dados estejam corretos na hora da inserção de dados.

## Consistência dos dados

Para que um sistema de banco de dados sempre possa fornecer informações confiáveis aos usuários, o administrador deve filtrar algumas ações realizadas a fim de evitar a ocorrência de possíveis erros relacionados às mesmas.

Além disso, esse sistema deve ser capaz de receber informações de forma constante sem ter que sofrer alterações com a mesma frequência.

O banco de dados deve possibilitar a inserção de uma grande quantidade de dados sem que o mesmo precise ser alterado em sua estrutura.



