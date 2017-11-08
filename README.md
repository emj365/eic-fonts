# Eic Fonts

## Useage

### install

```bash
npm install eic-fonts@<the-version-id> --save-dev
```

then require the Scss after other styles, the [webpack](https://webpack.github.io/) is needed to implement to require Scss in JSX.

```javascript
require('onsenui/css-components-src/src/onsen-css-components.css')
require('onsenui/css/onsenui.css')
require('eic-fonts/font.scss')
```

## How to Release

```bash
npm version v1.3.5 # new version id
git push --follow-tags
```

after that `circle.yml` will handle publish the npm package.
