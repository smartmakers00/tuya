[中文版](README_zh.md) | [English](README.md)

# SaaS 开发框架

## 什么是 SaaS 开发框架

SaaS 开发框架基于涂鸦 OpenAPI，预集成了多种 IoT SaaS 功能，并且提供前后端全套的解决方案代码。通过 SaaS 开发框架，开发者能快速搭建出各个行业的 SaaS 应用，极大缩短交付时间，同时显著降低开发成本。

目前框架完全基于涂鸦 OpenAPI，集成了用户登录、角色权限、设备管理、设备控制、数据大盘等常规的基础功能模块，并提供了基于 React（Ant.Design）的前端 UI 界面。开发者只需基于源码做简单的二次开发，即可快速投入商用。

## 快速入门 SaaS 开发框架

我们分别为您准备了快速入门 SaaS 开发框架的文章：

后端：[本地运行 SaaS 开发框架后端项目](https://developer.tuya.com/cn/docs/iot/SaaSDevelopmentFramework_backend?id=Kaqcx9hwc9i62)

前端：[本地运行 SaaS 开发框架前端项目](https://developer.tuya.com/cn/docs/iot/SaaSDevelopmentFramework_ftontend?id=Kaqcwpn4p8guu)

同时，如果您想直接快速体验SaaS 开发框架功能，或没有二次开发需求，可通过 `Docker` 镜像做本地私有化部署。

 - [Docker 镜像地址](https://hub.docker.com/r/iotportal/iot-suite)
 - [运行 SaaS 开发框架 Docker 镜像](https://developer.tuya.com/cn/docs/iot/SaaSDevelopmentFramework_Image?id=Kapsg7pttb8f2)


## 聚合仓库说明

#### iot-server
`Iot Server` 是实现云端行业能力，能灵活集成、扩展 IoT 的统一管控台后端服务应用。

#### tuya-connector
`tuya-connector`可以使得开发者在涂鸦云云对接（OpenAPI或者消息订阅）项目过程中，就如同本地开发一样，无需关注跟云端的连接和处理过程，从而帮助开发者更加聚焦在自身的业务逻辑上。

#### connector
`connector`框架通过简单的配置和灵活的扩展机制，将云端API映射成本地API，订阅云端消息分发为本地事件，使得开发者在云云对接（OpenAPI或者消息订阅）项目开发过程中，不需要花费过多精力关注云环境连接和请求处理过程，从而帮助开发者更好的聚焦在自身的业务逻辑上。

#### iot-portal
IOT Portal是SaaS开发框架的前端项目，基于`qiankun` 框架。IOT Portal UI 使用 React（Ant.Design），提供了标准化的设计界面，行业开发着可以开箱即用。

## Bug和反馈

您可以通过`GitHub Issue`向我们反馈使用的问题和获得帮助。

## 技术支持

可以通过以下链接获得更多帮助

* 涂鸦智能帮助中心: [https://support.tuya.com/en/help](https://support.tuya.com/en/help "https://support.tuya.com/en/help")

* 涂鸦智能全球化智能平台: [https://service.console.tuya.com ](https://service.console.tuya.com  "https://service.console.tuya.com ")


