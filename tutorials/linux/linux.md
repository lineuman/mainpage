# linux cmd

# text （文本处理）

## awk

## sed

## grep

## cut

## tr

## sort

## uniq

## wc

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

## nmap

echo 0 >/proc/sys/net/ipv4/icmp_ratelimit

echo 0 >/proc/sys/net/ipv4/icmp_ratemask


# 外部连接

## wget

wget *url*
## curl

大部分软件都有调试选项

curl -vv

curl -O *ulr*
## ssh

ssh *ip*

显示debug信息

ssh -vv *ip*

使用公钥私钥

ssh -t rsa

ssh-copy-id

ssh + curl + socks 能搞事情

# 进程和服务

## ps

ps -ef

ps aux


## service
## systemctl

# 系统监控

## top

## free

## vmstat
## mpstat
## vnstat
## lscpu
## lsmod
## lspci
## dmesg
## last
## cat /proc/meminfo

# 安装包管理
## cpio是更加底层的操作，rpm本质也是cpio归档的产物

cpio -itv <test.cpio

## rpm |dpkg

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

# other
计算网络存储os

## binutils

## coreutils

## glibc

## bash

# /proc目录解读


# 参考
[https://www.cyberciti.biz/faq/howto-list-find-files-in-rpm-package/](https://www.cyberciti.biz/faq/howto-list-find-files-in-rpm-package/)
