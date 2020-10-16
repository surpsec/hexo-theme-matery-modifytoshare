---
top: false # 置顶
cover: true # 开启轮播
# coverImg: /medias/banner/00.jpg # 指定轮播图
toc: true # 开启目录
# img: /medias/banner/00.jpg # 指定特色图
summary: Markdown语法从无到有一点一点学习 # 设置摘要内容
categories: Tools # 分类，建议只有一个
tags: # 标签可以多个
  - Markdown
reprintPolicy: cc_by # 版权
abbrlink: f81 # 文章链接数字化
password:  # 需要256位
mathjax: false # 数学公式
---
## 标题
> \#  一级标题
\##  二级标题
\###  三级标题
\####  四级标题
\#####  五级标题
\######  六级标题

**注意**：加上反斜杠“\”,可以嵌套语法。

## 段落

### 换行
2个空格加回车，即可换行成段  

### 首行缩进
【1】 &emsp;或&#8195; //全角
【2】 &ensp;或&#8194; //半角
【3】 &nbsp;或&#160;  //半角之半角

## 字体
加粗：\**加粗字**  或者 \__加粗字__
斜体：\*斜体*  或者 \_斜体_  

\<font face="STCAIYUN">我是华文彩云\</font>

### 字体颜色
**格式：**
\<font color=#0099ff size=12 face="黑体">黑体\</font>
\<font color=gray size=3>gray\</font>
\<font color=#00ffff size=3>null\</font>

> 效果：**加粗**，_斜体_
<font face="STCAIYUN">我是华文彩云</font>
<font color=#0099ff size=3 face="黑体">黑体</font>
<font color=gray size=3>gray</font>

## 分割线
分割线有多种，这里我习惯用3个星号：\***,
效果：
***

## 删除线
文字前后各自加2个波浪线  
> 效果：~~删除线测试~~

## 下划线
用标签\<u>文字\</u>
> 效果：<u>添加下划线</u>

## 脚注
在对应位置右上角加英文的中括号  

> 效果：脚注测试位置^[文末显示]

## 列表
无序列表：3个符号（* + -）都可以
> * 第一个 
>  + 第二个 
> - 第三个 

有序列表：数字加小数点

列表嵌套 :只需在子列表中的选项前面添加“-” ，加4个空格即再次嵌套
> 1.第一项
> - 子列表
>     - 1
>         - 2  

## 引用
### 单行

**格式**：在段落开头使用 > 符号 ，然后后面紧跟一个**空格**符号,即：<kbd>**\> 引用1**</kbd>

**效果：**
> 引用1

### 多行 
**格式：** 在段落开头使用 > 符号，空格+回车即可继续使用引用
效果：
> 第一行
第二行
...
### 嵌套引用 
**格式：** 连续2个> ,再加空格  ,
**效果：** 
>> 嵌套引用

### 列表下的引用 
**效果** ：
+ 列表加引用
    > 引
    > 用 

## 代码
### 行内代码
段落上的一个函数或片段的代码可以用反引号把它包起来（`）

如：`printf()` 函数

### 代码块
**格式：** 代码块:3个```包裹起来，\`\``后面可指定对应的编程语言

**效果** ：
``` javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```

## 链接
**格式**：
> \[地址标题](地址)  或者 <地址>  

效果：
[菜鸟教程](https://www.runoob.com) 或者 <https://www.runoob.com>

## 图片
**格式：**  

```
     ![](./01.jpg '描述')()
```
> 方括号，里面放上图片的替代文字
普通括号，里面放上图片的网址
单引号：鼠标悬浮在图片上显示出的文字。
第2个普通括号：可以是链接地址  

**效果：** 
![图片下备注](http://static.runoob.com/images/runoob-logo.png "鼠标悬浮图片显示说明")(http:www.baidu.com)

## 音乐视频
插入音乐视频可以在各大视频网站的分享处得到插入的代码。
**格式** ：
```
<iframe height=498 width=510 src='视频地址' frameborder=0 'allowfullscreen'></iframe>

<iframe width=430 height=86 src="音乐" frameborder="no" ></iframe>
```
<iframe height=400 width=100%  frameborder="0" src="https://v.qq.com/txp/iframe/player.html?vid=y0704v39a3j" allowFullScreen="true"></iframe>

<iframe width=100% height=86 src="//music.163.com/outchain/player?type=2&id=114389&auto=0&height=66" frameborder="no" ></iframe>


## 表格
**格式：** 制作表格使用 | 来分隔不同的单元格，使用 - 来分隔表头和其他行。

### 语法格式
> \|  表头   | 表头  |
\|  -  | -  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

### 对齐方式
> -: 设置内容和标题栏居右对齐。
:- 设置内容和标题栏居左对齐。
:-: 设置内容和标题栏居中对齐。

## HTML元素
不在 Markdown 涵盖范围之内的标签，都可以直接在文档里面用 HTML 撰写。

目前支持的 HTML 元素有：
\<kbd> \<b> \<i> \<em> \<sup> \<sub> \<br>
### 按键：
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

## 转义
使用了很多特殊符号来表示特定的意义，如果需要显示特定的符号则需要使用转义字符，Markdown 使用反斜杠（\）转义特殊字符：
> **文本加粗** 
\*\* 正常显示星号 \*\*
**注意：** 转义失效，可能需要多个反斜杠。

Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：
> \   反斜线
`   反引号
\> *   星号
_   下划线
{}  花括号
[]  方括号
()  小括号
> \#   井字号
\+   加号
\-   减号
.   英文句点
!   感叹号

