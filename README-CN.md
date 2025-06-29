# RongCloud Plugins

🔗 **GitHub 仓库**: [https://github.com/rongcloud/rongcloud-plugins-dify](https://github.com/rongcloud/rongcloud-plugins-dify)

## 概述

北京云中融信网络科技有限公司（简称“融云”），是全球智能通信云服务领创品牌，为全球数字化建设提供专业、安全、智能的互联网云通信 PaaS 和 SaaS 等产品，赋能开发者和企业的创新能力，在数字化领域不断创造新的应用场景和商业价值。
融云成立于 2015 年，核心团队来自中国移动飞信团队，拥有近 20 年的通信云行业经验。在全球范围内，融云累积多年打造了一张覆盖 245 个国家及地区的通信云网络，设立了多个海外数据中心以及数千加速节点，支持亿级用户的同时在线和日数千亿级的消息分发能力。

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

### v0.1.0
- 初始版本发布
- 支持用户管理功能
- 支持消息管理功能
- 支持历史消息查询
- 支持群组管理功能

## 技术支持

如有问题，请联系：
- 邮箱：huhangtao@rongcloud.cn
- GitHub 仓库：https://github.com/rongcloud/rongcloud-plugins-dify
- 融云技术支持：https://console.rongcloud.cn/agile/formwork/ticket


## 许可证

MIT License

Copyright (c) 2024 RongCloud Dify Plugin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



