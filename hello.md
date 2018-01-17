---
title: 搭建个人博客
date: 2018-01-17 16:32:12
tags:
---
http://blog.csdn.net/jzooo/article/details/46781805
常见问题解决方案：
http://wp.huangshiyang.com/hexo
在按照教程安装的过程中出现了一些（让人无语的）问题:
1、运行hexo init命令时，要注意必须在空文件夹下运行
2、运行hexo new “博客文件名xxx”新建博客时，报错“FATAL end of the stream or a document separator is expected at line 7, column 9：”
   错误原因是:配置_config.yml中的内容时:后面没有加一个空格。 

还有一个问题，就是公司用的是gitlab，所以如何在同一台电脑上gitlab和github一起使用呢？
https://www.cnblogs.com/qlshine/p/6041301.html
https://segmentfault.com/a/1190000002994742

上述链接最后一步gitlab测试不通过，结合sourcetree使用：
1、创建GitHub仓库（截图远程仓库为https://github.com/DawnSpring/DawnSpring.github.io）
2、在sourcetree各自的tab下，点击设置，输入全名和电子邮件地址，这样切换不同的tab就是不同的仓库。

   