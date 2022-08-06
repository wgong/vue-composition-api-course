# vue-composition-api-noteballs

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.vscode-typescript-vue-plugin).

## setup Vue+Vite

### https://linuxize.com/post/how-to-install-node-js-on-ubuntu-20-04/
```
sudo apt update
sudo apt install nodejs npm
```
not working for me on Ubuntu

### Install from source on Ubuntu
https://github.com/nodesource/distributions#debinstall
```
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash -
sudo apt-get install -y nodejs

node --version  # v18.7.0
npm --version   # 8.15.0

npm create vite@latest
cd noteball

cp -Rf ~/projects/vuejs/noteballs/vue-composition-api-course-module-18/vue-composition-api-noteballs/* .

npm install
npm run dev

```

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
