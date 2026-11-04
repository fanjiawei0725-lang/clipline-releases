# Clipline

macOS 屏幕顶部的截图晾衣绳，支持图片剪贴板、文件夹导入和待办任务。

从本仓库的 Releases 下载最新版 DMG，打开后把 Clipline 拖入“应用程序”。
也可下载 ZIP，解压后把 Clipline.app 移入“应用程序”。要求 macOS 14+，
同时支持 Apple silicon 与 Intel Mac。

从 1.8.1-clipline.24 开始，应用可检查、下载安装更新。默认每天检查，
发现新版时菜单“检查更新…”会有圆点提示，用户确认后安装。
更新列表和更新包使用 Ed25519 签名验证。旧版需先手动安装 .24 或更新版本。

当前发行包使用 ad hoc 签名，尚未使用 Apple Developer ID 签名或公证。
如果 macOS 阻止首次打开，可在“系统设置 → 隐私与安全性”查看“仍要打开”选项；
受组织策略管理的 Mac 可能无法打开。后续更新验证不代替 Apple 的初装检查。

仅更新检查和下载联网，不上传截图、待办或剪贴板内容，不包含 GitHub 登录凭证。
本仓库仅发布安装包、签名更新列表和发行说明，源码在独立私有仓库维护。

基于 Alejandro Buján 的 Tendedero（MIT）。见 LICENSE、THIRD_PARTY_NOTICES.md
和 Sparkle-LICENSE。Clipline 为独立衍生版本。
