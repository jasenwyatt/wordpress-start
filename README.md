# Wordpress + Sage Theme + Base Plugins


## Quick Start Guide

1. Fork this Repository.
2. Clone to your local development environment root.
3. Run WordPress' Famous 5-Minute Installation.
4. Complete [Sage Theme setup](#theme-setup).
5. Work on Exercises.
6. Commit your work.
7. Submit Pull Request.
8. Dance.


## Sage Theme

Our projects use [Sage Theme](https://roots.io/sage/). A WordPress starter theme with a modern development workflow. Sage is based on HTML5 Boilerplate, gulp, Bower, and Bootstrap Sass, that will help you make better themes.

### Theme Setup

Sage uses [gulp](http://gulpjs.com/) as its build system and [Bower](http://bower.io/) to manage front-end packages.

Building the theme requires [node.js](http://nodejs.org/download/). We recommend you update to the latest version of npm: `npm install -g npm@latest`.

From the command line in the theme directory:

1. Install [gulp](http://gulpjs.com) and [Bower](http://bower.io/) globally with `npm install -g gulp bower`
2. Navigate to the theme directory `/wp-content/themes/wp/`
3. Run `npm install`
4. Run `bower install`

You now have all the necessary dependencies to run the build process.

### Available gulp commands

* `gulp` — Compile and optimize the files in your assets directory
* `gulp watch` — Compile assets when file changes are made
* `gulp --production` — Compile assets for production (no source maps).

### Theme Features, Customization and Setup

Edit `lib/setup.php` to enable or disable theme features, setup navigation menus, post thumbnail sizes, post formats, and sidebars.

### Documentation

Sage documentation is available at [https://roots.io/sage/docs/](https://roots.io/sage/docs/).

### Theme Features

* [gulp](http://gulpjs.com/) build script that compiles both Sass and Less, checks for JavaScript errors, optimizes images, and concatenates and minifies files
* [Bower](http://bower.io/) for front-end package management
* [asset-builder](https://github.com/austinpray/asset-builder) for the JSON file based asset pipeline
* [Bootstrap](http://getbootstrap.com/)
* [BrowserSync](http://www.browsersync.io/) for keeping multiple browsers and devices synchronized while testing, along with injecting updated CSS and JS into your browser while you're developing


## Additional Plugins

| Name                      | Plugin Link
| ------------------------- | ------------- |
| All-in-One WP Migration   |
| Custom Post Type UI       |
| Advanced Custom Fields    | [nodejs.org](http://nodejs.org/)
| Beaver Builder            | [php.net](http://php.net/manual/en/install.php)