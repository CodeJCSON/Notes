# ReactNative移动跨平台开发

1. Atom下载链接：[Atom下载链接](https://atom.io/)
   Atom插件：[Atom插件](https://atom.io/packages)
     * 常用插件：
           * 浏览器浏览功能open-in-browser(可以设置快捷键)
           * 分页展示html页面效果atom-html-preview(可以设置快捷键)
           * 文件路径补全autocomplete-path
2. React官网：[React官网](https://facebook.github.io/react/)
   在React官网上面添加下载React包，下载JS框架
3. browser.min.js文件链接：[browser.min.js文件链接](https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.8.24/browser.min.js)
   这个文件很重要，可以使用链接，可以把链接到的内容保存在本地使用，生成一个JS文件

## 苹果操作系统下ReactNative开发环境搭建
### ReactNative开发环境配置：
     * Mac OS X操作系统
     * Xcode 
     * 安装Homebrew
     * 安装Node.js
     * 安装NVM
     * 安装watchman和flow
     * 安装ReactNative

1. 安装步骤：
   * 复制`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`到终端上面，回车执行
   * 在终端执行`brew`进行应用了
   * 在终端执行`brew install node`
   * 在终端执行`brew install watchman`
   * 在终端执行(新手可以跳过这一个执行)`brew install flow`
   * 在终端安装工具`npm install -g yarn react-native-cli`
   * 在终端安装`react-native init AwesomeProject`
   * 如果上一步运行不成功就先执行`yarn config set registry https://registry.npm.taobao.org --global`,`yarn config set disturl https://npm.taobao.org/dist --global`
2. 
# 科学上网工具(翻墙访问国外网站)
# 镜像源[ban.ninja]
### 开发环境搭建流程
* 参考ReactNative官网[参考ReactNative官网](http://reactnative.cn/docs/0.31/getting-started.html#content)
* 如果使用Atom开发ReactNative配置
[ReactNative开发之IDE（Atom+Nuclide）安装，运行，调试](http://blog.csdn.net/hello_hwc/article/details/51612139)
[ReactNative调试技巧](http://www.52learn.wang/archives/1071?utm_source=tuicool&utm_medium=referral)

3. 创建React项目


3. 创建ReactNative项目
   * cd ReactNativeDemo目录
   * react-native init 项目名称

4. 运行项目方法 4.1 直接用Xcode运行
              4.2 也可以用命令行运行 react-native run-ios/android
   用命令行可以运行在两个平台上面

5. 只要不是常量就用{}括起来,调用方法也是用{}

6. {/*注释部分*/}

7. var {width,height}= require('Dimensions').get('window');取得屏幕的宽度
   var screenWidth = require('Dimensions').get('window').width(一般用这个吧，这个比较可靠)
8. (sudo)npm install -g yarn react-native-cli

9. 在真机上面运行，写入IP地址，并且手机的联网地址和电脑地址要一样
   [NSURL URLWithString:@"http://localhost:8081/index.ios.bundle?platform=ios&dev=true"]
   [NSURL URLWithString:@"http://192.168.2.149:8081/index.ios.bundle?platform=ios&dev=true"]

10. 在ReactNative中发现一个比较好的效果(也可以说是很神奇的效果，便于调试),(只要是在同一个网段内，这个没必要，但可以使用)并且程序运行在手机上面，在WebStorm上面修改的东西不需要再一次运行程序就能在手机上面看到效果。

11. 安装定时器类库：
    * 首先先cd 目录文件夹
    * npm i react-timer-mixin --save
    * var TimerMixin = require('react-timer-mixin');
    * mixins: [TimerMixin]

12. this调用的方法：
       * 不加()就是把参数传过去
       * 加上括号()不传参数

13. 另一种调用方法：()=>{this.方法名+()}或()=>this.方法名+(),传参数就加上参数，不传就不加。

14. 九空格实现ListView(内容里面有`内容样式属性`={style.contentStyle},对它进行设置)

15. ListView显示列表，汽车列表：吸顶效果

16. 定义一些变量，一块定义最后用分号；结尾就行

17. padding 内边距，margin:内边距

18. style={[styles.container,{backgroundColor:'red'}]};

19. TabBarIOS

20. navgator navgatorIOS用法不一样

21. fetch

22. debugger 打印断点，控制台输出，console.log()

23. Runtime 热更新

24. state中设置默认属性，setState中修改属性，在文本内显示属性this.state.title

25. 组件和组件之间的传递：可以用属性进行传递；页面和页面之间的传递：可以通过导航之间的属性passProps传递

26. 爱吃鱼的小灰

27. 安卓和iOS不一样的地方：导航栏宽度，标签栏按钮图片，加载启动页的方式(安卓是使用定时器进行替换路由) 

28. 我的设置界面，更多界面，商家界面，首页

29. key一定要加在父组件上面

30. cd 项目目录，sudo npm install(这是直接从github上面下载的RN项目)

31. &bull;

32. Markdown写简历

33. http://www.pc6.com/mac/136546.html
  JDK下载地址：http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html 
  https://www.virtualbox.org/wiki/Downloads
  http://www.genymotion.cn/#theme=download
  start Genymotion
  下载参考简书：http://www.jianshu.com/p/d2071bf01d5b
  brew install gradle(https://gradle.org/install)
34. RN开发、RN和OC混编、Swift和OC混编、Swift和RN混编

35. WebStom设置React Native代码提示
    1  从gitHub上下载xml插件
git clone https://github.com/virtoolswebplayer/ReactNative-LiveTemplate  

    2  安装
将ReactNative.xml复制到 ~/Library/Preferences/WebStorm10/templates ，然后重启 WebStrom。

36. (sudo)npm i react-native-tab-navigator --save 下载标签框架

37. 
   $ git clone https://github.com/JasonStu/ReactNative_Shopping.git
   $ cd ReactNative_Shopping
   $ npm install
   $ react-native run-ios
