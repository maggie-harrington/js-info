## Javascript Project Setup

### NPM / Gulp:

Make sure you are in top level of project directory

Create .gitignore file containing:
  node_modules/
  DS_Store
  build/
  tmp/
  bower_components/
  .env

`npm init` (sets up npm, creates package.json)

Enter title etc when prompted (creates gulpfile.js)

Run the following installs:

`npm install gulp --save-dev`
`npm install browserify --save-dev`
`npm install vinyl-source-stream --save-dev`
`npm install gulp-concat --save-dev`
`npm install gulp-uglify --save-dev`
`npm install gulp-util --save-dev`
`npm install del --save-dev`
`npm install jshint --save-dev`
`npm install gulp-jshint --save-dev`


`gulp jshint` -> linter, run to check for errors in js code
`gulp build` OR `gulp build --production` -> run to build/rebuild app.js file


### Bower:

`npm install bower -g`

`bower init` (sets up bower, creates bower.json)

`bower install jquery --save`
`bower install bootstrap --save`
`bower install moment --save`

`npm install bower-files --save-dev`

`gulp bowerJS` -> run to add new JS front-end dependencies


### BrowserSync

`npm install browser-sync --save-dev`

`gulp serve` -> run from top level project directory to launch server and run app

### Sass

`npm install gulp-sass gulp-sourcemaps --save-dev`


### API Keys

* Keep API keys separate in a local .env file, add .env to .gitignore and require link on js
* Include instructions on readme to create .env with unique API key
