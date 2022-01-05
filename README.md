# BUILD-TOOLS-BUCHELI-COURSE-CREATING-A-WEBPACK-CONFIG

## In order to pack one JavaScript file, follow the next steps:

* We define Webpack’s settings in an object defined using the module.exports syntax. We can define an empty one like so:
```
module.exports = {
 
}
```
* Now that we have a config file, we can set the mode:
```
module.exports = {
  mode: 'development'
}
```
* 'development' mode is used when we develop our app, producing a more readable version of the output. We switch to 'production' when we have a finished version, which makes the 
output less readable and more compact. 

* npm install --save-dev webpack webpack-cli
* npm run build
