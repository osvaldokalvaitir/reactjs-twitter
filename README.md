# Twitter Frontend

Front-end with dinamic interface using React and consuming the features of the Twitter Backend API.

Front-end com interface dinâmica utilizando React e consumindo os recursos da API do Twitter Backend.

## Resumo

Este projeto foi desenvolvido em React consumindo os recursos da API do Twitter Backend, são eles:

- Busca todos os tweets
- Adiciona novos tweets
- Like nos tweets

## Instalação e execução

Depois de instalado o Node.js, abra o prompt de comando e dentro da pasta do projeto execute os comandos abaixo.

Para instalar as dependências do projeto:

```
npm install | yarn install
```

Executar o projeto localmente:

```
npm start | yarn start
```

Construir e executar o projeto:

```
npm run build | yarn run build
```

## Índice

- [Telas](#telas)

  - [Login](#login)
  - [Timeline](#timeline)

- [Componentes](#componentes)

  - [Listagem](#listagem)

- [Tecnologias](#tecnologias)

  - [Visual Studio Code](#visual-studio-code)

    - [Fonte](#fonte)

      - [Fira Code](#fira-code)

    - [Extensões](#extensões)

      - [Color Highlight](#color-highlight)
      - [DotEnv](#dotenv)
      - [Dracula Official](#dracula-official)
      - [EditorConfig for VS Code](#editorconfig-for-vs-code)
      - [ESLint](#eslint-for-vs-code)
      - [Markdown All in One](#markdown-all-in-one)
      - [Material Icon Theme](#material-icon-theme)
      - [Nunjucks](#nunjucks-for-vs-code)
      - [Prettier - Code formatter](#prettier---code-formatter)

    - [Configurações](#configurações)

  - [Node.js](#nodejs)
  - [Yarn](#yarn)

- [Bibliotecas](#bibliotecas)

  - [Create React App](#create-react-app)
  - [ESLint](#eslint)
  - [React Router](#react-router)
  - [Axios](#axios)
  - [socket.io-client](#socketio-client)

- [APIs](#apis)
  - [Twitter Backend](#twitter-backend)

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

## Tecnologias

### [Visual Studio Code](https://code.visualstudio.com)

Editor de código-fonte que inclui suporte para depuração, realce de sintaxe, complementação inteligente de código, snippets, entre outros.

#### Fonte

##### [Fira Code](https://github.com/tonsky/FiraCode)

Fonte monoespaçada com ligaduras de programação. É necessário adicionar a fonte no sistema operacional.

#### Extensões

##### [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

Exibe a cor exata de todos RGB’s ou HEX em seu código, muito útil para trabalhar com CSS ou SASS.

##### [DotEnv](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)

Utilizado para ter suporte à sintaxe .env, muito útil para quem trabalha com NodeJS, ReactJS ou qualquer outro tipo de projeto web.

##### [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)

Tema para o VSCode.

##### [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

Utilizado para padronizar quebra de linha, indentação, espaços e tabs entre desenvolvedores de um mesmo projeto.

##### [ESLint for VS Code](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

Utilizado para padronizar código entre desenvolvedores como utilização de pontos e vírgulas, tamanho máximo de caracteres em linhas e todo outro tipo de padronização.

##### [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

Utilizado para escrever e ler Markdown dentro do VSCode, muito útil para documentações o README’s do Github.

##### [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

Utilizado para exibir os ícones de acordo com a linguagem utilizada na barra lateral.

##### [Nunjucks for VS Code](https://marketplace.visualstudio.com/items?itemName=ronnidc.nunjucks)

Utilizado para ter suporte à sintaxe .njk.

##### [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

Utilizado para formatar JavaScript / TypeScript / CSS.

#### Configurações

Depois de adicionar a fonte e as extensões, setar as configurações (Settings > Open settings.json):

```
{
  // Define o tema do VSCode
  "workbench.colorTheme":"Dracula",

  // Configura tamanho e família da fonte
  "editor.fontSize":16,
  "editor.lineHeight":24,
  "editor.fontFamily":"Fira Code",
  "editor.fontLigatures":true,

  // Aplica linhas verticais para lembrar de quebrar linha em códigos muito grandes
  "editor.rulers": [
    80,
    120
  ],

  // Aplica um sinal visual na esquerda da linha selecionada
  "editor.renderLineHighlight":"gutter",

  // Aumenta a fonte do terminal
  "terminal.integrated.fontSize":14,

  // Define o tema dos ícones na sidebar
  "workbench.iconTheme":"material-icon-theme",

  // Configura o Prettier e o ESLint
  "prettier.eslintIntegration": true,
  "editor.formatOnSave": true
}
```

### [Node.js](https://nodejs.org/)

Interpretador de código JavaScript com o código aberto, focado em migrar o Javascript do lado do cliente para servidores.

### [Yarn](https://yarnpkg.com)

Gerenciamento de dependências rápido, confiável e seguro.

## Bibliotecas

### [Create React App](https://github.com/facebook/create-react-app)

Cria aplicativos React sem configuração de compilação.

### [ESLint](https://github.com/eslint/eslint)

Ferramenta para identificar e relatar padrões em JavaScript. Se o projeto for em Node é recomendado a utilização do guia de estilo 'Standard' e se for em React o guia de estilo do [AirBnB](https://www.npmjs.com/package/eslint-config-airbnb-base).

### [React Router](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)

Realiza o redirecionamento das rotas.

### [Axios](https://github.com/axios/axios)

Cliente HTTP baseado em promessas.

### [socket.io-client](https://github.com/socketio/socket.io-client)

Permite comunicação baseada em eventos bidirecional em tempo real (cliente).

## APIs

### [Twitter Backend](https://github.com/osvaldokalvaitir/twitter-backend)

Contém informações da API Twitter Backend.
