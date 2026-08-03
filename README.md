# General-Chatroom-Template-For-VelaOS (GCT for Vela)
适用于小米Vela的聊天室模板

在使用该项目之前，请确保你的网站至少有以下接口和数据：
- Login - 登录接口与密钥
- Message - 消息接口
- Send - 发送接口

你可以自由添加接口

! 注意：在测试完成后，应将获取方法从GET改为POST以增强安全性

# 使用方法
将代码中的 BASE_URL 替换成你的网站，并且将Login,fetchMessages中的接口替换成你的接口

如果想替换图标，将/commom目录下的图标替换成你的图标

该项目默认提供以下模块
- 公告
- 消息
- 群
- 好友
- 设置

你可以在该项目的基础上增加模块

---
