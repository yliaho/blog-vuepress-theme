# vuepress-theme-valle

> Simple [VuePress](https://github.com/vuejs/vuepress) theme with blogging support.

_Under development, not ready for use._

## Installing

* `yarn install vuepress-theme-valle` or `npm install vuepress-theme-valle --save`
* Inside your existing VuePress project, create (if not present) `config.js` inside `.vuepress` folder.
* Add `theme: 'valle'` to the config object.
* That's it! VuePress now uses Valle as its theme.

## Theme Config

Theme specific options in VuePress config.

```javascript
module.exports = {
  // The theme uses `title` and `description`
  title: 'Yliaho',
  description: 'My vuesome blog',

  // To use the theme from the node dependencies.
  theme: 'valle'

  themeConfig: {
    // Author specific metadata. Used for homepage bio.
    author: {
      name: 'John Doe'
      social: {
        facebook: 'url',
        twitter: 'url',
        linkedin: 'url',
        instagram: 'url'
      }
    },
    // defaults to '/posts/' if postDir isn't provided.
    postDir: '/posts/'
  }
}
```
