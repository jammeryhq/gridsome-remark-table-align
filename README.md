<div align="center">

<a href="https://www.jammeryhq.com" title="JammeryHQ" target="_blank">

  <img src="https://jammeryhq.com/jammeryhq.png" width="128" />
  
</a>

<p>
Fast-track your JAMstack development & learning
</p>
</div>

<hr />

# About this plugin

Gridsome Remark plugin move the `table` align defintion to the `tableCell` definition.

With this changes, you can use [@jammeryhq/gridsome-remark-classes](https://github.com/jammeryhq/gridsome-remark-classes) to add your own classes.

# Installation

```bash
npm install @jammeryhq/gridsome-remark-table-align

# or

yarn add @jammeryhq/gridsome-remark-table-align
```

# How to use

```js
//gridsome.config.js

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
