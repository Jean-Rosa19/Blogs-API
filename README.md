#Blogs API#

## Desenvolvimento

Projeto desenvolvido na Trybe durante o módulo de Back-End!

Nesse projeto foi desenvolvido uma API RESTful utilizando a arquitetura MSC (Model-Service-Controller) de blog, onde é possivel criar, visualizar, deletar e atualizar posts, categorias e usuários! A conexão com o banco de dados foi feita com o ORM Sequelize e a autenticação com Json Web Token.

## Instalação e execução

1 - Clone o repositório:
git clone git@github.com:Jean-Rosa19/Blogs-API.git 

2 - Na raíz do projeto, suba os containers blogs_api e blogs_api_db utilizando o docker-compose.
docker-compose up -d

3 - Abra o terminal do container blogs_api.
docker exec -it blogs_api bash

4 - No terminal do container, instale as dependências com o comando:
npm install

5 - Agora execute os comandos para criar e popular o banco de dados:
Criando as tabelas:
npm run prestart
Populando o banco com dados
npm run seed

6 - Agora execute a aplicação com o comando:
npm start

## Tecnologias:

- Node.js
- Express.js
- Sequelize.js
- Json Web Tokens
- DotEnv
- Joi
- Docker
- MySQL
