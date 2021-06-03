# Intro
My personal lint configs
## Lint
```bash
yarn add npm-run-all
```

```json
// package.json
{
  "lint:eslint": "eslint src/js/*.js",
  "lint:stylelint": "stylelint src/styles/**/*.scss",
  "lint": "run-p lint:stylelint lint:eslint"
}
```

# ESLint
## Dependencies
```bash
yarn add eslint eslint-config-airbnb-base eslint-plugin-import @babel/core @babel/eslint-parser
```

# StyleLint
## Dependencies
```bash
yarn add stylelint stylelint-config-prettier stylelint-config-sass-guidelines stylelint-config-standard stylelint-order stylelint-scss
```