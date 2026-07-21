# 2KMAN Production Releases

本仓库只维护 `production-user-client` 的公开发布描述和 GitHub Release 工件，不维护源码。

源码仓库：`https://github.com/zephyrusguooo028/2kman`

## 仓库边界

- `latest.json`：稳定频道的机器可读版本清单。
- `schemas/latest.schema.json`：`latest.json` 的 JSON Schema 契约。
- GitHub Releases：保存 Windows/macOS 安装包和校验信息。
- `releases/`：仅保留目录占位，不把安装包提交进 Git 历史。

国内加速代理不写入客户端，也不直接写入本仓库的正式清单。后续由更新服务根据公网 IP、平台和代理健康状态选择下载地址；客户端只信任固定更新入口和校验后的工件。

## 发布流程

1. 在本仓库创建 `vX.Y.Z` tag。
2. CI 从源码仓库构建 Windows/macOS 工件。
3. 将工件上传到本仓库对应 GitHub Release。
4. 更新根目录 `latest.json`，把 `status` 改为 `published`，填写版本、Release 页面、平台工件名、大小和 SHA-256。
5. 更新服务读取 `latest.json`，国外返回 GitHub 原始地址，国内返回服务端健康检查后的加速地址。

## 当前状态

当前 `latest.json` 是契约占位，尚未指向可下载工件。不要把 `status: draft` 的清单提供给正式客户端作为可更新版本。
