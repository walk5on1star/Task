# Markdown小笔记





## 一. 基本语法



---

### 1. Markdown标题语法



一级标题如上，      打法：#*（空格）* **标题**

二级标题，              打法：##*（空格）* **标题**

三、四级等如上以此类推，现最多能打到六级



---

### 2. Markdown段落语法（换段）



直接

打回车，<br>或在一段前后打\<p>与\</p>，如     \<p>*你的段落*\</p>



---

### 3. Markdown换行语法



在你要换行的地方<br>处打\<br>

如上一句：在你要换行的地方\<br>处打（不打后面那个了），即可实现上处效果



---

### 4. Markdown强调语法



* 加粗：单词或短语的前后各添加两个星号**或下划线__,或前后分别加上\<strong>、\</strong>。

  如：**小小加粗**

* 斜体：在单词或短语前后添加一个星号*或下划线_，或在前后分别加上\<em>、\</em>。

  如：<em>小小斜体</em>                                                                           

* 粗斜体：上三个***，以此类推

  如：***小小粗斜***    	             

  

---

### 5. Markdown引用语法



在段前加一个>

> 效果

嵌套再加一个>

> > 效果

> >
> >
> >> 以此类推
> >>
> >> > 



---

### 6. Markdown列表语法

创建有序列表，在每个列表项前添加数字并紧跟一个英文句点（记得空格）。

1.没空格

1. 有
2. 空格

创建无序列表，在每个列表项前面添加破折号 (-)、星号 (*) 或加号 (+)。

* 无序列表
* * 嵌套



---

### 7. Markdown代码语法

将单词或短语表示为代码，用两个`包起来。

如：\`你好\`<br>效果：`你好`



---

### 8. Markdown分割线语法

在单独一行上使用三个或多个星号 、破折号或下划线，且不能包含其他内容。

\*效果：

***

-效果：

---

_效果：

___

---

### 9. Markdown链接语法

* 能将一个词语、短语隐藏一个链接，链接平常不显示，当点击该词语，链接将显示出来。

如：我从这里面学的makrdown→\[Markdown语法](https://markdown.com.cn)

效果：[Markdown语法](https://markdown.com.cn)

* 进阶，当鼠标停在链接出现网站的标题或介绍。

如：\[没事百度](https://www.baidu.com "百度现在很少用啦")

效果：[没事百度](https://www.baidu.com "百度现在很少用啦")



---

### 10. Markdown图片语法

* 插入图片Markdown语法代码：\!\[图片alt](图片链接 "图片title") 

放个图片：

![img](http://mms1.baidu.com/it/u=1293202089,3111055882&fm=253&app=120&f=JPEG?w=500&h=500 "你好")

* 进阶，图片点击能进入你设定的链接中：\[\!\[图片alt](图片链接 "图片title") ]\(你放的链接)

再放个图片：

[![img](https://i0.hdslb.com/bfs/article/954bee9f1645a4d9836d4fb6e74ef2e8d7047231.jpg@942w_1677h_progressive.webp "我找不到什么")](https://static.hfi.me/mikutap/)



---

### 11.Markdown转义字符语法

你想在Markdown显示那些在Markdown会显示符号的字符，就在前面加 `\`

没加：**我好帅**

加了：\*\*我好帅**

* `please多实践`

以下列出的字符都可以通过使用反斜杠字符从而达到转义目的。

| Character | Name                                                         |
| --------- | ------------------------------------------------------------ |
| \         | backslash                                                    |
| `         | backtick (see also [escaping backticks in code](https://markdown.com.cn/basic-syntax/escaping-characters.html#escaping-backticks)) |
| *         | asterisk                                                     |
| _         | underscore                                                   |
| { }       | curly braces                                                 |
| [ ]       | brackets                                                     |
| ( )       | parentheses                                                  |
| #         | pound sign                                                   |
| +         | plus sign                                                    |
| -         | minus sign (hyphen)                                          |
| .         | dot                                                          |
| !         | exclamation mark                                             |
| \|        | pipe (see also [escaping pipe in tables](https://markdown.com.cn/extended-syntax/escaping-pipe-characters-in-tables.html)) |

`参考于`[Markdown语法](https://markdown.com.cn "建议直接去那边哦")



---

### 12.Markdown内嵌HTML标签

对于熟悉html的人群，在 Markdown 涵盖范围之外的标签，都可以直接在文件里面用 HTML 本身。如需使用 HTML，不需要额外标注这是 HTML 或是 Markdown，只需 HTML 标签添加到 Markdown 文本中即可。

* 注意：Markdown 语法在 HTML 区块标签中将不会被进行处理。例如，你无法在 HTML 区块内使用 Markdown 形式的`*强调*`。

>另：现我还不是很熟悉HTML，所以没有过多深入学习这条，以后可能会将其补充。

---

###      注 ：

* 当使用谷歌翻译（插件）后，会将某些中文换成另外的意思，如：以此类推（谷歌翻译后变成`以虚假未推`），以为是本地和github网页端之间的问题，后知后觉才发现是谷歌翻译的问题。

