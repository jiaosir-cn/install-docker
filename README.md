# install-docker
# 1.docker 安装
curl -sSL https://get.docker.com/ | sudo sh     //官网脚本安装docker



# 2.docker-compose 安装
官网方法 安装
运行此命令以下载 Docker Compose 的当前稳定版本：
curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

# 对二进制文件应用可执行权限：
chmod +x /usr/local/bin/docker-compose
