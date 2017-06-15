# wp-theme-boilerplate

My boilerplate starting theme for WordPress development.

## Key features:

* based on [HTML5 Blank](http://html5blank.com) theme by [Todd Motto](http://toddmotto.com) // [@toddmotto](http://twitter.com/toddmotto)
* gulp task runner to build production files

## Getting Started with wp-theme-boilerplate

* Go to the Wordpress' theme folder (`.../wp-content/themes`)
* In CLI run: `git clone https://github.com/kobiak/wp-theme-boilerplate.git`
* `cd wp-theme-boilerplate` and then `npm install`

## Folder structure
.
├── src
|   ├── template
|   ├── images
|   ├── scss
|   └── js
|
├── README.md
├── package.json
└── gulpfile.js

## Gulp tasks

* `gulp php` to build PHP files
* `gulp css` to build CSS file
* `gulp js` to build JS file
* `gulp images` to process IMAGES 
* `gulp build` to build php, css and js
* `gulp watch` to watch for changes in files and live reload browser