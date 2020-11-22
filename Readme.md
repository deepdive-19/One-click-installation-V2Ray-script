# V2Ray一键安装脚本
支持 V2Ray 绝大多数传输协议，WebSocket + TLS，HTTP/2，Shadowsocks，动态端口，集成 BBR 和锐速优化等。

## 前言
V2Ray 官网：https://www.v2ray.com

V2Ray 是一个于 Shadowsocks 之后非常好用的代理软件，但是由于 V2Ray 的配置略复杂，GUI 客户端不完善，所以 V2Ray 并没有像 Shadowsocks 在科学上网人群之中那么流行。
不过我想，像我这种小小白萌新，更需要的是一个好用的一键安装脚本……
所以，此脚本是为了方便像我这种小小白萌新更加容易去使用 V2Ray，配置 V2Ray。希望对你有帮助 ^_^

如果你是毫无经验的小白，搭建 V2Ray 请看此教程：V2Ray搭建详细图文教程

## 更新日志
* 2018-01-28
第一个完善版本发布…
* 2018-5-2
支持 HTTP/2 … 懒得发一个版本就在这里写一下
* 2018-5-26
支持 Socks5 …
2019-1-5
v3 版本，更加好用了。新年快乐！

## 这是一个提示
真是无聊，折腾啥啊。如果你担心 IP 被墙，建议买个 搬瓦工 Just My Socks 先凑合用着就可以了，被墙自动换 IP，无须担心 IP 被墙！Just My Socks 是搬瓦工出品的代理服务，质量可靠，优质 CN2 GIA 线路，并且支持退款，放心无忧。

## 温馨提示
特么这个脚本没有挖矿，没有挖矿，没有挖矿。 我很抱歉……认真的开了个玩笑
脚本是开源的，开源地址： https://github.com/deepdive-19/One-click-installation-V2Ray-script

## 功能特点
1. 支持 V2Ray 多数传输协议
2. 支持 WebSocket + TLS / HTTP/2
3. 支持 动态端口 (WebSocket + TLS，Socks5， HTTP/2 除外)
4. 支持 屏蔽广告
5. 支持 配置 Shadowsocks
6. 支持 下载客户端配置文件 (不用 Xshell 也可以下载)
7. 客户端配置文件同时支持 SOCKS 和 HTTP
8. 支持 生成 V2Ray 配置二维码链接 (仅适用部分客户端)
9. 支持 生成 V2Ray 配置信息链接
10. 支持 生成 Shadowsocks 配置二维码链接
11. 支持修改 V2Ray 传输协议
12. 支持修改 V2Ray 端口
13. 支持修改 动态端口
14. 支持修改 用户ID
15. 支持修改 TLS 域名
16. 支持修改 Shadowsocks 端口
17. 支持修改 Shadowsocks 密码
18. 支持修改 Shadowsocks 加密协议
19. 自动启用 BBR 优化 (如果内核支持)
20. 集成可选安装 BBR (by teddysun.com)
21. 集成可选安装 锐速 (by moeclub.org)
22. 一键 查看运行状态 / 查看配置信息 / 启动 / 停止 / 重启 / 更新 / 卸载 / 等等…
23. 人性化向导 & 纯净安装 & 卸载彻底

哈哈哈..我故意要写够 23 条的。说着当然，脚本肯定都会有如上所说的功能。

## 安装或卸载
> 温馨提醒，此脚本默认屏蔽一些不友好的网站！(仅限轮子相关)

要求：Ubuntu 16+ / Debian 8+ / CentOS 7+ 系统
推荐使用 Debian 9 系统，脚本会自动启用 BBR 优化。
备注：不推荐使用 Debian 8 系统，因为 Caddy 申请证书可能会出现一些莫名其妙的问题。

**我们推荐使用 搬瓦工VPS，稳定，快速，针对中国线路专门优化，无须担心跑路，服务好，并且支持退款。**

使用 root 用户输入下面命令安装或卸载
```
bash <(curl -s -L https://raw.githubusercontent.com/deepdive-19/One-click-installation-V2Ray-script/main/install.sh?token=ARV54R3X2JAAHU6VTMUKZ3K7XKOKC)
```



