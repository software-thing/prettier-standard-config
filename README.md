# 🎨 Prettier StandardJS config

This is a default configuration for Prettier to format code according to the StandardJS specification. In Havenworks by default, the [https://github.com/standard/ts-standard](`ts-standard`) package should be used so this is mainly used to format Svelte files.

Installation is very simple:

```bash
yarn add -D @havenworks/prettier-standard-config
```
Then just the configuration (the easiest way is to set it like this in your `package.json`):

```json
// package.json

{
  "prettier": "@havenworks/prettier-standard-config"
}
```
