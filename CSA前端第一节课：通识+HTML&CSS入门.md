# CSA前端第一节课：通识&HTML&CSS

## 前言

**前端是什么？😕**

前端即网站前台部分，运行在PC端，移动端等浏览器上展现给用户浏览的网页。随着互联网技术的发展，HTML5，CSS3，前端框架的应用，跨平台响应式网页设计能够适应各种屏幕分辨率，完美的动效设计，给用户带来极高的用户体验。

**前端只能做网页🐎？**

非也，依赖于react native等技术，我们还可以实现小程序和跨端移动应用，

通过nodejs，我们还可以写后端的程序

大前端的潮流已经是不可避免了

不过万丈高楼也要拔地起，我们就从基础的网页做起吧！😁

## 通识

### 1.VScode

首先我们需要一个写代码的地方，就像这样

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-18-45-01-image.png)

不过缺点显而易见，没有代码高亮，没有语法提示，没有文件管理功能等

所以我们需要一个高级的文本编辑器——VScode

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-18-49-11-image.png)

看起来是不是好多了。

**进入[vscode官网](https://code.visualstudio.com/)下载或者[点击这里](https://pan.stellaris.wang/d/aliyun/software/pc/%E7%BC%96%E7%A8%8B%E8%BD%AF%E4%BB%B6/VSCodeUserSetup-x64-1.72.2.exe)下载**

tips：一般来说安装，除了自己可以选一下安装路径，其他的霸王条框该同意就同意，一路next就好了。

### 2.VScode推荐插件

| 插件名                                                              | 介绍                       |
| ---------------------------------------------------------------- | ------------------------ |
| View In Browser                                                  | 快速在浏览器打开html页面           |
| HTML CSS Support                                                 | HTML CSS句法提示             |
| Path Intellisense                                                | 路径提示                     |
| Code Spell Checker                                               | 检测单词，命名错误，有助于良好的编程习惯     |
| Chinese (Simplified) (简体中文) Language Pack for Visual Studio Code | 中文插件，建议不用，敲代码还可以过级谁不喜欢呢？ |
| JavaScript (ES6) code snippets                                   | js语法提示                   |
| Atom One Dark Theme                                              | 一款我觉得挺好看的主题              |
| Auto Rename Tag                                                  | 自动修改html标签               |

插件在这安装

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-20-21-56-image.png)

### 3.GitHub+Git

#### GitHub

众所周知GitHub是全球最大的同性交友平台（bushi）

简而言之

github是一个帮你管理代码的**网络仓库**

不仅如此，它还有众多的**开源仓库**

它确实是全世界**最大**的代码托管平台

可以说如果一个开发者没有用过它，那他多半是out了。

首先你得注册一个[GitHub账号](https://github.com/)

#### Git

Git是什么？

Git 是目前世界上最先进的分布式版本控制系统

##### 什么是版本控制系统？

比如说你将来给甲方做🐂🐎了，你要给甲方写一个项目文档...

![image20221029124729958](https://typora.stellaris.wang/image-20221029124729958.png)

你学聪明了，之后你给每个版本的文档建立了一个独立文件...

![image20221029125220579](https://typora.stellaris.wang/image-20221029125220579.png)

于是你想，如果有一个软件，不但能自动帮我记录每次文件的改动，这样就不用自己管理一堆类似的文件了，也不需要把文件传来传去。如果想查看某次改动，只需要在软件里瞄一眼就可以，岂不是很方便？

这个软件应该是这样的：

| 版本号 | 文件名       | 用户  | 说明     | 日期                  |
| --- | --------- | --- | ------ | ------------------- |
| 1   | 项目文档.docx | 王鑫  | 初版     | 2022-10-29 12:55:22 |
| 2   | 项目文档.docx | 袁神  | 增加项目说明 | 2022-10-29 15:23:34 |
| 3   | 项目文档.docx | 灿灿  | 添加项目细节 | 2022-10-29 16:22:03 |
| 4   | 项目文档.docx | 荟荟子 | 修改拼写错误 | 2022-10-29 18:43:49 |

![image20221029213830541](https://typora.stellaris.wang/image-20221029213830541.png)

##### 什么是分布式？

![](https://img2020.cnblogs.com/blog/1673958/202103/1673958-20210329150044538-2059927341.png)

集中式版本控制系统，版本库是集中放在中央服务器的，而干活的时候，用的都是自己的电脑，所以首先要从中央服务器哪里得到最新的版本，然后干活，干完后，需要把自己做完的活推送到中央服务器。集中式版本控制系统是必须联网才能工作，如果在局域网还可以，带宽够大，速度够快，如果在互联网下，如果网速慢的话，就纳闷了。

分布式版本控制系统，那么它就没有中央服务器的，每个人的电脑就是一个完整的版本库，这样，工作的时候就不需要联网了，因为版本都是在自己的电脑上。既然每个人的电脑都有一个完整的版本库，那多个人如何协作呢？比如说自己在电脑上改了文件A，其他人也在电脑上改了文件A，这时，你们两之间只需把各自的修改推送给对方，就可以互相看到对方的修改了。

##### 使用

![68341950059ed5ebe73ac6](https://typora.stellaris.wang/683419500-59ed5ebe73ac6.png)

![](https://ask.qcloudimg.com/http-save/yehe-2728002/gq3h0y9rx1.png?imageView2/2/w/1620)

![image20221029215454210](https://typora.stellaris.wang/image-20221029215454210.png)

[Git从入门到入狱](https://blog.stellaris.wang/p/experience/git/)

##### 基本配置

```
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
```

##### 基本操作

**创建版本库（init）**

**将文件添加到暂存区（add）**

**将暂存区里面的文件添加到版本库（commit）**

**查看仓库状态（status）**

**查看仓库中的具体修改（diff）**

**查看提交历史记录（log）**

**查看命令历史（reflog）**

**版本回退（reset --hard）**

**撤销修改（checkout）**

**删除文件（rm）**

##### 分支管理

**查看分支（branch -v）**

**创建分支（branch branchname）**

**切换分支（branch branchname）**

**合并分支（merge）**

**删除分支（branch -d）**

##### 远程仓库

**添加远程仓库（remote add）**

**推送本地内容到远程仓库（push）**

**从远程克隆仓库到本地（clone）**

**修改本地指向远程仓库地址（remote set-url）**

**获取远程数据的变更（fetch/pull）**

##### 总结

tips：以上都是**蓝山鑫神**写的

是不是看到这人都看麻了，你先别急😭，其实常用就那么几个

1.进入登录github，你应该能看到这个页面，点击红框按钮![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-19-30-38-image.png)

2.填入你的仓库名字就好，然后Create

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-19-33-48-image.png)

3.

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-19-36-55-image.png)

4.打开VScode 通过<mark>Ctrl+Shift+` </mark>打开终端，输入以下命令

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-19-51-04-image.png)

5.这样就可以在你的网络厂库看到啦（到时候交作业吧下图网址给学长学姐就好了）

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-19-53-09-image.png)

## HTML

### 介绍

HTML是什么😕（——蓝山姜神）？

- HTML 指的是超文本标记语言 (**H**yper **T**ext **M**arkup **L**anguage)是用来描述网页的一种语言。

- HTML 不是一种编程语言，而是一种标记语言 (markup language)

- 标记语言是一套标记标签 (markup tag)

- 一句话说出html作用:

网页是由网页元素组成的 ， 这些元素是利用html标签描述出来，然后通过浏览器解析，就可以显示给用户了

***html 总结:***

- html 是超文本标记(标签)语言
- 我们学习html 主要学习html标签
- 我们用html标签描述网页元素。 比如 图片标签 、文字标签、链接标签等等
- 标签有自己的语法规范，所有的html标签都是用 <> 表示的
- H（很）T（甜）M（蜜）L（啦） 是很快乐的一件事情

### 第一个页面

打开VScode新建一个后缀名为html的页面，输入感叹号，按下回车键生产默认结构

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-20-30-06-image.png)

像这样

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-20-31-39-image.png)

不出意外的话就能在浏览器看到自己的页面了

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-20-33-22-image.png)

### HTML常用标签

#### 1.标题标签h1-h6

1.<h>`标签可定义标题。`<h1>`定义最大的标题。`<h6>` 定义最小的标题。

```html
<h1>这是标题1</h1>
<h2>这是标题2</h2>
<h3>这是标题3</h3>
<h4>这是标题4</h4>
<h5>这是标题5</h5>
<h6>这是标题6</h6>
```

#### 2.列表

##### ul无序列表

```html
<ul>
<li>1</li>
<li>2</li>
<li>3</li>
</ul>
```

1.u标签里只能嵌套li标签

2.li标签可以嵌套任意标签

##### ol有序列表

所有特性基本与ul 一致，比ul多了一个顺序数字

#### 3.div，span

div和span都是我们常用的盒子标签

##### div与span的区别

div和span的区别：1、div标签是块级元素，每个div标签都会从新行开始显示，占据一行；2、div标签内可以添加其他的标签元素；3、span标签是行内元素，会在一行显示；4、span标签内只能添加行内元素的标签或文本。

##### div

div标签是块级元素，拥有块级元素的特点。每对div标签（）里的内容都可以占据一行，不会其他标签在一行显示；div标签总是从新行开始显示；

由于div是块级元素,div可以设置宽高，且还可以设置标签之间的距离（外边距和内边距）；

##### span

span标签是行内元素，拥有行内元素的特点。span标签元素会和其他标签元素会在一行显示（块级元素除外），不会另起一行显示（如上例）。

span标签的宽度、高度都无法通过css样式设置，它的宽高受其本身内容（文字、图片）控制，随着内容的宽高改变而改变；span标签无法控制外边距和内边距，虽然可以设置左右的外边距和内边距，但上下的外边距和内边距无法设置。

且，span标签里只能容纳文本或者是其他的行内元素，不能容纳块级元素。

#### 4.a标签

a标签是定义网页的超链接，是用在从一个页面往另一个页面的超链接

a标签中最重要的一个属性是href属性，也是a标签必须的一个属性，因为href属性定义的是链接的目标。

```html
<a herf="www.baidu.com"></a>
```

#### 5.其他

```html
<img src="../image.png">//引入图片
<input type="属性值" value="输入框中的值"  name="name"/>//输入框
<input type="text" value="我是普通文本框"  name="name"/>
<input type="search" value="我是搜索框"/>
<input type="password" value="我是密码框" />
<table></table> //表格
<video></video>//引入视频
<audio></audio>  //引入音频
...
```

还有很多HTML标签，就不一 一列举了，

**建议到[pink老师](https://www.bilibili.com/video/BV14J4114768/?spm_id_from=333.337.search-card.all.click)这仔细学一下用法**

**或者看看[W3C文档 ](https://www.w3schools.com/html/default.asp)**

## CSS（层叠样式表）

**css就是让你的HTML变得好看的语法**

注意：本文解释css属性与值的内容比较少，需要对照着手册查询,css属性太多，不可能介绍完全,需要的话可以点击下面链接方便查找

[CSS 参考手册](https://www.w3school.com.cn/cssref/index.asp)

- CSS（层叠样式表）用于设置和布置网页 - 例如，更改内容的字体，颜色，大小和间距，将其拆分为多个列，或添加动画和其他装饰功能。

### css语法

它一般由 **选择器** **属性** **值** 三部分构成,如下图

![](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics/css-declaration-small.png)

### css引入

一共有三种方式引入css样式

1. 内联
2. 页级
3. 外联

```html
<!-- 内联css是通过标签的style属性引入,形式是"属性:值"，以";"为分割 -->
<div style="width:60px;font-size:20;">内联css</div>
```

```html
<!-- 页级css是通过style标签引入,一般放在head里，尽量避免使用，因为这样会导致文件过长难以维护 -->
<!DOCTYPE html>
<html lang="">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <style>
     /* 通过这段代码可以使所有的div变成400*400的猛男色方块 */
     div {
      width: 400px;
      height: 400px;
      background-color: deeppink;
    }
  </style>
</head>

<body>
  <div id="app" style="font-size: 20px;"></div>
</body>
</html>
```

```html
<!-- 外联css是通过link标签或者style标签的@import引入css文件,一般也放在head里 -->
<!DOCTYPE html>
<html lang="">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <!-- link标签引入,推荐着这种方式，可利用浏览器的缓存功能缓存资源 -->
  <link rel="stylesheet" href="/path/to/your/css/file">
  <style>  
    /* @import引入 */
    @import url(path/to/your/file); 
    @import "path/to/your/file";
  </style>
</head>

<body>
  <div id="app" style="font-size: 20px;"></div>
</body>
</html>
```

### 路径

- 相对路径

通过"."开头则为相对路径，即从当前文件出发,"./a"为当前目录下a文件,"../a"为上一级目录a文件,依次类推。

- 绝对路径  
  绝对路径则是完整的路径，比如: "https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png"或者"D:\web\img\logo.gif"

### css单位

CSS 有几个不同的单位用于表示长度。一些设置 CSS 长度的属性有 width, margin, padding, font-size, border-width, 等。长度有一个数字和单位组成如 10px, 2em, 等。数字与单位之间不能出现空格。如果长度值为 0，则可以省略单位。对于一些 CSS 属性，长度可以是负数。有两种类型的长度单位：相对和绝对。

- 常用的相对单位

- em 取决于当前元素的字体大小。一般浏览器字体大小默认为16px，则2em == 32px；

- rem 取决于根元素字体大小，其他和em一样

- vw 视口宽度 1vw = 浏览器视口的1%宽度

- vh 视口高度 1vh = 浏览器视口的1%高度

- % 百分比

- 常用的绝对单位

- px 像素

### css选择器

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-21-37-36-selector.png)

举个例子

```html
<!DOCTYPE html>
<html lang="">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <style>
    /* 类选择器用.开头 */
    .a {
      width: 300px;
      height: 300px;
    }
    .b{
      background-color:deeppink;
    }
    /* id选择器用#开头 */
    #a{
      opacity:0.5;
    }
   /* 标签选择器 */
    img{

    }
</style>
</head>
<body>
     <div class="a" id="a"></div>
     <div class="a b"></div>
     <img/>
</body>
</html>
```

### CSS自学内容

1.`position`属性相关内容 [资料](https://www.w3schools.com/Css/css_positioning.asp)

2.`display:flex`属性 [资料](https://www.ruanyifeng.com/blog/2015/07/flex-examples.html)

4.`transform`[资料](https://developer.mozilla.org/en-US/docs/web/css/transform)

3.`float`

5.`display:grid`

6.css动画

以上都可以在[MDN]([MDN Web Docs](https://developer.mozilla.org/en-US/))上学习哦（作业需要用到上述内容）

## 最后

### 建议

如果你之前没有接触过前端，我觉得你看完了会很懵，但是时间·内容限制，无法更详细的说明，所以xxx自习室的称号不是浪得虚名的。

[pink老师的html和css部分](https://www.bilibili.com/video/BV14J4114768/?spm_id_from=333.337.search-card.all.click&vd_source=a69f508a3c51f446bb2deb7ac55907b2)我建议把视频html和css的部分刷完，html和css的掌握在这个阶段就够用了。

没有基础的，一定一定一定要自己去学，我们给的课件都是基础，要自己通过网络资源学习——码山有路勤为径，学海无涯苦作舟。

### 资源

#### 文档

1.[MDN](https://developer.mozilla.org/zh-CN/)很全的文档

2.[W3C](https://www.w3schools.com/default.asp)很全的文档+1

3.[菜鸟](https://www.runoob.com/)看看语法就好，不怎么推荐

4.[另一个W3C](https://www.w3school.com.cn/w3c/index.asp)

5.[廖学峰](https://www.liaoxuefeng.com/)

6.[js](https://zh.javascript.info/)虽然还没有学，但是先收藏好吧，一般人我都不告诉他的，力推

#### 视频

1.[哔哩哔哩](https://www.bilibili.com/)其实大部分东西都可以在Bilibili大学学习

2.[慕课网](https://www.imooc.com/)

3.[极客时间](https://time.geekbang.org/)

#### 论坛（不懂先搜）

1.[CSDN](https://www.csdn.net/)

2.[掘金](https://juejin.im/)

3.[SegmentFault思否](https://segmentfault.com/)

#### 科学上网

可能你上github等外网会发现非常慢或者压根上不去，这时候你就需要一些科学上网工具。

1.[GreenHub](http://greenhubtx.ga/)免费，免配置，方便但不稳定

2.[魔戒](https://mojie.cyou)高速稳定，但不免费，要配置，具体不知道可以直接call我

#### 作业

作业推到自己的github仓库，发网址给自己的导师就好了

1.仿写这个页面,就是[这]([必应 (bing.com)](https://cn.bing.com/))（图片随意）（图标也随意，主要是把盒子放到合适的位置）（必做）

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-22-44-15-image.png)

2.实现如下布局（grid）（必做）![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-22-42-03-dense.png)

3.（附加项）让你的卡片3d环绕起来,如下图（图片随意）

![](C:\Users\Lenovo\AppData\Roaming\marktext\images\2022-11-01-22-46-47-1657553230195.png)
