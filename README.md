# install-docker
# 1.docker 安装 使用官网脚本安装
```curl -sSL https://get.docker.com/ | sudo sh```

验证方法 docker -v

# 2.docker-compose 安装  使用官网方法 安装

 I.运行此命令以下载 Docker Compose 的当前稳定版本：

```curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose```

 II.对二进制文件应用可执行权限：
```chmod +x /usr/local/bin/docker-compose```

验证方法 docker-compose -v



# 其他
 查询是否安装过 curl
 which curl
 查询是否安装过 docker
 which docker
