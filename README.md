# Lede-Compilation-Notes
xingshu1990自用编译杂记，记录自己编译LEDE固件碰到的问题，解决办法。

## 电脑配置

![电脑配置](https://raw.githubusercontent.com/xingshu1990/Lede-Compilation-Notes/main/images/QQ%E6%88%AA%E5%9B%BE20231230124028.jpg)

曾经我使用的电脑配置不允许，那时候的任何折腾属于【屎里找钻石】：
当时的电脑是W7，4G，硬盘还有坏道，W7系统还是精简版，硬盘大概是512G，还是多少GB，忘记了。
而现在的电脑，能开3-4个excel表格，运行vbox，开着迅雷下载，开着360极速浏览器（7-8个页面），开着photoshop CC 64位，
也没有明显感觉电脑有卡顿。

电脑系统如图，安装的是W11，
虚拟机使用的是virtualbox7.0，
编译用的系统，使用的是ubuntu20.04（ubuntu-20.04.6-desktop-amd64）

virtualbox 和ubuntu的安装，这里不做介绍。
virtualbox和ubuntu安装好以后，要设置虚拟机里的网卡1的【连接方式】，更改为【桥接网卡】，
如果可以，还要点击高级，混杂模式选择【全部允许】
![网卡设置](https://raw.githubusercontent.com/xingshu1990/Lede-Compilation-Notes/main/images/QQ%E6%88%AA%E5%9B%BE20231230142311.jpg)

