
# wangEditor

## 介绍

**wangEditor** —— 轻量级 web 富文本编辑器，配置方便，使用简单。支持 IE10+ 浏览器。

- 官网：[www.wangEditor.com](http://www.wangeditor.com/)
- 文档：[www.kancloud.cn/wangfupeng/wangeditor3/332599](http://www.kancloud.cn/wangfupeng/wangeditor3/332599)
- 源码：[github.com/wangfupeng1988/wangEditor](https://github.com/wangfupeng1988/wangEditor) （欢迎 star）

![图片](http://images2015.cnblogs.com/blog/138012/201705/138012-20170530202905633-1840158981.png)

*查看 v2 版本的代码和文档点击[这里](https://github.com/wangfupeng1988/wangEditor/tree/v2)*


## 下载

- 直接下载：[https://github.com/wangfupeng1988/wangEditor/releases](https://github.com/wangfupeng1988/wangEditor/releases)
- 使用`npm`下载：`npm install wangeditor` （注意 `wangeditor` 全部是**小写字母**）
- 使用`bower`下载：`bower install wangEditor` （前提保证电脑已安装了`bower`）
- 使用CDN：[//unpkg.com/wangeditor/release/wangEditor.min.js](https://unpkg.com/wangeditor/release/wangEditor.min.js)


## 使用

```javascript
var E = window.wangEditor
var editor = new E('#div1')
editor.create()
```


## 运行 demo

- 下载源码 `git clone git@github.com:wangfupeng1988/wangEditor.git`
- 安装或者升级最新版本 node（最低`v6.x.x`）
- 进入目录，安装依赖包 `cd wangEditor && npm i`
- 安装包完成之后，windows 用户运行`npm run win-example`，Mac 用户运行`npm run example`
- 打开浏览器访问[localhost:3000/index.html](http://localhost:3000/index.html)
- 用于 React、vue 或者 angular 可查阅[文档](http://www.kancloud.cn/wangfupeng/wangeditor3/332599)中[其他](https://www.kancloud.cn/wangfupeng/wangeditor3/335783)章节中的相关介绍
