# 创建redis6.25容器
## 在当前目录创建log, data, conf, conf/redis.conf
## 修改密码
密码存放在redis.conf中requirepass xxxxxx
xxxxxx就是你的密码
## 增加权限
```bash
chmod -R 777 ./log* ./data*
```
## 进入镜像
```bash
docker exec docker_redis -it bash
```
## 登录redis
```bash
redis-cli -a xxxxxxx
```
