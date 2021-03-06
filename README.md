<h1 align="center">
    <img alt="Next Level Week" src="web/src/assets/logo-nlw.svg" width="250px" />
</h1>

# Índice

- [Sobre](#sobre)
- [Documentação](#documentacao)
- [Como Usar](#como-usar)

<a id="sobre"></a>

## :memo: Sobre

O **Ecoleta** é uma aplicação desenvolvida para Web e Aplicativo Mobile que ajuda pessoas a encontrarem pontos de itens recicláveis em suas cidades.

A aplicação foi construída durante a semana **Next Level Week** realizada pela [Rocketseat](https://rocketseat.com.br/).

<a id="documentacao"></a>

## :books: Documentação

No projeto foram utilizadas diversas tecnologias e bibliotecas mas as principais são: **TypeScript**, **NodeJS**, **ReactJS** e **React Native**.

<a id="como-usar"></a>

## :computer: Como usar

1 - Faça o download ou clone do projeto:

```sh
  $ git clone https://github.com/felipedesenna/Ecoleta-NLW.git
```

2 - Executando o projeto:

```sh
  # Instale as dependências de cada aplicação do projeto
  $ npm install / yarn install

  ## Back-end / API
  $ cd server
  $ npm run knex:migrate / yarn run knex:migrate
  $ npm run knex:seed / yarn run knex:seed
  $ npm run dev / yarn run dev

  ## Aplicação web
  $ cd web
  $ npm start / yarn start

  ## Aplicação mobile
  $ cd mobile
  $ npm start / yarn start
```

- ### **Observação**

  - É **necessário** possuir o **[Node.js](https://nodejs.org/en/download/)** instalado na máquina e para gerenciar os pacotes da aplicação o **[NPM](https://www.npmjs.com/get-npm)** ou **[Yarn](https://yarnpkg.com/getting-started/install)**.
  - E para executar a aplicação mobile é **importante** ter o **[Expo](https://expo.io/learn)** instalado globalmente na máquina.
