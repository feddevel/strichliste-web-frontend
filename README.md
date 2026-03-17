# Strichliste Web Frontend [![Build Status](https://travis-ci.org/strichliste/strichliste-web-frontend.svg?branch=master)](https://travis-ci.org/strichliste/strichliste-web-frontend)

SPA Frontend for the [Strichliste](http://v2.strichliste.org/) project

## Getting Started

This project is build with [typescript](https://www.typescriptlang.org/), [react](https://reactjs.org/), [redux](https://redux.js.org/), [emotion](https://emotion.sh/) and [create-react-app](https://github.com/facebook/create-react-app).

### Prerequisites

You have to use [yarn](https://yarnpkg.com/lang/en/) to build this project.

Yarn is no longer bundled with Node.js 17+. If `yarn` is not available in your terminal, install it via one of these methods:

- **Using npm:** `npm install -g yarn`
- **Using corepack** (Node.js ≥ 16.9, recommended): `corepack enable`

### Installing

Fetch all dependencies by

```
yarn install
```

Start the development server by

```
yarn start
```

Build the project by

```
yarn build
```

the output will be copied to the dist folder.

## Contributing / FAQ

### Commit Messages

please follow the [angular commit message guidlines](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-guidelines)

### Ui Component Framework

all basic components are found inside the `src/bricks` folder. (Lego pun intended)

## End 2 End Tests

We do have e2e tests with cypress check our [test repo](https://github.com/strichliste/strichliste-web-e2e)
