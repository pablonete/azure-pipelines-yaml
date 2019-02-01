# node-js-with-grunt

The best project ever.

## Getting Started
### On the server
Install the module with: `npm install node-js-with-grunt`

```javascript
var node_js_with_grunt = require('node-js-with-grunt');
node_js_with_grunt.awesome(); // "awesome"
```

### In the browser
Download the [production version][min] or the [development version][max].

[min]: https://raw.github.com/pablonete/azure-pipelines-yaml/master/dist/node-js-with-grunt.min.js
[max]: https://raw.github.com/pablonete/azure-pipelines-yaml/master/dist/node-js-with-grunt.js

In your web page:

```html
<script src="dist/node-js-with-grunt.min.js"></script>
<script>
awesome(); // "awesome"
</script>
```

In your code, you can attach node-js-with-grunt's methods to any object.

```html
<script>
var exports = Bocoup.utils;
</script>
<script src="dist/node-js-with-grunt.min.js"></script>
<script>
Bocoup.utils.awesome(); // "awesome"
</script>
```

## Documentation
_(Coming soon)_

## Examples
_(Coming soon)_

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

_Also, please don't edit files in the "dist" subdirectory as they are generated via Grunt. You'll find source code in the "lib" subdirectory!_

## Release History
_(Nothing yet)_

## License
Copyright (c) 2019 Pablo Nunez Navarro  
Licensed under the MIT license.
