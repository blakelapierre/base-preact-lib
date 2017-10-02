#base-preact-lib

A simple and highly configurable base project for Preact libraries.


````
$ git clone https://github.com/blakelapierre/base-preact-lib
$ cd base-node
$ npm install -g gulp-cli
$ npm install
````


###Building

````
$ gulp build
````

###Running

````
$ node .dist/index.js
````

Tests:
````
$ node .dist/tests/index.js
````

###Developing
This command will watch your source files for changes and run them through `jshint` and the transpiler when they change.

````
$ gulp watch
````

-----------
This command will do what `watch` does, but will also run your program after transpiling and will restart it after each transpile.

````
$ gulp dev
````