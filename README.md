# Connecting the client to GraphQL with Apollo client

The blog-client is built by React (typescript) and [Graphql](https://graphql.org/code/#javascript-client).

## Using Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), using the [Redux](https://redux.js.org/) and [Redux Toolkit TS template](https://redux-toolkit.js.org/introduction/getting-started).

```sh
# Redux + TypeScript template
npx create-react-app my-app --template redux-typescript

npm i -D eslint
npm create @eslint/config
npm i react-router-dom
npm i -D prettier eslint-config-prettier @types/react-router-dom
```

Learn more: [Install ESLint, Prettier, ESLint Plugin for Testing Library, ESLint Plugin for Jest DOM](https://github.com/mehradi-github/jest-rtl/)

## Installing Apollo Client

[Apollo Client](https://www.apollographql.com/docs/react/get-started) is a comprehensive state management library for JavaScript that enables you to manage both local and remote data with GraphQL. Use it to fetch, cache, and modify application data, all while automatically updating your UI.

```sh
npm i @apollo/client graphql
```
