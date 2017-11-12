# PrestaShop Classic Theme Example hot module replacement


### Other
[Example Hot Module Replacement for `Webpack 1.x` Prestashop 1.7](https://github.com/retyui/prestashop-1.7-webpack-hot-module-replacement)

[Example Hot Module Replacement for `Webpack 2.x` Prestashop 1.7](https://github.com/retyui/prestashop-1.7-webpack-2-hot-module-replacement)

[Example Hot Module Replacement for `Webpack 3.x` Prestashop 1.7](https://github.com/retyui/prestashop-1.7-webpack-3-hot-module-replacement)


## If not working file watcher, add
```js
plugins.push(
  new webpack.OldWatchingPlugin()
);
```
in webpack.config.js, for webpack 1.12+ version.
Thx Damir Glax!


## Install :
```bash
cd _dev
npm install
# or
yarn 
```

## Start hot:
```bash
npm run hot
# or
yarn hot
```
## All changes:
https://github.com/retyui/prestashop-1.7-webpack-hot-module-replacement/commit/e25b5903f315609e7d4ec9a6c25a07be59c4c727
