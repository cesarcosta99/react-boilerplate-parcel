# React Boilerplate
A **super simple** way to start using React.

[![Dependencies Status](https://david-dm.org/cesarcosta99/react-boilerplate-parcel/status.svg)](https://david-dm.org/cesarcosta99/react-boilerplate-parcel)
[![Code Style](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](http://standardjs.com)

## Why use it?
This boilerplate provides the only ~~tooling~~ thing you need to start a new React application: Parcel. It also includes ESLint, Sass and Autoprefixer and it's **production-ready**!

## Install
    $ git clone https://github.com/cesarcosta99/react-boilerplate-parcel
    $ npm install
    $ npm start
> **Tip**: you can use [Yarn](https://yarnpkg.com) to install dependencies faster!

After `npm start` the project will be running at [http://localhost:1234](http://localhost:1234) by default but you are able to change with the `-p` flag.

## Build
The initial build results in three minified files in the `dist` folder: `index.html` and two hashed files which are the JS and CSS:

    $ yarn run build

## Guidelines
Below there are some instructions about the tooling:

#### Styleguide
Since there is Babel in the tooling, ES2015 is supported, and by default, ESLint is checking for [standard](https://github.com/feross/standard) style. You can change this by editing `.eslintrc.js`.

#### Sass
Parcel only requires `node-sass` to compile SASS which is already included in the `package.json` so nothing to worry about. Also I've included `autoprefixer` for vendor prefixing, you can configure it in the `package.json` or `postcssrc` file or remove as well.

## Tooling
- [Parcel](https://parceljs.org/)
- [Babel](http://babeljs.io/)
- [ESLint](http://eslint.org/)
- [Sass](http://sass-lang.com/)

## Contributing
I'll love any kind of contribution you can provide, feel free to do it.

## License
Licensed under the [MIT License](https://github.com/cesarcosta99/react-boilerplate-parcel/blob/master/LICENSE).
