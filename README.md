# MAN

MAN 正式客户端安装包与稳定频道更新清单。

## 下载

| 平台 | 当前版本 | 国内镜像 | GitHub 备用 |
| --- | --- | --- | --- |
| Windows 10/11 x64 | **2.0.20** | [下载安装包](https://dl.2kman.com/download/MAN-win-x64.exe) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.20/MAN-2.0.20-win-x64.exe) |
| macOS 13+ · Apple Silicon | **2.0.20** | [下载 DMG](https://dl.2kman.com/download/MAN-mac-arm64.dmg) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.20/MAN-2.0.20-mac-arm64.dmg) |
| macOS Intel | 暂未提供 | — | — |

2.0.20 是 2.0 正式版的更新版本，Windows 和 Mac 同步发布：MT 称霸赛战术版设 3-2 联防先认出「半场设置」菜单再选并复查，主界面参数精简，能认出历史和 WNBA 称霸赛；MT 进场停在「比赛」标签不再来回跳；正式版 PS5 十字键恢复正常。已装 2.0.x 的用户在软件内更新即可。

[2.0.20 更新清单](RELEASE-NOTES-2.0.20.md) · [安装与使用教程](https://docs.2kman.com/guide/install/)

## 安装与更新

Windows 用户运行安装程序；如提示缺少 WebView2，按提示安装后再打开。已经安装 MAN 的用户可在应用内检查更新，或下载完整安装包覆盖安装；升级与默认卸载保留用户数据。首次运行若出现 SmartScreen 提示，可选择“更多信息 → 仍要运行”。

Mac 用户打开 DMG，将应用拖入 Applications。首次打开若被系统拦截，在“系统设置 → 隐私与安全性”中允许打开。

Windows 2.0.20 安装包 SHA-256：

`9c42e9e122c05f57ad3903319f7a19353cd46d7fe4f7c96fec4aad0cb78bc85e`

Mac 2.0.20 DMG SHA-256：

`da31cc5e0a988bda8a2a6f9dafd08a3b53213718e6543a9bf5c02e7c2dc7e2ad`

仓库保留最近三版 Release 和更新说明；`latest.json` 是客户端信任根验签的稳定频道清单。安装包存放在 Releases，不提交进源码历史。
