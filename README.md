# vpn
vpn 使用文档
====
## VPN连接方法
* 1、打开开始菜单，选择网络与internet。
    ![P1]
* 2、在左边菜单栏选择VPN。
    ![P2]
* 3、选择添加VPN连接。
    ![P3]
* 4、选择Windows内置。
    ![P4]
* 5、依次输入连接名称和服务器地址。
    ![P5]
* 6、VPN类型选择使用预共享密钥的L2TP/IPsec。
    ![P6]
* 7、然后依次填入秘钥、用户名和密码。
    ![P7]
## 一直连接不上解决方法
* 1、修改注册表，按下win+R键，输入regedit,打开注册表。
    ![P8]
* 2、找到HKEY_LOCAL_MACHINE \SYSTEM \CurrentControlSet\ Services\ RasMan \Parameters下的ProhibitIPSec,若没有则创建。
    ![P9]
* 3、鼠标右键新建，选择DWORD值。
* 4、双击ProhibitIPSec,修改数值为1，点击确认，退出注册表编辑器，重启电脑。
    ![P10]
	
[P1]:(https://github.com/zhaofei1231/vpn/blob/main/picture/1.png)
[P2]:(https://github.com/zhaofei1231/vpn/blob/main/picture/2.png)
[P3]:(https://github.com/zhaofei1231/vpn/blob/main/picture/3.png)
[P4]:(https://github.com/zhaofei1231/vpn/blob/main/picture/4.png)
[P5]:(https://github.com/zhaofei1231/vpn/blob/main/picture/5.png)
[P6]:(https://github.com/zhaofei1231/vpn/blob/main/picture/6.png)
[P7]:(https://github.com/zhaofei1231/vpn/blob/main/picture/7.png)
[P8]:(https://github.com/zhaofei1231/vpn/blob/main/picture/8.png)
[P9]:(https://github.com/zhaofei1231/vpn/blob/main/picture/9.png)
[P10]:(https://github.com/zhaofei1231/vpn/blob/main/picture/10.png)

