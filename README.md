# Documentation

## Repositories

1. Use travis to run tests and linters before pull requests are allowed to be merged.
2. Use lowercase **kebab-case** for repository names ([what is kebab-case?](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles)).

## Architecture

## Coding Guidelines

Use this ist of preferred languages when coding if there isn't a good reason otherwise
* TypeScript
* JavaScript

### Typescript

1. Always use tslint. At the momemnt we extend the recommended config.
```javascript
// tslint.json
{
  "extends": [
  	"tslint:recommended"
  ]
}
```
