# Crystallize frontend template

The bare minimum skeleton you need to get a frontend up and running on Crystallize. React SSR with Next.js

[![React: latest](https://img.shields.io/badge/react-latest-44cc11.svg?style=flat-square)](https://github.com/facebook/react)

[![Next: latest](https://img.shields.io/badge/next-latest-44cc11.svg?style=flat-square)](https://github.com/zeit/next.js)

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

[![code linter: Eslint](https://img.shields.io/badge/code_linter-eslint-463fd4.svg?style=flat-square)](https://github.com/prettier/prettier)

# Develop locally

* Run `yarn install`
* Run `yarn dev`
* The site should be ready at [http://localhost:3000](http://localhost:3000)
* Develop and go wild!
* * (optional) Install [Editor config](http://editorconfig.org/#download) and [Prettier](https://prettier.io/docs/en/editors.html) plugin for your editor

# App structure

## ./pages

Put all your entry pages here

## ./components

Put all your single components here. Most of your app will live here

## ./server

This is where the ultra-light frontend server lives. Its only function is to render a React response to a request

## ./isomorphic

Non React code shared between the server and the client side code.

# Deploy

There are multiple alternatives for deployments, however for the easiest hosting of a Node application, one option is [Now](https://zeit.co/now).

## Deploying with Now

* Register a Now account
* Run `yarn global add now`
* Navigate to your project folder
* Run `now`
