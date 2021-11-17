# GMS.icu
## 展示国产Android手机GMS支持情况

## GMS是什么

> Google Mobile Services (GMS) is a collection of proprietary applications and application programming interfaces (APIs) services from Google that are typically pre-installed on Android devices, such as smartphones, tablets, and smart TVs.GMS is not a part of the Android Open Source Project (AOSP), which means an Android manufacturer needs to obtain a license from Google in order to legally pre-install GMS on an Android device. This license is provided by Google without any license fees.
>
> From [*Wikipedia*](https://en.wikipedia.org/wiki/Google_mobile_services)

GMS 是谷歌移动服务的缩写，软件的包名通常为：`com.google.android.gms`，其用途是为Android设备提供一套与谷歌服务相连接的接口。
GMS 并非所有Android设备必须，部分手机厂商或者某些手机厂商的不同型号的手机可能对**GMS**服务进行了精简（*魔改*）或者干脆移除了 GMS。


## 项目简介

开发者、极客、外服游戏玩家或者在中国的外国用户对于Android设备上的**GMS**是有相对于普通用户更强烈的需求。比如需要正常从Google Play Store下载应用、通过**GMS**快捷登录YouTube Twitter等国际化应用账户、通过Google Play Games连接国际服游戏等。

由于从Android 11开始，Google认为侧载**GMS**服务不再安全，要求相关厂商不再支持用户侧自行安装**GMS**服务，所以对于有**GMS**购买手机需求的用户，在购买前提前了解设备是否支持**GMS**就十分必要。

本项目就是想通过开源平台的能力，众人拾柴火焰高，尽可能多的收集国产手机、平板、智能电视等Android终端（或者国外品牌的中国区型号）的**GMS**支持情况，为需要的人提供参考。


## 贡献

非常欢迎访问到这里的朋友贡献一份数据，对于不熟悉Markdown或者Git操作的朋友➡️[腾讯文档](https://docs.qq.com/form/page/DVXlYek5RYXR4WHhJ)。

`clone`本仓库，在相应的分区中添加你的数据，`commit`并向本仓库`pull request`，相关提交格式请参见[Contributing](start.md#contributing)


## 关于项目

- 渲染引擎：[docsify](https://docsify.js.org/#/)