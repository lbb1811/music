# music

> music player

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## 小结

### 章节模块

#### 第1章 课程内容介绍

包括课程概述、课程安排、学习前提、讲授方式等方面的介绍，最后演示了整个音乐App的功能，让同学们对课程项目有一个直观的了解。

 1-1 导学  
 1-2 课前必读（源码获取方式）  

#### 第2章 项目准备工作  

包括项目需求分析、脚手架初始化代码、项目目录介绍及图标字体、公共样式等资源的准备。

 2-1 需求分析  
 2-2 Vue-cli脚手架安装  
 2-3 项目目录介绍及图标字体、公共样式等资源准备  

#### 第3章 页面骨架开发

包括页面入口、header 组件的编写、路由配置及顶导 tab 组件开发。

 3-1 页面入口+header 组件的编写  
 3-2 路由配置+ tab 顶导组件开发  

#### 第4章 推荐页面开发

包括 jsonp 原理介绍和 Promise 封装、轮播图组件开发、歌单接口数据分析和抓取、axios 介绍和后端接口代理、歌单列表组件开发和数据应用、scroll 组件的抽象和应用、vue-lazyloader 懒加载插件的介绍和应用、loading 基础组件开发和应用。...

 4-1 页面简介+轮播图数据分析  
 4-2 jsonp原理介绍+Promise封装  
 4-3 jsonp的应用+轮播图数据抓取  
 4-4 轮播图组件实现（上)  
 4-5 轮播图组件实现（中)  
 4-6 轮播图组件实现（下）  
 4-7 歌单数据接口分析  
 4-8 axios 介绍和后端接口代理  
 4-9 歌单列表组件开发和数据的应用  
 4-10 scroll 组件的抽象和应用（上）  
 4-11 scroll 组件的抽象和应用（下）  
 4-12 vue-lazyload 懒加载插件介绍和应用  
 4-13 loading 基础组件的开发和应用  

#### 第5章 歌手页面开发

包括歌手数据的抓取和处理、Singer 类的封装、类通讯录组件 listview开发和应用。

 5-1 歌手页面布局和设计讲解  
 5-2 歌手数据接口抓取  
 5-3 歌手数据处理和 Singer 类的封装  
 5-4 listview 基础组件的开发和应用-滚动列表实现  
 5-5 listview 基础组件的开发和应用-右侧快速入口实现（1）  
 5-6 listview 基础组件的开发和应用-右侧快速入口实现（2）  
 5-7 listview 基础组件的开发和应用-右侧快速入口实现（3）  
 5-8 listview 基础组件的开发和应用-右侧快速入口实现（4）  
 5-9 listview 基础组件的开发和应用-滚动固定标题实现（上）  
 5-10 listview 基础组件的开发和应用-滚动固定标题实现（下）  

#### 第6章 歌手详情页开发

包括子路由的配置及转场动画实现、Vuex 的介绍、Vuex 初始化歌手数据的配置、歌手详情页数据抓取和处理、Song 类的封装、music-list 组件开发。

 6-1 歌手详情页布局和设计详解  
 6-2 子路由配置以及转场动画实现  
 6-3 初识 Vuex  
 6-4 Vuex 初始化及歌手数据的配置  
 6-5 歌手详情数据抓取  
 6-6 歌手详情数据处理和Song类的封装（上）  
 6-7 歌手详情数据处理和Song类的封装（下）  
 6-8 music-list 组件开发（1）  
 6-9 music-list 组件开发（2）  
 6-10 music-list 组件开发（3）  
 6-11 music-list 组件开发（4）  
 6-12 music-list 组件开发（5）  
 6-13 music-list 组件开发（6）  
 6-14 music-list 组件开发（7）  

#### 第7章 播放器内置组件开发

包括播放器 Vuex 数据设计和相关应用、播放器基础样式及歌曲数据应用、	播放器展开收起动画的实现、播放器前进后退功能实现、播放器播放时间获取和更新、progress-bar 进度条组件开发、progress-circle 圆形进度条组件开发、播放器模式切换功能实现、播放器歌词数据抓取和解析、播放器歌词左右滑动的实现、播放器底部播...

 7-1 播放器页面设计详解  
 7-2 播放器Vuex数据设计  
 7-3 播放器Vuex的相关应用  
 7-4 播放器基础样式及歌曲数据的应用  
 7-5 播放器展开收起动画（上）  
 7-6 播放器展开收起动画（中）  
 7-7 播放器展开收起动画（下）  
 7-8 播放器歌曲播放功能实现  
 7-9 播放器歌曲前进后退功能实现（上）  
 7-10 播放器歌曲前进后退功能实现（下）  
 7-11 播放器播放时间获取和更新  
 7-12 播放器progress-bar进度条组件实现（上）  
 7-13 播放器progress-bar进度条组件实现（中）  
 7-14 播放器progress-bar进度条组件实现（下）  
 7-15 播放器progress-circle 圆形进度条组件实现  
 7-16 播放器模式切换功能实现（上）  
 7-17 播放器模式切换功能实现（中）  
 7-18 播放器模式切换功能实现（下）  
 7-19 播放器歌词数据抓取  
 7-20 播放器歌词数据解析  
 7-21 播放器歌词滚动列表实现  
 7-22 播放器歌词左右滑动实现（上）  
 7-23 播放器歌词左右滑动实现（下）  
 7-24 播放器歌词剩余功能实现  
 7-25 播放器底部播放器适配+mixin的应用  

#### 第8章 歌单页面开发

包括歌单页面的布局介绍、Vuex 实现路由数据通讯、歌单详情页数据抓取和处理。

 8-1 歌单详情页布局介绍及Vuex实现路由数据通讯  
 8-2 歌单详情页数据抓取  
 8-3 歌单详情页数据的处理和应用  

#### 第9章 排行榜及详情页开发

包括排行榜布局介绍、排行榜数据抓取和应用、榜单详情页布局介绍、Vuex 实现路由数据通讯、榜单详情页数据抓取和应用。

 9-1 排行页面布局介绍及排行榜数据抓取  
 9-2 排行页排行榜数据应用  
 9-3 榜单详情页布局介绍及Vuex实现路由数据通讯  
 9-4 榜单详情页数据抓取和应用  
 9-5 带排行的song-list组件扩展和应用  

#### 第10章 搜索页面开发

包括search-box 组件开发、热门搜索数据抓取和应用、suggest 组件开发、搜索结果保存功能实现、search-list 组件开发、confirm 组件开发。

 10-1 搜索页面页面布局和功能介绍  
 10-2 搜索页面search-box组件开发  
 10-3 搜索页面热门搜索数据抓取和应用  
 10-4 搜索页面suggest组件开发（1）  
 10-5 搜索页面suggest组件开发（2）  
 10-6 搜索页面suggest组件开发（3）  
 10-7 搜索页面suggest组件开发（4）  
 10-8 搜索页面suggest组件开发（5）  
 10-9 搜索页面suggest组件开发（6）  
 10-10 搜索页面suggest组件开发（7）  
 10-11 搜索页面搜索结果保存功能实现（1）  
 10-12 搜索页面搜索结果保存功能实现（2）  
 10-13 搜索页面搜索结果保存功能实现（3）  
 10-14 搜索页面search-list 组件功能实现（上）  
 10-15 搜索页面search-list 组件功能实现（下）  
 10-16 搜索页面confirm 组件功能实现  
 10-17 搜索页面剩余功能实现（上）  
 10-18 搜索页面剩余功能实现（下）  

#### 第11章 歌曲列表组件

包括歌曲列表组件的显示和隐藏控制、播放列表的实现、player mixin 的抽象、 add-song 组件开发、top-list 组件开发、scroll 组件能力的扩展

 11-1 歌曲列表组件布局和功能介绍  
 11-2 歌曲列表组件显示和隐藏的控制  
 11-3 歌曲列表组件播放列表的实现（1）  
 11-4 歌曲列表组件播放列表的实现（2）  
 11-5 歌曲列表组件播放列表的实现（3）  
 11-6 歌曲列表组件播放列表的实现（4）  
 11-7 歌曲列表组件播放列表的实现（5）  
 11-8 歌曲列表组件 playerMixin的抽象（上）  
 11-9 歌曲列表组件 playerMixin的抽象（下）  
 11-10 歌曲列表组件add-song组件实现（1）  
 11-11 歌曲列表组件add-song组件实现（2）  
 11-12 歌曲列表组件add-song组件实现（3）  
 11-13 歌曲列表组件add-song组件实现（4）  
 11-14 歌曲列表组件add-song组件实现（5）  
 11-15 歌曲列表组件add-song组件实现（6）  
 11-16 歌曲列表组件top-list组件实现  
 11-17 歌曲列表组件scroll组件能力的扩展  

#### 第12章 用户中心页面

包括收藏列表的 Vuex 数据设计与实现、收藏歌曲功能实现、页面功能开发。

 12-1 用户中心页面布局和功能介绍  
 12-2 用户中心页面收藏列表的Vuex数据设计和实现  
 12-3 用户中心页面收藏歌曲功能实现（上）  
 12-4 用户中心页面收藏歌曲功能实现（下）  
 12-5 用户中心页面剩余功能实现（上）  
 12-6 用户中心页面剩余功能实现（下）  

#### 第13章 编译打包

包括播放内核小 bug 修复、项目编译打包及 node 服务调试、路由组件实现懒加载、Vue.js 升级到最新版。

 13-1 编译打包-播放内核小bug修复  
 13-2 编译打包-项目编译打包及node服务测试  
 13-3 编译打包-路由组件实现懒加载  
 13-4 编译打包-Vue.js升级到最新版  

#### 第14章 课程总结

包括移动端常用工具 charles 和 vconsole 的介绍、课程回顾。

 14-1 移动端调试工具和抓包工具介绍（上）  
 14-2 移动端调试工具和抓包工具介绍（下）  
 14-3 课程总结  

### 开发问题

1. [vue-music 使用better-scroll遇到轮播图不能自动轮播](https://www.cnblogs.com/shengnan-2017/p/9103270.html)

better-scroll新版本参数发生变化。可查阅官方文档。

2. [`this.$refs.list.style.bottom = bottom` 不能这样设置](https://blog.csdn.net/tangxiujiang/article/details/80660819)

应该写成：  `this.$refs.list.$el.style.bottom = bottom`  

3. [获取音乐播放源地址](https://blog.csdn.net/TCF_JingFeng/article/details/86739589)

播放源

4. [懒加载](https://www.cnblogs.com/lijuntao/p/7777581.html)

懒加载