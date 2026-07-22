# 2KMAN Releases

发布仓库：https://github.com/maxshiila/2kman-release

本仓库只维护 `production-user-client` 的公开发布描述和 GitHub Release 工件，不维护源码。

源码仓库：`https://github.com/zephyrusguooo028/2kman`

## 仓库边界

- `latest.json`：稳定频道的机器可读版本清单。
- `schemas/latest.schema.json`：`latest.json` 的 JSON Schema 契约。
- GitHub Releases：只保存 Windows/macOS 可安装工件和校验信息，不把裸 `.app`、便携压缩包作为正式交付物。
- `releases/`：仅保留目录占位，不把安装包提交进 Git 历史。

客户端会根据公网 IP 自动选择下载线路：中国大陆使用 GitHub 加速代理，其他地区使用 GitHub Release 直连。发布清单仍只记录 Release 原始地址、文件名、大小和 SHA-256；客户端负责在国内线路上加速清单和工件请求。

## 发布流程

1. 在本仓库创建 `vX.Y.Z` tag；本次 Windows 版本候选为 `v0.0.1`。
2. CI 从源码仓库构建 Windows/macOS 安装包：Windows 优先 `.exe` 安装程序，macOS 优先 `.dmg` 安装包；若后续选择 `.msi` 或 `.pkg`，必须在清单中明确标注。
3. 将工件上传到本仓库对应 GitHub Release。
4. 更新根目录 `latest.json`，把 `status` 改为 `published`，填写版本、Release 页面、安装包类型、文件名、大小和 SHA-256。
5. 更新服务读取 `latest.json`，国外返回 GitHub 原始地址，国内返回服务端健康检查后的加速地址。

## 当前状态

当前 `latest.json` 是契约占位，尚未指向可下载工件。不要把 `status: draft` 的清单提供给正式客户端作为可更新版本。
