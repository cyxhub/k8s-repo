把helm放到/usr/local/bin 目录下，在GitHub下载，helm 3.2.3
进入ingress-nginx 目录，执行： [root@master1 yaml]# helm install ingress-nginx -n ingress-nginx .   # 如果不对，去 https://github.com/kubernetes/ingress-nginx/releases 下载chart包，并修改values.yaml，参考已上传的部分

