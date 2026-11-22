# HALF 多机投屏

在 Windows 上通过 USB 同时查看和操控多台 iPhone 与安卓手机，支持标签分组、独立大屏和选中设备同步操作。

## 下载 Windows x64 安装包

打开 [最新发布](https://github.com/wuyong1996/half-iphone-mirror-releases/releases/latest)，下载以下文件。

| 文件 | 用途 |
| --- | --- |
| `HALF-iPhone-Mirror-Setup-版本号-win-x64.exe` | Windows 安装程序 |
| `SHA256SUMS.txt` | 安装包的 SHA-256 校验值 |

从旧版升级前，请先从系统托盘选择「退出应用」。安装程序可创建桌面和开始菜单快捷方式。文件名沿用此前版本，安装后的工作台同时支持 iPhone 和安卓。

发布库提供安装包及使用说明。Windows 可能对未签名的安装程序显示未知发布者提示。可以用 PowerShell 的 `Get-FileHash -Algorithm SHA256 文件路径` 核对校验值。

## 接入设备

- **iPhone**。确保 Apple Mobile Device USB 服务正常。手机解锁并信任电脑，开启开发者模式，安装签名有效的 WebDriverAgent。
- **安卓**。开启「USB 调试」，用数据线连接后在手机上授权。部分小米和红米机型需要额外开启「USB 调试（安全设置）」才能点击和输入。只有普通 USB 调试时，仍可查看画面。
- 打开 HALF，等待设备就绪。「设置 → 连接平台」可开关苹果和安卓接入。选中多台设备后，可同步执行共同支持的操作。
- 安卓大屏和右键菜单的三个按键从左到右为最近任务、主页、返回。要用电脑输入文字，请先点选手机里的输入框。

[HALF 官网与接入指南](https://half-mirror-account.halfsuger017.workers.dev/)
