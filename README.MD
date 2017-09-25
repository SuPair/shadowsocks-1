# 原福利社或fireSs加速器全套源码
 ## 安装步骤（前台+后台）
    1.下载ss-panel-v3-mod.sh 到linux目录
    2.给到ss-panel-v3-mod.sh 权限 chmod 777 ss-panel-v3-mod.sh 即可
    3. ./ss-panel-v3-mod.sh 运行 ，根据提示操作
    4.注意 如遇到download zip 包从github下载失败问题，可以手动rz上传,并去除脚本中响应的wget位置即可
    5.前台网站配置文件 默认在 /home/wwwroot/default/config/.config.php
      后台节点服务默认配置在 shadowsocks/userapiconfig.py
 ## Google BBR 加速 
    1.下载 bbr.sh 到linux 目录
    2.给到 bbr.sh 权限
    3. ./bbr.sh 即可
    4.系统支持：CentOS 6+，Debian 7+，Ubuntu 12+
    5.虚拟技术：OpenVZ 以外的，比如 KVM、Xen、VMware 等
    6.内存要求：≥128M
    7.安装完成后 uname -r 查看系统内核
    8.含有 4.12 就表示 OK 了 sysctl net.ipv4.tcp_available_congestion_control 
    
 ## status.sh 为监控脚本
    1. 运行，选择服务端还是客户端，
    2. 配置文件默认在 `/usr/local/ServerStatus/server/config.json`
 ## ssr.sh 一键单端口多用户shadowsocksR 脚本
    1. 上传到服务器，给777权限
    2. 根据提示操作即可
 ### 鸣谢：
    基于91vps脚本更改，前后台取自github相应开源项目，
    使用一键脚本使部署更简单。
    再次感谢相应开源作者的贡献。