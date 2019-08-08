# Parcel Vue Demo    

A Vue demo including Code Splitting, Hot Reloading, ESLint, Vuex, Vue Router, Pug, Stylus and Livescript.

## :fire: Get Started

```bash
git clone git@github.com:proYang/vue-parcel-demo.git
cd vue-parcel-ls
npm i
```

## :building_construction: Development

```bash
npm start
```
The application opened `http://127.0.0.1:1234` in the browser default.

Transpiled code for [pug](https://pugjs.org/api/getting-started.html) [stylus](http://stylus-lang.com/) and [livescript](http://livescript.net/) is only located in *App.vue* and *Home.vue*. The rest defaults to CSS, HTML and ES6.

## :rocket: Build

```bash
npm run build
```
the default output directory is `/dist`. You can change the destination in `package.json`.

## :bento: Code Linting

```bash
npm run lint
```
Linting your code by ESLint.    

Edit `.eslintrc.js` file to configure rules.
See: 
- [http://eslint.org/docs/user-guide/configuring](http://eslint.org/docs/user-guide/configuring)    
- [https://github.com/vuejs/eslint-plugin-vue](https://github.com/vuejs/eslint-plugin-vue) 

## :package: Other Config
If you want to use other configs( port, public-url, out-dir... ), see the [Parcel official documentation](https://parceljs.org/) or submit the Issue.
