[![Build Status](https://travis-ci.org/JohnsonMauro/cssshortcut-app.svg?branch=master)](https://travis-ci.org/JohnsonMauro/cssshortcut-app) 
[![devDependencies Status](https://david-dm.org/JohnsonMauro/cssshortcut-app/dev-status.svg)](https://david-dm.org/JohnsonMauro/cssshortcut-app?type=dev)
[![licence mit](https://img.shields.io/badge/licence-MIT-blue.svg)](https://github.com/afonsopacifer/open-source-boilerplate/blob/master/LICENSE.md) 

![EasyBuy](https://www.transformagency.com/media/bl8-Make-it-Easy-for-Visitors-to-Buy-and-Increase-Conversions1.png)

# EasyBuy

> Projeto destinado a disciplina de práticas 1 e 2 para a universidade Uninabuco

## Stack

- Build Interfaces: [React](https://reactjs.org/)
- Task Runner: [Gulp](https://gulpjs.com/)
- CSS Preprocessor: [Stylus](http://stylus-lang.com/)

## Run the project locally

**1 -** Prepare the environment:

```sh
$ npm install -g gulp-cli
```

**2 -** Clone the project and install the dependencies:

```sh
$ git clone https://github.com/elit-pe/EasyBuy.git
$ cd EasyBuy
$ npm install
```
**3 -** Run static server and livereload:

```sh
$ gulp server
```

## Folders Structure
      .
      ├── README.md
      ├── LICENSE.md
      ├── CONTRIBUTING.md
      ├── out/
      ├── src/
      |   ├── assets/
      |   |   ├── img/
      |   |   ├── scripts/
      |   |   |   └── script.js
      |   |   └── styles/
      |   |       ├── modules/
      |   |       └── style.styl
      |   ├── partials/
      |   |   ├── footer.pug
      |   |   └── header.pug
      |   ├── layouts/
      |   |   └── default.pug
      |   ├── projects.pug
      |   └── index.pug
      ├── gulpfile.js
      ├── package.json
      ├── projects.json
      ├── .editorconfig
      └── .gitignore

## Automatic Tasks

- `$ gulp build`: Compile, concat and minify all files.
- `$ gulp server`: Watch the files to build and start a static server.
- `$ gulp deploy`: Deploy for gh-pages.

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing
Find on our [roadmap](https://github.com/elit-pe/EasyBuy/issues/1) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://github.com/elit-pe/EasyBuy/blob/master/CONTRIBUTING.md).

## License
[MIT License](https://github.com/elit-pe/EasyBuy/blob/master/LICENSE.md) ©
