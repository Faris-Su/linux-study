# Day 7 Git 与 GitHub

## Git 基础

初始化仓库：

    git init

查看状态：

    git status

添加文件：

    git add 文件

提交：

    git commit -m "说明"

推送：

    git push

## GitHub 登录

使用 GitHub CLI：

    gh auth login

## VMware + Clash 代理记录

虚拟机访问 GitHub 时，需要让 Ubuntu 使用宿主机 Clash 代理。

查看 VMware NAT 网关：

    ip route

测试代理端口：

    timeout 5 bash -c '</dev/tcp/IP/7897'

设置代理：

    export http_proxy=http://IP:7897
    export https_proxy=http://IP:7897

## 总结

完成：

-   Vim 学习
-   Git 初始化
-   GitHub 仓库同步
-   VMware 网络代理配置
