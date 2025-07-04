# RongCloud Plugins

🔗 **GitHub Repository**: [https://github.com/rongcloud/rongcloud-plugins-dify](https://github.com/rongcloud/rongcloud-plugins-dify)

## Overview

RongCloud (Beijing Yunzhong Rongxin Network Technology Co., Ltd.) is a leading global provider of intelligent cloud communication services. Our professional and secure PaaS and SaaS solutions empower developers and enterprises to drive digital transformation, creating new application scenarios and unlocking business value in the digital world.

Founded in 2015, our core team, hailing from China Mobile's Fetion, brings nearly two decades of experience in the cloud communication industry. We have built a global network spanning 245 countries and regions, supported by multiple data centers and thousands of acceleration nodes. This powerful infrastructure supports hundreds of millions of concurrent users and handles a daily volume of hundreds of billions of messages.

The RongCloud Plugin for Dify enables seamless integration with the RongCloud server API. This allows you to easily implement a wide range of RongCloud's features into your Dify applications, such as sending messages, retrieving user tokens, and more.

## Features

- User Management
  - User Registration
  - User Information Update
  - User Information Retrieval
- Message Management
  - Send Private Messages
  - Send Group Messages
- Message History
  - Get Private Chat History
  - Get Group Chat History
- Group Management
  - Create Group
  - Join Group
  - Dismiss Group
  - Get Group Members
  - Leave Group
- Other Features
  - Support for Chinese and English interfaces
  - Simple and easy parameter configuration

## Quick Start

### Requirements

- Python 3.12+
- Dify Platform

### Installation Steps

1. Search for "RongCloud Plugins" in the Dify plugin marketplace
2. Click the install button
3. Fill in the necessary configuration information on the plugin configuration page:
   - App Key
   - App Secret
   - Host

### Configuration Guide

| Parameter | Description | Required |
|-----------|-------------|----------|
| App Key | RongCloud App Key | Yes |
| App Secret | RongCloud App Secret | Yes |
| Host | RongCloud API Address | Yes |

## Notes

1. Please ensure that RongCloud App Key and App Secret are correctly configured before use
2. Message content must comply with RongCloud's format requirements
3. It is recommended to conduct thorough testing before using in production environment

## Version History

### v0.1.0
- Initial version release
- Support for user management features
- Support for message management features
- Support for message history query
- Support for group management features

## Technical Support

For any issues, please contact:
- Email: huhangtao@rongcloud.cn
- GitHub Repository: https://github.com/rongcloud/rongcloud-plugins-dify
- RongCloud Technical Support: https://console.rongcloud.cn/agile/formwork/ticket

## License

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



