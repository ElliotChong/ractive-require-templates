# Require Ractive templates

Require [Ractive](http://www.ractivejs.org/) templates within Node.js.

## Installation

```bash
$ npm install debug-plus
```

## Usage

Default usage supporting `ract`, `ractive`, and `html` file extensions:
```JavaScript
require("ractive-require-templates");
var Ractive = require("ractive");

var ractive = new Ractive({
	template: require("./template.ractive")
});

console.log(ractive.toHTML());
```

Specify file extensions:
```JavaScript
require("ractive-require-templates")(".ractstache");
```
