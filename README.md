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

new Ractive({
	el: "container",
	template: require("./template.ractive")
});
```
  
Specify file extensions:
```JavaScript
require("ractive-require-templates")(".mustache");
```
