# nlw-01
Projeto desenvolvido dentro da semana next level week ministrada pelo Diego
<h1 align="center">
    <img alt="ecoleta" src="https://user-images.githubusercontent.com/46031023/83979459-e1a63f00-a8e4-11ea-8547-0010c8105b07.png" width="200">
</h1>
<h4 align="center">
  Projeto desenvolvido dentro da semana Next Level Week da Rocketseat 🚀. Ministrada pelo Diego
</h4>
<p align="center">
  <img alt="typescript" src="https://img.shields.io/badge/%E2%9D%A4-typescript-brightgreen">

  <img alt="server" src="https://img.shields.io/badge/server-nodejs-brightgreen">
  
  <img alt="mobile" src="https://img.shields.io/badge/mobile-react--native-blueviolet">
  
  <img alt="web" src="https://img.shields.io/badge/web-react-blue">

  <a href="https://github.com/CorreiaEduardo/nlw-ecoleta/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/CorreiaEduardo/nlw-ecoleta">
  </a>
  
  <a href="https://github.com/CorreiaEduardo/nlw-ecoleta/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/CorreiaEduardo/nlw-ecoleta">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-critical">
</p>

### 💻 O Projeto
<hr/>
Ecoleta, sistema desenvolvido para ajudar pessoas/empresas a encontrarem pontos de coleta especificos para o descarte de resíduos de forma  rapída e fácil.

### :rocket: Guia de instalação Express + Mysql 
<hr/>

- Primeiro iremos clonar o projeto, é bem simples, siga as instruções abaixo.:
  1. ``git clone https://github.com/railopz/nlw-01.git``
  2. ``cd nlw-01``

<br/>

- Start Backend:
  1. vá até a pasta ``backend``
  2. Execute ``npm i``
  3. agora dentro da pasta src/database configure o arquivo ``connection`` inserindo as informações do seu banco mysql.
  4. Execute ``npm run knex:migrate:dev``
  5. Execute ``npm run knex:seed:dev``
  6. Dentro da pasta ``controllers/PointsControllers``, edite o campo ``image_url`` adicionando o ip do seu localhost.
  7. execute ``yarn dev``

<br/>

- Start web:
  1. Localize e abra a pasta ``web``
  2. Execute ``npm i``
  3. Dentro de ``src/services/api.ts`` adicione a url da sua api no campo ``baseURL``
  4. Execute ``yarn start``

<br/>

- Executando módulo mobile:
  1. Localize e abra a pasta ``mobile``
  2. Execute ``npm i``
  3. Dentro de ``src/services/api.ts`` adicione a url da sua api no campo ``baseURL``
  4. Execute ``yarn start``