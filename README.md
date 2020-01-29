
Documentation toolbox for your **javascript** / **typescript** projects based on JSDoc3 with **@category**, **@component** and **@optional** plugins.

This theme is based on the (better-docs)[https://github.com/SoftwareBrothers/better-docs] theme.

# Installation

```sh
npm install --save-dev connect-jsdoc-theme
```

# Theme Usage

## With command line

Assuming that you have [jsdoc](https://github.com/jsdoc/jsdoc) installed globally:

```
jsdoc your-documented-file.js -t ./node_modules/onnect-jsdoc-theme
```

## With npm and configuration file

In your projects package.json file - add a new script:

```
"script": {
  "docs": "jsdoc -c jsdoc.json"
}
```

in your `jsdoc.json` file, set the template:

```json
"opts": {
  "template": "node_modules/@cloudblueconnect/connect-jsdoc-theme"
}
```

For full documentation visit [https://github.com/SoftwareBrothers/better-docs](https://github.com/SoftwareBrothers/better-docs).