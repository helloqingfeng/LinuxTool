install
=======
经常在`Makefile`中用到的命令。

该命令执行文件复制工作，所以要指明原文件和目的文件。文件名可包含路径。
类似cp，但与cp不同的是该命令可以有许多附加效果。
##常用选项
|选项|附加参数|描述
|:---:|----|----
|-m|权限值|修改文件权限，相当于chmod
|-p|无|修改原文件的的mtime（修改时间），相当于touch
|-D|无|创建目的文件路径中所缺的目录文件
