# 移动端Flutter 第1课 - 如何开始工作？

## 开发环境搭建和升级

> 下文中的网址为 `国内镜像站点`，将域名替换为 `flutter.dev` 即可进入官方站点（需科学上网）
>
> 本文档编写时 Flutter SDK 版本为 v1.22.2

### Windows

[官方Windows安装教程](https://flutter.cn/docs/get-started/install/windows)

### macOS

下载[最新版SDK](https://flutter.cn/docs/get-started/install/macos#get-sdk)，也可以下载[历史版本](https://flutter.cn/docs/development/tools/sdk/releases?tab=macos)。

解压缩 `flutter_macos_1.22.2-stable.zip` 到任意文件夹。

为 Flutter 设定国内镜像，修改 `~/.zshrc` 文件，添加以下命令：

```bash
# Flutter
export PUB_HOSTED_URL=https://pub.flutter-io.cn
export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn
export PATH=/PATH/TO/flutter/bin:$PATH
```

<!-- /Users/maosong/Library/Android/sdk/platform-tools: -->

[官方macOS安装教程](https://flutter.cn/docs/get-started/install/macos)

### Linux

与 macOS 安装方式类似，因为Linux用户量较少这里不做详细阐述，查看[官方Linux安装教程](https://flutter.cn/docs/get-started/install/linux)即可。
