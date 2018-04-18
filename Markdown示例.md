# Markdown——从入门到精通
#### 导语：
>[Markdown](http://zh.wikipedia.org/wiki/markdown) 是一种轻量级的『标记语言』，它的优点很多，目前也被越来越多的写作爱好者、撰稿者广泛使用。看到这里请不要被『标记』、『语言』所迷惑，Markdown的语法十分简单。常用的标记符号也不超过十个，这种相对于更为复杂的HTML标记语言来说，Markdown可谓是十分轻量的，学习成本也不需要太多，且一旦熟悉这种语法规则，会有一劳永逸的效果。

## 一，认识Markdown

在刚才的导语里提到，Markdown是一种用来写作的轻量级的『标记语言』，它用简洁的语言代替排版，而不像一般我们用的一般字处理软件 *Word* 或 *Pages* 有大量的排版、字体设置。它使我们专心于码字，用『标记』语法，来代替常见的排版格式。例如此文从内容到格式，设置插图，键盘就可以通通搞定了。目前来看，支持Markdown语法的编辑器有很多，包括很多网站（例如，[简书](http://jianshu.io)）也支持了Markdown的文字录入。Markdown从写作到完成，到处格式随心所欲，你可以导出HTML文件用来网站发布，用Markdown写出的简历也可以十分方便的导出PDF格式更能得到HR的好感。本文的所有内容也是用Markdown写成。<Br/><Br/>

### Markdown官方文档
>这里可以看到官方的Markdown语法规则文档，当然，后文我也会用自己的方式阐述这些语法的具体用法。

* [*创始人Joahn Gruber的Markdown语法说明*](http://daringfireball.net/projects/markdown/syntax)
* [*Markdown中文版语法说明*](http://wowubuntu.com/Markdown/#list)

### 使用Markdown的优点

* 专注你的文字内容而不是排版样式。
* 轻松地导出HTML、PDF和本身的.md文件。
* 纯文本内容，兼容所有的文本编辑器与字处理软件。
* 可读、直观。适合所有人的写作语言。

### 我该用什么工具

![Mou icon](http://mouapp.com/Mou_128.png)

#### Mac平台

* 在Mac OS X上，我强烈建议你用[Mou](http://mouapp.com/)这款免费且十分好用的Markdown编辑器，它支持实时预览，既左边是你编辑的Markdown语言，右边会实时的生成预览效果，笔者文章就是Mou这款应用写出来的。

![markdown](https://cdn.sspai.com/attachment/origin/2014/04/15/69489.jpg?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)
其次还有很多同类选择。如果你是个编辑作者，我强烈建议你购买[Ulysses III](http://www.ulyssesapp.com/), 这款应用入围了苹果去年 Mac App Store 的 *The Best of 2013*，相比 Mou 它支持更多的写作格式、多文档的支持。Mou、iA Writer 这些应用都是基于单文档的管理方式，而 Ulysses Ⅲ 支持 Folder、Filter 的管理，一个 Folder 里面可以创建多个 Sheet，Sheet 之间还可以进行 Combine 处理。

![markdown1](https://cdn.sspai.com/attachment/origin/2014/04/15/69490.jpg?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

#### Windows、ios、Web平台
* 笔者并未使用过 Windows 下的 Markdown 工具，但经朋友介绍，有两款还算不错，一款叫 [MarkdownPad](http://www.markdownpad.com/) ，另一款叫 [MarkPad](http://code52.org/DownmarkerWPF/)。
* iOS 端已有相当多的 app 支持 Markdown 语法编辑，例如 Drafts、Day One、iA Writer 等。
* Web 端上，我强烈推荐 简书 这款产品，上面有无数热爱文字的人在不停的创造、分享。在 Web 端使用 Markdown 没有比 [简书](http://jianshu.io/) 更舒服的地方了，它同样支持左右两栏的实时预览，字体优雅、简洁。
![tumblr](https://cdn.sspai.com/attachment/origin/2014/04/15/69491.jpg?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)
* 同样是 Web 端，[Draftin](https://draftin.com/) 这款在线 MD 编辑器也近乎完美。

### Markdown语法的简要规则
#### 标题
![标题](https://cdn.sspai.com/attachment/origin/2014/04/15/69492.jpg?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

标题是每篇文章都需要也是最常用的格式，在 Markdown 中，如果一段文字被定义为标题，只要在这段文字前加 # 号即可。

 # 一级标题

 ## 二级标题

 ### 三级标题

以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。

### 列表
熟悉 HTML 的同学肯定知道有序列表与无序列表的区别，在 Markdown 下，列表的显示只需要在文字前加上 - 或 * 即可变为无序列表，有序列表则直接在文字前加 1. 2. 3. 符号要和文字之间加上一个字符的空格。

![列表](https://cdn.sspai.com/attachment/origin/2014/04/15/69493.jpg?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

### 引用
如果你需要引用一小段别处的句子，那么就要用引用的格式。

> 例如这样

只需要在文本前加入 > 这种尖括号（大于号）即可

![引用](https://cdn.sspai.com/attachment/origin/2014/04/15/69494.jpg?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

### 图片与链接
插入链接与插入图片的语法很像，区别在一个 !号

插入图片的地址需要图床，这里推荐 [CloudApp](http://www.getcloudapp.com/) 的服务，生成URL地址即可。
![图片链接](https://cdn.sspai.com/attachment/origin/2014/04/15/69495.jpg?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

### 粗体与斜体
Markdown 的粗体和斜体也非常简单，用两个 * 包含一段文本就是粗体的语法，用一个 * 包含一段文本就是斜体的语法。

例如：**这里是粗体** *这里是斜体*

### 表格
表格是我觉得 Markdown 比较累人的地方，例子如下：

|Tables     |Are     | cool   |
|---------- |:------:|-------:|
|col 3 is    |right-aligned|$1600|
|col 2 is    |centered|$12|
|zebra stripes| are neat|$1|

### 代码框
如果你是个程序猿，需要在文章里优雅的引用代码框，在 Markdown 下实现也非常简单，只需要用 `` 把中间的代码包裹起来，如 `code` 。图例：

![代码框](https://cdn.sspai.com/attachment/origin/2014/04/15/69496.jpg?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

使用 tab 键即可缩进。

### 分割线
分割线的语法只需要另起一行，连续输入三个星号 *** 即可。

### 小结
到这里，Markdown 的基本语法在日常的使用中基本就没什么大问题了，只要多加练习，配合好用的工具，写起东西来肯定会行云流水。更多的语法规则，其实 Mou 的 Help 文档例子很好，当你第一次使用 Mou 时，就会显示该文档，其次，你也可在撰写过程中，使用 CMD+R 快捷键来快速打开文档，以随时查阅和学习语法。
![Mou Help](https://cdn.sspai.com/attachment/origin/2014/04/15/69497.jpg?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

## 与 Markdown 相关的一些推荐
### 可配套使用的工具
* [Droplr](http://droplr.com/)
* [Cloudapp](http://www.getcloudapp.com/)
* [ezShare for Mac](https://itunes.apple.com/cn/app/yi-xiang/id672522335?mt=12&uo=4)
* [围脖图床修复计划](http://weibotuchuang.sinaapp.com/)
* [马克飞象，专为印象笔记打造的 Markdown 编辑器，非常推荐](http://maxiang.info/)
### 相关文章阅读
* [为什么作家应该用 Markdown 保存自己的文稿](http://apple4us.com/2012/02/why-writers-should-use-markdown.html)
* [Markdown 写作浅谈](http://www.yangzhiping.com/tech/r-markdown-knitr.html)
* [Markdown 工具补完](http://www.appinn.com/markdown-tools/)
* [Drafts + Scriptogr.am + Dropbox 打造移动端 Markdown 风格博客](http://jianshu.io/p/63HYZ6)
* [图灵社区 - 怎样使用 Markdown](http://www.ituring.com.cn/article/23)
* [为什么我们要学习 Markdown 的三个理由](http://news.cnblogs.com/n/139649/)
* [Markdown 语法写作入门指南 by ibuick](http://ibuick.me/?p=4093)

***