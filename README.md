﻿# 备忘录
    用于收录开发过程中开源库，优秀的文章，自己写的工具类等
## 目录 ##

- [性能优化](#性能优化)
- [高仿项目和完整的app](#高仿项目和完整的app)
- [服务器相关](#服务器相关)
- [构建布局UI](#构建布局ui)
- [webview](#webview)
- [自己封装的工具](#自己封装的工具)
- [IOS新功能适配](#ios新功能适配)

## 性能优化 ##
 - [iOS 保持界面流畅的技巧][1]
 - [如何让iOS 保持界面流畅技巧2][2]
 - [iOS图片加载速度极限优化—FastImageCache解析][3]
 - [Flexbox优化][4]-Flexbox     是W3C在2009年提出的一种新的前端页面布局，目前，它已经得到了所有浏览器的支持。而最早将这一页面布局方案引入iOS开发中的是开源库 AsyncDisplayKit。但随着React Native与Weex在动态化领域的兴起， 让iOS开发越来越多的接触到Flexbox 页面布局。相关文章：[FlexBoxLayout][5]、[Yoga][6]
 - [iOS小技巧总结][7] —— 在这里总结一些iOS开发中的小技巧，能大大方便我们的开发，持续更新。

## 高仿项目和完整的app ##

- [iOS 高仿少数派客户端 代码+思路讲解][8]
- [Github备忘录][9]

## 服务器相关 ##

- [Perfect for swift][10]

## 构建布局ui##

 - [Componentkit][11]-FaceBook推出的构造UI的新思路，相关文章[iOS：ComponentKit 使用总结][12]
 - [AsyncDisplayKit][13] - AsyncDisplayKit的基本使用单元是node. ASDisplayNode是一个UIView层之上的封装，就像UIView是对CALayer的封装一样。相关文章[AsyncDisplayKit使用详解][14]、* [AsyncDisplayKit 2.0 Objective-C 教程][15]、*[AsyncDisplayKit2.0教程(上)][16]、* [AsyncDisplayKit2.0教程(下)][17]、即刻技术团队的文章介绍【[AsyncDisplayKit介绍（一）原理和思路][18]、[AsyncDisplayKit介绍（二）布局系统][19]、[AsyncDisplayKit介绍（三）深度优化列表性能][20]】、[复杂布局介绍-AsyncDisplaykit2.0使用「复杂界面流畅性」][21]、比较优秀的教程[AsyncDisplayKit 教程：达到 60 FPS 的滚动帧率][22]、原理解释[iOS 保持界面流畅的技巧][23]

## webview ##

 - [WKWebView][24]-IOS8以后的web加载神器。相关文章[使用WKWebView替换UIWebView][25]、[UIWebview加载进度条实现][26]、[WKWebView进度条实现][27]、实战文章:[WKWebView与OC的交互][28]
 - UIWebView - [解决WebView与OC的交互（JSContext循环引用问题）][29]、[JavaScript和Objective-C交互的那些事(续)][30]、优雅的解决jscontenxt问题:[JS和UIWebview通过JavaScriptCore无法执行iOS本地方法解决方案][31];如果不需要兼容IOS7，可以使用新的WKWevView;


## 自己封装的工具 ##

1.XYYSegmentControl https://github.com/1273011249/XYYSegmentControl

简介：多页签显示，基于HMSegmentedControl再封装，便于使用

## ios新功能适配 ##

 1. IOS11适配
    - [你可能需要为你的APP适配iOS11][32]
    - [App界面适配iOS11][33]
    - [Xcode9下iOS11适配注意事项及无线部署调试][34]
    - [The file couldn’t be opened because you don’t have permission to view it][35]  
    - [iOS 11 安全区域适配总结][36]
    - [iPhone X 设计适配指南 & iOS 11 新特性][37]
    - [10分钟适配 iOS 11 & iPhone X][38]


  [1]: https://blog.ibireme.com/2015/11/12/smooth_user_interfaces_for_ios/
  [2]: http://www.cnblogs.com/ioriwellings/p/5011993.html
  [3]: http://blog.cnbang.net/tech/2578/
  [4]: http://www.cocoachina.com/ios/20170314/18878.html
  [5]: https://github.com/LPD-iOS/FlexBoxLayout
  [6]: https://github.com/facebook/yoga
  [7]: http://www.jianshu.com/p/4523eafb4cd4
  [8]: http://www.jianshu.com/p/1265eea814c6
  [9]: http://www.jianshu.com/p/5c16f21a74de
  [10]: https://github.com/PerfectlySoft/Perfect
  [11]: https://github.com/facebook/componentkit
  [12]: https://segmentfault.com/a/1190000002706612
  [13]: https://github.com/facebookarchive/AsyncDisplayKit
  [14]: http://www.jianshu.com/p/a6105e22d394
  [15]: http://blog.csdn.net/kmyhy/article/details/55656939
  [16]: http://blog.csdn.net/kmyhy/article/details/54632659
  [17]: http://blog.csdn.net/kmyhy/article/details/54846322
  [18]: https://zhuanlan.zhihu.com/p/25371361
  [19]: https://zhuanlan.zhihu.com/p/26283742
  [20]: https://zhuanlan.zhihu.com/p/29537687
  [21]: http://www.jianshu.com/p/afc69cd9e824
  [22]: http://www.cocoachina.com/swift/20141124/10298.html
  [23]: https://blog.ibireme.com/2015/11/12/smooth_user_interfaces_for_ios/
  [24]: https://github.com/XFIOSXiaoFeng/WKWebView
  [25]: http://www.jianshu.com/p/6ba2507445e4
  [26]: http://www.cnblogs.com/yajunLi/p/6292507.html
  [27]: http://www.jianshu.com/p/b32b9fb6cb0a
  [28]: http://www.jianshu.com/p/d8a8913d7e8e
  [29]: http://www.jianshu.com/p/94bd66874dba
  [30]: http://www.jianshu.com/p/939db6215436
  [31]: https://galileioo.github.io/posts/UIWebview-JS.html
  [32]: http://www.jianshu.com/p/370d82ba3939
  [33]: http://www.jianshu.com/p/352f101d6df1
  [34]: http://shizhifang886.blog.163.com/blog/static/30585110201482912125657/
  [35]: http://shizhifang886.blog.163.com/blog/static/30585110201482912125657/
  [36]: http://www.jianshu.com/p/efbc8619d56b
  [37]: https://mp.weixin.qq.com/s/7kM8Qiha7np6_QWfduxD-A
  [38]: http://www.cocoachina.com/ios/20170925/20642.html