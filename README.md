# 展e宝项目技术周报
![zeb](https://img.shields.io/github/license/mashape/apistatus.svg)
<br>
展e宝iOS项目组技术周报汇总，分享自己每周看到的好博客与收获～

***

项目成员：

* 七两（[blog](http://www.developfan.com)）
* 阿刚
* 亮亮

***

**目录**

- [Swift](#Swift)
  - [学习资料](#学习资料)
- [Object-C](#Object-C)
  - [多线程部分](#多线程部分)
  - [架构方向探索](#架构方向探索)
  - [AsyncDisplayKit异步渲染](#AsyncDisplayKit异步渲染)
  - [开源完整工程](#开源完整工程)
  - [源码解析](#源码解析)
  - [扩展](#扩展)
- [开发效率](#开发效率)
- [Apple通用部分](#Apple通用部分)
- [网络知识](#网络知识)
- [其他](#其他)
- [博客推荐](#博客推荐)
- [书籍阅读](#书籍阅读)


## Swift
### 学习资料
|资料网站          |简单概述         |贡献         |
|----------------|----------------|-------------|
|[swift.org](https://swift.org/documentation/#the-swift-programming-language)|官方的学习资料网站（英文）|七两|
|[Raywenderlich的Swift视频教程-英文](https://videos.raywenderlich.com/courses/90-programming-in-swift/lessons/1)|官方的学习资料网站（英文）|七两|

## Object-C
### 多线程部分
|博客链接          |简单概述         |贡献         |
|----------------|----------------|-------------|
|[探讨iOS开发中各种锁](https://juejin.im/entry/5859236061ff4b006cbaae2d)|讲诉了iOS开发中各种锁的性能|七两|
|[不再安全的 OSSpinLock](https://blog.ibireme.com/2016/01/16/spinlock_is_unsafe_in_ios/)|优先级反转问题|七两|
|[选择 GCD 还是 NSTimer ？](http://www.jianshu.com/p/0c050af6c5ee)|有关任务延迟或周期性执行的实现讨论|阿刚|
### 架构方向探索
|类别|博客链接          |简单概述         |贡献         |
|---|----------------|----------------|-------------|
|网络框架|                |               |              |
|缓存框架|                |               |              |
|图片框架|                |               |              |
|Hybrid框架|                |               |              |
|APM框架|                |               |              |
|设计模式|[关于埋点](http://www.jianshu.com/p/0497afdad36d)|可复用而且高度解耦的用户统计埋点实现|阿刚|
### AsyncDisplayKit异步渲染
|资料          |资料介绍         |贡献         |
|----------------|----------------|-------------|
### 开源完整工程
|名称          |推荐理由         |贡献         |
|----------------|----------------|-------------|
### 源码解析
|优秀SDK名称      |推荐理由|源码解读Blog与实践         |贡献         |
|----------------|-------|------------------------|-------------|

### 扩展
|博客链接          |简单概述         |贡献         |
|----------------|----------------|-------------|
|[谓词](http://www.jianshu.com/p/88be28860cde)|iOS中的谓词（NSPredicate）使用|阿刚|
|[用户默认设置](http://www.cnblogs.com/azuo/p/5090718.html?utm_source=tuicool&utm_medium=referral)|iOS中的Setting中的用户默认设置|七两|
|[用户默认设置具体属性](http://www.jianshu.com/p/9e1b21789076)|iOS中的Setting中的用户默认设置的具体属性解析|七两|

## 开发效率
|博客链接          |简单概述         |贡献         |
|----------------|----------------|-------------|
|[多个Target的使用](http://www.jianshu.com/p/d1608ff946a9)|讲述了iOS开发中多个Target的使用|阿刚|
|[Xcode Search功能详解](http://holko.pl/2016/04/26/xcode-search/)|iOS中搜索功能的深入|七两|
|[iOS高效调试](http://www.jianshu.com/p/a4ae30a10fb8)|断点的高级调试|七两|
|[与调试器共舞 - LLDB 的华尔兹](https://objccn.io/issue-19-2/)|LLDB调试器的高级使用|七两|
|[Swift Playground Markdown 的支持](http://blog.csdn.net/hello_hwc/article/details/53966889)|Swift Playground Markdown 的支持|七两|

## Apple通用部分
|博客链接          |简单概述         |贡献         |
|----------------|----------------|-------------|
|[iOS App签名的原理](www.cocoachina.com/ios/20170602/19427.html)|bang大神讲诉了app签名的基本原理与由来|七两|
|[iOS App后台运行](http://blog.csdn.net/u011270282/article/details/68066730)|后台运行实现总结|阿刚|
|[iOS核心动画高级技巧](https://www.kancloud.cn/manual/ios/97759)|Core Animation介绍,关于calayer的用法，以及隐显式动画，以及图层性能的处理|亮亮|
## 网络知识
|博客链接          |简单概述         |贡献         |
|----------------|----------------|-------------|
|[DNS原理入门](http://www.ruanyifeng.com/blog/2016/06/dns.html)|讲的还是通俗易懂的|七两|
|[互联网协议入门](http://www.ruanyifeng.com/blog/2012/05/internet_protocol_suite_part_i.html)|对互联网的分层进行了原理性的讲诉，强烈推荐|七两|
|[“HTTPS”安全在哪里？](http://www.cnblogs.com/bugly/p/5543417.html)|通俗易懂的解释HTTPS的工作机制|七两|

## 其他
|博客链接          |简单概述         |贡献         |
|----------------|----------------|-------------|
|[生成git标签](https://shields.io)|git上面readme中的标签生成|七两|
|[使用hexo搭建gitpage博客](https://linghucong.js.org/2016/04/15/2016-04-15-hexo-github-pages-blog/)|用hexo免费搭建自己的博客|七两|
## 博客推荐
|博客             |博主信息        |贡献         |
|----------------|----------------|-------------|
|[ibireme](https://blog.ibireme.com/)|YYKit的开发者，文章虽少，每篇经典透彻|七两|
|[网易乐得技术团队](http://tech.lede.com/2017/02/15/rd/iOS/iOS_NSURLProtocol/)|网易乐得技术团队|七两|
|[喵神](http://onevcat.com/)|喵神|七两|
|[腾讯bugly](http://www.cnblogs.com/bugly/)|腾讯bugly|七两|
|[Casa](https://casatwy.com/archives.html)|Casa|七两|
|[阿毛的蛋疼地](http://xiangwangfeng.com/)|阿毛的蛋疼地|七两|
|[美团点评技术团队](https://tech.meituan.com/)|美团点评技术团队|七两|
|[百度HI团队](https://github.com/BaiduHiDeviOS/iOS-Tech-Weekly)|百度HI团队|七两|
|[FaceBookiOS技术团队blog](https://code.facebook.com/ios/)|FaceBookiOS技术团队blog|七两|
|[巧神](http://blog.devtang.com/)|唐巧|七两|
|[nshipster](http://nshipster.cn/)|nshipster.cn|七两|
|[OBJC中国](http://www.objccn.io/)|OBJC中国|七两|
|[bang](http://blog.cnbang.net/)|JSPatch开发者|七两|

## 书籍阅读
|书名             |书中内容概述        |贡献         |推荐星数（满星：5星）      |
|----------------|----------------|-------------|-----------|
|iOS开发进阶|简单介绍了开发中的常用的工具，block讲的并不是很透彻|七两|3星|
|iOS核心开发手册[美·Erica]|介绍了开发中常见的一些问题，并且提供详细的案例解析|七两|4.5星|
|程序员的自我修养|介绍的是一个应用启动时，处理的事情，虽然主要讲诉的是windows下的启动，但很有借鉴意义|七两|4星|




