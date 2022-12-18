<h1>Fimblr Core UI</h1>

<p>Helping you during the process of creating entreprise applications that provide meaningful and relevant experiences to your users.</p>

[![NPM](https://img.shields.io/npm/v/ui-core-library.svg)](https://www.npmjs.com/package/ui-core-library) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Usage

<p>Visit <a href="http://ui.fimblr.com/">ui.fimblr.com</a> for full documentation.</p>


## Install

```
yarn add @fimblr/ui-core
```

<p align="center">or</p>

```
npm install @fimblr/ui-core --save
```

## Contributions
Local development is broken into two parts (ideally using two tabs).

First, run rollup to watch your `src/` module and automatically recompile it into `dist/` whenever you make changes.

```bash
npm start # runs rollup with watch flag
```

The second part will be running the `example/` create-react-app that's linked to the local version of your module.

```bash
# (in another tab)
cd example
npm start # runs create-react-app dev server
```

Now, anytime you make a change to your library in `src/` or to the example app's `example/src`, `create-react-app` will live-reload your local dev server so you can iterate on your component in real-time.
