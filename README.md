# General-Chatroom-Template-For-VelaOS (GCT for Vela)
适用于小米Vela的聊天室模板

在使用该项目之前，请确保你的网站至少有以下接口和数据：
- Login   - 登录接口与密钥
- Message - 消息接口
- Send    - 发送接口

你可以自由添加接口

## 使用方法
将你的网站API总址写入BASE_URL，并且将具体的API写入各模块之内

可以查找let url以方便快速定位

示例: 

`BASE_URL: https://example.com/api/`

`let url=${BASE_URL}main?api_key=${api_key}&action=get_messages`

! 由于暂未整合接口模块，代码看上去会有点乱

! 注意：在测试完成后，应将获取方法从GET改为POST以增强安全性

如果想替换图标，将/commom目录下的图标替换成你的图标，图标名称尽量与原图标一致以减少修改量

该项目默认提供以下模块
- 公告（需要自行编写）
- 消息（暂不支持对消息进行操作）
- 群组（暂未完成）
- 好友（暂不支持添加好友）
- 设置

你可以在该项目的基础上修改模块

---
## 更新日志

- 2026/8/14 - 对应用进行了一些优化，同时新增了精简版本（精简版本在带有S的文件夹中）
- 2026/8/15 - 修复了storage无法正常读取api_key的问题，修复了私信界面无法返回的问题
