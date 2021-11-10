> 刚开始看到css例子代码后，觉得像是用另一种格式来替代原本的html元素属性格式？是有点像吧~。

# CSS

## 1.css

* css为 Cascading Style Sheet （级联样式表）的缩写

* CSS 是一种描述 HTML 文档样式的语言
* CSS 描述应该如何显示 HTML 元素
* CSS 从 HTML 页面中删除了样式格式
* CSS 节省了大量工作

* * 样式定义通常保存在外部 .css 文件中。
  * 通过使用外部样式表文件，您只需更改一个文件即可更改整个网站的外观

## 2.css选择器

* CSS 选择器用于“查找”（或选取）要设置样式的 HTML 元素

**选择器分类：**

> - 简单选择器（根据名称、id、类来选取元素）
>
> > - [组合器选择器](https://www.w3school.com.cn/css/css_combinators.asp)（根据它们之间的特定关系来选取元素）
> > - [伪类选择器](https://www.w3school.com.cn/css/css_pseudo_classes.asp)（根据特定状态选取元素）
> > - [伪元素选择器](https://www.w3school.com.cn/css/css_pseudo_elements.asp)（选取元素的一部分并设置其样式）
> > - [属性选择器](https://www.w3school.com.cn/css/css_attribute_selectors.asp)（根据属性或属性值来选取元素）

​      `1. 要选择具有特定 id 的元素，请写一个井号（＃），后跟该元素的 id。`

​       `2. 要选择拥有特定 class 的元素，请写一个句点（.）字符，后面跟类名。`

​      `3. 通用选择器（*）选择页面上的所有的 HTML 元素。`

注：id、类名不能以数字开头

## 3.三种插入样式表

1. 外部css：

* 在文件外部，文件后缀为.css

2. 内部css：

* 在 head 部分的 \<style> 元素中进行定义。

3. 行内css：

* 与刚开始接触的HTML样式类似

---

4. 层叠顺序，其中第一优先级最高：

* 1.行内样式（在 HTML 元素中）
* 2.外部和内部样式表（在 head 部分）
* 3.浏览器默认样式

# 参考于：

[W3school css学习](https://www.w3school.com.cn/css/index.asp)

[了解外部css   link](https://www.cnblogs.com/forforever/p/12343832.html)

