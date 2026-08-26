# MAN

MAN 是面向用户的客户端。此仓库提供正式安装包、版本信息和机器可读的稳定频道清单；源码位于 [zephyrusguooo028/2kman](https://github.com/zephyrusguooo028/2kman)。

## 下载最新版

当前稳定版本：**MAN 0.1.9**

| 平台 | 状态 | 下载 |
| --- | --- | --- |
| Windows 10/11 x64 | 可用 | [下载安装程序](https://github.com/maxshiila/2kman-release/releases/download/v0.1.9/MAN-0.1.9-win-x64.exe) |
| macOS Apple Silicon（macOS 13+） | 0.1.7 为最后发布版本（存档） | [下载 macOS DMG](https://github.com/maxshiila/2kman-release/releases/download/v0.1.7/MAN-Production-User-Mac-arm64-0.1.7.dmg) |
| macOS Intel | 尚未提供 | — |

也可以打开[所有版本](https://github.com/maxshiila/2kman-release/releases)查看历史安装包和更新说明。

## Windows 安装

1. 下载并运行 `.exe` 安装程序，按向导选择语言和目录。
2. 升级安装会沿用原目录并保留配置、授权和配对数据。
3. 若首次启动被 SmartScreen 提示，选择“仍要运行”；安装包以本页和 `latest.json` 中的 SHA-256 作为完整性基准。

## macOS 安装

1. 下载并打开 `.dmg` 文件。
2. 将 `MAN-Production-User-Mac.app` 拖入 Applications。
3. 首次打开若被系统拦截，请在“系统设置 → 隐私与安全性”选择“仍要打开”。

## 当前版本

[0.1.9 更新说明](RELEASE-NOTES-0.1.9.md)

Windows 安装包 SHA-256：

`41ADBA25FB1B60905FDC1C8AE42F06C3C5C4C1A1C748C7F0384ED57505EF2F9E`

## 仓库内容

- `latest.json`：稳定频道的机器可读版本清单。
- `schemas/latest.schema.json`：`latest.json` 的 JSON Schema 契约。
- GitHub Releases：正式 Windows/macOS 安装工件及其校验信息。
- `releases/`：目录占位；安装包不会提交进 Git 历史。
