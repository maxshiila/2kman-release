# MAN

MAN 正式客户端安装包与稳定频道更新清单。

## 下载

| 平台 | 当前版本 | 国内镜像 | GitHub 备用 |
| --- | --- | --- | --- |
| Windows 10/11 x64 | **2.0.18** | [下载安装包](https://dl.2kman.com/download/MAN-win-x64.exe) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.18/MAN-2.0.18-win-x64.exe) |
| macOS 13+ · Apple Silicon | **2.0.18** | [下载 DMG](https://dl.2kman.com/download/MAN-mac-arm64.dmg) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.18/MAN-2.0.18-mac-arm64.dmg) |
| macOS Intel | 暂未提供 | — | — |

2.0.18 是 2.0 正式版的更新版本，Windows 和 Mac 同步发布：加强付款保护，断线或卡在比赛外不再连续乱按确认键；比赛与休息可设局数和金币目标；称霸赛新增战术版打法；街球之王新增切入终结（内测）。已装 2.0.x 的用户在软件内更新即可。

[2.0.18 更新清单](RELEASE-NOTES-2.0.18.md) · [安装与使用教程](https://docs.2kman.com/guide/install/)

## 安装与更新

Windows 用户运行安装程序；如提示缺少 WebView2，按提示安装后再打开。已经安装 MAN 的用户可在应用内检查更新，或下载完整安装包覆盖安装；升级与默认卸载保留用户数据。首次运行若出现 SmartScreen 提示，可选择“更多信息 → 仍要运行”。

Mac 用户打开 DMG，将应用拖入 Applications。首次打开若被系统拦截，在“系统设置 → 隐私与安全性”中允许打开。

Windows 2.0.18 安装包 SHA-256：

`7d2aafa06e68efaa3ce1a86dc4e2171262bdd74331ed0cd1d810867e05ec194e`

Mac 2.0.18 DMG SHA-256：

`0895dac04748aabde9800cd51fe03437d1bfef10bb7a4106b407f0c36272620a`

仓库保留最近三版 Release 和更新说明；`latest.json` 是客户端信任根验签的稳定频道清单。安装包存放在 Releases，不提交进源码历史。
