<p align="center">
  <img src="./.github/logo.png" />
</p>

<p align="center">
  Aplicativo para auxiliar ONGs a encontrar colaboradores, feito com ReactJS, React Native e Node.js.  
</p>

<img src=".github/thumbnail.png" />

## Sobre o projeto

#### Web
A página web será usada para cadastrar as ONGs, onde você receberá uma identificação para acesso. Posteriormente, os casos serão registrados na página de perfil.

#### App
No aplicativo serão listados todos os casos cadastrados pelas ONGs, onde o usuário pode entrar em contato com a ONG via WhatsApp ou E-mail e assim contribuir com o caso.

## Tech
- [NodeJs](https://nodejs.org/en/) - Build the server
- [ReactJs](https://reactjs.org) - A JavaScript library for building user interfaces
  - [React Icons](https://react-icons.github.io/react-icons/) - Utilizes ES6 imports that allows you to include only the icons that your project is using.
  - [React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom) - DOM bindings
- [React Native](https://reactnative.dev) - Native Development
  - [React Navigation](https://reactnavigation.org/docs/getting-started/) - Routing and navigation for your React Native apps.
- [Expo](https://expo.io) - Deploy and quickly iterate on native Android, iOS, and web apps
  - [Expo Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/) - Compose and send mail 
- [SQLite3](https://www.sqlite.org) - DB Connector
- [Express](https://expressjs.com/) - Router of the Application
- [KnexJs](http://knexjs.org) - SQL query builder for Postgres, MSSQL, MySQL, MariaDB, SQLite3, Oracle, and Amazon Redshift
- [Celebrate](https://github.com/arb/celebrate) - A joi validation middleware for Express.
- [CORS](https://www.npmjs.com/package/cors) - Cross-origin Resource Sharing
- [Axios](https://github.com/axios/axios) - Promise based HTTP client for the browser and NodeJs
- [Jest](https://jestjs.io) - Jest is a JavaScript testing framework maintained by Facebook
- [Supertest](https://github.com/visionmedia/supertest) - Super-agent driven library for testing node.js HTTP servers
- [Nodemon](https://nodemon.io/) - Process Manager used in the development
- [Intl](https://www.npmjs.com/package/intl) - Internationalization and localization facilities, including message translation, plurals and genders, date/number.
- [Prettier](https://prettier.io/docs/en/cli.html) - An opinionated code formatter
- [ESlint](https://eslint.org) - ESLint statically analyzes your code to quickly find problems.

## 🚀 Como executar o projeto
Este projeto é divido em 3 partes:
1. Backend (pasta backend) 
2. Mobile (pasta mobile)
3. Web (pasta web)

💡 O Mobile precisa que o Backend esteja sendo executado para funcionar.

### Pré-requisitos
Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas: [Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).

#### 🎲 Executando o backend (servidor)
```bash
# Clone este repositório
$ git clone https://github.com/alisson-moura/be-the-hero.git

# Acesse a pasta do projeto no terminal/cmd
$ cd be-the-hero

# Vá para a pasta server
$ cd backend

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn dev

# A API vai ficar disponível  na porta:3333 

# Executando as migrations
$ knex migrate:latest
```

#### 🎲 Executando o front-end (web)
```bash
# Acesse a pasta do projeto no terminal/cmd
$ cd be-the-hero

# Vá para a pasta server
$ cd web

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn start

# A pagína web vai ficar disponível em http://localhost:3000
```

#### 🎲 Executando o aplicativo (mobile)
```bash
# Acesse a pasta do projeto no terminal/cmd
$ cd be-the-hero

# Vá para a pasta server
$ cd mobile

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ expo start
```

## 🦸 Autor

 <img style="border-radius: 50%;" src="https://avatars2.githubusercontent.com/u/48321754?s=460&u=9faab799c661b3f1227c25e0233a2f30b699218a&v=4" width="100px;" alt=""/><br />
<b>Alisson Moura 👋🏽 [Entre em contato!](https://www.linkedin.com/in/alisson-mo-moura/) </b>
 
## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Projeto desenvolvido durante a semana Omnistack 11 da Rocketset.
