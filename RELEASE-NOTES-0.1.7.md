# MAN 0.1.7 更新说明

- macOS Apple Silicon（M1/M2/M3/M4，macOS 13+）正式安装包已更新。
- 内置配置契约升级为 v1.6.0，并轮换为新的 Ed25519 配置签名信任根；旧配置签名包不再被本版本接受。
- 正式端只加载完整的外置运行配置，缺失或无效的 profile/runtime policy 不会由代码默认值补齐。
- macOS 包使用 ad-hoc 签名与 Hardened Runtime，未经过 Apple 公证。若首次打开被系统拦截，请在“系统设置 → 隐私与安全性”选择“仍要打开”。

## macOS Apple Silicon

- 文件：`MAN-Production-User-Mac-arm64-0.1.7.dmg`
- SHA-256：`61adca52083e62d774bf90a00d40724507bea475aa95799a64b69b0a461f3d8b`
- 大小：191,367,255 bytes
- 安装：打开 DMG，将 `MAN-Production-User-Mac.app` 拖入 Applications。

Windows 0.1.7 工件尚未构建和验收，因此本次 Release 不提供 Windows 更新。
