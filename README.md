# p4d-release

Pay4Dream Public 发布页面与应用内更新元数据。该仓库不包含模型凭证、Internal/Beta 安装包或内部接口信息。

## 1.0.4 准备状态

当前工作树准备的是 1.0.4 Public 页面和 Release 说明，状态为 `released`。双平台安装包已在同一 Release 完成下载读回验证。

发布时必须将 `release-meta.json` 中以下占位字段替换为同版本、已读回的真实值，并将 `status` 改为 `released`：

- `released_at`
- `checksums.macos_sha256` 与 `checksums.windows_sha256`
- `sizes.macos_bytes` 与 `sizes.windows_bytes`

macOS 和 Windows 两个 Public 资产必须同时存在于 `pay4dream/p4d-release` 的同一 `v1.0.4` Release。`latest.json`、`release-meta.json`、`index.html` 和 Release body 必须使用相同版本与更新说明。
