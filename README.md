# serverspeeder锐速一键破解安装版 (转自91yun)
本锐速一键破解安装会在[91Yun](http://www.91yun.org/archives/683)持续发布更新，请大家关注

破解版锐速linux一键自动安装包在本贴持续更新，大家可以加收藏夹，以后有更新都会在这个文章同步。

本破解锐速是是无限带宽版的，破解版锐速的一些代码将逐步开源在github这里。

锐速破解版自动安装过程中有什么问题都可以留言，我尽量解答。

# 特别说明
另外：重要的事情说三遍！！！

锐速不支持Openvz！！！锐速不支持Openvz！！！锐速不支持Openvz！！！

一键检测VPS是Openvz还是KVM还是Xen:
#运行代码:
        wget -N --no-check-certificate https://raw.githubusercontent.com/NightMoon032/ServerSpeeder_Cracked/master/vm_check.sh && bash vm_check.sh
代码运行结束就会在最后一行显示虚拟化技术：kvm还是openv或者是xen一目了然。
		 
CentOS更换内核，提供锐速可用的内核下载:
#CentOS6内核更换为：2.6.32-504.3.3.el6.x86_64
        rpm -ivh http://soft.91yun.org/ISO/Linux/CentOS/kernel/kernel-firmware-2.6.32-504.3.3.el6.noarch.rpm
        rpm -ivh http://soft.91yun.org/ISO/Linux/CentOS/kernel/kernel-2.6.32-504.3.3.el6.x86_64.rpm --force
#CentOS7内核更换为： 3.10.0-229.1.2.el7.x86_64
        rpm -ivh http://soft.91yun.org/ISO/Linux/CentOS/kernel/kernel-3.10.0-229.1.2.el7.x86_64.rpm --force
#查看内核是否安装成功
     	rpm -qa | grep kernel   


* 如果你嫌麻烦，只是想找个好用的SS，嫌麻烦又不想花太多钱，你可以和我合租我的自用精选线路。。。[想租SS的进](https://www.vpn100.xyz/)
* 如果你想知道一些服务器是否适合你，请食用 各种[评测报告](http://www.91yun.org/?s=%E8%AF%84%E6%B5%8B)。我每天都会把我尝试的一些vps评测报告发出来，大家可以收藏好本站，及时关注。


# 锐速破解版安装方法：
        wget -N --no-check-certificate https://raw.githubusercontent.com/NightMoon032/ServerSpeeder_Cracked/master/serverspeeder-all.sh && bash serverspeeder-all.sh
# 锐速破解版卸载方法：
        chattr -i /serverspeeder/etc/apx* && /serverspeeder/bin/serverSpeeder.sh uninstall -f


锐速破解版功能：
如果内核完全匹配就会自动下载安装。
如果没有完全匹配的内核，会在界面提示可选内核，可以手动选个最接近的尝试
自动下载授权文件
自动修改配置文件
已chattr +i /serverspeeder/etc/apx*禁止修改配置文件，可以不用加hosts了
目前只支持CentOS，ubuntu和debian。如果有其他系统支持，可以到[91yun.org我的博客](http://www.91yun.org/serverspeeder91yun)手动下载其他系统的安装包
