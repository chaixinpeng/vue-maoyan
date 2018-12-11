## 前言

我是做php的，最早接触的大部分项目都是要前端写好的页面整合到后端模版，css,js分别做抽离，之后上线。但是整合期间，你可能会发现页面文字不折行，浏览器兼容，js效果不对等等，但又不想老是麻烦前端修改，于是也开始走上前端之路。

2016年左右吧，开始感觉到前端领域发展很快，稍不留神就会跟不上前端节奏，不知道大家这样同样的疑问？刚开始去学前端到底该去学什么，一堆的名词。当时我们还在用jQuery的时候，Angular.js出现了 刚打算去学Angular React,Vue也横空出世了 设计模式最早也从MVC（Backbone.js）到MVP 再到现在MVVM,构建工具也是grunt,glup,到现在的webpack 或者rollup。

后来发现了，其实还是句老话，基础是最重要的，不应该技术什么火学什么，把基础打牢比一切都重要。举几个印象很深的例子。

- 当初想做前端就是想去写一些比较有意思的效果，之后css,js学了一段时间后，去翻看一些效果源码，发现里面很多用到了勾股定理，摩擦力，矩阵，圆，堆栈，概率啥的。这些东西都是我们上学都接触到的。所以想做好前端一些数学，物理，数据结构，算法也是要不可缺少的。

- 之前跟一个朋友创业，负责技术是一个外企的架构师，一直底层C语言底层开发。做项目的时候我负责做接口开发，他负责前端，我想他应该没怎么接触过js，然而我们一块做开发的过程中，人家一个星期就把没接触过Angular就吃的比较透彻了。然后用ionic打包app上线。当时网上还没有太多的这种Angular ionic的资料。
所以英文还是一定要好，基础要牢。

- 最后大家没事的时候推荐去看看 [张鑫旭的博客](https://www.zhangxinxu.com/wordpress/) 他对于一个技术点是研究的特别细，相信看完会有比较大的收获。

## 为什么想写这个项目？

- 这一两年趁业余时间接触了Vue、React，平时也都是拿小功能练练手，知识点比较碎。想借个项目梳理一下,把一些移动端很细的技术点都融进这个项目中。

- 帮助刚学习vue的同学，能够能快的上手项目。vue基本上都是要运用各种全家桶技术栈，所以这个可以帮助刚学习的同学更好的掌握Vue各个基础知识点和各种全家桶技术的结合的项目。

- 很多同学应该有这个疑问，看完vue文档之后，vue的项目怎么合理搭建目录，这个帮刚准备写vue的项目的目录结构能够很清晰的划分。

## Vue、React技术选型

Vue、React无论哪个都能实现我们市面上常见的网站。上手难度Vue相对React要简单点，初步接触这两个框架，vue中文文档资料相对react好找。两个也都是MVVM,组件化开发。其实一个框架用好了，另外一个也很快能上手。我们这里采用vue开发。

## 技术栈

Vue2.5 + Vuex + Vue Router + axios + Es6 + stylus + flex + Webpack + ESlint + git


## 都包含什么
- 合理的项目目录规划
- Flex布局项目中使用
- iconfont使用
- 移动端点击穿透
- 图片懒加载
- 移动端1px边框问题
- 移动端2x,3x背景图问题
- 基础组件库如topbar、loading、弹出框、滚动条、城市选择等组件的封装
- Vue动画
- Promise
- axios获取数据
- Vuex的使用
- LocalStorge本地存储
- 异步组件
- ......

项目结束后也会跟大家分享一下深浅拷贝，Event Loop，MVVM 双向绑定,虚拟DOM，SSR，预渲染等相关的知识，详情可以看文档。

## 说明

?>看这个项目前能够用预备html,css,vue,es6,webpack的一些知识

项目仅作为学习使用，代码里面的组件库可以下载作为自己项目使用，代码会放到github上面，大家可以点击右上角那只猫跳转到github下载源代码。

大家都能坚持学习下去，有疑问的可以到github提issue，共同探讨学习。如果该项目对于您有所帮助，希望您可以点到github star 能支持一下 ^_^