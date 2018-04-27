## 安装iptables

- 检查iptables

service iptables status

根据提示进行安装

- 快速安装iptables 

apt-get install iptables  //Debian,Ubuntu使用此命令
yum install iptables   //Linux,CentOS使用此命令

## 保存防火墙规则

service iptables save
或者/etc/rc.d/init.d/iptables save

## 重启防火墙才能使规则生效

service iptables restart

## 查询修改及删除

iptables -L –n   
#查询正在使用的规则
iptables -L -n --line-numbers  
#将规则按数字序号显示方便删除

## 设定开机启动，这一步很重要推荐设置。

chkconfig iptables on 