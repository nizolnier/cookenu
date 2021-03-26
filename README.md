# Cookenu 🍳

<a id="en-readme"></a>
### English | [Português](#pt-readme)
Back-end project developed in Labenu's bootcamp \
Cookenu is a REST API to create recipes and make friends! 👩‍🍳

<a name="pt-menu"></a>
- [Documentation](#documentacao)
- [Getting Started](#steps)
- [Available Scripts](#en-scripts)
- [Features](#features)
- [Libraries and Frameworks](#libs)


<a id="documentation"></a>
## ✦ Documentation
- [Postman](https://documenter.getpostman.com/view/13242152/TzCJfVEu)
- [Endpoints](ENDPOINTS.md)

<a id="steps"></a>
## ✦ Getting Started
1- clone this repository

2- run this command
```
npm install
```
3- create .env file on the root directory of the project with this data:
```
// your database

DB_HOST =
DB_USER =
DB_PASSWORD = 
DB_DATABASE_NAME = 

//your key and time expire preferences

JWT_KEY =
JWT_EXPIRES_IN = 

//your cost preference

BCRYPT_COST = 
```
4- run this command

```
npm run setup
```
5- now this one
```
npm start
```
6- YOU'RE ICE CREAM IS READY!!!

<a id="en-scripts"></a>
## ✦ Available Scripts
* `npm run setup` to create tables
* `npm run start` to run the aplication
* `npm run dev` to run the aplication with hot reload

<a id="features"></a>
## ✦ Features
* Sign up
* Login
* Follow user
* Unfollow user
* Reset password
* Get all users
* Get your own profile
* Get another user's profile
* Delete user
* Publish a recipe
* Get all recipes
* Get a specific recipe

<a id="libs"></a>
## ✦ Libraries and Frameworks:
* cors
* express
* knex
* mysql
* dotenv
* uuid
* jsonwebtoken
* bcryptjs
* nodemailer
* dayjs

*Developed with 🧡 by Nicole Zolnier*

-------
<a id="pt-readme"></a>
### [English](#en-readme) | Português
Projeto back-end desenvolvido no bootcamp da Labenu. \
Cookenu é uma API REST para criar receitas e fazer amigos! 👩‍🍳

<a name="pt-menu"></a>
- [Documentação](#documentacao)
- [Primeiros Passos](#passos)
- [Scripts Disponíveis](#pt-scripts)
- [Funcionalidades](#funcionalidades)
- [Bibliotecas e Frameworks](#bibliotecas)


<a id="documentacao"></a>
## ✦ Documentação
- [Postman](https://documenter.getpostman.com/view/13242152/TzCJfVEu)
- [Endpoints](ENDPOINTS.md)

<a id="passos"></a>
## ✦ Primeiros Passos
1- clone ese repositório

2- rode o comando abaixo
```
npm install
```
3- crie um arquivo .env na raíz do projeto com esses dados:
```
//dados do seu banco

DB_HOST =
DB_USER =
DB_PASSWORD = 
DB_DATABASE_NAME = 

//suas preferências para key e expire

JWT_KEY =
JWT_EXPIRES_IN = 

//suas preferências de cost

BCRYPT_COST = 
```
4- rode esse comando:

```
npm run setup
```
5- agora esse
```
npm start
```
6- TÁ PRONTO O SORVETINHOOOOO!

<a id="pt-scripts"></a>
## ✦ Scripts Disponíveis:
* `npm run setup` para criar as tabelas
* `npm run start` para rodar a aplicação
* `npm run dev` para iniciar a aplicação com hot reload

<a id="funcionalidades"></a>
## ✦ Funcionalidades:
* Cadastro
* Login
* Seguir usuário
* Deixar de seguir usuário
* Resetar senha
* Ver todos os usuários
* Ver seu próprio perfil
* Ver perfil de outro usuário
* Deletar Usuário
* Publicar uma receita
* Ver feed de receitas
* Ver uma receita em específico

<a id="bibliotecas"></a>
## ✦ Bibliotecas e Frameworks:
* cors
* express
* knex
* mysql
* dotenv
* uuid
* jsonwebtoken
* bcryptjs
* nodemailer
* dayjs

*Desenvolvido com 🧡 por Nicole Zolnier*
