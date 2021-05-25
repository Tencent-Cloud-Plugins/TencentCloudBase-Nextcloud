<p align="center">
  <img height="100px" src="./nextcloud.png" />
</p>

# [Nextcloud](https://github.com/nextcloud/server)

NextCloud是一款能快速搭建个人专属或团队共享的私有云同步网盘的开源软件。

## 部署

本项目基于开源应用中心 [oac](https://app.cloud.tencent.com/) 开发部署，支持一键云端部署


[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-Nextcloud&branch=master)

### 配置

- `MYSQL_HOST`：数据库地址
- `MYSQL_USER`：数据库用户名
- `MYSQL_PASSWORD`：数据库密码
- `MYSQL_DATABASE`：数据库名


### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
