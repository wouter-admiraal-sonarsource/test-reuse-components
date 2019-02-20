Test (S)CSS Re-use
==================

This is a POC for maintaining and re-using CSS and SCSS components across projects using `yarn`.

This package re-uses some variables and helpers from another package, namely: https://github.com/wouter-admiraal-sonarsource/test-css-component

To compile the SCSS files, call:

```sh
yarn install
yarn build:css
```

The result will be compiled to the `dist/` folder.

Checkout https://github.com/wouter-admiraal-sonarsource/test-css-component for more information.