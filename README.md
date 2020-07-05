![](https://qgt-style.oss-cn-hangzhou.aliyuncs.com/newcoursep4/g1/g1-2-2/tenor.gif)
##2.1章节 配置SSH 学习几条简单的命令行##
### ssh-keygen -t rsa -b 4096 -C "your_email@example.com" 生成本地SSH---注意：your_email@example.com 写的是自己在注册GitHub时的邮箱   ###
### cat ~/.ssh/id_rsa.pub ---查看生成的SSH 的key【以ssh-rsa为开头 以自己注册的邮箱结尾】 ###
##2.2章节 git clone##
查看当前目录下的文件：ls
查看当前目录下的文件，包含隐藏文件：ls -a
在当前目录下创建文件：touch 文件
在当前目录下创建文件夹：mkdir 文件夹
进入某个文件夹：cd 文件目录
如果直接cd，则会返回根目录，在window电脑下回到当前所在的盘符
删除当前目录下的指定文件（慎用）rm -rf 文件




