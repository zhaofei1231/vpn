# vpn
vpn 使用文档
====
## VPN连接方法
* 1、打开开始菜单，选择网络与internet。

* 2、在左边菜单栏选择VPN。
* 3、选择添加VPN连接。
* 4、选择Windows内置。
* 5、依次输入连接名称和服务器地址。
* 6、VPN类型选择使用预共享密钥的L2TP/IPsec。
* 7、然后依次填入秘钥、用户名和密码。
## 一直连接不上解决方法
* 1、修改注册表，按下win+R键，输入regedit,打开注册表。
* 2、找到HKEY_LOCAL_MACHINE \SYSTEM \CurrentControlSet\ Services\ RasMan \Parameters下的ProhibitIPSec,若没有则创建。
* 3、鼠标右键新建，选择DWORD值。
* 4、双击ProhibitIPSec,修改数值为1，点击确认，退出注册表编辑器，重启电脑。