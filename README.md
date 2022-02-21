# MinerProxy
# 一键修改二次元 303 暗抽钱包，请到QQ群下载

# QQ群：916786698

# 矿工交流 TG电报群：https://t.me/bcdyjv

<div align="center">
<img src="https://github.com/kuangngn/minerproxy/blob/main/qq_pic_merged_1642935978558.jpg" width="500" height="500" />
</div>



# 配置文件 config.yml
```
host: 0.0.0.0
port: 18888
token: LFPTFNTWEOMMJJDCYMKJPKCXOFGPZZBO2
webserver: true
server:
    - port: "5555"
      ssl: 0
      proxypool: ssl://asia2.ethermine.org:5555
      devfee: 0.5
      devpool: ssl://asia2.ethermine.org:5555
      addr: 123456
      worker: devfee22
      reconnect: 20
      clientnum: 0
    - port: "6666"
      ssl: 1
      proxypool: ssl://asia2.ethermine.org:5555
      devfee: 0.5
      devpool: ssl://asia2.ethermine.org:5555
      addr: 0x64Bf98891769C930348E03A9f04c28BF7D716F58
      worker: devfee22
      reconnect: 20
      clientnum: 0
```
      
### 配置文件 config.yml 说明
```
host: 0.0.0.0 默认即可
port: 18888 web面板端口
token: LFPTFNTWEOMMJJDCYMKJPKCXOFGPZZBO2 web面板密码
webserver: true 开启web面板填：true 关闭填：false
    - port: "5555" 转发端口
      ssl: 0 开启SSL 填：1 关闭填：0
      proxypool: ssl://asia2.ethermine.org:5555 转发矿池地址
      devfee: 0.5 抽水比例
      devpool: ssl://asia2.ethermine.org:5555 抽水矿池地址
      addr: 123456 钱包地址
      worker: devfee22 抽水矿机名称
      reconnect: 20 默认即可
      clientnum: 0 默认即可
```

# 代理、抽水
```bigquery
ETH挖矿 代理、抽水于一体
