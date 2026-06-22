# Android开源项目全面梳理与介绍

> 本文档对Android开源项目进行全面系统化梳理，涵盖个性化控件、工具库、优秀项目、开发测试工具及杰出个人和团体等五大类别。

## 文档概述

本文档基于Trinea维护的Android开源项目汇总仓库，系统性地介绍了Android开发中常用的开源项目，帮助开发者快速了解和选择合适的开源组件。

---

## 一、个性化控件(View)篇

### 1. ListView相关控件

#### 下拉刷新控件
- **android-pulltorefresh**: 强大的下拉刷新控件，支持ListView、ViewPager、WebView等多种控件
  - 项目地址: https://github.com/chrisbanes/Android-PullToRefresh
  - 特点: 支持上下左右拉动刷新，体验优化
  
- **android-Ultra-Pull-to-Refresh**: 终极下拉刷新方案，继承ViewGroup可包含任何View
  - 项目地址: https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh
  - 特点: 功能强大，定制简单，支持API LEVEL >= 8

- **DropDownListView**: 下拉刷新及滑动到底部加载更多ListView
  - 项目地址: https://github.com/Trinea/AndroidCommon
  - 特点: 同时支持下拉刷新和底部加载更多

#### 拖拽排序控件
- **DragSortListView**: 拖动排序的ListView，支持item删除、高度不一、单选复选等
  - 项目地址: https://github.com/bauerca/drag-sort-listview
  - 应用示例: Wordpress Android

- **SlideAndDragListView**: 支持item拖动排序、左右滑动事件的ListView
  - 项目地址: https://github.com/yydcdut/SlideAndDragListView
  - 应用示例: Android手机QQ 5.0

#### 滑动删除控件
- **SwipeListView**: 支持左右滑动事件定义、动画时间设置的ListView
  - 项目地址: https://github.com/47deg/android-swipelistview
  - 应用示例: 微信

- **RecyclerViewSwipeDismiss**: 轻量级RecyclerView滑动删除库
  - 项目地址: https://github.com/CodeFalling/RecyclerViewSwipeDismiss
  - 特点: 只需绑定onTouchListener

#### 分组固定控件
- **StickyListHeaders**: GroupName滑动到顶端固定不动的ExpandListView
  - 项目地址: https://github.com/emilsjolander/StickyListHeaders
  - 应用示例: Android 4.0联系人

- **pinned-section-listview**: 分组固定ListView
  - 项目地址: https://github.com/beworker/pinned-section-listview

#### 快速滚动控件
- **IndexableListView**: 右侧显示item首字母快捷索引的ListView
  - 项目地址: https://github.com/woozzu/IndexableListView
  - 应用示例: 微信通讯录、小米联系人

- **CustomFastScrollView**: 快速滑动时显示item内容的ListView
  - 项目地址: https://github.com/nolanlawson/CustomFastScrollViewDemo

#### 动画效果控件
- **JazzyListView**: item以特殊动画效果进入屏幕的ListView
  - 项目地址: https://github.com/twotoasters/JazzyListView
  - 动画效果: grow、cards、curl、wave、flip、fly等

- **ListViewAnimations**: 带Item显示动画的ListView
  - 项目地址: https://github.com/nhaarman/ListViewAnimations
  - 应用示例: Google plus、Google Now等

#### 其他ListView控件
- **DevsmartLib-Android**: 横向ListView
  - 项目地址: https://github.com/dinocore1/DevsmartLib-Android

- **ListBuddies**: 自动滚动的双列ListView，有视差效果
  - 项目地址: https://github.com/jpardogo/ListBuddies

### 2. ActionBar相关控件

- **ActionBarSherlock**: 为Android所有版本提供统一的ActionBar
  - 项目地址: https://github.com/JakeWharton/ActionBarSherlock
  - 特点: 解决4.0以下ActionBar适配问题

- **FadingActionBar**: ListView向下滚动逐渐显现的ActionBar
  - 项目地址: https://github.com/ManuelPeinado/FadingActionBar
  - 应用示例: google music、知乎

- **NotBoringActionBar**: google music下拉收缩的ActionBar
  - 项目地址: https://github.com/flavienlaurent/NotBoringActionBar

### 3. Menu相关控件

#### 滑出式菜单
- **MenuDrawer**: 滑出式菜单，支持屏幕上下左右划出
  - 项目地址: https://github.com/SimonVT/android-menudrawer
  - 应用示例: Gmail、Google Music

- **SlidingMenu**: 滑出式菜单，支持zoom、scale、slide动画样式
  - 项目地址: https://github.com/jfeinstein10/SlidingMenu
  - 应用示例: Foursquare、LinkedIn、Evernote等

#### 特殊菜单样式
- **ArcMenu**: 类似Path的左下角动画旋转菜单
  - 项目地址: https://github.com/daCapricorn/ArcMenu
  - 应用示例: Path

- **AndroidResideMenu**: 仿Dribbble的边栏菜单
  - 项目地址: https://github.com/SpecialCyCi/AndroidResideMenu

### 4. ViewPager、Gallery相关控件

#### ViewPager指示器
- **Android-ViewPagerIndicator**: 配合ViewPager使用的Indicator
  - 项目地址: https://github.com/JakeWharton/Android-ViewPagerIndicator
  - 特点: 支持各种位置和样式

- **PagerSlidingTabStrip**: ViewPager Scroll时Indicator联动
  - 项目地址: https://github.com/astuetz/PagerSlidingTabStrip

- **SmartTabLayout**: 滑动时Indicator平滑过渡
  - 项目地址: https://github.com/ogaclejapan/SmartTabLayout

#### ViewPager动画效果
- **JazzyViewPager**: 支持Fragment切换动画的ViewPager
  - 项目地址: https://github.com/jfeinstein10/JazzyViewPager
  - 动画: 转盘、淡入淡出、翻页、层叠、旋转等

- **ViewPager3D**: 3D效果的ViewPager
  - 项目地址: https://github.com/inovex/ViewPager3D

#### 其他ViewPager控件
- **Android Auto Scroll ViewPager**: 自动滚动轮播循环的ViewPager
  - 项目地址: https://github.com/Trinea/android-auto-scroll-view-pager

- **LoopingViewPager**: 无限循环的ViewPager
  - 项目地址: https://github.com/imbryk/LoopingViewPager

- **android_page_curl**: 翻书卷曲效果
  - 项目地址: https://github.com/harism/android_page_curl
  - 应用示例: iReader

### 5. GridView相关控件

#### 瀑布流控件
- **StaggeredGridView**: 类似Pinterest的瀑布流GridView
  - 项目地址: https://github.com/maurycyw/StaggeredGridView
  - 特点: 自带View缓存，继承自ViewGroup

- **AndroidStaggeredGrid**: 允许非对齐行的GridView
  - 项目地址: https://github.com/etsy/AndroidStaggeredGrid
  - 应用示例: Pinterest

#### 拖拽GridView
- **DraggableGridView**: Item可拖动交换位置的GridView
  - 项目地址: https://github.com/thquinn/DraggableGridView

- **Android-DraggableGridViewPager**: 多屏拖拽GridView
  - 项目地址: https://github.com/zzhouj/Android-DraggableGridViewPager

#### 其他GridView控件
- **StickyGridHeaders**: 分组固定GridView
  - 项目地址: https://github.com/TonicArtos/StickyGridHeaders

- **GridView with Header and Footer**: 带头尾的GridView
  - 项目地址: https://github.com/liaohuqiu/android-GridViewWithHeaderAndFooter

### 6. ImageView相关控件

#### 图片缩放控件
- **PhotoView**: 支持双击或双指缩放的ImageView
  - 项目地址: https://github.com/chrisbanes/PhotoView
  - 特点: 在ViewPager等Scrolling view中正常使用

- **ImageViewZoom**: 支持放大和平移的ImageView
  - 项目地址: https://github.com/sephiroth74/ImageViewZoom

#### GIF图片控件
- **android-gif-drawable**: 支持gif显示的view，用jni实现
  - 项目地址: https://github.com/koral--/android-gif-drawable
  - 特点: 不依赖其他开源项目

- **ImageViewEx**: 支持Gif显示的ImageView
  - 项目地址: https://github.com/frapontillo/ImageViewEx

#### 特殊形状ImageView
- **RoundedImageView**: 带圆角的ImageView
  - 项目地址: https://github.com/vinc3m1/RoundedImageView

- **CircleImageView**: 圆形的ImageView
  - 项目地址: https://github.com/hdodenhof/CircleImageView

- **CustomShapeImageView**: 各种形状的ImageView
  - 项目地址: https://github.com/MostafaGazar/CustomShapeImageView

#### 其他ImageView控件
- **KenBurnsView**: 实现Ken Burns effect效果的ImageView
  - 项目地址: https://github.com/flavioarfaria/KenBurnsView

- **ColorArt**: 根据图片均色设置背景色显示
  - 项目地址: https://github.com/MichaelEvans/ColorArt

### 7. ProgressBar相关控件

#### 水平进度条
- **SmoothProgressBar**: 水平进度条
  - 项目地址: https://github.com/castorflex/SmoothProgressBar

- **NumberProgressBar**: 带数字进度的进度条
  - 项目地址: https://github.com/daimajia/NumberProgressBar

#### 圆形进度条
- **ProgressWheel**: 支持进度显示的圆形ProgressBar
  - 项目地址: https://github.com/Todd-Davies/ProgressWheel

- **HoloCircularProgressBar**: Android4.1时钟App样式
  - 项目地址: https://github.com/passsy/android-HoloCircularProgressBar

- **CircularProgressDrawable**: 带圆形进度显示的进度条
  - 项目地址: https://github.com/Sefford/CircularProgressDrawable

#### 特殊进度条
- **android-square-progressbar**: 在图片周围显示进度
  - 项目地址: https://github.com/mrwonderman/android-square-progressbar
  - 应用示例: square

- **WaveView**: 波纹效果的View，可做ProgressBar
  - 项目地址: https://github.com/john990/WaveView

- **LoadingDrawable**: 酷炫的android加载动画
  - 项目地址: https://github.com/dinuscxj/LoadingDrawable

#### 进度按钮
- **ProgressButton**: 通过图钉不同状态显示进度
  - 项目地址: https://github.com/f2prateek/progressbutton

- **circular-progress-button**: 进度显示的Button
  - 项目地址: https://github.com/dmytrodanylyk/circular-progress-button

### 8. TextView相关控件

#### 特殊效果TextView
- **android-flowtextview**: 文字自动环绕其他View的Layout
  - 项目地址: https://code.google.com/p/android-flowtextview/

- **Shimmer for Android**: 文字发淡光的TextView
  - 项目地址: https://github.com/RomainPiel/Shimmer-android

- **Titanic**: 显示水位上升下降的TextView
  - 项目地址: https://github.com/RomainPiel/Titanic

#### 输入验证控件
- **Android Form EditText**: 验证输入合法性的编辑框
  - 项目地址: https://github.com/vekexasia/android-edittext-validator
  - 特点: 支持多种正则验证

#### 特殊按钮
- **android-circlebutton**: Android圆形按钮
  - 项目地址: https://github.com/markushi/android-circlebutton

- **Segmented Radio Buttons**: iOS分段控制的实现
  - 项目地址: https://github.com/vinc3m1/android-segmentedradiobutton

#### 其他TextView控件
- **AutoFitTextView**: 字体大小自适应的TextView
  - 项目地址: https://github.com/grantland/android-autofittextview

- **Emojicon**: 支持emojis的TextView和EditText
  - 项目地址: https://github.com/rockerhieu/emojicon

- **MoneyTextView**: 支持加法运算的金额输入TextView
  - 项目地址: https://github.com/andyken/MoneyTextView

### 9. ScrollView相关控件

- **Discrollview**: 支持滚动时Item淡入淡出、平移、缩放效果的ScrollView
  - 项目地址: https://github.com/flavienlaurent/discrollview

- **PullScrollView**: 仿新浪微博下拉背景伸缩回弹效果
  - 项目地址: https://github.com/MarkMjw/PullScrollView

- **ParallaxScrollView**: 支持视差滚动的ScrollView
  - 项目地址: https://github.com/chrisjenx/ParallaxScrollView

### 10. TimeView相关控件

- **android-times-square**: Android日历时间部件
  - 项目地址: https://github.com/square/android-times-square
  - 特点: 支持选取单个日期、多个日期、日期区间段

- **android-calendar-card**: 日历
  - 项目地址: https://github.com/kenumir/android-calendar-card

- **AndroidWheel**: 支持城市、日期时间、密码、图片的Wheel
  - 项目地址: https://github.com/sephiroth74/AndroidWheel

### 11. TipView相关控件

- **Crouton**: 丰富样式的Toast
  - 项目地址: https://github.com/keyboardsurfer/Crouton
  - 特点: 支持alert、confirm、info样式

- **SuperToasts**: 更丰富样式的toast
  - 项目地址: https://github.com/JohnPersano/SuperToasts
  - 特点: 支持Button、Progress样式、进入动画

- **Android ViewBadger**: 为其他View添加角标
  - 项目地址: https://github.com/jgilfelt/android-viewbadger

- **UndoBar**: 屏幕底部显示取消或确认的PopupWindows
  - 项目地址: https://github.com/soarcn/UndoBar

### 12. FlipView相关控件

- **android-flip**: 类似Flipboard翻转动画的实现
  - 项目地址: https://github.com/openaphid/android-flip
  - 应用示例: flipboard

- **FlipImageView**: 支持x、y、z及动画选择的翻转动画
  - 项目地址: https://github.com/castorflex/FlipImageView

### 13. ColorPickView相关控件

- **ColorPickerView**: 颜色选择器
  - 项目地址: https://code.google.com/p/color-picker-view/

- **HoloColorPicker**: 颜色选择器
  - 项目地址: https://github.com/LarsWerkman/HoloColorPicker

- **ColorPickerPreference**: 颜色选择器
  - 项目地址: https://github.com/attenzione/android-ColorPickerPreference

### 14. GraphView相关控件

- **achartengine**: 强大的图表绘制工具
  - 项目地址: https://code.google.com/p/achartengine/
  - 特点: 支持折线图、面积图、散点图、柱状图、饼图等
  - 应用示例: Wordpress Android、Google Analytics

- **GraphView**: 绘制图表和曲线图的View
  - 项目地址: https://github.com/jjoe64/GraphView

- **HoloGraphLibrary**: 绘制线状图、柱状图、饼状图
  - 项目地址: https://bitbucket.org/danielnadeau/holographlibrary/src

### 15. UI Style相关控件

- **UITableView**: iOS风格控件
  - 项目地址: https://github.com/thiagolocatelli/android-uitableview

- **ATableView**: iOS风格控件
  - 项目地址: https://github.com/dmacosta/ATableView

- **Cards-UI**: 卡片式View
  - 项目地址: https://github.com/afollestad/Cards-UI

- **cardslib**: 卡片式View，支持ListView和GridView
  - 项目地址: https://github.com/gabrielemariotti/cardslib

- **Android-Bootstrap**: Bootstrap风格的按钮
  - 项目地址: https://github.com/Bearded-Hen/Android-Bootstrap

### 16. 其他控件

#### Activity切换
- **SwipeBackLayout**: 左右或向上滑动返回的Activity
  - 项目地址: https://github.com/Issacw0ng/SwipeBackLayout
  - 应用示例: 知乎

- **ActivityTransition**: Activity切换动画
  - 项目地址: https://github.com/ophilbert/ActivityTransition

#### Dialog样式
- **android-styled-dialogs**: 可自定义样式的dialog
  - 项目地址: https://github.com/inmite/android-styled-dialogs

#### 滑动面板
- **Android Sliding Up Panel**: 可拖动的View，能在当前Activity上扶起可拖动Panel
  - 项目地址: https://github.com/umano/AndroidSlidingUpPanel
  - 应用示例: Google Music精简播放栏

#### 锁屏解锁
- **GlowPadBackport**: Android4.2锁屏界面解锁扩展到Android1.6+
  - 项目地址: https://github.com/rock3r/GlowPadBackport

- **GlowPadView**: Android4锁屏界面解锁
  - 项目地址: https://github.com/nadavfima/GlowPadView

#### 图案密码
- **android-lockpattern**: Android图案密码解锁
  - 项目地址: https://code.google.com/p/android-lockpattern/
  - 应用示例: Android开机图案密码解锁、支付宝密码解锁

- **PatternLock**: 另一个Android图案解锁库
  - 项目地址: https://github.com/DreaminginCodeZH/PatternLock

#### 其他特殊控件
- **RangeBar**: 可选择范围内值的控件
  - 项目地址: https://github.com/edmodo/range-bar

- **TableFixHeaders**: 第一列固定的Table
  - 项目地址: https://github.com/InQBarna/TableFixHeaders

- **ChromeView**: 利用Chromium实现的WebView
  - 项目地址: https://github.com/pwnall/chromeview

- **ShowcaseView library**: 高亮显示应用特定部分
  - 项目地址: https://github.com/amlcurran/ShowcaseView

- **Spotlight**: Android图书馆点亮项目的教程或漫步等
  - 项目地址: https://github.com/TakuSemba/Spotlight

- **SpeedView**: Android动态车速表和量规
  - 项目地址: https://github.com/anastr/SpeedView

---

## 二、工具库篇

### 1. 依赖注入DI

#### AndroidAnnotations
- **项目地址**: https://github.com/excilys/androidannotations
- **官方网站**: http://androidannotations.org/
- **特点**:
  - 依赖注入：包括view、extras、系统服务、资源等
  - 简单的线程模型
  - 事件绑定：通过annotation表示view响应事件
  - REST客户端：定义客户端接口，自动生成REST请求实现
  - 编译时生成子类，不影响运行时性能

#### roboguice
- **项目地址**: https://github.com/roboguice/roboguice
- **特点**: 运行时读取annotations进行反射

#### butterknife
- **项目地址**: https://github.com/JakeWharton/butterknife
- **特点**: 利用annotation快速完成View初始化

#### Dagger
- **项目地址**: https://github.com/square/dagger
- **特点**: 依赖注入，适用于Android和Java

#### Anvil
- **项目地址**: https://github.com/zserge/anvil
- **特点**: 小型库用于构建响应式UI组件，数据绑定和事件监听器注入

### 2. 图片缓存

#### Android-Universal-Image-Loader
- **项目地址**: https://github.com/nostra13/Android-Universal-Image-Loader
- **特点**: 目前使用最广泛的图片缓存，支持主流图片缓存绝大多数特性

#### picasso
- **项目地址**: https://github.com/square/picasso
- **特点**:
  - 自动检测adapter重用并取消之前下载
  - 图片变换
  - 加载本地资源
  - 设置占位资源
  - 支持debug模式

#### ImageCache
- **项目地址**: https://github.com/Trinea/AndroidCommon
- **特点**:
  - 支持预取新图片，支持等待队列
  - 包含二级缓存，可自定义文件名保存规则
  - 可选择多种缓存算法(FIFO、LIFO、LRU、MRU、LFU、MFU等13种)
  - 可方便保存及初始化恢复数据

#### Cube ImageLoader
- **项目地址**: https://github.com/etao-open-source/cube-sdk
- **特点**: 阿里巴巴一些App使用的图片加载组件，简单易用

### 3. 网络相关

#### Asynchronous Http Client for Android
- **项目地址**: https://github.com/loopj/android-async-http
- **特点**:
  - 在匿名回调中处理请求结果
  - 在UI线程外进行http请求
  - 文件断点上传
  - 智能重试
  - 默认gzip压缩
  - 支持解析成Json格式
  - 可将Cookies持久化

#### Retrofit
- **项目地址**: https://github.com/square/retrofit
- **特点**: RESTFUL API设计

#### okhttp
- **项目地址**: https://github.com/square/okhttp
- **特点**:
  - 支持SPDY协议
  - 利用连接池减少请求延迟
  - Gzip压缩
  - Response缓存减少不必要的请求

#### android-query
- **项目地址**: https://github.com/androidquery/androidquery
- **特点**: 异步加载，更少代码完成Android加载

#### Ion
- **项目地址**: https://github.com/koush/ion
- **特点**: 支持图片、json、http post等异步请求

#### Volley
- **项目地址**: https://android.googlesource.com/platform/frameworks/volley
- **特点**: Google提供的网络通信库，使网络请求更简单、更快速

#### HttpCache
- **项目地址**: https://github.com/Trinea/AndroidCommon
- **特点**:
  - 根据cache-control、expires缓存http请求
  - 支持同步、异步Http请求
  - 在UI线程外进行http请求
  - 默认gzip压缩

#### Android Networking
- **项目地址**: https://github.com/amitshekhariitbhu/AndroidNetworking
- **特点**: 强大的Android网络库

### 4. 数据库ORM工具包

#### greenDAO
- **项目地址**: https://github.com/greenrobot/greenDAO
- **特点**:
  - 性能佳
  - 简单易用的API
  - 内存小好小
  - 库大小小

#### ActiveAndroid
- **项目地址**: https://github.com/pardom/ActiveAndroid
- **特点**: Android Sqlite orm的db工具类

#### Sprinkles
- **项目地址**: https://github.com/emilsjolander/sprinkles
- **特点**: 配合Retrofit能保存从服务器获取的数据

#### ormlite-android
- **项目地址**: https://github.com/j256/ormlite-android
- **特点**: ORMLite Android功能

### 5. Android公共库

#### Guava
- **项目地址**: https://code.google.com/p/guava-libraries/
- **特点**: Google基于java1.6的类库集合扩展项目

#### AndroidCommon
- **项目地址**: https://github.com/Trinea/AndroidCommon
- **特点**:
  - 缓存(图片缓存、预取缓存、网络缓存)
  - 公共View(下拉及底部加载更多ListView等)
  - Android常用工具类

#### shipfaster
- **项目地址**: https://github.com/pyricau/shipfaster
- **特点**: 整合Dagger Otto Retrofit Robolectric Picasso OkHttp

#### CleanAndroidCode
- **项目地址**: https://github.com/pyricau/CleanAndroidCode
- **特点**: 整合Dagger Otto AndroidAnnotations

### 6. Android高版本向低版本兼容

#### ActionBarSherlock
- **项目地址**: https://github.com/JakeWharton/ActionBarSherlock
- **特点**: 为Android所有版本提供统一的ActionBar

#### Nine Old Androids
- **项目地址**: https://github.com/JakeWharton/NineOldAndroids
- **特点**: 将Android 3.0动画API兼容到Android1.0

#### HoloEverywhere
- **项目地址**: https://github.com/Prototik/HoloEverywhere
- **特点**: 将Android 3.0的Holo主题兼容到Android2.1++

#### SherlockNavigationDrawer
- **项目地址**: https://github.com/tobykurien/SherlockNavigationDrawer
- **特点**: 将NavigationDrawer和ActionbarSherlock结合

#### Notifications4EveryWhere
- **项目地址**: https://github.com/youxiachai/Notifications4EveryWhere
- **特点**: 将Android 4.1的Notifications兼容到Android2.2++

#### Android Switch Widget Backport
- **项目地址**: https://github.com/BoD/android-switch-backport
- **特点**: 将Android Switch兼容到Android2.1++

#### android-datepicker
- **项目地址**: https://github.com/SimonVT/android-datepicker
- **特点**: 将Android 4.0的datepicker兼容到Android2.2++

### 7. 多媒体相关

#### cocos2d-x
- **项目地址**: https://github.com/cocos2d/cocos2d-x
- **特点**: 跨平台的2d游戏框架，支持Android、IOS、Linux、Windows等

#### Vitamio
- **项目地址**: https://github.com/yixia/VitamioBundle
- **特点**:
  - 全面支持硬件解码与GPU渲染
  - 流畅播放720P甚至1080P高清视频
  - 跨平台支持多种视频流媒体协议

#### PhotoProcessing
- **项目地址**: https://github.com/lightbox/PhotoProcessing
- **特点**: 利用ndk处理图片，支持各种特效

#### Android StackBlur
- **项目地址**: https://github.com/kikoso/android-stackblur
- **特点**: 图片模糊效果工具类

#### Bitmap Smart Clipping using OpenCV
- **项目地址**: https://github.com/beartung/tclip-android
- **特点**: 图片智能裁剪保留重要部分显示

#### Cropper
- **项目地址**: https://github.com/edmodo/cropper
- **特点**: 图片局部剪切工具，可触摸控制选择区域或旋转

#### android-crop
- **项目地址**: https://github.com/jdamcd/android-crop
- **特点**: 图片裁剪Activity

#### TileView
- **项目地址**: https://github.com/moagrius/TileView
- **特点**: 可分块显示大图，支持2D拖动、双击、双指放大

#### BlurEffectForAndroidDesign
- **项目地址**: https://github.com/PomepuyN/BlurEffectForAndroidDesign
- **特点**: 图片模糊效果

#### android-eye
- **项目地址**: https://github.com/Teaonly/android-eye
- **特点**: PC端网页查看手机摄像头内容

#### android-gpuimage
- **项目地址**: https://github.com/CyberAgent/android-gpuimage
- **特点**: 基于GPU的图片滤镜

#### AndroidFaceCropper
- **项目地址**: https://github.com/lafosca/AndroidFaceCropper
- **特点**: 图片脸部自动识别

#### Android Video Crop
- **项目地址**: https://github.com/dmytrodanylyk/android-video-crop
- **特点**: 利用TextureView播放和剪切视频

#### svg-android
- **项目地址**: https://github.com/japgolly/svg-android
- **特点**: Android Svg矢量图形支持

### 8. 事件总线(订阅者模式)

#### EventBus
- **项目地址**: https://github.com/greenrobot/EventBus
- **特点**:
  - 支持在不同类型线程中处理订阅
  - 支持事件优先级定义
  - 支持粘性事件
  - 性能更优
  - 体積小

#### Otto
- **项目地址**: https://github.com/square/otto
- **特点**: Square的开源项目，基于Guava的Android优化

### 9. 传感器

#### Great Android Sensing Toolkit
- **项目地址**: https://github.com/gast-lib/gast-lib
- **特点**: Android感应器工具包，包含示例及算法

#### SensorManager
- **项目地址**: https://github.com/nlathia/SensorManager
- **特点**: Android传感器管理

#### GPSLogger
- **项目地址**: https://github.com/mendhak/gpslogger
- **特点**: 记录GPS信息

#### Pedometer
- **项目地址**: https://github.com/j4velin/Pedometer
- **特点**: 计步器，使用硬件计步感应器

#### leapcast
- **项目地址**: https://github.com/dz0ny/leapcast
- **特点**: ChromeCast模拟器的App

#### Arduino-Communicator
- **项目地址**: https://github.com/jeppsson/Arduino-Communicator
- **特点**: 与Arduino通信的App

#### android-pedometer
- **项目地址**: https://github.com/bagilevi/android-pedometer
- **特点**: Android计步器

#### OwnTracks for Android
- **项目地址**: https://github.com/owntracks/android
- **特点**: 自己的轨迹记录

#### Shake Detector library for Android
- **项目地址**: https://github.com/tbouron/ShakeDetector
- **特点**: Android手机震动摇晃检测库

#### Android heart rate monitor
- **项目地址**: https://github.com/phishman3579/android-heart-rate-monitor
- **特点**: Android心跳检测

#### Bluetooth LE Library for Android
- **项目地址**: https://github.com/alt236/Bluetooth-LE-Library---Android
- **特点**: 蓝牙源信息

#### farebot
- **项目地址**: https://github.com/codebutler/farebot
- **特点**: 通过NFC从公交卡中读取数据

#### Sensey
- **项目地址**: https://github.com/nisrulz/sensey
- **特点**: Android手势检测库

### 10. 安全

#### SQLCipher
- **项目地址**: https://github.com/sqlcipher/sqlcipher
- **特点**: Sqlite加密工具

#### Conceal
- **项目地址**: https://github.com/facebook/conceal
- **特点**: 快速高效进行文件加密解密

#### Android-PasscodeLock
- **项目地址**: https://github.com/wordpress-mobile/Android-PasscodeLock
- **特点**: 应用锁，每次启动需要输入密码
- **应用示例**: Wordpress Android、支付宝、挖财

### 11. 地图相关

#### GraphHopper
- **项目地址**: https://github.com/graphhopper/graphhopper/
- **特点**: 快速路由库和服务器使用OpenStreetMap

#### Mapsforge
- **项目地址**: https://github.com/mapsforge/mapsforge/
- **特点**: 基于OpenStreetMap的地图渲染软件

### 12. 插件化

#### Android Plugin Framework
- **项目地址**: https://github.com/umeng/apf
- **特点**: Android插件式开发

#### xCombine
- **项目地址**: https://github.com/wyouflf/xCombine
- **特点**: Android App插件式插件开发

#### dynamic-load-apk
- **项目地址**: https://github.com/singwhatiwanna/dynamic-load-apk
- **特点**: Android动态加载Apk，热部署

### 13. 文件

#### purePDF
- **项目地址**: https://github.com/sephiroth74/purePDF
- **特点**: 允许从SWF文件读取和创建PDF文档

#### Office 365 SDK for Android Preview
- **项目地址**: https://github.com/OfficeDev/Office-365-SDK-for-Android
- **特点**: 支持Microsoft SharePoint、Exchange等

#### OpenSpritz-Android
- **项目地址**: https://github.com/OnlyInAmerica/OpenSpritz-Android
- **特点**: EPub阅读器

#### jsoup
- **项目地址**: https://github.com/jhy/jsoup
- **特点**: 解析html的java库

#### ZIP
- **项目地址**: https://github.com/zeroturnaround/zt-zip
- **特点**: Java压缩和解压库

#### Image File Selector
- **项目地址**: https://github.com/sw926/ImageFileSelector
- **特点**: 轻量级图片文件选择器

### 14. 其他

#### Salvage view
- **项目地址**: https://github.com/JakeWharton/salvage
- **特点**: 带View缓存的Viewpager PagerAdapter

#### Android Priority Job Queue
- **项目地址**: https://github.com/path/android-priority-jobqueue
- **特点**: Android后台任务队列

#### Glide Bitmap Pool
- **项目地址**: https://github.com/amitshekhariitbhu/GlideBitmapPool
- **特点**: Glide Bitmap内存管理库

#### Cobub Razor
- **项目地址**: https://github.com/cobub/razor
- **特点**: 开源的mobile行为分析系统

#### aFileChooser
- **项目地址**: https://github.com/iPaulPro/aFileChooser
- **特点**: 文件选择器

#### androidpn
- **项目地址**: https://github.com/dannytiehui/androidpn
- **特点**: 基于xmpp协议的消息推送解决方案

#### Bolts
- **项目地址**: https://github.com/BoltsFramework/Bolts-Android/
- **特点**: Android的异步编程模式

#### CastCompanionLibrary-android
- **项目地址**: https://github.com/googlecast/CastCompanionLibrary-android
- **特点**: 使Android程序更快接入Google Cast

#### Uninstall_Statics
- **项目地址**: https://github.com/sevenler/Uninstall_Statics
- **特点**: Android应用自身被卸载监听

#### Memento
- **项目地址**: https://github.com/mttkay/memento
- **特点**: 保证Activity数据在配置改变时保持不变

#### FreeFlow
- **项目地址**: https://github.com/Comcast/FreeFlow
- **特点**: 布局引擎，更简单创建自定义布局

#### Android Gesture Detectors Framework
- **项目地址**: https://github.com/Almeros/android-gesture-detectors
- **特点**: Android手势框架，支持双指旋转、移动、平移、缩放

#### CacheUtilsLibrary
- **项目地址**: https://github.com/westlinkin/CacheUtilsLibrary
- **特点**: 简单Android缓存库

#### EasyDeviceInfo
- **项目地址**: https://github.com/nisrulz/easydeviceinfo
- **特点**: Android设备信息获取库

---

## 三、优秀项目篇

### 1. 系统级项目

#### Linux
- **项目地址**: https://github.com/torvalds/linux

#### Android
- **项目地址**: https://android.googlesource.com/

### 2. 实用应用项目

#### ZXing
- **项目地址**: https://github.com/zxing/zxing
- **特点**: 二维码扫描工具
- **备注**: 市面上很多应用的二维码扫描功能都从此修改而来

#### photup
- **项目地址**: https://github.com/chrisbanes/photup
- **特点**: 编辑机批量上传照片到facebook
- **备注**: 代码分包合理，很棒

#### github-android
- **项目地址**: https://github.com/github/android
- **特点**: Github的Android客户端项目

#### Notes
- **项目地址**: https://github.com/MiCode/Notes
- **特点**: MIUI便签
- **备注**: 项目分包比较合理

#### weicuiyuan
- **项目地址**: https://github.com/qii/weiciyuan
- **特点**: 四次元-新浪微博客户端

#### gnucash-android
- **项目地址**: https://github.com/codinguser/gnucash-android
- **特点**: 记账理财软件

#### AntennaPod
- **项目地址**: https://github.com/danieloeh/AntennaPod
- **特点**: 支持rss订阅、音乐订阅

#### ChaseWhisplyProject
- **项目地址**: https://github.com/tvbarthel/ChaseWhisplyProject
- **特点**: 打鬼游戏

#### Tweet Lanes
- **项目地址**: https://github.com/chrislacy/TweetLanes
- **特点**: 功能完整的Twitter客户端

#### Financius
- **项目地址**: https://github.com/mvarnagiris/Financius
- **特点**: 简单易用的记账程序

#### todo.txt-android
- **项目地址**: https://github.com/ginatrapani/todo.txt-android
- **特点**: todo.txt的官方Android应用

#### simpletask
- **项目地址**: https://github.com/mpcjanssen/simpletask-android
- **特点**: 基于todo.txt官方应用的另一个客户端

#### Muzei Live Wallpaper
- **项目地址**: https://github.com/romannurik/muzei
- **特点**: 定时更换桌面精美壁纸

#### Etar Calendar
- **项目地址**: https://github.com/xsoh/Etar-Calendar
- **特点**: OpenSource material designed calendar

---

## 四、开发工具及测试工具篇

### 1. 开发效率工具

#### Json2Java
- **项目地址**: https://github.com/jonfhancock/JsonToJava
- **特点**: 根据JSon数据自动生成对应Java实体类
- **在线演示**: http://jsontojava.appspot.com/

#### IntelliJ Plugin for Android Parcelable
- **项目地址**: https://github.com/mcharmas/android-parcelable-intellij-plugin
- **特点**: Android studio插件，生成Parcelable代码

#### Android Holo Colors IntelliJ Plugin
- **项目地址**: https://github.com/jeromevdl/android-holo-colors-idea-plugin
- **特点**: Android studio插件，生成holo样式9 patch图片

#### Android Drawable Factory
- **项目地址**: https://github.com/tizionario/AndroidDrawableFactory
- **特点**: 用于生成各个分辨率的图片

#### SelectorChapek for Android
- **项目地址**: https://github.com/inmite/android-selector-chapek
- **特点**: Android Studio插件，自动生成drawable selectors xml文件

#### Android Action Bar Style Generator
- **项目地址**: https://github.com/jgilfelt/android-actionbarstylegenerator
- **特点**: Android ActionBar样式生成器
- **在线演示**: http://jgilfelt.github.io/android-actionbarstylegenerator/

#### ButterKnifeZelezny
- **项目地址**: https://github.com/inmite/android-butterknife-zelezny
- **特点**: 快速生成ButterKnife View注入代码的插件

#### RoboCoP
- **项目地址**: https://github.com/mediarain/RoboCoP
- **特点**: 利用Gradle task根据json文件生成ContentProvider

#### appiconsizes
- **项目地址**: http://www.appiconsizes.com/
- **特点**: 用于生成各个分辨率的图片

#### Gradle Retrolambda Plugin
- **项目地址**: https://github.com/evant/gradle-retrolambda
- **特点**: 使Java或Android项目用Java8的Lambdas编写

#### jsonschema2pojo
- **项目地址**: https://github.com/joelittlejohn/jsonschema2pojo
- **特点**: 根据Json内容生成java对象
- **在线演示**: http://www.jsonschema2pojo.org/

### 2. 开发自测相关

#### Quality Tools for Android
- **项目地址**: https://github.com/stephanenicolas/Quality-Tools-for-Android
- **特点**: Android测试及自测工具集合和示例

#### android-test-kit
- **项目地址**: https://code.google.com/p/android-test-kit/
- **特点**: Google的Android测试工具

#### robolectric
- **项目地址**: https://github.com/robolectric/robolectric
- **特点**: 测试用例编写框架
  - 不需要模拟器在一般JVM就可以运行测试用例
  - 能完成在真机上的大部分测试包括感应器

#### Android FEST
- **项目地址**: https://github.com/square/fest-android
- **特点**: 提供方便的断言，提高编写Android自测代码效率

#### BoundBox
- **项目地址**: https://github.com/stephanenicolas/boundbox
- **特点**: 可用于测试类各种访问权限的属性、方法

#### Hugo
- **项目地址**: https://github.com/JakeWharton/hugo
- **特点**: 打印函数信息及执行时间，仅在debug模式生效

#### scalpel
- **项目地址**: https://github.com/JakeWharton/scalpel
- **特点**: 在应用下面添加一层用于界面调试

#### Android Screenshot library
- **项目地址**: https://github.com/rtyley/android-screenshot-lib
- **特点**: Android截图工具类，用于持续集成时截图

#### sonar-android-lint-plugin
- **项目地址**: https://github.com/SonarCommunity/sonar-android
- **特点**: 将android lint的错误在sonar中展现

### 3. 测试工具

#### Spoon
- **项目地址**: https://github.com/square/spoon
- **特点**: 可用于android不同机型设备自动化测试

#### Tencent APT
- **项目地址**: https://github.com/stormzhang/APT
- **特点**: 騰訊开源的Android平台高效性能测试组件

#### Emmagee
- **项目地址**: https://github.com/NetEase/Emmagee
- **特点**: 网易开源的性能测试工具

### 4. 开发及编译环境

#### Buck
- **项目地址**: https://github.com/facebook/buck
- **特点**: facebook开源的Android编译工具，效率是ant的两倍
  - 加快编译速度
  - 可以在编译系统中生成编译规则
  - 编译同时可生成单元测试结果

#### Android Maven Plugin
- **项目地址**: https://github.com/jayway/maven-android-plugin
- **特点**: Android Maven插件，可用于对android三方依赖进行管理

#### umeng-muti-channel-build-tool
- **项目地址**: https://github.com/umeng/umeng-muti-channel-build-tool
- **特点**: 渠道打包工具

#### Genymotion
- **项目地址**: http://www.genymotion.com/
- **特点**: 目前最好用最快的android模拟器

#### gradle-mvn-push
- **项目地址**: https://github.com/chrisbanes/gradle-mvn-push
- **特点**: 方便将Gradle的Artifacts上传到Maven仓库

#### Android Emulator Plugin for Jenkins
- **项目地址**: https://github.com/jenkinsci/android-emulator-plugin
- **特点**: Android模拟器jenkins插件

#### SDK Manager Plugin
- **项目地址**: https://github.com/JakeWharton/sdk-manager-plugin
- **特点**: 下载和管理Android SDK的Gradle插件

#### Gradle Protobuf Plugin
- **项目地址**: https://github.com/andrewkroh/gradle-protobuf-plugin
- **特点**: 将.proto文件转换成Java文件的gradle插件

### 5. 其他开发工具

#### ViewServer
- **项目地址**: https://github.com/romainguy/ViewServer
- **特点**: 允许app运行在任何手机上都可以用HierarchyViewer查看

#### GridWichterle for Android
- **项目地址**: https://github.com/inmite/android-grid-wichterle
- **特点**: 在整个系统上显示grid，用来帮助查看应用布局

#### Catlog
- **项目地址**: https://github.com/nolanlawson/Catlog
- **特点**: 手机端log查看工具

#### PID Cat
- **项目地址**: https://github.com/JakeWharton/pidcat
- **特点**: 根据package查看logcat日志

#### ACRA
- **项目地址**: https://github.com/ACRA/acra
- **特点**: 应用崩溃信息上报到GoogleDoc工具

#### Crashlytics
- **项目地址**: http://www.crashlytics.com/
- **特点**: 提供丰富的应用崩溃信息收集

#### Android Resource Navigator
- **项目地址**: https://github.com/jgilfelt/android-resource-navigator
- **特点**: chrome插件，方便查看github上android源码工程资源文件

#### android-resource-remover
- **项目地址**: https://github.com/KeepSafe/android-resource-remover
- **特点**: 根据lint的提示删除项目中无用的资源

#### Telescope
- **项目地址**: https://github.com/mattprecious/telescope
- **特点**: 通过手势截图报告Bug

---

## 五、杰出个人和团体篇

### 1. 个人

#### JakeWharton
- **Github地址**: https://github.com/JakeWharton
- **就职**: Square
- **代表作**: ActionBarSherlock、Android-ViewPagerIndicator、Nine Old Androids、SwipeToDismissNOA、hugo、butterknife、Android-DirectionalViewPager、scalpel、pidcat
- **主页**: http://jakewharton.com/
- **特点**: 绝对牛逼的大神，项目主要集中在Android版本兼容、ViewPager及开发工具上

#### Chris Banes
- **Github地址**: https://github.com/chrisbanes
- **代表作**: ActionBar-PullToRefresh、PhotoView、Android-BitmapCache、Android-PullToRefresh
- **主页**: http://chris.banes.me/

#### Koushik Dutta
- **Github地址**: https://github.com/koush
- **就职**: ClockworkMod
- **代表作**: Superuser、AndroidAsync、UrlImageViewHelper、ion
- **主页**: http://koush.com/
- **备注**: 对CyanogenMod开源项目有很多贡献

#### Simon Vig
- **Github地址**: https://github.com/SimonVT
- **代表作**: android-menudrawer、MessageBar
- **主页**: http://simonvt.net/

#### Manuel Peinado
- **Github地址**: https://github.com/ManuelPeinado
- **代表作**: FadingActionBar、GlassActionBar、RefreshActionItem、QuickReturnHeader

#### Emil Sjölander
- **Github地址**: https://github.com/emilsjolander
- **代表作**: StickyListHeaders、sprinkles、android-FlipView
- **主页**: http://emilsjolander.se/

#### greenrobot
- **Github地址**: https://github.com/greenrobot
- **代表作**: greenDAO、EventBus
- **主页**: http://greenrobot.de/

#### Jeff Gilfelt
- **Github地址**: https://github.com/jgilfelt
- **代表作**: android-mapviewballoons、android-viewbadger、android-actionbarstylegenerator、android-sqlite-asset-helper
- **主页**: http://jeffgilfelt.com

#### Romain Guy
- **Github地址**: https://github.com/romainguy
- **身份**: Android team成员(2013.10已离开Android team，仍在Google)
- **代表作**: ViewServer
- **主页**: http://www.curious-creature.org/category/android/
- **个人摄影作品**: http://www.flickr.com/photos/romainguy

#### sephiroth74
- **Github地址**: https://github.com/sephiroth74
- **就职**: Aviary.com
- **代表作**: ImageViewZoom、HorizontalVariableListView、AndroidWheel、purePDF
- **主页**: http://www.sephiroth.it/

#### Cyril Mottier
- **Github地址**: https://github.com/cyrilmottier
- **身份**: Google开发者专家认证
- **代表作**: GreenDroid、Polaris
- **主页**: http://cyrilmottier.com/

### 2. 组织

#### Square
- **Github地址**: https://github.com/square
- **代表作**: okhttp、fest-android、android-times-square、picasso、dagger、spoon等
- **主页**: http://square.github.io/
- **特点**: 有态度有良心的企业，很多不错的分享

#### Inmite s.r.o.
- **Github地址**: https://github.com/inmite
- **代表作**: android-styled-dialogs、android-grid-wichterle、android-selector-chapek
- **主页**: http://www.inmite.eu/

### 3. 博客

#### Chet Haase
- **身份**: Android framework UI team成员
- **主页**: http://graphics-geek.blogspot.com/

---

## 六、推荐资源与平台

### 1. 官方平台

#### codekk.com
- **网址**: https://codekk.com
- **特点**: 收集了数万开源项目，支持最新开源项目查看和自动推送、支持开源项目搜索

#### 开发助手App
- **下载渠道**: 小米应用商店、华为应用商店、Vivo应用市场、Opp应用市场、Google Play、酷安、应用宝
- **功能**:
  - 反编译其他应用
  - 查看其他应用布局和控件信息
  - 屏幕取色(颜色取样器)
  - 查看Activity历史记录
  - 查看其他应用Manifest
  - 查看最近使用和最近安装的应用
  - 提取任何应用Apk和So文件
  - 查看最新开源项目
  - 调试应用
  - 查看手机软硬件信息

#### 微信公众号codekk
- **专注**: 技术分享、职业成长、互联网内推、开发助手版本更新

### 2. 作者信息

- **GitHub**: https://github.com/Trinea (Trinea)
- **微博**: http://weibo.com/trinea (Trinea)
- **个人主页**: https://www.trinea.cn/ (关注Android、Java、性能优化、开源项目)

---

## 七、总结

本文档系统性地梳理了Android开源项目的五大类别：

1. **个性化控件(View)篇**: 包含ListView、ActionBar、Menu、ViewPager、GridView、ImageView、ProgressBar、TextView、ScrollView、TimeView、TipView、FlipView、ColorPickView、GraphView、UI Style等16个子类别，共计100+个开源项目

2. **工具库篇**: 包含依赖注入、图片缓存、网络相关、数据库ORM、Android公共库、版本兼容、多媒体、事件总线、传感器、安全、地图、插件化、文件、其他等14个子类别，共计80+个开源项目

3. **优秀项目篇**: 包含系统级项目和实用应用项目，共计15+个完整项目

4. **开发工具及测试工具篇**: 包含开发效率工具、开发自测相关、测试工具、开发及编译环境、其他等5个子类别，共计40+个工具

5. **杰出个人和团体篇**: 包含11位杰出个人、2个杰出组织、1个博客推荐

总计涵盖**250+**个Android开源项目和工具，为Android开发者提供了全面的参考资源。

---

## 八、使用建议

### 1. 如何选择开源项目

在选择开源项目时，建议考虑以下因素：

- **项目活跃度**: 查看最近的commit时间和issue处理情况
- **文档完善度**: 是否有详细的使用文档和示例
- **社区支持**: 是否有活跃的社区和问题解答
- **性能表现**: 是否有性能测试数据
- **兼容性**: 是否支持所需的Android版本
- **依赖关系**: 是否依赖过多其他库

### 2. 如何贡献开源项目

- **提交Issue**: 发现问题及时反馈
- **提交Pull Request**: 修复bug或添加功能
- **完善文档**: 帮助完善使用文档
- **分享推广**: 向社区推荐好的开源项目

### 3. 学习路径建议

对于Android开发者，建议按以下路径学习：

1. **基础控件**: 先学习ListView、ViewPager等基础控件
2. **图片处理**: 学习图片缓存和加载库
3. **网络请求**: 学习网络请求库
4. **数据存储**: 学习数据库ORM工具
5. **架构优化**: 学习依赖注入和事件总线
6. **性能优化**: 学习性能测试工具
7. **开发效率**: 学习开发效率工具

---

## 九、版权信息

本文档基于Trinea维护的Android开源项目汇总仓库整理而成。

**原始项目地址**: https://github.com/Trinea/android-open-project

**许可证**: Apache License 2.0

**版权声明**: Copyright 2014 trinea.cn

---

**文档生成时间**: 2026-06-22

**文档版本**: v1.0

**维护者**: 系统自动生成整理

---

> **提示**: 本文档内容基于原始README文件整理，最新最全版本请访问 [codekk.com](https://codekk.com) 获取实时更新的开源项目信息。