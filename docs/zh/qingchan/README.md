---
title: 使用说明
---

# 简介

青蝉是一个致力于搭建前端云构建服务的开源项目。适用于搭建企业级的前端通用构建服务。
青蝉系统相对于传统的jenkins，优点是更轻量级、更易于使用。默认整合基于github的CI流程，同时提供了标准化的可替代模块说明，用户可以快速地将该系统集成到企业内部CI/CD流程中。

## 安装运行
### 资源需求
- 数据库： Mysql

### 安装全局依赖
```
npm i -g @vue/cli @vue/cli-service
npm i -g @nestjs/cli
```

### 初始化
```
git clone https://github.com/sjli/CicadaCi.git
cd CicadaCi
sh install.sh
```

### 开发环境
```
# webclient
cd webclient && npm run serve
# webserver
cd webserver && npm run start:dev
# ciserver
cd ciserver && npm run start:dev
```

### 代码发布
```
sh deploy.sh
```

## 基本功能说明
### 

## 相关技术

## 集成到企业内部

