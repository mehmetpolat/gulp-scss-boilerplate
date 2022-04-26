# Gulp   STARTER TEMPLATE
### Note

The `docs` folder is for demo purposes only.

Changes should be commited to `src` files only.

The `dist` folder is not kept in source control.

### How to use

The template is built with Sass and Gulp build system with these features:

-	Handlebars HTML templates with Panini – a super simple flat file generator for use with Gulp. It compiles a series of HTML pages using a common layout. These pages can also include HTML partials, external Handlebars helpers, or external data as JSON or YAML.
-	Sass compilation, prefixing with autoprefixer, and javaScript concatenation
-	Built-in BrowserSync server - will automatically reload your page when files are changed. It also live-injects CSS changes when you save a Sass file. This task runs continuously and defaults to localhost.
-	For production builds - CSS compression, JavaScript compression, Image compression and more.

### Requirements

To use this template, your computer needs:

-	Node.js is used to run the build processes. https://nodejs.org/en/download/
- Run ` node -v ` in the terminal
-	npm (Node comes with npm installed so you should have a version of npm.) Used to manage development dependencies.
-  Run ` npm -v`  in the terminal
-	Gulp – task runner
	`npm install -g gulp`
-	Run `gulp -v ` in the terminal

### Installing:

- Clone this repo: `git clone https://github.com/johndavemanuel/bootstrap-gulp-starter-template.git`
- Navigate into the repo directory: `cd bootstrap-gulp-starter-template`
- Install all node packages: `npm install`
- Run `gulp development`
- Your site is now viewable at this URL: http://localhost:3000
- To create compressed, production-ready assets run `gulp production`. This will delete everything in the dist folder and recreate all of your complied files. Never make updates directly into the dist folder as these files get overridden each time.

### Folder Structure:

- `dist/` - compiled distribution files
- `node_modules` - front-end dependencies
- `src/` - contains all of your core, working files—static assets, pages, templates, etc
- `src/assets/` - scss files, JS files, images, and fonts
- `src/data/` - external data (JSON or YAML)
- `src/layouts/` - HTML layouts templates
- `src/pages/` - site pages
- `src/partials/` - handlebars partials files.
- `gulpfile.js` - all task definitions
- `package.json` - handles the project dependencies
- `.htmllintrc` - handles the HTML lint rules
- `.sass-lint.yml` - handles the SCSS lint rules
- `reports` - txt generated file for accessibility issues

### Includes:
- [Fontawesome 5](https://fontawesome.com/)
- [Animate CSS](https://animate.style/)
- [RTL Support](https://github.com/tysonmatanich/directional-scss)

### Gulp Plugins:
- [gulp-accessibility](https://www.npmjs.com/package/gulp-accessibility)
- [gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer)
- [gulp-compile-handlebars](https://www.npmjs.com/package/gulp-compile-handlebars)
- [gulp-concat](https://www.npmjs.com/package/gulp-concat)
- [gulp-cssmin](https://www.npmjs.com/package/gulp-cssmin)
- [gulp-gh-pages](https://www.npmjs.com/package/gulp-gh-pages)
- [gulp-html-replace](https://www.npmjs.com/package/gulp-html-replace)
- [gulp-htmllint](https://www.npmjs.com/package/gulp-htmllint)
- [gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin)
- [gulp-jshint](https://www.npmjs.com/package/gulp-jshint)
- [gulp-newer](https://www.npmjs.com/package/gulp-newer)
- [gulp-pretty-html](https://www.npmjs.com/package/gulp-pretty-html)
- [gulp-purgecss](https://www.npmjs.com/package/gulp-purgecss)
- [gulp-remove-code](https://www.npmjs.com/package/gulp-remove-code)
- [gulp-remove-logging](https://www.npmjs.com/package/gulp-remove-logging)
- [gulp-rename](https://www.npmjs.com/package/gulp-rename)
- [gulp-sass](https://www.npmjs.com/package/gulp-sass)
- [gulp-sass-lint](https://www.npmjs.com/package/gulp-sass-lint)
- [gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps)
- [gulp-uglify](https://www.npmjs.com/package/gulp-uglify)
- [gulp-babel](https://www.npmjs.com/package/gulp-babel)

### Additional Resources:
- [Sass: Syntactically Awesome Style Sheets](http://sass-lang.com/)
- [Bootstrap](https://getbootstrap.com/)
- [Handlebars](http://handlebarsjs.com/)
- [Panini](https://github.com/zurb/panini)
- [Gulp](https://gulpjs.org/getting-started)

### License

[MIT](LICENSE)

<a href="https://www.buymeacoffee.com/mpolat3" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

