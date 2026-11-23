# MAN

MAN 正式客户端安装包与稳定频道更新清单。

## 下载

| 平台 | 当前版本 | 国内镜像 | GitHub 备用 |
| --- | --- | --- | --- |
| Windows 10/11 x64 | **2.0.19** | [下载安装包](https://dl.2kman.com/download/MAN-win-x64.exe) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.19/MAN-2.0.19-win-x64.exe) |
| macOS 13+ · Apple Silicon | **2.0.19** | [下载 DMG](https://dl.2kman.com/download/MAN-mac-arm64.dmg) | [备用下载](https://github.com/maxshiila/2kman-release/releases/download/v2.0.19/MAN-2.0.19-mac-arm64.dmg) |
| macOS Intel | 暂未提供 | — | — |

2.0.19 是 2.0 正式版的更新版本，Windows 和 Mac 同步发布：街球之王成就的试炼在对手的公园也能认准球员和区域，全部解锁时选对手不再一直上下翻；称霸赛能认出历史称霸赛的比赛画面，原版打法边线球等不到计时也会自动发球。已装 2.0.x 的用户在软件内更新即可。

[2.0.19 更新清单](RELEASE-NOTES-2.0.19.md) · [安装与使用教程](https://docs.2kman.com/guide/install/)

## 安装与更新

Windows 用户运行安装程序；如提示缺少 WebView2，按提示安装后再打开。已经安装 MAN 的用户可在应用内检查更新，或下载完整安装包覆盖安装；升级与默认卸载保留用户数据。首次运行若出现 SmartScreen 提示，可选择“更多信息 → 仍要运行”。

Mac 用户打开 DMG，将应用拖入 Applications。首次打开若被系统拦截，在“系统设置 → 隐私与安全性”中允许打开。

Windows 2.0.19 安装包 SHA-256：

`9148181c7610701320793d0fc06c73315eed8eb94c5e01c5ccc87363cd63c0a2`

Mac 2.0.19 DMG SHA-256：

`6fdf9598a2f4d4e2485815109a98fd8308513c912492df163f842527dc05fc8f`

仓库保留最近三版 Release 和更新说明；`latest.json` 是客户端信任根验签的稳定频道清单。安装包存放在 Releases，不提交进源码历史。
