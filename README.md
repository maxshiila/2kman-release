# MAN

MAN 正式客户端安装包与稳定频道更新清单。

## 下载

| 平台 | 当前版本 | 国内镜像 | GitHub 备用 |
| --- | --- | --- | --- |
| Windows 10/11 x64 | **2.0.14** | [下载安装包](https://dl.2kman.com/download/MAN-win-x64.exe) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.14/MAN-2.0.14-win-x64.exe) |
| macOS 13+ · Apple Silicon | **2.0.14** | [下载 DMG](https://dl.2kman.com/download/MAN-mac-arm64.dmg) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.14/MAN-2.0.14-mac-arm64.dmg) |
| macOS Intel | 暂未提供 | — | — |

2.0.14 是 2.0 正式版的更新版本，Windows 和 Mac 同步发布：剧院 1v1、街球之王成就、足球27 单挑和黑切转为正式版，走位和区域判断大幅改进。已装 2.0.x 的用户在软件内更新即可。

[2.0.14 更新清单](RELEASE-NOTES-2.0.14.md) · [安装与使用教程](https://docs.2kman.com/guide/install/)

## 安装与更新

Windows 用户运行安装程序；如提示缺少 WebView2，按提示安装后再打开。已经安装 MAN 的用户可在应用内检查更新，或下载完整安装包覆盖安装；升级与默认卸载保留用户数据。首次运行若出现 SmartScreen 提示，可选择“更多信息 → 仍要运行”。

Mac 用户打开 DMG，将应用拖入 Applications。首次打开若被系统拦截，在“系统设置 → 隐私与安全性”中允许打开。

Windows 2.0.14 安装包 SHA-256：

`196e4bd598403e6f4d4bbe032f75790a075ea3a8fa5342a0e45a4fea6e01d790`

Mac 2.0.14 DMG SHA-256：

`70e452bbf2029fffef401e0db13712aee87be81f39bb90a46f835eb491bbd836`

仓库保留最近三版 Release 和更新说明；`latest.json` 是客户端信任根验签的稳定频道清单。安装包存放在 Releases，不提交进源码历史。
