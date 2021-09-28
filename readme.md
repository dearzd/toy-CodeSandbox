# Toy CodeSandbox

使用 monaco-editor 实现在线编辑 vue 代码，试试预览效果。

## 功能

- 网页编辑 vue 代码，点击 preview 按钮，fetch 发送请求，后端 NodeJS 接受请求编译文件，通知前端渲染页面。
- 特色1：支持多文件编辑（初始化代码为 vue-cli 初始化代码平铺），编辑器多 tab 切换，不同文件类型的 icon 高亮。
- 特色2：支持新建文件，上传 image 在代码中使用，删除文件，以及导出所有代码为 Zip。
- 特色3：除了支持编辑代码外，还支持预览图片。

## 如何运行
1. `npm instasll`
2. `npm run server`
3. `go to http://localhost:8080`

## Gif 演示

![Gif Demo](./demo.gif)
