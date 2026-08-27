# MindList Releases

本仓库只托管 MindList 的公开安装包和自动更新清单，应用源码保存在私有仓库。

## 稳定地址

- Windows/Android 更新清单：<https://huagelong.github.io/mindlist-releases/latest.json>
- 安装包：<https://github.com/huagelong/mindlist-releases/releases>

Windows 首次安装需要从 Releases 下载并运行 `MindList-windows-*-x64-setup.exe`。后续版本由 MindList 检查更新、校验文件大小和 SHA-256，然后静默运行 Inno Setup 安装器完成覆盖升级并重新启动应用。安装器按当前用户安装，不需要管理员权限；未使用商业代码签名证书时，Windows SmartScreen 可能显示“未知发布者”。

Android 首次安装需要从 Releases 下载 APK。后续版本由 MindList 检查更新、校验 SHA-256，并交给 Android 系统安装器确认安装。

`site/latest.json` 由私有源码仓库的标签发布流水线生成，不应手工修改。
