# Godplace Blog

一个基于Vue3 + SpringBoot的个人博客系统，包含完整的单页版本和前后端分离版本。

## 项目介绍

Godplace Blog 是一个功能丰富的个人博客系统，具备以下特性：

- 🎨 现代化的UI设计，支持暗黑模式
- 🎵 内置音乐播放器，支持歌词显示
- 📱 完全响应式设计，支持移动端
- 🔧 前后端分离架构
- 🚀 单页版本（可直接部署）

## 项目结构

```
GodplaceBlog-GitHub/
├── frontend/                 # Vue3前端项目
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
├── backend/                 # SpringBoot后端项目
│   ├── src/main/java/
│   ├── pom.xml
│   └── application.yml
├── single-page/            # 单页版本（可直接部署）
│   ├── index.html
│   └── monse_gif/
└── README.md
```

## 快速开始

### 单页版本（推荐）

1. 直接打开 `single-page/index.html` 文件
2. 或部署到任意Web服务器

### 前后端分离版本

#### 前端启动

```bash
cd frontend
npm install
npm run dev
```

#### 后端启动

1. 确保已安装Java 17+
2. 配置数据库（修改 `backend/src/main/resources/application.yml`）
3. 运行：

```bash
cd backend
mvn spring-boot:run
```

## 功能特性

### 前端功能
- 用户登录/注册
- 文章浏览和管理
- 音乐播放器
- 响应式布局
- 暗黑模式切换

### 后端功能
- 用户认证和授权
- 文章管理API
- 文件上传
- WebSocket实时通信
- 数据库操作

### 单页版本特色
- 打字机效果的动态文本
- 修仙文字特效
- 点击爱心动画
- 自动音乐播放
- 滚动导航栏

## 技术栈

### 前端
- Vue 3 + Vite
- Element Plus
- Vue Router
- Axios
- WebSocket

### 后端
- Spring Boot 3.x
- MyBatis Plus
- JWT认证
- MySQL
- Redis
- WebSocket

### 单页版本
- 纯HTML/CSS/JavaScript
- 自定义CSS动画
- 原生Web Audio API

## 部署说明

### 单页部署
直接将 `single-page` 文件夹上传到Web服务器即可。

### 前后端部署
1. 前端打包：`npm run build`
2. 后端打包：`mvn clean package`
3. 部署生成的jar文件到服务器

## 许可证

MIT License

## 联系方式

- 邮箱：15708300285@qq.com
- 项目地址：[GitHub项目链接]