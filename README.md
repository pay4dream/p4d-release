# p4d-release

Pay4Dream Public 发布页面与应用内更新元数据。该仓库不包含模型凭证、Internal/Beta 安装包或内部接口信息。

## 1.1.0 发布状态

macOS Apple Silicon 与 Windows x64 Public 1.1.0 已在同一个 Release 提供，两份安装包均通过完整下载大小和 SHA256 校验。`release-meta.json` 与 `latest.json` 已同步为 1.1.0。

下载入口：[Public 发布页](https://pay4dream.github.io/p4d-release/) · [1.1.0 Release](https://github.com/pay4dream/p4d-release/releases/tag/v1.1.0) · [使用手册](https://pay4dream.github.io/p4d-release/manual.html)。

## 维护约定

Windows 包体验证通过后补到同一个 v1.1.0 Release，不另建发布记录。必须核对实际 Public 文件、来源与渠道、防泄漏证据、完整下载大小和 SHA256，再更新页面与元数据；未完成的构建不得标为可下载。公共元数据只包含 Public 链接，不分发 Internal/Beta 包。

正式提升 latest 前，须确认本轮所有渠道下载均已完成校验；保持公共 `download_page_url` 不变。最终同步 README、index、manual、release-meta、latest、Release 说明、Public-only manifest 与校验文件，并确认 Pages 已部署预期提交及线上内容一致。历史 Release、截图和视频保留原版本标注。

Public 3D 使用程序化胶囊体作为角色占位，支持基础场景编辑，不提供骨骼姿态或关节手柄编辑。macOS 为 ad-hoc 签名、未公证；Windows 实机验收未进行，不得将构建或文件校验称为实机验证。
