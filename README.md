# Pug-Sass Boilerplate Starter Kit

Pug-Sass Boilerplate Starter Kit is a Front-end web kit and boilerplate for building web apps or sites using Pug(Jade) and Sass

This starter kit and boilerplate project is based on a simple workflow for small apps and personal sites. It gives a solid starting point for newcomers who wants a ready to deploy local environment setup. The sources used to build this project includes:

  * [H5BP Project](https://github.com/h5bp/html5-boilerplate)
  * [React Redux Starter Kit](https://github.com/davezuko/react-redux-starter-kit)
  * [Mark Goodyear's Blog](https://markgoodyear.com/2014/01/getting-started-with-gulp/)
  * [Material Design Palette](https://www.materialpalette.com/)
  * [Flat UI Colors](https://flatuicolors.com/)

## Features

  * Pug-Sass ready.
  * Easy to deploy your production files
  * Includes:
    * [`Normalize.css`](https://necolas.github.com/normalize.css/) for CSS normalizations and common bug fixes
    * [`gulpfile.js`](http://gulpjs.com/) with Gulp presets
    * `Sass variables` with with popular color palettes

## Requirements

* [Node.js](https://nodejs.org)
* [npm](https://www.npmjs.com)
* [Gulp](http://gulpjs.com/)
* [Bower](https://bower.io/)

## Getting Started

After [Node.js](https://nodejs.org/en/download/), [npm](https://docs.npmjs.com/getting-started/installing-node), [Gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md) and [Bower](https://bower.io/#install-bower) installation, you can create a new project based on `pug-sass-boilerplate-starter-kit` by doing the following:

### Install From Source

First, clone the project:

```bash
$ git clone https://github.com/Errec/pug-sass-boilerplate-starter-kit.git <my-project-name>
```

Initialize `npm` on `<my-project-name>` directory

```bash
$ cd <my-project-name>
$ npm init
```

Then install `Gulp` required dependencies

```bash
$ sudo npm install gulp-uglify browser-sync gulp-plumber gulp-autoprefixer gulp-sass gulp-jade gulp-imagemin del gulp-cache gulp-clean-css gulp-sourcemaps gulp-concat beeper gulp-util gulp-rename gulp-notify --save-dev
```

Finally initialize `Bower` and install the dependencies

```bash
$ bower init
$ bower install jquery --save
$ bower install bootstrap --save
```

### Running Your Local Server With Gulp

After the installation of all requirements and its dependencies, your local web development environment is ready to run. First run a gulp task to create your `build` directory: on `<my-project-name>`:

```bash
$ gulp
```

Now your local server is ready to run using

```bash
$ gulp watch
```

## Project Structure

The structure presented in this boilerplate is grouped primarily by folder content and file type. Please note that this structure is only meant to serve as a guide, it is by no means prescriptive.

```
.
├── img                      # Main folder for image files
├── js                       # Main folder for JS files
│   ├── vendor               # Store third part library files (e.g.: jquery, bootstrap)
│   └── main.js             # Index JS code goes here
├── styles                   # Main folder for cascade style files
│   ├── modules              # Store third party modules and initializers (e.g.: normalize)
│   ├── variables            # Store sass variables files
│   └── main.scss           # Index Sass goes here
├── templates                # Main folder for jade template files
│   └── index.jade           # Index jade/pug markup goes here
├── .bowerrc                 # Setup bower library destination path
└── gulpfile.js              # Setup Gulp tasks
```

## The Output Contents
