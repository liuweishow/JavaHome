### 常用Linux 命令
1. 修改目录，文件权限的命令 
  chmod
2. 如何获取一个本地服务器上可用的端口。
grep
3. 说说常见的linux命令，linux查看内存的命令是什么？
ls,pwd,cat,tail,grep,vim ;free
4. 查看系统磁盘空间剩余情况的命令
fdisk -l
5. 如何获取java进程的pid
ps -aux | grep appName
6. 如何获取某个进程的网络端口号；
netstat -nap | grep 进程pid
7. 如何实时打印日志
tail
8. 如何统计某个字符串行数；
grep hi /path/to/test/*.txt | wc -l
9. 用一行命令查看文件的最后五行。
# tail  -n 5 /etc/profile
10. 用一行命令输出正在运行的java进程。
jps
11. 绝对路径，当前目录、上层目录，切换目录分别用什么命令？
绝对路径： 如/etc/init.d
当前目录和上层目录： ./  ../
主目录： ~/
切换目录： cd

12. 怎么清屏？怎么退出当前命令？
clear,ctrl+c
13. 目录创建，创建文件，复制文件分别用什么命令？
mkdir, touch、vi，cp

14. 查看文件内容有哪些命令可以使用？tail？cat？less？more？
15. 怎么使一个命令在后台运行? &
16. 终止进程用什么命令? 带什么参数? kill-9 pid有什么风险？
17. 搜索文件用什么命令? 格式是怎么样的? 
find / -name “string*”
18. 使用什么命令查看网络是否连通?
ip addr
19. 使用什么命令查看 ip 地址及接口信息？
ifconfig
19. 使用什么命令查看 ip 地址及接口信息？
20. awk 详解
文本分析
