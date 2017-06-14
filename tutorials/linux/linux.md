# linux cmd

# text （文本处理）

## awk

## sed

## grep

## find


# 网络和端口

## lsof

lsof -u *username*

lsof -i:*port*

lsof -p *pid*

lsof -c *cmd*


## ss

ss --help


-a, --all		display all sockets

-n, --numeric	don't resolve service names

-s, --summary	show socket usage summary

-l, --listening	display listening sockets


## netstat

netstat -ant

netstat -anu

# 进程和服务

## ps

ps -ef

ps aux


## service
## systemctl

# 安装包管理

## rpm

list files in package

rpm -ql *package*
 
rpm -qi --changelog *package*

query/verify package(s) owning file 

rpm -qf *filename* 

rpm -qR *package*


## yum | apt-get

**速记法:增删查改生命周期**

yum install 

yum remove 

yum search

yum list

apt-get install


# 账号和密码

/etc/passwd
/etc/shadow

## useradd

## passwd

## userdel

# 归档压缩

tar -xvf 

tar -cvf
