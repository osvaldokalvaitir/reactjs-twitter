# Twitter Frontend

Front-end com interface dinâmica utilizando React e consumindo os recursos da API do Twitter Backend.

## Resumo

Este projeto foi desenvolvido em React consumindo os recursos da API do Twitter Backend, são eles:

- Busca todos os tweets
- Adiciona novos tweets
- Like nos tweets

## Índice

- [Telas](#telas)

  - [Login](#login)
  - [Timeline](#timeline)

- [Componentes](#componentes)

  - [Listagem](#listagem)

- [Desenvolvimento](#desenvolvimento)

  - [Configurações Iniciais](#configurações-iniciais)

  - [Instalação e Execução](#instalação-e-execução)

  - [Bibliotecas do Node.js](#bibliotecas-do-nodejs)

  - [APIs](#apis)

## Telas

### Login

![Screenshoot Login](https://github.com/osvaldokalvaitir/twitter-frontend/blob/master/screenshots/Login.png)
Esta é a primeira tela, para entrar o usuário terá que digitar seu nome e clicar em 'Entrar'.

### Timeline

![Screenshoot Timeline](https://github.com/osvaldokalvaitir/twitter-frontend/blob/master/screenshots/Timeline.png)
É a tela onde estão todos os tweets vindos da API, podendo adicionar novos tweets e dar like nos tweets existentes.
Composto por: Listagem

## Componentes

### Listagem

É a lista onde encontram-se os tweets vindos da API.

## Desenvolvimento

### Configurações Iniciais

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings) e siga as Configurações Iniciais.

### Instalação e Execução

Depois de instalado o Node.js/Yarn, abra o prompt de comando e dentro da pasta do projeto execute os comandos abaixo.

Para instalar as dependências do projeto:

```
npm install | yarn
```

Executar o projeto localmente:

```
npm start | yarn start
```

Construir e executar o projeto:

```
npm run build | yarn run build
```

### Bibliotecas do Node.js

- [Axios](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/axios.md)

- [Create React App](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/create-react-app.md)

- [ESLint](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint.md)

- [React Router](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-router.md)

- [socket.io-client](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/socketio-client.md)

### APIs

- [Twitter Backend](https://github.com/osvaldokalvaitir/twitter-backend)
