## 依赖库以及工具

> 主要收集依赖库和帮助快速、稳定开发的工具

## 网络
#### 1.android-async-http:

一个比较老的网络框架项目，虽然已经很少使用了，但是可以学习一下里面的写作方法。

源码地址：[android-async-http](https://github.com/loopj/android-async-http)

详解：
1. [官方网址](http://loopj.com/android-async-http/)
2. [快速Android开发系列网络篇之Android-Async-Http](http://www.cnblogs.com/angeldevil/p/3729808.html)
3. [android-async-http框架库使用基础](http://blog.csdn.net/yanbober/article/details/45307549)

#### 2.retrofit:
retrofit是由square开源组织开源的一款非常流行的网络请求框架，现在使用已经非常广泛。

源码地址：[retrofit](https://github.com/square/retrofit)

详解：
1. [官方详解](http://square.github.io/retrofit/)
2. [Retrofit用法详解](http://duanyytop.github.io/2016/08/06/Retrofit用法详解/)
3. [Retrofit分析-漂亮的解耦套路](http://www.jianshu.com/p/45cb536be2f4)
4. [Retrofit 2.0：有史以来最大的改进](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0915/3460.html)
5. [Android 手把手教你使用Retrofit2](http://www.jianshu.com/p/73216939806a)

#### 3.okhttp:
okhttp也是由square开源组织开源的一款网络底层封装库，上面介绍的Retrofit也是基于此库进行的二次封装。

源码地址：[okhttp](https://github.com/square/okhttp)

详解：
1. [官方详解](http://square.github.io/okhttp/)
2. [如何更高效地使用 OkHttp](http://brucezz.itscoder.com/effective-okhttp)
3. [OkHttp：Java 平台上的新一代 HTTP 客户端](https://www.ibm.com/developerworks/cn/java/j-lo-okhttp/)
4. [OKHttp源码解析](http://frodoking.github.io/2015/03/12/android-okhttp/)
5. [OKHttp源码解析-ConnectionPool对Connection重用机制&Http/Https/SPDY协议选择](http://frodoking.github.io/2015/06/29/android-okhttp-connectionpool-http1-x-http2-x/)

#### 4.Volley
Volley是由谷歌开源的一款网络请求框架。

源码地址：[Volley](https://android.googlesource.com/platform/frameworks/volley)

详解：
1. [Android 网络通信框架Volley简介(Google IO 2013)](http://blog.csdn.net/t12x3456/article/details/9221611)
2. [Android Volley完全解析(系列)](http://blog.csdn.net/guolin_blog/article/details/17482095)

## ReactiveX
知名的响应式开发Rx系列，根据语言包含：
* Java: [RxJava](https://github.com/ReactiveX/RxJava)
* JavaScript: [RxJS](https://github.com/Reactive-Extensions/RxJS)
* C#: [Rx.NET](https://github.com/Reactive-Extensions/Rx.NET)
* C#(Unity): [UniRx](https://github.com/neuecc/UniRx)
* Scala: [RxScala](https://github.com/ReactiveX/RxScala)
* Clojure: [RxClojure](https://github.com/ReactiveX/RxClojure)
* C++: [RxCpp](https://github.com/Reactive-Extensions/RxCpp)
* Lua: [RxLua](https://github.com/bjornbytes/RxLua)
* Ruby: [Rx.rb](https://github.com/ReactiveX/RxRuby)
* Python: [RxPY](https://github.com/ReactiveX/RxPY)
* Groovy: [RxGroovy](https://github.com/ReactiveX/RxGroovy)
* JRuby: [RxJRuby](https://github.com/ReactiveX/RxJRuby)
* Kotlin: [RxKotlin](https://github.com/ReactiveX/RxKotlin)
* Swift: [RxSwift](https://github.com/ReactiveX/RxSwift)
* PHP: [RxPHP](https://github.com/ReactiveX/RxPHP)

根据平台包含：
RxNetty：[RxNetty](https://github.com/ReactiveX/RxNetty)
RxAndroid：[RxAndroid](https://github.com/ReactiveX/RxAndroid)
RxCocoa：[RxCocoa](https://github.com/ReactiveX/RxSwift)

详解：
[官方网址](http://reactivex.io)
[给 Android 开发者的 RxJava 详解](http://gank.io/post/560e15be2dca930e00da1083)
[RxJava 与 Retrofit 结合的最佳实践](http://gank.io/post/56e80c2c677659311bed9841)


## 图片加载及显示

#### 1.Android-Universal-Image-Loader:
源码地址：[Android-Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader)

详解：
[Android 开源框架Universal-Image-Loader完全解析（一）--- 基本介绍及使用](http://blog.csdn.net/xiaanming/article/details/26810303)

[Android 开源框架Universal-Image-Loader完全解析（二）--- 图片缓存策略详解](http://blog.csdn.net/xiaanming/article/details/27525741)

[Android 开源框架Universal-Image-Loader完全解析（三）---源代码解读](http://blog.csdn.net/xiaanming/article/details/39057201)



#### 2.fresco：
源码地址：[fresco](https://github.com/facebook/fresco)

详解：[官方文档](https://www.fresco-cn.org/docs/index.html)



#### 3.glide:
源码地址：[glide](https://github.com/bumptech/glide)

详解：
[Glide 一个专注于平滑滚动的图片加载和缓存库](http://www.jianshu.com/p/4a3177b57949)

[Google推荐的图片加载库Glide介绍](http://jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0327/2650.html)


#### 4.picasso:
源码地址：[picasso](https://github.com/square/picasso)

详解：
[官方文档](http://square.github.io/picasso/)

[picasso-强大的Android图片下载缓存库](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2014/0731/1639.html)


#### 5.PhotoView
源码地址：[PhotoView](https://github.com/chrisbanes/PhotoView)

详解：[PhotoView 源码解析](http://a.codekk.com/detail/Android/dkmeteor/PhotoView%20源码解析)

#### 6.SmartCropper
 A library for cropping image in a smart way that can identify the border and correct the cropped image. 智能图片裁剪框架。自动识别边框，手动调节选区，使用透视变换裁剪并矫正选区；适用于身份证，名片，文档等照片的裁剪。

源码地址：[https://github.com/pqpo/SmartCropper](https://github.com/pqpo/SmartCropper)

详解：[Android 端基于 OpenCV 的边框识别功能](Android 端基于 OpenCV 的边框识别功能)

#### 7.glide-transformations
An Android transformation library providing a variety of image transformations for Glide.

源码地址：[https://github.com/wasabeef/glide-transformations](https://github.com/wasabeef/glide-transformations)




## 热更新

#### 1.Robust:--美团
源码地址：[Robust](https://github.com/Meituan-Dianping/Robust)

详解：
[Android热更新方案Robust](http://tech.meituan.com/android_robust.html)
[Android热更新方案Robust开源，新增自动化补丁工具](http://tech.meituan.com/android_autopatch.html)

#### 2.Tinker
源码地址：[tinker](https://github.com/Tencent/tinker)

Tinker补丁后台管理：[tinker-manager](https://github.com/baidao/tinker-manager)

详解：
[官方文档](https://github.com/Tencent/tinker/wiki)

[Android N混合编译与对热补丁影响解析](http://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=2649286341&idx=1&sn=054d595af6e824cbe4edd79427fc2706&scene=0#wechat_redirect)

[tinker源码研读（一）：补丁生成之DexDiff原理简析](https://halfstackdeveloper.github.io/2016/10/19/tinker源码研读（一）：补丁生成之DexDiff原理简析/)

#### 3.AndFix:--Alibaba
源码地址：[AndFix](https://github.com/alibaba/AndFix)

详解：
[Alibaba-AndFix Bug热修复框架原理及源码解析](http://blog.csdn.net/qxs965266509/article/details/49816007)
[Android热补丁之AndFix原理解析](http://w4lle.github.io/2016/03/03/Android热补丁之AndFix原理解析/)

#### 4.AndroidInstantRun:--google
源码地址：[instant-run](https://android.googlesource.com/platform/tools/base/+/gradle_2.0.0/instant-run/)

详解：
[深度理解Android InstantRun原理以及源码分析](http://www.jianshu.com/p/780eb85260b3)
[Instant Run: How Does it Work?!](https://medium.com/google-developers/instant-run-how-does-it-work-294a1633367f#.5n510pbv2)

#### 5.DroidFix:
源码地址：[DroidFix](https://github.com/bunnyblue/DroidFix)

详解：
[安卓App热补丁动态修复技术介绍](https://mp.weixin.qq.com/s?__biz=MzI1MTA1MzM2Nw==&mid=400118620&idx=1&sn=b4fdd5055731290eef12ad0d17f39d4a&scene=1&srcid=1106Imu9ZgwybID13e7y2nEi#wechat_redirect)


#### 6.HotFix:
源码地址：[HotFix](https://github.com/dodola/HotFix)

详解：
[基于Nuwa实现Android自动化HotFix](http://www.jianshu.com/p/72c17fb76f21)

#### 7.Nuwa
源码地址：[Nuwa](https://github.com/jasonross/Nuwa)

详解：
[Android 热修复Nuwa的原理及Gradle插件源码解析](http://blog.csdn.net/sbsujjbcy/article/details/50812674)
[安卓热更新之Nuwa实现步骤](http://www.cnblogs.com/fanfu1/p/5506149.html)


#### 8.RocooFix:
源码地址：[RocooFix](https://github.com/dodola/RocooFix)


#### 9.AnoleFix:
源码地址：[AnoleFix](https://github.com/dodola/AnoleFix)


## 插件化

#### 1.VirtualAPK--滴滴
源码地址：[VirtualAPK](https://github.com/didi/VirtualAPK)


#### 2.ZeusPlugin--iReader
源码地址：[ZeusPlugin](https://github.com/iReaderAndroid/ZeusPlugin)
    

#### 3.dynamic-load-apk（DL）
源码地址：[dynamic-load-apk](https://github.com/singwhatiwanna/dynamic-load-apk)


#### 4.RePlugin--360
源码地址：[RePlugin](https://github.com/Qihoo360/RePlugin)


#### 5.android-pluginmgr
源码地址：[android-pluginmgr](https://github.com/mmin18/AndroidDynamicLoader)


#### 6.AndroidDynamicLoader
源码地址：[AndroidDynamicLoader](https://github.com/mmin18/AndroidDynamicLoader)


#### 7.VirtualApp
源码地址：[VirtualApp](https://github.com/asLody/VirtualApp)

## 注解
#### 1.dagger:
源码地址：[dagger](https://github.com/square/dagger)

详解：[官方文档](http://square.github.io/dagger/)

#### 2.butterknife
源码地址：[butterknife](https://github.com/JakeWharton/butterknife)

详解：[官方文档](http://jakewharton.github.io/butterknife/)

#### 3.androidannotations：
源码地址：[androidannotations](https://github.com/androidannotations/androidannotations)

详解：[官方文档](https://github.com/androidannotations/androidannotations/wiki)

#### 4.Dagger2
源码地址：[Dagger2](https://github.com/google/dagger)

#### 5.roboguice
源码地址：[roboguice](https://github.com/roboguice/roboguice)


## 图表
#### 1.WilliamChart：
源码地址：[WilliamChart](https://github.com/diogobernardino/WilliamChart)

功能：绘制图表的库，支持 LineChartView、BarChartView 和 StackBarChartView 三中图表类型，并且支持 Android 2.2 及以上的系统。

#### 2.XCL-Charts：
源码地址：[XCL-Charts](https://github.com/xcltapestry/XCL-Charts)

功能：XCL-Charts 基于原生的 Canvas 来绘制各种图表,在设计时，尽量在保证开发效率的同时，给使用者提供足够多的定制化能力。因此使用简便,同时具有相当灵活的定制能力。目前支持 3D/非 3D 柱形图(Bar Chart)、3D/非 3D 饼图(Pie Chart)、堆积图(Stacked Bar Chart)、面积图(Area Chart)、 折线图(Line Chart)、曲线图(Spline Chart)、环形图(Dount Chart)、南丁格尔玫瑰图(Rose Chart)、仪表盘(Dial Chart)、刻度盘(Gauge Chart)、雷达图(Radar Chart)、圆形图(Circle Chart)等图表。其它特性还包括支持图表缩放、手势移动、动画显示效果、高密度柱形显示、图表分界定制线、多图表的混合显示及同数据源不同类型图表切换等。

#### 3.HelloCharts for Android：
源码地址：[HelloCharts for Android](https://github.com/lecho/hellocharts-android)

功能：支持折线图、柱状图、饼图、气泡图、组合图；支持预览、放大缩小，滚动，部分图表支持动画；支持 Android 2.2 以上

#### 4.MPAndroidChart：
源码地址：[MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)

功能：强大的图表绘制工具，支持折线图、面积图、散点图、时间图、柱状图、条图、饼图、气泡图、圆环图、范围（高至低）条形图、网状图等；支持图的拖拽缩放；支持 Android 2.2 以上，支持横纵轴缩放，多指缩放，展现动画、高亮、保存到 sdcard、从文件读取图表

#### 5.achartengine：
源码地址：[achartengine](https://code.google.com/p/achartengine/)

功能：强大的图表绘制工具，支持折线图、面积图、散点图、时间图、柱状图、条图、饼图、气泡图、圆环图、范围（高至低）条形图、拨号图/表、立方线图及各种图的结合

#### 6.GraphView：
源码地址：[GraphView](https://github.com/jjoe64/GraphView)

功能：绘制图表和曲线图的 View，可用于 Android 上的曲形图、柱状图、波浪图展示

#### 7.HoloGraphLibrary：
源码地址：[HoloGraphLibrary](https://bitbucket.org/danielnadeau/holographlibrary/src)

功能：绘制现状图、柱状图、饼状图

#### 8.EazeGraph：
源码地址：[EazeGraph](https://github.com/blackfizz/EazeGraph)

功能：Android 图表库，支持柱状图、分层柱状图、饼状图、线性图


#### 9.PieChartView：
源码地址：[PieChartView](https://github.com/wuseal/PieChartView)

功能：比较简单直接的饼状统计报表图，使用方便，设置相应的属性参数即可

## 设计模式
此处说的设计模式是谷歌官方公开的对MVP模式的代码示例，大家可以做为参考学习一下：

#### Stable samples
* [todo-mvp](https://github.com/googlesamples/android-architecture/tree/todo-mvp/) - Basic Model-View-Presenter architecture.

* [todo-mvp-loaders](https://github.com/googlesamples/android-architecture/tree/todo-mvp-loaders/) - Based on todo-mvp, fetches data using Loaders.

* [todo-databinding](https://github.com/googlesamples/android-architecture/tree/todo-databinding/) - Based on todo-mvp, uses the Data Binding Library.

* [todo-mvp-clean](https://github.com/googlesamples/android-architecture/tree/todo-mvp-clean/) - Based on todo-mvp, uses concepts from Clean Architecture.

* [todo-mvp-dagger](https://github.com/googlesamples/android-architecture/tree/todo-mvp-dagger/) - Based on todo-mvp, uses Dagger2 for Dependency Injection

* [todo-mvp-contentproviders](https://github.com/googlesamples/android-architecture/tree/todo-mvp-contentproviders/) - Based on todo-mvp-loaders, fetches data using Loaders and uses Content Providers

* [todo-mvp-rxjava](https://github.com/googlesamples/android-architecture/tree/todo-mvp-rxjava/) - Based on todo-mvp, uses RxJava for concurrency and data layer abstraction.

#### Samples in progress

* [dev-todo-mvp-tablet](https://github.com/googlesamples/android-architecture/tree/dev-todo-mvp-tablet/) - Based on todo-mvp, adds a master/detail view for tablets.

#### External samples
External samples are variants that may not be in sync with the rest of the branches.

* [todo-mvp-fragmentless](https://github.com/Syhids/android-architecture/tree/todo-mvp-fragmentless) - Based on todo-mvp, uses Android views instead of Fragments.

* [todo-mvp-conductor](https://github.com/grepx/android-architecture/tree/todo-mvp-conductor) - Based on todo-mvp, uses the Conductor framework to refactor to a single Activity architecture.

#### Google官方设计模式的扩展

* [android-clean-architecture-boilerplate](https://github.com/bufferapp/android-clean-architecture-boilerplate) - An android boilerplate project using clean architecture

    Languages, libraries and tools used

    * [Kotlin](https://kotlinlang.org/)
    * Android Support Libraries
    * [RxJava2](https://github.com/ReactiveX/RxJava/wiki/What's-different-in-2.0)
    * [Dagger 2 (2.11)](https://github.com/google/dagger)
    * [Glide](https://github.com/bumptech/glide)
    * [Retrofit](http://square.github.io/retrofit/)
    * [OkHttp](http://square.github.io/okhttp/)
    * [Gson](https://github.com/google/gson)
    * [Timber](https://github.com/JakeWharton/timber)
    * [Mockito](http://site.mockito.org/)
    * [Espresso](https://developer.android.com/training/testing/espresso/index.html)
    * [Robolectric](http://robolectric.org/)




## 事件总线
* [EventBus](https://github.com/greenrobot/EventBus)

* [otto](https://github.com/square/otto)

## 数据库
* [ORMLite](http://ormlite.com)

* [greendao](https://github.com/greenrobot/greenDAO)

* [ormndroid](https://github.com/roscopeco/ormdroid)

* [androrm](https://github.com/androrm/androrm)

* [ActiveAndroid](https://github.com/pardom/ActiveAndroid)

* [Realm](https://github.com/realm/realm-java)

* [Sugar](https://github.com/satyan/sugar)

* [sqlbrite](https://github.com/square/sqlbrite)

* [LitePal](https://github.com/LitePalFramework/LitePal)

## 网络解析
* [gson](https://github.com/google/gson)

* [fastjson](https://github.com/alibaba/fastjson)

* [jackson-databind](https://github.com/FasterXML/jackson-databind)

* [HtmlPaser2](https://github.com/fb55/htmlparser2/)

* [jsoup](https://github.com/jhy/jsoup) 


## Animation
* [lottie-android](https://github.com/airbnb/lottie-android)

* [lottie-ios](https://github.com/airbnb/lottie-ios)

* [lottie-react-native](https://github.com/airbnb/lottie-react-native)


## 跨平台移动开发工具
#### 1.Flutter

Github：[Flutter](https://github.com/flutter)

英文：[Flutter-EN](https://flutter.dev/)

英文：[Flutter-CN](https://flutterchina.club/)

#### 2.Weex

源码地址：[weex](https://github.com/alibaba/weex/)

官方文档：

#### 2.React Native
源码地址：[React Native](https://github.com/facebook/react-native)

官方文档：
[React Native中文](http://reactnative.cn)
[React Native英文](http://facebook.github.io/react-native/docs/getting-started.html)

## Log框架
* [Logger](https://github.com/orhanobut/logger)

* [hugo](https://github.com/JakeWharton/hugo)

* [timber](https://github.com/JakeWharton/timber)

## 测试框架(单元测试)
* [Mockito](https://github.com/mockito/mockito)

* [Robotium](https://github.com/RobotiumTech/robotium)

* [robolectric](https://github.com/robolectric/robolectric)

## 视频
* [Bilibili/ijkplayer](https://github.com/Bilibili/ijkplayer)

* [vlc](https://github.com/videolan/vlc)

* [vlc-android-sdk](https://github.com/mrmaffen/vlc-android-sdk)

* [FFmpeg](https://github.com/FFmpeg/FFmpeg)

* [android-ffmpeg-java](https://github.com/guardianproject/android-ffmpeg-java)

* [ffmpeg-android](https://github.com/WritingMinds/ffmpeg-android)

* [GSYVideoPlayer](https://github.com/CarGuo/GSYVideoPlayer)

## 多主题
* [Bilibili/MagicaSakura](https://github.com/Bilibili/MagicaSakura)


## 其他
谷歌开源手机号验证库：
[libphonenumber](https://github.com/googlei18n/libphonenumber)

编译器抓取常见错误工具：

[**error-prone**](https://github.com/google/error-prone)