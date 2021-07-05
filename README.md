Gazin Pontential CRUD
Este é o escopo do projeto base para o teste de avaliação para o ingresso de novos desenvolvedores junto a Gazin<Tech>

O projeto consiste em uma aplicação onde o candidato deverá desenvolver uma aplicação na *linguagem que desejar*, criando um Backend e um Frontend  que deverá ser interligados através de uma API REST JSON.
  
O propósito do teste é analisar boas práticas, lógica de programação, boas práticas, reaproveitamento de código e conhecimento geral de tecnologias utilizadas.

# O Backend
Você deverá desenvolver uma API RESTful na que utilize os métodos (​GET​, ​POST​, ​PUT/PATCH​, ​DELETE​).

# O Frontend
UI/UX fica a critério do desenvolvedor porém deverá ser SPA (single-page
application) e atender o consumo de todos endpoints da API 

# Especificação
Monte uma base de desenvolvedores com a seguinte estrutura:

```
nome: varchar
sexo: char
idade: integer
hobby: varchar
datanascimento: date
```

Utilize o ​banco de dados​ de sua preferência para armazenar os dados que a API irá
consumir.

# API endpoints

```
GET /developers
Codes 200
```
Retorna todos os desenvolvedores

```
GET /developers?
Codes 200 / 404
```
Retorna os desenvolvedores de acordo com o termo passado via querystring e
paginação

```
GET /developers/{id}
Codes 200 / 404
```
Retorna os dados de um desenvolvedor

```
POST /developers
Codes 201 / 400
```
Adiciona um novo desenvolvedor

```
PUT /developers/{id}
Codes 200 / 400
```
Atualiza os dados de um desenvolvedor

```
DELETE /developers/{id}
Codes 204 / 400
```
Apaga o registro de um desenvolvedor


# Entrega
Desejável aplicação e o banco deve rodar em docker

# O que será avaliado
- Estrutura do código
- Lógica de progamação
- Clean Code
- Teste Unitários


Após finalizado enviar por e-mail o link do projeto no github, com explicação no README.
