# eslint-plugin-no-js

This is an ESLint plugin to disable JavaScript.

## Installing

`npm install eslint-plugin-no-js --save-dev`

## ESLint Rules

### no-js

There's no reason to use JavaScript.

### no-jsx

JSX is for PHP-lovers. We don't need that!

## Sample Configuration File

Here's a sample ESLint configuration file that activates these rules:

```
{
  "plugins": [
    "no-js"
  ],
  "rules": {
    "no-js/no-js": 2,
    "no-js/no-jsx": 2
  }
}
```
