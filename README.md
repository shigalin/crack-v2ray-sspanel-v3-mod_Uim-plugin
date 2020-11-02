# crack-v2ray-sspanel-v3-mod_Uim-plugin
# 本版本是肮脏的破解版本，只是自己学习使用，请支持原版
> 破解版可能存在各种未知的风险，请自行判断后使用，本人不对使用本软件产生的各种后果负责。
# 破解二进制文件下载地址：[release](https://github.com/RManLuo/crack-v2ray-sspanel-v3-mod_Uim-plugin/releases)
# 使用教程请看 [备份WIKI](https://github.com/splendidwrx/v2ray-wiki)
## 支持原版
Malio SSPANEL主题 + V2Ray后端，原价1000，现在只需899（V2ray 是按年订阅），👉[查看详情](https://malio.fxxkmy.life/)
## 推广
[crack-soga, 一个更强大的支持v2ray,trojan,ss的后端](https://github.com/RManLuo/crack-soga-v2ray)
## 普通安装
### 后端安装
``` bash
bash <(curl -L -s  https://raw.githubusercontent.com/RManLuo/crack-v2ray-sspanel-v3-mod_Uim-plugin/master/install-release.sh) \
--panelurl http://webapi.com --panelkey webkey --nodeid 2 \
--downwithpanel 1 --speedtestrate 6 --paneltype 0 --usemysql 0 --cfemail mail --cfkey xxx
```
### caddy安装
``` bash
bash <(curl -L -s https://raw.githubusercontent.com/RManLuo/crack-v2ray-sspanel-v3-mod_Uim-plugin/master/install_caddy.sh) node.com xxx@gmail.com https://fakeurl.com v2ray 10550
```

## Docker
### ws+tls
``` bash
cd docker_crack_tls
vi docker-compose.yml
docker-compose up -d
```
### ws
``` bash
cd docker_crack_ws
vi docker-compose.yml
docker-compose up -d
```
