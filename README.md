# 暨美丽管理后台

面向运营人员和管理员的 Vue Web 管理后台，用于维护商品、门店、会员、订单、预约及平台配置。

## 项目简介

管理后台在若依 Vue 3 基础上扩展了暨美丽业务工作台和管理页面，覆盖经营概览、商品与图片、门店、会员、订单、预约、活动、礼品、联盟、收益、分享、支付审计和店铺设置等运营场景，通过 `anqi-beauty-backend` 提供认证、权限和业务 API。

## 技术栈

- Vue 3.5、Vue Router 4、Pinia
- Vite 6、JavaScript、Sass
- Element Plus、Element Plus Icons
- Axios、ECharts、VueUse、Vue Quill
- JSEncrypt（仅保留公开加密逻辑，登录不再在浏览器保存密码）
- npm

## 关联仓库

| 项目 | 说明 | GitHub |
| --- | --- | --- |
| anqi-beauty-backend | 后端服务 | [anqi-beauty-backend](https://github.com/sickelgroupe-create/anqi-beauty-backend) |
| anqi-beauty-admin | 管理后台 | [anqi-beauty-admin](https://github.com/sickelgroupe-create/anqi-beauty-admin) |
| anqi-beauty-app | 用户端 | [anqi-beauty-app](https://github.com/sickelgroupe-create/anqi-beauty-app) |

## 快速启动

```sh
npm ci
npm run dev
```

生产构建：

```sh
npm run build:prod
```

复制 `.env.example` 为本地环境配置，并将 `VITE_APP_BASE_API` 指向后端地址。真实环境变量和服务器地址由部署平台注入，不提交 `.env*` 文件。

## 项目结构

- `src/views/anqi/`：暨美丽经营概览及业务管理页面。
- `src/api/`：登录、系统管理和业务接口封装。
- `src/layout/`、`src/router/`、`src/store/`：后台布局、路由和状态管理。
- `src/components/`、`src/utils/`：通用组件与工具。
- `vite/`：Vite 构建辅助配置。

## 简历描述示例

负责暨美丽运营后台前端开发，使用 Vue 3、Element Plus 和 Pinia 构建商品、订单、会员、门店及经营数据管理界面，并与统一后端 API 完成权限和业务联动。
