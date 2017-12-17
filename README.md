# Linux-Command
learn Linux Command

一、 curl

1.$ curl http://www.baidu.com

回车之后，www.baidu.com 的html就显示在屏幕上了


2.下载安装包
下载方式：
curl -O https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-3.2.9.tgz
就会下载mongodb安装包


二 tar

linux下最常用的打包程序就是tar了，使用tar程序打出来的包我们常称为tar包，tar包文件的命令通常都是以.tar结尾的。生成tar包后，就可以用其它的程序来进行压缩。

三 ll命令

ll并不是linux下一个基本的命令，它实际上是ls -l的一个别名。

四 grep命令

Linux系统中grep命令是一种强大的文本搜索工具，它能使用正则表达式搜索文本，并把匹 配的行打印出来。grep全称是Global Regular Expression Print，表示全局正则表达式版本，它的使用权限是所有用户。例：npm list | grep ***

五 ssh

远程登录 $ ssh user@host

六 :wq :x

:wq   强制性写入文件并退出（存盘并退出）。即使文件没有被修改也强制写入，并更新文件的修改时间。
:x    写入文件并退出。仅当文件被修改时才写入，并更新文件修改时间；否则不会更新文件修改时间。

七  管道符号 |

管道符号，是unix一个很强大的功能,符号为一条竖线:"|"。
用法: command 1 | command 2 他的功能是把第一个命令command 1执行的结果作为command 2的输入传给command 2

八 mikdir -p

p代表parents，表示递归创建目录。
列如：
如果要创建目录A并创建目录A的子目录B，没有用-p的情况下是mkdir 2次
如果用-p 可以直接创建2个目录 mkdir -p 目录A/子目录B就可以。
