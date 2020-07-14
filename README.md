# gridsome-remark-table-align
Gridsome Remark plugin move the `table` align defintion to the `tableCell` definition.

With this changes, you can use [@jammeryhq/gridsome-remark-classes](https://github.com/jammeryhq/gridsome-remark-classes) to add your own classes.


# Installation

```
npm install --save @jammeryhq/gridsome-remark-table-align
```

# Usage

```js
module.exports = {

  plugins: [
    {
      use: '@gridsome/source-filesystem',
      options: {
        typeName: 'Blog',
        path: './content/blog/**/*.md',
      }
    }
  ],

  transformers : {
    remark : {
      plugins : [
        '@jammeryhq/gridsome-remark-table-align'
      ]
    }
  }
}
```

# Documentation

You can find the complete documentation here: https://webstone.info/documentation/gridsome-remark-table-align
