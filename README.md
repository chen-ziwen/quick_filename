﻿## 写个小工具 处理图片路径问题
  工作中，经常需要引入大量的图片资源，而这些图片资源基本都用于插件的主题，它们的命名都存在一定的规律。为了避免每次重复的替换图片工作，搞了一个简单的electron应用，用于快速检查图片资源是否符合要求和一键将图片资源复制到对应的文件夹并重命名。
  由于软件很简单，仅限自己自用，所以没有向外提供配置文件来自由配置替换规则，如果有相同需求的人，可作为参考。

## 示例
![mmexport1706621902997](https://github.com/chen-ziwen/resolve_file_path/assets/85820568/970020e7-9dc1-4823-b9ec-32e5b11af8ff)
![mmexport1706621909331](https://github.com/chen-ziwen/resolve_file_path/assets/85820568/de70f207-4d2a-43b2-8b56-d23aeea3ba68)

## 运行
```git
$ git clone git@github.com:chen-ziwen/quick_filename.git`
$ npm install
$ npm start
```
## 编译成软件
```git
$ npm run build // 编译Vue
$ npm run electron:build // 编译Vue同时编译Electron
```

