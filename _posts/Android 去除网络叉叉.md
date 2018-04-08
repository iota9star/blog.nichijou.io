---
title: Android 去掉网络叉叉（叹号）
date: 2018-04-07 21:00:00
tags: [去掉网络叉叉,叉叉,Android,网络叹号]
---
## adb 下载地址（部分地区可能需要梯子）
### 官网
[SDK Platform-Tools](https://developer.android.google.cn/studio/releases/platform-tools.html#revisions)  
### 快速下载
[SDK Platform-Tools for Windows](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)  
[SDK Platform-Tools for Mac](https://dl.google.com/android/repository/platform-tools-latest-darwin.zip)  
[SDK Platform-Tools for Linux](https://dl.google.com/android/repository/platform-tools-latest-linux.zip)
## adb 命令
### Android 5.0 ~ 6.0
```shell
adb shell "settings put global captive_portal_server https://www.google.cn"
```
### Android 7.0 ~ 8.1.0
```shell
adb shell "settings put global captive_portal_https_url https://www.google.cn/generate_204"
```

