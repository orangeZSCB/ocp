<h1 align="center">橙 OCP - 专为全龄人开放的备案平台</h1>

总之了啦，这个备案系统就是图一乐。

灵感来源于萌国 ICP，自己因为~~该死的虚荣心~~搓了一份

欢迎各位大佬蒟蒻们前来围观。

## ~~抄袭~~ 借鉴了哪些东西

1. 谭景元大佬写的一些东西：`tjy-gitnub/nikov, tjy-gitnub/tapple` 等GitHub站内项目
2. 萌ICP备案：`https://icp.gov.moe/` [点击跳转](https://icp.gov.moe/)

## 运行

此项目分为前端和后端，前端是基于 HTML 和 CSS 的纯静态注册网页，托管到 GitHub 上面超级合适。

后端是使用 Python Flask 编写的 API，存放在服务器里面，用来存放备案数据。（当然如果你有时间配置的话可以放到 GitHub Action 之中）

前端只需要将本仓库的 main 分支在 GitHub Pages 中设置以下即可，后端需要自行安装 requirement.txt 中的轮子。（好像也就只有一个 flask 来着...）
