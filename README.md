JSON Lint
=========

Fork of pure JavaScript [jsonlinter](http://zaach.github.com/jsonlint/) by [Zach Carter](https://github.com/zaach) where is used callback function instead of `.parseError` property.

##Example of usage
```javascript
var jsonlint = require('jsonlint');
var jsonToParse = '{
    iAm: "JSON"
}'

jsonlint.parse(jsonToParse, function(errorMessage, hash) {
	//Do whatever you want with returned error
})
```
