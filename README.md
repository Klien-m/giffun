# giffun
前几天把 kotlin 看了下，这个项目是看着 郭霖大神 的 giffun 项目跟敲的。

大概总结了以下东西：

1. 在自定义 Application 中进行全局的初始化操作。

2. 封装 SharedPreferences 的操作。
3. 定义常量标识符。
4. 导入 module `api project('module name')`
5. [umeng][1]（数据统计）、 Litepal、 gson、 [eventbus][2]（事件发布订阅，观察者？）、 okhttp、Glide图片加载、[`implementation 'jp.wasabeef:glide-transformations:4.1.0'`][3]、[`'de.hdodenhof:circleimageview:2.1.0'`][4]、七牛云、[Android-Image-Cropper][5]、filebrowser、[PhotoView][6]

6. 接口指定方法，继承接口则有此方法
7. 设置 activity 的基类，就像《第二行代码》里讲的
8. 日志操作的扩展工具类，就像《第二行代码》里讲的
9. AndroidVersion.kt

10. looper
11. 集成 Toast 方法的 Context 使用 Application 的 Context，当前所在代码类有 Context 则使用当前的。
12. Nickname（昵称）
13. isNotEmpty(str) 等价于 str != null && str.length > 0  
    isNot Blank(str) 等价于 str != null && str.length > 0 && str.trim().length() > 0
14. `@JvmStatic` 指定如果它是函数，则需要从此元素生成额外的静态方法。如果此元素是属性，则应生成额外的静态 getter / setter 方法。
15. api 和 implementation
16. implementation "androidx.palette:palette:1.0.0" 拾色器
17. actionStart()
18. setupViews() 初始化布局控件 UserInfo modify
19. CountDownTimer 计时器
