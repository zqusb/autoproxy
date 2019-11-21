# autoproxy
shadowsocks, shadowsocksr, jsproxy, tls, https

## ssr.sh</br>
脚本说明: ShadowsocksR 真一键安装管理脚本</br>
系统支持: Debian 8+ </br>
脚本特点: </br>
伪装https流量 </br>
ssr默认配置： </br>
端口:9443
密码：somebody
加密方式:chacha20-ietf
协议：origin
混淆：tls1.2_ticket_auth

支持 限制 用户速度 </br>
支持 限制 端口设备数 </br>
支持 显示 当前连接IP </br>
支持 显示 SS/SSR连接+二维码 </br>

下载安装:</br>
```wget -N --no-check-certificate https://github.com/zqusb/autoproxy/releases/download/1.0/ssr.sh && chmod +x ssr.sh && bash ssr.sh auto```
