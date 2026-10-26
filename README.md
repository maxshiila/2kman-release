# MAN

MAN 正式客户端安装包与稳定频道更新清单。

## 下载

| 平台 | 当前版本 | 国内镜像 | GitHub 备用 |
| --- | --- | --- | --- |
| Windows 10/11 x64 | **2.0.7** | [下载安装包](https://dl.2kman.com/download/MAN-win-x64.exe) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.7/MAN-2.0.7-win-x64.exe) |
| macOS 13+ · Apple Silicon | **2.0.7** | [下载 DMG](https://dl.2kman.com/download/MAN-mac-arm64.dmg) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.7/MAN-2.0.7-mac-arm64.dmg) |
| macOS Intel | 暂未提供 | — | — |

2.0.7 是 2.0 正式版的更新版本，Windows 和 Mac 同步发布：剧院新增冲刺上篮、两个赛季的场地都能打，场地识别更稳更准，走位统一按「米」，Xbox 卡住自动恢复。已装 2.0.0 的用户请下载安装包覆盖安装。

[2.0.7 更新清单](RELEASE-NOTES-2.0.7.md) · [安装与使用教程](https://docs.2kman.com/guide/install/)

## 安装与更新

Windows 用户运行安装程序；如提示缺少 WebView2，按提示安装后再打开。已经安装 MAN 的用户可在应用内检查更新，或下载完整安装包覆盖安装；升级与默认卸载保留用户数据。首次运行若出现 SmartScreen 提示，可选择“更多信息 → 仍要运行”。

Mac 用户打开 DMG，将应用拖入 Applications。首次打开若被系统拦截，在“系统设置 → 隐私与安全性”中允许打开。

Windows 2.0.7 安装包 SHA-256：

`77a0e8b8585a80dac7544519d2efcbc36b6adbf5bd171a9f56749ee24a8f26dd`

Mac 2.0.7 DMG SHA-256：

`128d6f2580d20d212baa3d514155584565ab96490379ec9e7b519213c0c8625c`

仓库保留最近三版 Release 和更新说明；`latest.json` 是客户端信任根验签的稳定频道清单。安装包存放在 Releases，不提交进源码历史。
