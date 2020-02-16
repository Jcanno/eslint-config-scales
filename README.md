# eslint-config-scales
ESLint config for JavaScript

[![npm package](https://img.shields.io/npm/v/eslint-config-scales.svg?style=flat-square)](https://www.npmjs.org/package/eslint-config-scales)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://www.npmjs.org/package/eslint-config-scales)

## Installation
```javascript
$ npm i -D eslint-config-scales
```

## Usage
If you installed `eslint-config-scales`, you can specify `scales` in the `extends` array of your `eslint-config.js` or `.eslintrc` file.
```js
{
	"extends": [ "scales" ],
	"rules": [
		// you can overwrite the rules in the extend
		// or add your additional rules
	]
}
```
You can also use `scales` config with `eslint:recommended` or any other eslint config, making sure to list `scales` last
```js
{
	"extends": [ "eslint:recommended", "scales" ],
	"rules": [
		// you can overwrite the rules in the extend
		// or add your additional rules
	]
}
```
## License

MIT