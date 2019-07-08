# 使用docker-compose 安装dreamfactory

> docker-compose 安装dreamfactory

- [dreamfactory](https://www.dreamfactory.com/)
  - DreamFactory是一款自动生成RESTful API的工具，代替标准的CRUD操作，同时集成了很多的插件可以供开发人员个性化使用
- [docker](https://www.docker.com/)
  - Docker是在容器的基础上，进行了进一步的封装，从文件系统、网络互联到进程隔离等等，极大的简化了容器的创建和维护。使得 Docker 技术比虚拟机技术更为轻便、快捷。
- docker-compose
  - Docker Compose 是Docker官方编排（Orchestration）项目之一，负责快速的部署分布式应用

## docker安装

- [官方安装文档](https://docs.docker.com/install/linux/docker-ce/centos/)
  - 在左侧选择对应的操作系统进行逐步安装
- 检测安装是否成功
  - ```$ docker version```

## docker-compose 安装

- [官方安装文档](https://docs.docker.com/compose/install/)
  - 同样选择对应的操作系统进行逐步安装
- 检测是否安装成功
  - ```$ docker-compose version```

## 获取docker-compose.yml

- 下载`docker-compose.yml`
  - ```$ git clone git@github.com:CNBlackJ/docker-compose-dreamfactory.git dreamfactory```

## 启动安装dreamfactory

- 进入docker-compose.yml对应的文件目录
  - ```$ cd dreamfactory```
- 启动
  - ```$ docker-compose up -d```

## 停止服务

- 进入docker-compose.yml对应的文件目录
  - ```$ cd dreamfactory```
- 停止
  - ```$ docker-compose stop```

## Author

👤 **vinli**

* Github: [@cnblackj](https://github.com/cnblackj)
