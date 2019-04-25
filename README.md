# 汇总linux shell 使用总结

## shell 快捷键总结

###1.常见快捷键
Ctrl-Alt-T  ---> 打开shell终端

Ctrl-Alt-Del ---> 挂起或者重新启动系统

Ctrl + l ---> 清屏

Ctrl + A ---> 光标移到行首

Ctrl + E ---> 光标移到行尾

Ctrl + W ---> 清除光标之前一个单词

Ctrl + K ---> 清除光标到行尾的字符

Ctrl + T ---> 交换光标前两个字符

Ctrl + V ---> 输入控制字符 如Ctrl+v ,会输入^M

Ctrl + F ---> 光标后移一个字符

Ctrl + B ---> 光标前移一个字符

Ctrl + H ---> 删除光标前一个字符

## shell 常用命令总结
###1. 常见命令汇总

ls ---> 常看当前目录文件及其文件夹

df -l ---> 查看磁盘空间

free ---> 内存使用情况

netstat -nltp ---> 查看端口使用情况

grep *** ---> 查询

rm -rf step00000[5,9,1]* --->利用正则删除满足[]表示或，？表示任意一个字符等

ps aux ---> 查看进程使用情况

2. 远程连接服务器

ssh 用户名@服务器ip

注意出现如下错误：

condition1: 出现：ssh: connect to host port 22: Connection refused

解决办法:

sudo apt-get install openssh-server

service sshd restart

3. 命令行拷贝文件到服务器

scp -r 需要拷贝的文件地址 用户名@地址:~/下载
###2. 一个常见的终端安装

 sudo apt-get install terminator




