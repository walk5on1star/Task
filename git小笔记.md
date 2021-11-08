# 一.git的安装

我是处在Windows平台，所以我安装的方法可能仅适用于Windows。

* 在[git官网](https://git-scm.com/downloads)直接下载，过程中按默认选项即可。

* 安装完成后，还需要最后一步设置，打开git bash，在命令行输入：

  `$ git config --global user.name "Your Name"
  $ git config --global user.email "email@example.com"`

> 问题：因为全是英文，所以什么都看不懂，什么都是按照教程来的，未免有些迷茫，不知道是否到达要求，但依葫芦画瓢，先做着，等出现问题再去各大学习平台查找，一个世界这么多人，不可能就我一个只有这种问题吧？所以不要慌。

# 二.git的使用

## 1.创建仓库

> 使用mkdir于合适的地方进行创建一个空目录
>
> + 如 mkdir test `回车`

> 通过git init命令吧空目录变成git可以管理的仓库，这样仓库即创建完成。

+ + 注：如果你使用Windows系统，为了避免遇到各种莫名其妙的问题，请确保目录名（包括父目录）不包含中文。
  + 且不要对目录中.git文件夹进行修改

## 2.把文件添加到仓库

> 1. 自己手动的将文件放到你所创建的仓库的空目录里
> 2. 在git bash用命令git add `文件名`，把文件添加到仓库
> 3. 用命令git commit，把文件提交到仓库
>
> + + 其中git commit (-m "XXX")为常用用法，括号内容可选择添加，意义是用双引号“ ”内的内容来作为该次提交的说明，方便以后查找、定位改动记录

## 3.仓库版本回退

> 1. 当每次改动文件并提交时，都会有一个版本号，可通过输入git log查看并且将会附有你每次提交的提交说明，git log --pretty=oneline命令效果类似，但更简洁
> 2. 回退上一个版本：通过`git reset --hard HEAD^命令`<br>两个版本：`git reset --hard HEAD^^`<br>回退至上一百个版本：`git reset --hard HEAD~100`
>
> ​       也可指定回到某一个版本，如：`git reset --hard 版本号`
>
> * 注：版本号没必要写全，前几位就可以了，Git会自动去找。当然也不能只写前一两位，因为Git可能会找到多个版本号，就无法确定是哪一个了。
>
> 3. 当你进行回退版本后，又想重返未来，可用`git reflog`命令查看命令历史，来确定回到未来的哪个版本。
>
> 

## 4.远程仓库

> 可以在github添加一个远程仓库，与你在本地创建的仓库同步，这样既可作为备份，又方便与其他人的交流协作
>
> 1. 设置SSH key
>
> 在此电脑中C盘的用户目录中，点击.ssh目录，其中有两个文件`id_rsa`和`id_rsa.pub`,`id_rsa`是私钥，不能泄露出去，`id_rsa.pub`是公钥，可以放心地告诉任何人。
>
> * 若找不到该文件，请于[csdn官网](https://www.csdn.net/)等网站自行查找如何创建秘钥
>
> 之后登录github将`id_rsa.pub`内的内容（可通过记事本打开）粘贴与key文本框中，完成后点击Add key，你就能看到已添加的key了。
>
> 2. 于github创建一个空的仓库，以便等下于本地仓库关联。
>
> 3. 在git bash中输入`git remote add origin git@github.com:michaelliao/learngit.git`命令
>
>    * 注：orgin后面的链接可于github中仓库直接复制过来，如图：![QQ截图20211108172222.png](https://i.loli.net/2021/11/08/DVOcTSebRKr3YUw.png)
>
>    这就关联好了，后面直接输入`git push -u origin master`命令，稍作等待，即完成把本地仓库的内容推送到远程仓库
>

---

# 三.学习git的地方

##### 参考链接：

[廖雪峰的 Git 教程](https://www.liaoxuefeng.com/wiki/896043488029600)、[知乎上挺详细的git教程](https://zhuanlan.zhihu.com/p/30044692 "我廖雪峰的看不懂，又去找了个并照着做完了")、

##### 参考网站：

b站、知乎、csdn、贴吧（应该）等。

* 去培养自己强大的自学能力吧吧——~~——   O-o!!





