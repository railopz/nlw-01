<h1 align="center">
    <img alt="ecoleta" src="https://user-images.githubusercontent.com/46031023/83979459-e1a63f00-a8e4-11ea-8547-0010c8105b07.png" width="200">
</h1>
<h4 align="center">
  Projeto desenvolvido dentro da semana Next Level Week da Rocketseat 🚀  <br/> Ministrada pelo Diego
</h4>
<p align="center">
  <img alt="typescript" src="https://img.shields.io/badge/%E2%9D%A4-typescript-brightgreen">

  <img alt="server" src="https://img.shields.io/badge/server-nodejs-brightgreen">
  
  <img alt="mobile" src="https://img.shields.io/badge/mobile-react--native-blueviolet">
  
  <img alt="web" src="https://img.shields.io/badge/web-react-blue">

  <a href="https://github.com/railopz/nlw-01/issues">
    <img alt="Repository issues" src="https://github.com/railopz/nlw-01/issues">
  </a>
  
  <a href="https://github.com/railopz/nlw-01/commits/masterr">
    <img alt="GitHub last commit" src="https://github.com/railopz/nlw-01/commits/master">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-critical">
</p>

### 💻 O Projeto
<hr/>
Ecoleta, sistema desenvolvido para ajudar pessoas/empresas a encontrarem pontos de coleta especificos para o descarte de resíduos de forma  rapída e fácil.

### 🚀 Guia de instalação Express + Mysql 
<hr/>

- Primeiro iremos clonar o projeto, é bem simples, siga as instruções abaixo.:
  1. ``git clone https://github.com/railopz/nlw-01.git``
  2. ``cd nlw-01``

<br/>

- Start Backend:
  - vá até a pasta ``backend``
  - Execute ``npm i``
  - agora dentro da pasta src/database configure o arquivo ``connection`` inserindo as informações do seu banco mysql.
  - Execute ``npm run knex:migrate:dev``
  - Execute ``npm run knex:seed:dev``
  - Dentro da pasta ``controllers/PointsControllers``, edite o campo ``image_url`` adicionando o ip do seu localhost.
  - execute ``yarn dev``

<br/>

- Start web:
  - Localize e abra a pasta ``web``
  - Execute ``npm i``
  - Dentro de ``src/services/api.ts`` adicione a url da sua api no campo ``baseURL``
  - Execute ``yarn start``

<br/>

- Executando módulo mobile:
  - Localize e abra a pasta ``mobile``
  - Execute ``npm i``
  - Dentro de ``src/services/api.ts`` adicione a url da sua api no campo ``baseURL``
  - Execute ``yarn start``