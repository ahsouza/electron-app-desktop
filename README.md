<p align="center">
 <img width="100px" src="docs/assets/img/electron.png" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">Electron.js with React, Vue & Angular</h2>
 <p align="center">
    Use your Desktop Application with React.js, Vue.js & Angular.js frameworks to manage your Interfaces
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
    <a href="/docs/readme_fr.md">Français </a>
    ·
    <a href="/docs/readme_cn.md">简体中文</a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_de.md">Deutsch</a>
    ·
    <a href="/docs/readme_ja.md">日本語</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português Brasileiro</a>
    ·
    <a href="/docs/readme_it.md">Italiano</a>
    ·
    <a href="/docs/readme_kr.md">한국어</a>
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

## How To Use?

We need to configure the main input that contains the path that points to the **main.js** file in **package.json** na raíz do projeto.


In case you want to use with **React**:

```js
"description": "Electron Desktop",
"main": "react/public/main.js",
```
<br>
In case you want to use with **Vue**:

```js
"description": "Electron Desktop",
"main": "vue/public/main.js",
```

Now install the dependencies electron

`npm install` or `yarn install`

We're almost there, let's not forget to install your front end dependencies and get the server up

**To React.js**

```sh
cd react
npm i
npm run start
```

**To Vue.js**

```sh
cd vue
npm i
npm run dev
```

<br>
<br>
Now that we've indicated our Frontend to the Electron Application, let's run the Desktop

At the root of the project electron, run the following command:

`npm run start`

<br>
<br>
<br>

## Package And Distribute Your App

The fastest way to distribute your desktop app is using [Electron Forge](https://www.electronforge.io/)

As we already have these dependencies installed in package.json, we will just build the application with the command below:

```sh
npm run make
```

Electron Forge creates the `out` folder where your package will be located

output example:

```sh
// Example for macOS
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




[download](https://github.com/ahsouza/electron-app-desktop/archive/electron.zip) the project on Electron `Electron.js 15.3.0`

[download](https://github.com/ahsouza/electron-app-desktop/archive/electron-react.zip) the project on React `React.js 16.4.1`

[download](https://github.com/ahsouza/electron-app-desktop/archive/electron-vue.zip) the project on Vue `Vue.js 3.1.1`
