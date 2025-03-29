[基于程序员鱼皮修改的本地看板娘](https://juejin.cn/post/7439232445470359552?searchId=202503291922287153499850D084DD4E05)

# Live2D Widget

![](https://forthebadge.com/images/badges/built-with-love.svg)
![](https://forthebadge.com/images/badges/uses-html.svg)
![](https://forthebadge.com/images/badges/made-with-javascript.svg)
![](https://forthebadge.com/images/badges/contains-cat-gifs.svg)
![](https://forthebadge.com/images/badges/powered-by-electricity.svg)
![](https://forthebadge.com/images/badges/makes-people-smile.svg)

[English](README.en.md)

## 特性

在网页中添加 Live2D 看板娘。兼容 PJAX，支持无刷新加载。

<img src="demo/screenshot-2.png" width="280"><img src="demo/screenshot-3.png" width="280"><img src="demo/screenshot-1.png" width="270">

（注：以上人物模型仅供展示之用，本仓库并不包含任何模型。）

你也可以查看示例网页：

- 在 [米米的博客](https://zhangshuqiao.org) 的左下角可查看效果
- [demo/demo.html](https://live2d-widget.pages.dev/demo/demo)，展现基础功能
- [demo/login.html](https://live2d-widget.pages.dev/demo/login)，仿 NPM 的登陆界面

## 使用

如果你是小白，或者只需要最基础的功能，那么只用将这一行代码加入 html 页面的 `head` 或 `body` 中，即可加载看板娘：

```xml
<script src="https://fastly.jsdelivr.net/npm/live2d-widgets@0/autoload.js"></script>
```

添加代码的位置取决于你的网站的构建方式。例如，如果你使用的是 [Hexo](https://hexo.io)，那么需要在主题的模版文件中添加以上代码。对于用各种模版引擎生成的页面，修改方法类似。  
如果网站启用了 PJAX，由于看板娘不必每页刷新，需要注意将该脚本放到 PJAX 刷新区域之外。

**但是！我们强烈推荐自己进行配置，让看板娘更加适合你的网站！**  
如果你有兴趣自己折腾的话，请看下面的详细说明。
