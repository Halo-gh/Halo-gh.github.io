---
layout: post
title:  "Tortoisegit图文使用教程"
date:   2020-09-28 09:27:36 +0530
categories: Tortoisegit  git
---

本文只针对使用Tortoisegit的用户，使用命令行的后面可以不用看了

1.安装Git及Tortoisegit

先上图，首先需要把123按顺序安装了

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026101750129-443249537.png)

Git下载地址：https://git-for-windows.github.io/

Tortoisegit及语言包下载地址：http://tortoisegit.org/download/

注：Tortoisegit是Git的一个插件，Git程序本身还是要安装的。

2.创建本地Git仓库

本地Git仓库的创建有两种，一是直接Clone已存在的Git仓库，二是本地创建

2.1.Clone仓库

在存放代码的目录点右键，选择Clone

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026104413269-895098843.png)

 输入Url，自动创建本地目录，也可以手动选择

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026104931613-304236887.png)

注：递归需要勾上

确定以后就会Clone本地仓库了

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026105429613-2069426384.png)

2.2.创建本地版本库

新建一个项目目录StudyGit, 在代码目录右键选择创建版本库

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026110327738-198744498.png)

弹出提示，不要勾选纯版本库，直接确定

 ![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026110532129-126199554.png)

目录下生成一个.git的目录，这个目录里面记录的是git操作相关内容，不要动。创建一个新的Code目录

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026111132363-1152696614.png)

至此，采购版本库建立完成了。后面续继操作。

3.Commit,Push,Pull

3.1.当修改完一段代码后，需要把代码提交到版本库中

以从远端Clone的库为例，在2.1.中的目录中右键点击Commit

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026112229269-2078122293.png)

 第一次操作的时候会提示需要输入身份（邮箱）

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026112323894-70943115.png)

点定后进入设置

 ![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026131838926-742219950.png)

确定后提交到本地版本库

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026132343535-1822022286.png)

 

2.2.推送Push更改

提交完成以后弹出如下提示

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026132412301-663002542.png)

可以选择推送（如果已经编译通过），也可以先关闭不Push，点了推送

如果是第一次会出现身份认证的对话框（缺图）

-----------------------------------------我是一张图片-------------------------------------------------

否则出现下图对话框，可以选择推送到哪个分支（什么是分支后面再讲）

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026132648254-158125946.png)

确定之后出现如下图的对话框

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026132805519-1915898410.png)

这就完成了一次从提交Commit到推送Push的操作

2.3.拉取Pull

当工作组里面的其它人写了一段代码，你需要获取时，就需要用到Pull操作。

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026133235660-114567750.png)

选好远端分支

![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026133336426-5659431.png)

 

3.分支

 ![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026134557504-1622810753.png)

 

4.合并

 

5.保存贮藏

 ![img](https://images2017.cnblogs.com/blog/318519/201710/318519-20171026134145519-1705706787.png)

 

6.标签

 

7.版本分支图

 

8.冲突解决

 

9.其它

 

 

本文引用了廖雪峰的Git教程，

讲的很细，大家可以认真阅读一下。

https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000


------------------------------END------------------------------

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
