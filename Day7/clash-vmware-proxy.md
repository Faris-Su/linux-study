# VMware Ubuntu 使用 Clash 代理

问题：
Ubuntu可以访问HTTP，但是HTTPS失败

原因：
Clash混合端口未正确处理HTTPS

排查：
ping 192.168.65.1
测试7897端口
curl测试HTTP/HTTPS

解决：
开启Clash局域网连接
使用192.168.65.1:7897
