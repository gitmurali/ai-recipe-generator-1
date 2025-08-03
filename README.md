# AI Recipe Generator

A recipe generation application built with React, TypeScript, and Vite.

## Tech Stack: React + TypeScript + Vite

This project provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

create the react app locally and push to your github and connect the app to amplify github repo.

```js
npm create vite@latest ai-recipe-generator -- --template react-ts -y
cd ai-recipe-generator
npm install
npm run dev
```


install amplify packages

```js
npm create amplify@latest -y
```

create amplify sandbox

```js
npx ampx sandbox
```

install amplify on frontend react

```js
npm install aws-amplify @aws-amplify/ui-react
```

and run your app

```js
npm run dev
```