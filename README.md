# poster-girl-l2d-2233-Frontend

2233 娘的 Live2D 看板娘纯前端版，将原项目的 php 后端 API 改为前端实现，并且去除了和 Wordpress 有关的部分，这样就可以在任何站点启用。

[Demo: https://ran-ying.github.io/poster-girl-l2d-2233-Frontend](https://ran-ying.github.io/poster-girl-l2d-2233-Frontend)

## 使用方法

1. 将 `index.html` 下的 `body` 部分源码复制到您的页面。
2. 将 `css`，`js`，`model` 文件夹复制到您的托管服务器。

## 注意

请注意，考虑到用户访问体验，我们移除了移动端加载。如果有此需求，请将 `css/waifu.min.css` 文件的第 `10` 行删除。

一言部分实现在 `js/waifu-tips.js` 的 `69-73` 行，如果此 API 失效，请更换新的 API 源。

另外，服务器需要允许下列 MIME 类型才可以正常使用：.json / .moc / .mtn

## 开源许可证

本项目基于 [poster-girl-l2d-2233](https://github.com/xb2016/poster-girl-l2d-2233) 开发。

由于原项目使用 GPL 2.0 协议，故本项目也采用相同的开源协议进行授权。
