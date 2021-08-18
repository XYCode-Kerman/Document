---
sidebar_position: 1
---

# 简介

YiriMirai 是一个轻量级、低耦合的基于 mirai-api-http 的 Python SDK。


## 特点

 - 全面支持 mirai-api-http 2.X 版本的新 API。
 - 基于 asyncio，支持异步 I/O，运行效率更高。
 - 使用 pydantic 进行数据解析，对几乎所有数据进行了封装，提供了更好的可读性，支持在编写代码时使用 IDE 的自动完成。


## 其他优秀的项目

首先感谢 [mirai](https://github.com/mamoe/mirai) 和 [mirai-api-http](https://github.com/project-mirai/mirai-api-http)，这两个项目是我们的基础。

基于 mirai-api-http 的 Python 框架还有：

 - [Graia Framework](https://github.com/GraiaProject/Application)。这是一个设计精巧，协议实现完备的，基于 mirai-api-http 的即时聊天软件自动化框架。
 - [saaya](https://github.com/jerrita/saaya)。这是一个基于 mirai-api-http 的轻量机器人框架。
 - [miraicle](https://github.com/Excaive/miraicle)。这是一个基于 mirai-api-http 的轻量级 Python SDK。

支持 mirai 的 Python 框架（SDK）还有：

 - [NoneBot](https://github.com/nonebot/nonebot2)。这是一个可扩展的 Python 异步机器人框架，支持 mirai（OneBot）、Telegram、钉钉等多种平台。
 - [aiocqhttp](https://github.com/nonebot/aiocqhttp)。这是 NoneBot 所使用的 OneBot SDK。

其他可用于 Python 的 QQ 聊天机器人框架（SDK）还有：

 - [CAI](https://github.com/cscs181/CAI)。这是一个完全使用 Python 编写的 QQ 协议支持库。

## 开源协议

由于 mirai 及 mirai-api-http 均采用了 AGPL-3.0 开源协议，本项目同样采用 AGPL-3.0 协议。

请注意，AGPL-3.0 是传染性协议。如果你的项目引用了 YiriMirai，请在发布时公开源代码，并同样采用 AGPL-3.0 协议。
