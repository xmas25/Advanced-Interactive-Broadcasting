#Agora-Interactive-Broadcasting-Live-Streaming-Injection-Windows
*Read this in other languages: [English](README.md)*

导入外部数据流(sdk2.9.0及以上)

在这个示例项目中包含了以下功能：

- 加入通话和离开通话；
- 导入在线媒体流；
- 移处在线媒体流；

**注意：**
调用addInjectStreamUrl必须在收到OnJoinSuccess回掉之后才能生效.

## 运行环境
* VC++2013 或更高版本
* WIN7 或更高版本

## 运行示例程序

首先在 [Agora.io 注册](https://dashboard.agora.io/cn/signup/) 注册账号，并创建自己的测试项目，获取到 AppID。将appid放入代码中APP_ID宏定义中


```
  #define APP_ID _T("Your App ID")
```

然后在 [Agora.io SDK](https://www.agora.io/cn/download/) 获取window端sdk 放到 LiveStreaming目录下 sdk目录下包含 dll,lib,include 3各部分文件

最后用 Visual Studio 2013 打开该项目，编译并运行。

## 联系我们

- 如果你遇到了困难，可以先参阅[常见问题](https://docs.agora.io/cn/faq)
- 如果你想了解更多官方示例，可以参考[官方SDK示例](https://github.com/AgoraIO)
- 如果你想了解声网SDK在复杂场景下的应用，可以参考[官方场景案例](https://github.com/AgoraIO-usecase)
- 如果你想了解声网的一些社区开发者维护的项目，可以查看[社区](https://github.com/AgoraIO-Community)
- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 若遇到问题需要开发者帮助，你可以到 [开发者社区](https://rtcdeveloper.com/) 提问
- 如果发现了示例代码的 bug，欢迎提交 [issue](https://github.com/AgoraIO/Advanced-Interactive-Broadcasting/issues)

## 代码许可
The MIT License (MIT).
