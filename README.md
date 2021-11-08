# lint config

## Use in other projects

```cli
npm install --save-de eslint-config-lint
```

### .eslinrtc

create file .eslintrc and extends from this ext:

```js
{
  "extends": "eslint-config-lint"
}
```

### install additional plugin

```cli
npm install --save-dev eslint-plugin-react
```

### Add prettier

add in package.json

```json
  "prettier": "eslint-config-lint/prettier.config.js",
```
