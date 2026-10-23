# MAN

MAN 正式客户端安装包与稳定频道更新清单。

## 下载

| 平台 | 当前版本 | 国内镜像 | GitHub 备用 |
| --- | --- | --- | --- |
| Windows 10/11 x64 | **2.0.6** | [下载安装包](https://dl.2kman.com/download/MAN-win-x64.exe) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.6/MAN-2.0.6-win-x64.exe) |
| macOS 13+ · Apple Silicon | **2.0.6** | [下载 DMG](https://dl.2kman.com/download/MAN-mac-arm64.dmg) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.6/MAN-2.0.6-mac-arm64.dmg) |
| macOS Intel | 暂未提供 | — | — |

2.0.6 是 2.0 正式版的更新版本，Windows 和 Mac 同步发布：新增 MT 关键时刻、MT 称霸赛、街球之王成就（内测），剧院 1v1 按 Season 2 新场地重新开放（内测），27 街球之王按球场定投篮区域、走位重做。已装 2.0.0 的用户请下载安装包覆盖安装。

[2.0.6 更新清单](RELEASE-NOTES-2.0.6.md) · [安装与使用教程](https://docs.2kman.com/guide/install/)

## 安装与更新

Windows 用户运行安装程序；如提示缺少 WebView2，按提示安装后再打开。已经安装 MAN 的用户可在应用内检查更新，或下载完整安装包覆盖安装；升级与默认卸载保留用户数据。首次运行若出现 SmartScreen 提示，可选择“更多信息 → 仍要运行”。

Mac 用户打开 DMG，将应用拖入 Applications。首次打开若被系统拦截，在“系统设置 → 隐私与安全性”中允许打开。

Windows 2.0.6 安装包 SHA-256：

`834e11cfb421291731371cbe41db346ba9c5c1413b738a9394ec3f1eb8c7f3aa`

Mac 2.0.6 DMG SHA-256：

`405fc0a74ea8f5d67d1854735b741736b5be0bb297d652691b96bfaf5ff574e5`

仓库保留最近三版 Release 和更新说明；`latest.json` 是客户端信任根验签的稳定频道清单。安装包存放在 Releases，不提交进源码历史。
