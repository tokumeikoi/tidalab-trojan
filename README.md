<img src='https://github.com/tokumeikoi/tidalab-trojan/raw/master/img/tidalab.png' width='100px' align='center'>

## 快速使用

1.首先将节点域名解析到节点服务器，并且可以ping通  
2.执行下列命令签发证书

```
# 请将命令中的domain.com替换成节点域名
curl -fsSL https://github.com/tokumeikoi/tidalab-trojan/raw/master/sign.sh | bash -s domain.com
```

3.执行部署命令

```
# 请将命令中的API替换成V2board面板地址如：https://v2board.com
# 请将命令中的TOKEN替换成V2Board后台系统配置->服务端->通讯密钥
# 请将命令中的NODEID替换成V2Board后台Trojan中添加的节点ID
# 请将命令中的LICENSE替换成授权字符
curl -fsSL https://github.com/tokumeikoi/tidalab-trojan/raw/master/install.sh | bash -s API TOKEN NODEID LOCALPORT LICENSE 60
```

4.当看到如下信息即为部署完成

```
.-----..-..---.  .--. .-.    .--. .---.
`-. .-': :: .  :: .; :: :   : .; :: .; :
  : :  : :: :: ::    :: :   :    ::   .'
  : :  : :: :; :: :: :: :__ : :: :: .; :
  :_;  :_;:___.':_;:_;:___.':_;:_;:___.'

Tidalab Trojan v1.0.0
service.log
[WARN]  2020/06/12 07:36:56 empty fallback address
[WARN]  2020/06/12 07:36:56 empty fallback port
[INFO]  2020/06/12 07:36:56 transport server is listening on tcp: [::]:443
[INFO]  2020/06/12 07:36:56 server-side api service is listening on 127.0.0.1:10000
```

## 动态

telegram@[tidalab](https://t.me/tidalab)
关注channel获得更多讯息