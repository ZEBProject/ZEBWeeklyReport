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
- [头脑风暴](#头脑风暴)


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
|[pthread和NSThread](http://www.jianshu.com/p/d429b6802cdb)|iOS多线程之pthread和NSThread|阿刚|
|[GCD](http://www.jianshu.com/p/2d57c72016c6)|iOS多线程之GCD|阿刚|
|[GCD死锁](http://ios.jobbole.com/82622/)|五个案例让你明白GCD死锁|阿刚|
|[NSOperation](http://www.jianshu.com/p/c49556a22863)|iOS多线程之NSOperation|阿刚|
|[RunLoop](https://blog.ibireme.com/2015/05/18/runloop/)|深入理解RunLoop|阿刚|
### 架构方向探索
|类别|博客链接          |简单概述         |贡献         |
|---|----------------|----------------|-------------|
|网络框架|                |               |              |
|缓存框架|                |               |              |
|图片框架|                |               |              |
|Hybrid框架|                |               |              |
|APM框架|                |               |              |
||设计模式|[关于埋点](http://www.jianshu.com/p/0497afdad36d)|可复用而且高度解耦的用户统计埋点实现|阿刚|
|设计模式|                |               |              |
||适配器设计模式解耦|可复用而且高度解耦，由一个抽象的父类为中间层|七两|
||AOP设计模式|统一入口，有效的统一调用，增加分层|七两|
||单例模式的理解|正常开发或封装时，对于单例的一个使用理解|七两|
||统一导航的方式|对于模态／push／native／h5/混合页面的跳转逻辑统一（待续）|七两|
|组件化框架实现|                |               |              |
||组件化的探索|参考蘑菇街的设计思路（待续）|七两|
|本地Router的框架实现|                |               |              |


### AsyncDisplayKit异步渲染
|资料          |资料介绍         |贡献         |
|----------------|----------------|-------------|
### 开源完整工程
|名称          |推荐理由         |贡献         |
|----------------|----------------|-------------|
### 源码解析
|优秀SDK名称      |推荐理由|源码解读Blog与实践         |贡献         |
|----------------|-------|------------------------|-------------|
|YTKNetwork|猿题库技术团队对af的封装理解|（待完成）|七两|
|SDWebImage|经典的图片下载框架|（待完成）|七两|
|AFNetworking|经典的网络请求框架|（待完成）|七两|
|YYCache|yy大神设计的cache|（待完成）|七两|
|LuaViewSDK|阿里聚划算团队对动态解决方案的一种实践|（待完成）|七两|
|ALI-WAX|阿里对WAX框架的维护|（待完成）|七两|

### 扩展
|博客链接          |简单概述         |贡献         |
|----------------|----------------|-------------|
|[谓词](http://www.jianshu.com/p/88be28860cde)|iOS中的谓词（NSPredicate）使用|阿刚|
|[用户默认设置](http://www.cnblogs.com/azuo/p/5090718.html?utm_source=tuicool&utm_medium=referral)|iOS中的Setting中的用户默认设置|七两|
|[用户默认设置具体属性](http://www.jianshu.com/p/9e1b21789076)|iOS中的Setting中的用户默认设置的具体属性解析|七两|
|[iOS触摸事件与相应者链的解析]()|iOS触摸事件与相应者链的解析|七两|
|[摇一摇功能的实现](摇一摇功能的实现)|摇一摇功能的实现|七两|

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
|[iOS控件](http://www.jianshu.com/p/adbf1ed14ffc)|UI控件创建使用weak还是strong|阿刚|
|[圆角卡顿刨根问底](http://awhisper.github.io/2016/03/12/%E6%BB%9A%E5%8A%A8%E5%9C%86%E8%A7%92%E5%8D%A1%E9%A1%BF%E5%88%A8%E6%A0%B9%E9%97%AE%E5%BA%95/)|关于离屏渲染的深入理解|七两|
|[离屏渲染学习笔记](http://foggry.com/blog/2015/05/06/chi-ping-xuan-ran-xue-xi-bi-ji/?utm_source=tuicool)|关于离屏渲染的概念理解|七两|
|[深入理解iOS开发中的BitCode功能](http://www.jianshu.com/p/f42a33f5eb61)|理解bitcode的意思与作用|七两|
|[iOS 图文并茂的带你了解深拷贝与浅拷贝](http://www.cnblogs.com/beckwang0912/p/7212075.html)|图解深拷贝与浅拷贝|七两|
|[NSHashtable和NSMaptable](http://zhangbuhuai.com/nshashtable-and-nsmaptable/)|理解NSHashTable与NSMapTable|七两|
|[NSMapTable: 不只是一个能放weak指针的 NSDictionary](http://www.isaced.com/post-235.html)|理解NSMapTable|七两|
|[使用iOS AirPrint 让你的APP轻松实现打印功能](https://www.jianshu.com/p/f5863a1833d0)|Airprint的简单介绍|七两|
|[iOS MDM详解 — 初识和深入](https://www.jianshu.com/p/6112050ea31a)|MDM的简单介绍|七两|
|[Custom Container View Controller](http://www.cocoachina.com/industry/20140523/8528.html)|对于容器vc的较为深入的剖析|七两|
|[iOS5中UIViewController的新方法](http://blog.devtang.com/2012/02/06/new-methods-in-uiviewcontroller-of-ios5/)|介绍addChildViewController|七两|

## 网络知识
|博客链接          |简单概述         |贡献         |
|----------------|----------------|-------------|
|[DNS原理入门](http://www.ruanyifeng.com/blog/2016/06/dns.html)|讲的还是通俗易懂的|七两|
|[互联网协议入门](http://www.ruanyifeng.com/blog/2012/05/internet_protocol_suite_part_i.html)|对互联网的分层进行了原理性的讲诉，强烈推荐|七两|
|[“HTTPS”安全在哪里？](http://www.cnblogs.com/bugly/p/5543417.html)|通俗易懂的解释HTTPS的工作机制|七两|
|[网络延迟高的原因](https://blog.wilddog.com/?p=974)|讲解了一下整个网络发起的整个流程，为加快网络请求提供了方向|七两|

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
|[味精](http://awhisper.github.io/)|挺有料的博主|七两|
|[深度开源OPEN经验](http://www.open-open.com/lib/)|深度开源OPEN经验，主要讲一些框架类的东西，还有主流前沿技术|七两|

## 书籍阅读
|书名             |书中内容概述        |贡献         |推荐星数（满星：5星）      |
|----------------|----------------|-------------|-----------|
|iOS开发进阶|简单介绍了开发中的常用的工具，block讲的并不是很透彻|七两|3星|
|iOS核心开发手册[美·Erica]|介绍了开发中常见的一些问题，并且提供详细的案例解析|七两|4.5星|
|程序员的自我修养|介绍的是一个应用启动时，处理的事情，虽然主要讲诉的是windows下的启动，但很有借鉴意义|七两|4星|

## 头脑风暴
|期数             |主要内容概括          |
|----------------|--------------------|
|第一期           |移动框架小组搭建，移动插件化小组搭建，启动环境切换小组|      




