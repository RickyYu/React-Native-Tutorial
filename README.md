# React Native 教程

作者是一名移动端开发人员，对 iOS/Android 原生开发均有涉足，此文用于知识积累、分享、交流，关于文中不足之处，欢迎指正。

## 准备工作

1. 开发用电脑一台，推荐Mac，可Android和IOS切换调试运行。
2. 良好网络环境，有人说 一句`npm install` 就足以让人生到尽头，此言不假。当然现在可安装国内镜像，速度会大大提升
3. 一定的英文文档阅读能力，React Native 更新非常快，需要及时阅读英文文档获取最新API变动信息。


## 搭建环境

在 Mac 下开发 React Native，需要准备以下环境：

1. [Xcode](https://developer.apple.com/xcode/cn/) - 用于编译、构建项目，运行模拟器等
2. [node.js](https://nodejs.org/en/) - 项目的依赖等都需要通过 node.js 的 npm 包管理器安装、管理
3. [AndroidStudio](https://developer.android.google.cn/index.html) - Android集成开发工具
4. [Watchman](https://facebook.github.io/watchman/) - 文件监控工具，可以监听文件变化，然后执行各种任务
5. [WebStorm](https://www.jetbrains.com/webstorm/) - Web前端开发神器

在安装完以上各项后，我们就可以在命令行下初始化项目并运行起来：

```bash
$ react-native init FirstApp
$ cd FirstApp
$ react-native run-ios
$ react-native run-android
```

## 目录

1. [Day 01](syntax.md)
2. [Day 02](text.md)
3. [Day 03](image.md)
4. [Day 04](image.md)

&copy; 2017，Ricky
