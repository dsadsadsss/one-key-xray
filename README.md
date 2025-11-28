### xray-sb

#### 一键部署三协议,无需登录面板，体验不一样的快感

#### SSH登陆后执行

带哪吒和临时隧道的：
```
NSERVER='' NKEY='' SUB_NAME='vps' bash <(curl -Ls https://dl.argo.nyc.mn/ser.sh)
```
带哪吒和固定隧道的：
```
NSERVER='' NKEY='' SUB_NAME='vps' TOK='' DOM='' bash <(curl -Ls https://dl.argo.nyc.mn/ser.sh)
```
其他可选参数:

TOK 隧道  

DOM 隧道域名 

SUB_NAME 节点名称，

TMP_ARGO 节点类型，可选vls,vms，rel,socks,tuic,hy2,3x等,默认为3x，即vmess.tuic,hy2三协议



#### 推荐一个抱脸保活项目:

https://github.com/dsadsadsss/serv00-baohuo.git

#### 其他平台通用脚本

https://github.com/dsadsadsss/java-wanju.git
