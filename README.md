# MAN

MAN 是面向用户的客户端。此仓库提供正式安装包、版本信息和机器可读的稳定频道清单；源码位于 [zephyrusguooo028/2kman](https://github.com/zephyrusguooo028/2kman)。

## 下载最新版

当前稳定版本：**MAN 0.1.7**

| 平台 | 状态 | 下载 |
| --- | --- | --- |
| Windows 10/11 x64 | 尚未提供 | — |
| macOS Apple Silicon（macOS 13+） | 可用 | [下载 macOS DMG](https://github.com/maxshiila/2kman-release/releases/download/v0.1.7/MAN-Production-User-Mac-arm64-0.1.7.dmg) |
| macOS Intel | 尚未提供 | — |

也可以打开[所有版本](https://github.com/maxshiila/2kman-release/releases)查看历史安装包和更新说明。

## macOS 安装

1. 下载并打开 `.dmg` 文件。
2. 将 `MAN-Production-User-Mac.app` 拖入 Applications。
3. 首次打开若被系统拦截，请在“系统设置 → 隐私与安全性”选择“仍要打开”。

## 当前版本

[0.1.7 更新说明](RELEASE-NOTES-0.1.7.md)

macOS Apple Silicon 安装包 SHA-256：

`61adca52083e62d774bf90a00d40724507bea475aa95799a64b69b0a461f3d8b`

## 仓库内容

- `latest.json`：稳定频道的机器可读版本清单。
- `schemas/latest.schema.json`：`latest.json` 的 JSON Schema 契约。
- GitHub Releases：正式 Windows/macOS 安装工件及其校验信息。
- `releases/`：目录占位；安装包不会提交进 Git 历史。
