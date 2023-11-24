# docsify-paper
A template for using Docsify to organize your paper and code

## 1. 修改`index.html`
```html
  <title>Document</title>
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <meta name="description" content="Description">
```
将其中的title和description修改为自己的文档信息。


## 2. 添加内容
1. 修改`index.html`中的`data-dir`为`docs/contents`。
1. 在`docs/contents`目录下添加内容，然后在`_sidebar.md`中添加链接。

## [可选] 3.本地调试
如果你希望在本地对模版进行修改和调试，可以使用以下命令：
```bash
npm i docsify-cli -g
docsify serve docs
```