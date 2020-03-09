# MapleRtc-Apicloud-Demo
## 简介：
maple-rtc 为[蓝蘑云](http://www.lmaple.com)推出的实时音视频系统，包括了实时音频，视频，变声，美颜等功能，适用于娱乐，游戏，教育等实时场景中；

----------
- 完整的 API 文档见 [文档中心](http://doc.lmaple.com/maple-rtc-apicloud-sdk.html)

----------
这个开源项目演示了如何快速集成 maple-rtc SDK 到 apicloud 中，实现在apicloud应用中音频通话效果。

注意：该demo包括master和1v1sample两个分支，如果您场景为1对1视频通话，请参考1v1sample 分支。

在这个示例项目中包含了以下功能：
- 加入通话和离开通话；
- 打开／关闭本地麦克风说话；
- 打开／关闭扬声器播放；
- 扬声器和听筒切换功能；
- 打开／关闭本地预览视频；
- 开始／停止发送本地视频；
- 打开／关闭显示远端视频；
- 打开／关闭美颜功能；
- 切换前后摄像头功能；


## 运行示例程序
首先在 联系对接群 **701150764**, [蓝蘑云后台管理](http://account.lmaple.com) 注册账号，获取到 appID。将 appID 填写进 config.xml的appId的value中；

<img src="http://doc.lmaple.com/image/maple-rtc-apicloud_2.png" width="500">

```
  <feature name="mapleRTC">
    <param name="appId" value="##########"/>
  </feature>
```

然后在 [maple-rtc SDK](http://sdk.lmaple.com/MapleRtc_ApiCloud_SDK_Release.zip) 下载 **maple-rtc  SDK for Apicloud**，解压后将其中的 **mapleRTC.zip** 文件夹复制到本项目的指定目录下。

- 建议在[apicloud 控制平台](https://www.apicloud.com/)进行云编译运行；

- 额外自行加入该项目源码到Android Studio 和 Xcode编译运行； 


## 运行环境
- Android Studio 2.0+ 或 Xcode 8.0+
- [apicloud 控制平台](https://www.apicloud.com/)云编译
- 真实 Android / iOS 设备
- SDK不包含模拟器库，所以推荐使用真机调试运行

## 联系我们

对接qq群  **701150764**

## Demo
注：android可以测试运行，iOS 打包的为开发者账号，只能部分机子可以测试运行；

android:
[Android 视频会议演示Demo](http://fir.kcrtu.com/mapleandroid)

iOS:
[iOS 视频会议演示Demo](http://fir.kcrtu.com/mapleios)

android:
[Android 1对1视频通话演示Demo](http://fir.kcrtu.com/maple1v1android)

iOS:
[iOS 1对1视频通话演示Demo](http://fir.kcrtu.com/maple1v1ios)


