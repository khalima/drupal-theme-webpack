# THEME_NAME Theme

## Introduction

THEME_NAME theme is an extension of BASE_THEME_NAME theme. Style follows the [BEM methodology](http://getbem.com/) and javascript is written as ES6. The JS and SCSS files are compiled and minified with webpack.

## Requirements

This theme requires Drupal core >= 8.8.0. 

Requirements for developing:
- [NodeJS ( ^ 12.18 )](https://nodejs.org/en/)
- [NPM](https://npmjs.com/) 

## Commands

| Command       | Description                                                         |
| ------------- | ------------------------------------------------------------------- |
| npm i         | Install dependencies and link local packages.                       |
| npm run dev   | Compile styles for development environment. and watch file changes. |
| npm run build | Build packages for production. Minify CSS/JS.                       |

Setup the developing environment by running

    nvm use 
    npm i 

## Structure for files and folders

```
THEME_NAME
│   README.md
└───src
│   └───scss
│   │   │   styles.scss
│   └───js
│   │   │   common.js
│   └───icons
│       |   sprite.svg
│       └───subdir
│           |   some-icon.svg
└───dist
    └───css
    └───js 
    └───icons 
```
