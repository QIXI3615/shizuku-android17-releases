# Shizuku Android 17/API 37 兼容版

基于 Shizuku 13.6.0 官方界面和交互制作的 Android 17/API 37 兼容版本。保持原版 UI、使用方式、包名和 Shizuku 应用兼容性，没有加入模块管理、终端或额外界面功能。

## 功能

- 支持通过无线调试、ADB 或 Root 启动 Shizuku 服务。
- 为支持 Shizuku 的应用提供系统 API 访问能力。
- 修复 Android 17 上授权应用列表无法正常读取的问题。
- 兼容 Android 16，并面向 Android 17/API 37 构建。

## 下载

请从本仓库的 [Releases](../../releases/latest) 页面下载 APK。

## 安装方法

1. 如果设备已安装官方 Shizuku或其他不同签名版本，请先卸载；Android 不允许不同签名的同包名应用直接覆盖安装。
2. 从 Releases 下载 `Shizuku-13.6.0-Android17-API37-release.apk` 并安装。
3. 按 Shizuku 原有方式，通过无线调试、ADB 或 Root 启动服务。
4. 在需要使用 Shizuku 的应用中授予权限。

## 适用系统

- 最低 Android 7.0（API 24）。
- 已在 Android 16 上正常使用。
- 针对 Android 17/API 37 完成兼容修改、Release 构建及 APK 静态验证；尚未进行 Android 17 真机测试。

## 签名与升级

此版本使用固定发布密钥签名。后续由本仓库发布、且使用相同签名的新版 APK 可以直接覆盖升级。

APK 的 SHA-256 请参见对应 Release 说明。

