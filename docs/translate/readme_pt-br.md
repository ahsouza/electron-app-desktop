<p align="center">
 <img width="100px" src="docs/assets/img/electron.png" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">Electron.js com React, Vue & Angular</h2>
 <p align="center">
    Utilize seu Aplicativo Desktop em Electron with React.js, Vue.js & Angular.js para gerenciar suas interfaces
</p>
 </p>
  <p align="center">
    <a href="https://github.com/ahsouza/github-readme-stats/actions">
      <img alt="GitHub issues" src="https://img.shields.io/github/issues/ahsouza/mern">
    </a>
    <a href="https://codecov.io/gh/ahsouza/github-readme-stats">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/ahsouza/mern">
    </a>
    <a href="https://a.paddle.com/v2/click/16413/119403?link=1227">
      <img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/ahsouza/mern">
    </a>
    <a href="https://a.paddle.com/v2/click/16413/119403?link=2345">
      <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/ahsouza/mern">
    </a>
  </p>
  <p align="center">
    <a href="/docs/translate/readme_fr.md">Français </a>
    ·
    <a href="/docs/translate/readme_cn.md">简体中文</a>
    ·
    <a href="/docs/translate/readme_es.md">Español</a>
    ·
    <a href="/docs/translate/readme_de.md">Deutsch</a>
    ·
    <a href="/docs/translate/readme_ja.md">日本語</a>
    ·
    <a href="/docs/translate/readme_pt-BR.md">Português Brasileiro</a>
    ·
    <a href="/docs/translate/readme_it.md">Italiano</a>
    ·
    <a href="/docs/translate/readme_kr.md">한국어</a>
  </p>
  <br>
  <div style="display: flex" align="center">
    <img src="docs/assets/img/react.png" width=50 height=50 title='react'/> <img src="docs/assets/img/nodejs.png" width=50 height=50 title='node'/> <img src="docs/assets/img/html.png" width=50 height=50 title='html'/> <img src="docs/assets/img/css.png" width=50 height=50 title='css'/> <img src="docs/assets/img/npm.png" width=50 height=50 title='npm'/> 
  </div>
</p>

<br>
<br>
<br>

## Estrutura de Arquivos & Pastas

```
branch: master

├📂 docs
├📂 react
└📂 vue
├📄 .gitignore.md
├📄 LICENSE.md
├📄 README.md
├📄 index.html
├📄 package.json
├📄 preload.js
├📄 renderer.js
├📄 style.css
```
<br>
<br>
<br>
<br>

## Como usar?

Precisamos configurar a entrada principal que contém o caminho que aponta para o arquivo **main.js** em **package.json** na raiz do projeto.


Caso você for usar com **React**:

```js
"description": "Electron Desktop",
"main": "react/public/main.js",
```
<br>
Caso você for usar com **Vue**:

```js
"description": "Electron Desktop",
"main": "vue/public/main.js",
```

Agora instale as dependências Electron.js

`npm install` or `yarn install`

Estamos quase lá, não vamos esquecer de instalar suas dependências de front-end e preparar o servidor

**Para React.js**

```sh
cd react
npm i
npm run start
```

**Para Vue.js**

```sh
cd vue
npm i
npm run dev
```

<br>
<br>
Agora que indicamos nosso front-end para o aplicativo Electron, vamos executar o Desktop

Na raiz do Electron do projeto, execute o seguinte comando:

`npm run start`

<br>
<br>
<br>

## Empacote e Distribua Seu Aplicativo

A maneira mais rápida de distribuir seu aplicativo de desktop é usando [Electron Forge](https://www.electronforge.io/)

Como já temos essas dependências instaladas no **package.json**, vamos apenas construir o aplicativo com o comando abaixo:

```sh
npm run make
```

Electron Forge cria a pasta `out` onde seu pacote estará localizado

Exemplo de saída:

```sh
// Exemplo para MacOS
out/
├── out/make/zip/darwin/x64/my-electron-app-darwin-x64-1.0.0.zip
├── ...
└── out/my-electron-app-darwin-x64/my-electron-app.app/Contents/MacOS/my-electron-app
```

 

Ramificações (branch) ```git branch -a```

- [main](https://github.com/ahsouza/electron-app-desktop/tree/main)
- [electron](https://github.com/ahsouza/electron-app-desktop/tree/frontend)
- [electron-react](https://github.com/ahsouza/electron-app-desktop/tree/electron-react)
- [electron-vue](https://github.com/ahsouza/electron-app-desktop/tree/electron-vue)

<br>
<br>


[download](https://github.com/ahsouza/electron-app-desktop/archive/electron.zip) do projeto somente Electron `Electron.js 15.3.0`

[download](https://github.com/ahsouza/electron-app-desktop/archive/electron-react.zip) do projeto React com Electron `React.js 16.4.1`

[download](https://github.com/ahsouza/electron-app-desktop/archive/electron-vue.zip) do projeto Vue com Electron `Vue.js 3.1.1`
