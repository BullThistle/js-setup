## Foundation

_Make sure that foundation cli is globally installed_

```
npm install -g foundation-cli
```

_Go to project directory set up foundation project_

```
foundation new
```

## Initialize npm
```
npm init
 
```

## Npm packages

```
npm install gulp --save-dev
npm install browserify --save-dev
npm install vinyl-source-stream --save-dev
npm install gulp-concat --save-dev
npm install gulp-uglify --save-dev
npm install gulp-util --save-dev
npm install del --save-dev
npm install gulp-jshint --save-dev
npm install babelify babel-preset-es2015 --save-dev
 
```

## Test Packages

```
npm install jasmine --save-dev
./node_modules/.bin/jasmine init
npm install watchify --save-dev
npm install karma --save-dev
npm install karma-jasmine jasmine-core --save-dev
npm install karma-chrome-launcher --save-dev
npm install karma-cli --save-dev
npm install karma-browserify --save-dev
npm install karma-jquery --save-dev
npm install karma-jasmine-html-reporter --save-dev
npm install -g karma-cli
npm install karma karma-coverage --save-dev
karma-coverage --save-dev
npm i nyc --save-dev
npm install browserify-istanbul
```
_Hit enter many times_
```
karma init
```
_Hit enter many times_
_copy gulpfile.js to project_

_copy karma.config file to project_ 

_set package.json "test" to "nyc karma start karma.conf.js istanbul"_

```
gulp build
 
```

