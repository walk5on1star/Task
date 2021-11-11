# HTML的学习

## 一. HTML

* 是一种语言，超文本标记语言
* 不是编程语言，是标记语言
* 标记语言是一套标记标签，HTML用标记标签来描述网页

### 1.HTML标签

* HTML标签是由尖括号包围的关键词，如\<html>
* 通常成对出现
* 标签对中，第一个是开始标签（开放标签），第二个是结束标签（闭合标签）

### 2.HTML文档=网页

* HTML 文档描述网页

- HTML 文档包含 HTML 标签和纯文本
- HTML 文档也被称为网页

> 浏览器的作用是读取 HTML 文档，并以网页的形式显示出它们。浏览器不会显示 HTML 标签，而是使用标签来解释页面的内容。

## 二.HTML标签

### 主要 

- \<html> 与\</html> 之间的文本描述网页
- \<body> 与 \</body> 之间的文本是可见的页面内容

### 1.标题

HTML 标题是通过 \<h1> - \<h6> 等标签进行定义的。

### 2.段落

HTML 段落是通过 \<p> -\</p>标签进行定义的。

### 3.链接

HTML 链接是通过 \<a href="`链接`"> `显示文本`\</a>标签进行定义的。

### 4.图像

HTML 图像是通过 \<img> 标签进行定义的。

### 有待补充

...

HTML标签集在哪里鸭？

[在这里](https://www.w3school.com.cn/tags/index.asp)

---



## 三.元素

- 元素的内容是开始标签与结束标签之间的内容
- 元素是元素的内容加上两端的标签
- 大多数 HTML 元素可拥有属性(属性等下讲)
- 空元素，没有内容的 HTML 元素被称为空元素

* * 空元素是在开始标签中关闭的
  * \<br> （定义换行）就是没有关闭标签的空元素

> HTML 标签对大小写不敏感：\<P> 等同于 \<p>。许多网站都使用大写的 HTML 标签。
>
> > 但暂时推荐使用小写。

## 四.属性

* HTML 标签中可以拥有属性。
* 属性为HTML标签添加各种附加信息或者配置选项的参数，为 HTML 元素提供附加信息
* 属性总是以名称/值对的形式出现，如：name="value"
* 属性总是在 HTML 元素的开始标签中

* * 例子：\<h1> 定义标题的开始。

    \<h1 align="center"> 拥有关于对齐方式的附加信息。

    效果：<h1> 定义标题的开始。

    <h1 align="center"> 拥有关于对齐方式的附加信息。

    加个链接：[TIY : 居中排列标题](https://www.w3school.com.cn/tiy/t.asp?f=eg_html_header)

> 属性和属性值对大小写不敏感,但推荐小写。

* 属性值应该始终被包括在引号内。双引号是最常用的，不过使用单引号也没有问题。

### 属性表有吗？

[有个参考](https://www.w3school.com.cn/tags/html_ref_standardattributes.asp)

## 五.样式

* style 属性用于改变 HTML 元素的样式
* style 属性的作用：提供了一种改变所有 HTML 元素的样式的通用方法

### 1.背景颜色

* background-color 属性为元素定义了背景颜色
* 如定义\<body>元素的背景颜色：

\<body style="background-color:red">

\</body>

就定义成红色疗！！

### 2.字体、颜色、尺寸

* font-family、color 以及 font-size 属性分别定义元素中文本的字体系列、颜色和字体尺寸

### 3.文本对齐

text-align 属性规定了元素中文本的水平对齐方式

### 4.等等，有待补充

...

## 六.块级元素与内联元素

### 块级元素：

> > div、p、h1-h6、form、ul、ol、dl、dt、dd、li、table、tr、td、th、hr、blockquote、address、table、menu、pre
>
> > 块级元素独占一行，当没有设置宽高时，它默认设置为100%（其宽度自动填满其父元素宽度）
> >
> > 块级元素允许设置宽高，width、height、margin、padding、border都可控制
> >
> > * 块级元素设置了width宽度属性后仍然独占一行
> >
> > 块级元素可以包行内元素、块级元素

### 内联元素：

a – 锚点 <br>
abbr – 缩写 <br>
b – 粗体(不推荐) <br>
big – 大字体 <br>
br – 换行 <br>
cite – 引用 <br>
code – 计算机代码(在引用源码的时候需要) <br>
em – 强调 <br>
font – 字体设定(不推荐) <br>
i – 斜体 <br>
img – 图片 <br>
input – 输入框 <br>
kbd – 定义键盘文本 <br>
label – 表格标签 <br>
q – 短引用 <br>
span – 常用内联容器，定义文本内区块 <br>
strong – 粗体强调 <br>
textarea – 多行文本输入框<br>

> 内联元素(inline)不会独占一行，相邻的内联元素会排在同一行。其宽度随内容的变化而变化。 
>
> 内联元素不可以设置宽高 
>
> 内联元素可以设置margin，padding,但只在水平方向有效。



# 参考于

以上参考于：

* [html w3school](https://www.w3school.com.cn/html/html5_intro.asp)
* [csdn 块级元素](https://blog.csdn.net/weixin_43675447/article/details/90742635?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522163645872716780265446872%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=163645872716780265446872&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-90742635.first_rank_v2_pc_rank_v29&utm_term=%E5%9D%97%E7%BA%A7%E5%85%83%E7%B4%A0&spm=1018.2226.3001.4187)

* [csdn 内联元素](https://blog.csdn.net/ycq521131/article/details/82590308?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522163646210516780262536615%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=163646210516780262536615&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-82590308.first_rank_v2_pc_rank_v29&utm_term=%E5%86%85%E8%81%94%E5%85%83%E7%B4%A0&spm=1018.2226.3001.4187)

