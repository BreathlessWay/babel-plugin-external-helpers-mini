# fork from @babel/plugin-external-helpers

> This plugin contains helper functions that’ll be placed at the top of the generated code

See our website [@babel/plugin-external-helpers](https://babeljs.io/docs/en/next/babel-plugin-external-helpers.html) for more information.

> 为了解决生成的`babelHelpers`在小程序中`undefined`，将`babelHelpers`改成`global.babelHelpers`，可以自定义前缀

```
options:{
    helperVersion = "7.0.0-beta.0",
    whitelist = false,
    prefix='global'  // 自定义前缀
}
```

## Install

Using npm:

```sh
npm install --save-dev @breathlessway/babel-plugin-external-helpers-mini
```

or using yarn:

```sh
yarn add @breathlessway/babel-plugin-external-helpers-mini --dev
```
