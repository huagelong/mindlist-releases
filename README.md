# MindList Releases

本仓库只托管 MindList 的公开安装包和自动更新清单，应用源码保存在私有仓库。

## 稳定地址

- Android/客户端更新清单：<https://huagelong.github.io/mindlist-releases/latest.json>
- Windows App Installer：<https://huagelong.github.io/mindlist-releases/MindList.appinstaller>
- 安装包：<https://github.com/huagelong/mindlist-releases/releases>

Windows 首次安装需要下载并打开 `MindList.appinstaller`。安装完成后，Windows 会在应用启动时和后台检查后续 MSIX 更新。

Android 首次安装需要从 Releases 下载 APK。后续版本由 MindList 检查更新、校验 SHA-256，并交给 Android 系统安装器确认安装。

`site/latest.json` 和 `site/MindList.appinstaller` 由私有源码仓库的标签发布流水线生成，不应手工修改。
