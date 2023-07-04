# React Tac Toe

Part of the [Learn And Explore Super Repo](https://github.com/constalexander/learn-and-explore-super-repo)

This app is a tic tac toe game made in React. It was created with the following command:

```shell
npx nano-react-app tictactoe
```

## Tech Stack

[![React](https://img.shields.io/badge/React-16-gray?style=plastic&logo=react)]()
[![Nano React App](https://img.shields.io/badge/Nano_React_App-0.1-gray?style=plastic)](https://github.com/adrianmcli/nano-react-app)
[![Parcel](https://img.shields.io/badge/Parcel-2-gray?style=plastic)]()


## Getting Started

### Prerequisites

- Node/npm 18

### Installation

1. Clone the repository
2. Install dependencies

### Development

1. Start the development server:
   ```shell
   npm run start
   ```
2. Open your browser and visit: [http://localhost:1234](http://localhost:1234)

### Build

1. To build the app for production
   ```shell
   npm run build
   ```

### Misc


---

Begin auto-generated readme...


# Nano React App Default Javascript Template

The default template project for [nano-react-app](https://github.com/adrianmcli/nano-react-app).

- `npm start` — This will spawn a development server with a default port of `1234`.
- `npm run build` — This will output a production build in the `dist` directory.

## Custom port

You can use the `-p` flag to specify a port for development. To do this, you can either run `npm start` with an additional flag:

```
npm start -- -p 3000
```

Or edit the `start` script directly:

```
parcel index.html -p 3000
```

## Adding styles

You can use CSS files with simple ES2015 `import` statements anywhere in your Javascript:

```js
import './index.css';
```

## Babel transforms

The Babel preset [babel-preset-nano-react-app](https://github.com/nano-react-app/babel-preset-nano-react-app) is used to support the same transforms that Create React App supports.

The Babel configuration lives inside `package.json` and will override an external `.babelrc` file, so if you want to use `.babelrc` remember to delete the `babel` property inside `package.json`.

## Deploy to GitHub Pages

You can also deploy your project using GitHub pages.
First install the `gh-pages` [package](https://github.com/tschaub/gh-pages):

`npm i -D gh-pages`

With Parcel's `--public-url` flag, use the following scripts for deployment:

```
"scripts": {
  "start": "parcel index.html",
  "build": "parcel build index.html --public-url '.'",
  "predeploy": "rm -rf dist && parcel build index.html --public-url '.'",
  "deploy": "gh-pages -d dist"
},
```

Then follow the normal procedure in GitHub Pages and select the `gh-pages` branch.
