---
sidebarDepth: 3
---

# vuepress-plugin-nprogress <GitHubLink repo="vuepress/vuepress-plugin-nprogress"/>

Use [nprogress](https://github.com/rstacruz/nprogress) in your VuePress site.

This plugin will show progress bar on the top when navigating to another page.

## Installation

```sh
npm install vuepress-plugin-nprogress
```

## Usage

### Use this plugin

Add `vuepress-plugin-nprogress` in your config file.

> See [official docs](https://v1.vuepress.vuejs.org/plugin/using-a-plugin.html)

```js
module.exports = {
  plugins: [
    'vuepress-plugin-nprogress',
  ],
}
```

### Custom color

Set `$nprogressColor` in `palette.styl` file to change the color of the progress bar. If not set, the color is set to `$accentColor` of VuePress.

> See [official docs](https://v1.vuepress.vuejs.org/config/#palette-styl)

```stylus
$nprogressColor = red

// by default:
// $nprogressColor ?= $accentColor
```
