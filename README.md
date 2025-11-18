### xray-sb

#### 一键部署三协议,无需登录面板，体验不一样的快感

#### SSH登陆后执行

1.首次部署，复制一建命令，根据需要修改参数,如果配合订阅服务器就能自动订阅，搭建教程看最下面的链接
```
NEZHA_SERVER='' NEZHA_KEY='' SUB_NAME='serv00' bash <(curl -Ls https://dl.argo.nyc.mn/ser.sh)
```
可选参数:TOK 隧道key ，ARGO_DOMAIN 隧道域名 ，SUB_NAME 节点名称，

TMP_ARGO 节点类型，可选vls,vms，rel,socks,tuic,hy2,3x等,默认为3x，即vmess.tuic,hy2三协议

2.重新部署
```
pkill -kill -u $(whoami);NEZHA_SERVER='' NEZHA_KEY='' SUB_NAME='serv00' bash <(curl -Ls https://dl.argo.nyc.mn/ser.sh)
```


#### 推荐一个抱脸保活项目:

https://github.com/dsadsadsss/serv00-baohuo.git

#### 其他平台通用脚本

https://github.com/dsadsadsss/java-wanju.git
