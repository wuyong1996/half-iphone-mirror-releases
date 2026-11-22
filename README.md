# HALF 苹果多机投屏

Windows USB 多 iPhone 投屏与控制工作台。

## 下载 Windows 版本

打开 [最新版本 Releases](https://github.com/wuyong1996/half-iphone-mirror-releases/releases/latest)，在 **Assets** 中选择：

| 文件 | 用途 |
| --- | --- |
| `HALF-iPhone-Mirror-Setup-版本号-win-x64.exe` | 推荐安装版，按向导安装，创建桌面与开始菜单快捷方式 |
| `SHA256SUMS.txt` | 安装包的 SHA-256 校验值 |

GitHub 自动生成的 **Source code** 压缩包仅包含本发布库说明，不是 Windows 安装程序。本仓库只公开安装包和使用说明；应用源码保存在私有仓库。

当前程序未进行代码签名，Windows 可能显示未知发布者提示。下载后可以用 PowerShell 的 `Get-FileHash -Algorithm SHA256 文件路径` 与 `SHA256SUMS.txt` 对照校验。

## 开始使用

1. 电脑应已具备可正常运行的 Apple Mobile Device USB 服务。
2. 手机通过 USB 连接，解锁并信任电脑，开启开发者模式，保留已安装且签名有效的 WebDriverAgent。
3. 打开 HALF，等待程序发现并连接手机。可查看单台画面，选中多台后同步点击、滑动与输入。
4. Ctrl+点击增减选机；空白处拖动框选；放大镜打开大屏。先在手机中选中输入框，再用 Ctrl+V 粘贴电脑文字。
5. 关闭窗口后仍在托盘运行；从托盘菜单选择「退出应用」才会完全退出。

安装包不包含苹果 USB 驱动、手机组件、签名证书，也不会自动安装或续签手机组件。不包含系统音频、音视频录制或多指触控。安装版本可通过 Windows 设置卸载；本地设置默认保留。

## 更新

当前版本没有程序内自动更新。请从 [Releases/latest](https://github.com/wuyong1996/half-iphone-mirror-releases/releases/latest) 下载新版本，退出托盘中的旧程序后安装新版。
