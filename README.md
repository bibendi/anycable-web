## About

AnyCable website generator (https://anycable.github.io).

Includes:
- [Jade](http://jade-lang.com) HTML preprocessor;
- [PostCSS](https://github.com/postcss/postcss) with [autoprefixer](https://github.com/postcss/autoprefixer), [precss](https://github.com/jonathantneal/precss) and [cssnext](http://cssnext.io);
- [JSPM](http://jspm.io) with ES6 set up.

## Usage

Run `npm install` and then `npm start` or `gulp` to start dev server with livereload.

## SVG Optimization

Use [svgo](https://github.com/svg/svgo) to optimize SVG images.

For animated illustration use: `svgo --disable=moveGroupAttrsToElems --disable=convertTransform src/images/illustration.svg src/images/illustration.min.svg`
