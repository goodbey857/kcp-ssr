wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocksR.sh

chmod +x shadowsocksR.sh

./shadowsocksR.sh 2>&1 | tee shadowsocksR.log

使用命令：

启动：/etc/init.d/shadowsocks start
停止：/etc/init.d/shadowsocks stop
重启：/etc/init.d/shadowsocks restart
状态：/etc/init.d/shadowsocks status
配置文件路径：/etc/shadowsocks.json
日志文件路径：/var/log/shadowsocks.log
代码安装目录：/usr/local/shadowsocks

卸载方法：

使用 root 用户登录，运行以下命令：

./shadowsocksR.sh uninstall
安装完成后即已后台启动 ShadowsocksR

运行：

/etc/init.d/shadowsocks status


wget https://raw.githubusercontent.com/kuoruan/kcptun_installer/master/kcptun.sh

chmod +x ./kcptun.sh

./kcptun.sh
