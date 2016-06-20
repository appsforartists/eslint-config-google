# eslint-config-google [![Build Status](https://travis-ci.org/google/eslint-config-google.svg?branch=master)](https://travis-ci.org/google/eslint-config-google)

> ESLint [shareable
> config](http://eslint.org/docs/developer-guide/shareable-configs.html)
> for [Google's JavaScript Style
> Guide](http://google.github.io/styleguide/javascriptguide.xml)

Note that there are some [rules](https://github.com/google/eslint-config-
google/blob/master/index.js#L42-L46) the Google style guide isn't opinionated
about and you might want to set yourself.


## Install

```
$ npm install --save-dev eslint eslint-config-google
```


## Usage

Add some ESLint config to your `package.json`:

```json
{
	"scripts": {
		"lint": "eslint ."
	},
	"devDependencies": {
		"eslint": "^2.7.0",
		"eslint-config-google": "^0.5.0"
	},
	"eslintConfig": {
		"extends": "google"
	}
}
```

Then lint with `$ npm run lint`.


## Notes

- We try to be supportive of the JavaScript ecosystem, even for projects
  we don't use internally.  Therefore, we've applied the spirit of our [JS Style
  Guide](https://google.github.io/styleguide/javascriptguide.xml) to
  [JSX](https://facebook.github.io/jsx/) too.  Of course, if you don't use JSX,
  these extra rules will be ignored.


## License

Apache-2 © Google
