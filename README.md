# nginx-ssl

```
docker-compose up
```

浏览器访问 https://jupyterhub.ysee.com

先修改 /etc/hosts

```
sudo echo "127.0.0.1  jupyterhub.ysee.com" >> /etc/hosts
```

如果想修改域名，更改ssl证书

```
sh ssl/gencert.sh
```

修改nginx.conf配置

# 参考文档 

http://www.liaoxuefeng.com/article/0014189023237367e8d42829de24b6eaf893ca47df4fb5e000
