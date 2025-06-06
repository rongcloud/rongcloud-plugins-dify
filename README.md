# RongCloud Plugins

## 项目简介

RongCloud Plugins 是一个 Dify 插件，用于快速集成融云 Server API 接口。通过该插件，您可以轻松地在 Dify 应用中实现融云的各种功能，如发送消息、获取用户 Token 等。

## 功能特性

- 用户管理
  - 用户注册
  - 用户信息更新
  - 用户信息获取
- 消息管理
  - 发送单聊消息
  - 发送群聊消息
- 历史消息
  - 获取单聊历史消息
  - 获取群聊历史消息
- 群组管理
  - 创建群组
  - 加入群组
  - 解散群组
  - 获取群成员
  - 退出群组
- 其他特性
  - 支持中英文界面
  - 简单易用的参数配置

## 快速开始

### 环境要求

- Python 3.12+
- Dify 平台

### 安装步骤

1. 在 Dify 插件市场中搜索 "RongCloud Plugins"
2. 点击安装按钮
3. 在插件配置页面填写必要的配置信息：
   - App Key
   - App Secret
   - Host

### 配置说明

| 参数 | 说明 | 是否必填 |
|------|------|----------|
| App Key | 融云应用 App Key | 是 |
| App Secret | 融云应用 App Secret | 是 |
| Host | 融云 API 地址 | 是 |

## 注意事项

1. 使用前请确保已正确配置融云的 App Key 和 App Secret
2. 消息内容需要符合融云的格式要求
3. 建议在正式环境中使用前进行充分测试

## 版本历史

### v0.1.0 (2024-03-05)
- 初始版本发布
- 支持用户管理功能
- 支持消息管理功能
- 支持历史消息查询
- 支持群组管理功能

## 技术支持

如有问题，请联系：
- 邮箱：huhangtao@rongcloud.cn
- 融云技术支持：https://www.rongcloud.cn/support

## 许可证

Copyright © 2024 RongCloud. All rights reserved.



