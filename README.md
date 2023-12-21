# fly-nginx-web
高性能web渲染服务


## openresty

安装
```
brew tap openresty/brew
brew install openresty

```
启动

```shell
nginx -p `pwd`/ -c conf/nginx.conf
```
```
To start openresty/brew/openresty now and restart at startup:
  sudo brew services start openresty/brew/openresty
Or, if you don't want/need a background service you can just run:
  /usr/local/opt/openresty/bin/openresty -g daemon off;
```
性能测试

