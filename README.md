## dockerhub

```
docker pull 1q2a3z/nessus:latest
docker run -it -d -p 8834:8834 --privileged=true --name=nessu 1q2a3z/nessus /sbin/init
```

## dockerhub暂未同步，直接选择阿里云

```
docker pull registry.cn-hangzhou.aliyuncs.com/wisd0m/nessus2021
docker run -it -d -p 8834:8834 --privileged=true --name=nessu 199bcbb7bbda /sbin/init
```

## 账号密码

```

Nessus
Nessus.2020
```

docker run 注意加privileged=true /sbin/init
