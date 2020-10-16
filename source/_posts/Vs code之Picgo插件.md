---
top: false # 置顶
cover: true # 开启轮播
# coverImg: /medias/banner/00.jpg # 指定轮播图
toc: true # 开启目录
# img: /medias/banner/00.jpg # 指定特色图
summary: Picgo图床 # 设置摘要内容
categories: Tools # 分类，建议只有一个
tags: # 标签可以多个
  - Markdown
  - vscode
reprintPolicy: cc_by # 版权
abbrlink: '8808' # 文章链接数字化
password:  # 需要256位
mathjax: false # 数学公式
---
## 一、了解Picgo
一个用于快速上传图片并获取图片 URL 链接的工具。

> PicGo 本体支持如下图床：
七牛图床 v1.0
腾讯云 COS v4\v5 版本 v1.1 & v1.5.0
又拍云 v1.2.0
GitHub v1.5.0
SM.MS V2 v2.3.0-beta.0
阿里云 OSS v1.6.0
Imgur v1.6.0

本体不再增加默认的图床支持。你可以自行开发第三方图床插件。详见 PicGo-Core[官方指南](https://picgo.github.io/PicGo-Doc/zh/guide/getting-started.html#%E5%BF%AB%E9%80%9F%E4%B8%8A%E6%89%8B)

## 二、配置到vscode
> 1.我使用的图床：[SMms](https://sm.ms/),到这注册，获得<kbd> Secret Token </kbd>
2.Vs code搜索安装Picgo插件
3.将Smms获得的Token填入<kbd> picgo>Pic Bed>Smms：Token </kbd>下的框中即可。

## 三、快捷使用
> 剪贴板：<kbd>ctrl</kbd>+<kbd>alt </kbd>+<kbd>u </kbd>
文件夹:<kbd>ctrl </kbd>+<kbd>alt </kbd>+<kbd>e </kbd>
指定路径:<kbd>ctrl </kbd>+<kbd>alt </kbd>+<kbd>o </kbd>

**注意:**若是无反应，查看是否与vscode其他快捷键有冲突，或者与本地其他软件的全局快捷键有从图。


现在就可以愉快的在vscode，尽情书写博客了！
