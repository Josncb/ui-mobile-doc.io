## npm安装

```
  npm install hr-chenbin-ui

```
并修改 vue.config.js 添加
```
css: {
    loaderOptions: {
      stylus: {
        'resolve url': true,
        'import': [
          './src/theme'
        ]
      }
    }
```
可以通过 src 目录下新建 theme.styl 以修改色值

#### 配置rem

 如需配置 rem 移动端适配 请安装 `amfe-flexible` 和 `postcss-px2rem`。

