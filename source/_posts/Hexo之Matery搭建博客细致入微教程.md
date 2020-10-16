---
author: 
top: true # 置顶
cover: true # 开启轮播
# coverImg: /medias/banner/00.jpg # 指定轮播图
toc: true # 开启目录
# img: /medias/banner/00.jpg # 指定特色图
summary: 爱好技术总要折腾一个博客网站才过得去吧！ # 设置摘要内容
categories: Hexo # 分类，建议只有一个
tags: # 标签可以多个
  - Blog
reprintPolicy: cc_by # 版权
abbrlink: f81 # 文章链接数字化
password:  # 需要256位
mathjax: false # 数学公式
---
## 一、了解[Hexo](https://hexo.io/zh-cn/docs/)
**官方介绍**：Hexo 是一个快速、简洁且高效的博客框架。Hexo 使用 Markdown（或其他渲染引擎）解析文章，在几秒内，即可利用靓丽的主题生成静态网页。  

你不需要什么编程代码的知识储备，只要按照步骤来就可以搭建一个免费的属于子自己的博客网站。

## 二、环境准备
> * 下载安装git, Node.js：**[Git安装](https://blog.csdn.net/qq_36292543/article/details/109021023)** 、**[ Node.js安装](https://blog.csdn.net/qq_36292543/article/details/109021779)**
> * 准备一个Github账号
> * 修改编辑器：Vs code，**[官网下载](https://code.visualstudio.com/)**
> * 学习Markdown基本语法，**[菜鸟教程](https://www.runoob.com/markdown/md-tutorial.html)**
> * 安装Hexo框架：**[安装教程](https://yafine-blog.cn/posts/4ab2.html)**
> * 基于Hexo的博客主题模板：**[模板市场]()**

## 三、搭建配置
有了前面环境部分的准备，接下来就比较快了。  

### 1.切换模板
Hexo框架自带一个主题demo，主题名：landscape，在文件夹<kbd>themes</kbd>中。 切换主题，其实就是替换主题模板。  

### 2.基础配置
首先，我们要能把自己的主题模板在本地运行起来，才能做下一步修改。
> 修改hexo根目录de 配置文件（_config.yml）,<kbd>ctrl</kbd> + <kbd>f</kbd> 搜索：theme的值
修改为：hexo-theme-matery（你的模板文件夹名）

<font color=red>**注意：**</font>所有配置文件的修改，注意冒号后要加【空格】！！

这个时候模板的样式就可以看的到了。

### 3.逐页修改
#### 3.1 首页
##### 3.1.1 网站logo+favicon
logo：商标,格式通常：<kbd>.png</kbd>，favicon：网页图标，格式通常<kbd>.ico</kbd>。
![](https://i.loli.net/2020/10/10/maiJWM82UzoBSkb.png)

> 做ico图标，[比特虫](http://www.bitbug.net/)
将ico图标,放到模板文件夹的/source/img文件夹下
修改模板主题下的_config.yml文件，找到对应的设置,如：

![](https://i.loli.net/2020/10/10/9voYf75lnjRikS4.png)
可以自己修改图片放置的位置！

##### 3.1.2 导航菜单
+ **新增菜单**
>主题配置文件新增菜单
然后到根目录下：hexo new page 新菜单名（英文）

新的文件在：根目录/source/_posts/新菜单名，在对应的md文件新增type： 菜单名

+ **修改图标**
> 主题内置了Awesome图标，路径：主题/source/libs/awesome/all.css
查看对应的图标到[Awesome](https://fontawesome.dashgame.com/)直接复制使用即可。

注意：[Awesome官网](https://fontawesome.com/)可能打不开，很慢！

+ **二级菜单**
``` yml
menu：
  icon：
  children：
   - name：
    url：
    icon：
```
+ **Github小猫**
> 在主题配置文件中，搜索<kbd>githubLink</kbd>,修改true为false即可！

+ **导航栏背景色**
导航栏背景色和页脚footer的背景色是一个css控制的，url：主题/source/css/matery.css
``` css
.bg color{
  background-image: linear-gradient(to right, #e41164 0%, #ffe200 100%);
}
```
这里的颜色为渐变色，透明度可调。

##### 3.1.3 Banner
+ **banner图**


+ **轮播效果**

+ **副标题和字幕**

+ **2个按钮**

+ **社交和rss**

+ **rainbow**

##### 3.1.4 置顶模块
+ **梦想语录**

+ **音乐视频**

+ **置顶文章**

##### 3.1.5 footer
+ **运行时间**

+ **备案地址**

#### 3.2 详情
##### 3.2.1 目录
+ **目录按钮**
+ **背景边框**
##### 3.2.2 评论
+ **Valine评论**

##### 3.2.3 赞赏

#### 3.3 友链
##### 3.3.1 设置友链

##### 3.3.2 头像链接

#### 3.4 关于

#### 3.5 搜索

## 四、进阶美化
基本功能完成后，就是进一步完善修改的阶段了，>>>**[进阶美化]()！**