# 仿朋友圈集赞页面生成

[去这里使用](https://pyq.jzzz66.cn/about.html)

此工具是一个前端菜鸟初学者为了更好的学习前端，练手项目时所写的。  
开源让大家相互学习，指点一下代码可优化的地方。  
使用 [uniapp](https://uniapp.dcloud.io/) 写的，目前只兼容了 h5，后续有空再兼容微信小程序。  
可以通过填写发表者信息或者根据截图生成仿微信朋友圈的集赞页面。  
总共可以生成 3 种样式。

- 图文样式
- 链接样式
- 主图样式

<img style="width: 800px;" src="./gitImg/pyqstyle.png" />

## 如何运行

- 克隆项目到本地

```
git clone https://github.com/zxb1655/weipyq
```

- 安装依赖

```
yarn
```

- 运行项目

```
yarn dev:h5
```

- 打包项目

```
yarn build:h5
```

## 开源免责声明

本工具仅可用于**前端个人学习，前端项目练手**，请不要用于以下用途：

- 将生成的截图用于**造谣诽谤、微商宣传**等非法或令人反感的用途
- 使用各种方式大量批量生成截图
- 将其用于商业用途，源代码或生成的截图有偿售卖
- 以 **“关注 ○○，发送 ○○ 获取工具地址”** 等方式为自己的公众号**引流**

当你使用时，你应该确定你可以接受向他人发送该截图将会带来的后果和影响，否则请不要使用本工具。

### 怎么获取微信文章详情？

- 目前使用的获取公众号文章的封面图和标题的 API 是我自己用 node 写的小程序，仅仅只是获取封面和标题。已经设置允许跨域，可以直接调用这个接口获取信息。

### 生成头像是从哪来的？

- 头像都是我自己手动从 [我要个性网](https://www.woyaogexing.com/) 转存的。如果你在此工具中发现了你正在使用的头像则纯属巧合。
