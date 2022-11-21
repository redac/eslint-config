My current ESLint configuration.

## Installation

```
npm install @redac/eslint-config --dev
```

## Usage

Once the `@redac/eslint-config` package is installed, you can use it by specifying `@redac` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

In `.eslintrc` :

```js
{
  "extends": "@redac",
  "rules": {
    // Additional, per-project rules...
  }
}
```
