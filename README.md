Note: Users of Vue.js version 1 please use [this package](https://www.npmjs.com/package/vue-formular) instead.

[![npm version](https://badge.fury.io/js/vue-form-2.svg)](https://badge.fury.io/js/vue-form-2)

This vue.js package offers a comperhensive solution for HTML form management, including presentation, validation and (optional) AJAX submission.
The presentation is based on [Bootstrap's form component](http://v4-alpha.getbootstrap.com/components/forms/).

Compilation requires [babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx).

Webpack users, use the following setup to compile the package's `jsx` files:
```js
loaders: [
    {
        test: /\.jsx?$/,
        loader: 'babel',
        exclude: /node_modules(?!\/(vue-form-2))/
    }
]
```

* [Documentation](https://matfish2.gitbooks.io/vue-form-2/content/)

