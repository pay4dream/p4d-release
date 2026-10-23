# p4d-release

Pay4Dream Public 发布页面与应用内更新元数据。该仓库只包含公开下载与更新信息，不包含模型凭证或其他非公开信息。

## 1.1.2 发布状态

2026-10-23：Pay4Dream Public 1.1.2 的 macOS Apple Silicon 与 Windows x64 安装包已在同一个公开 Release 提供。`release-meta.json` 与 `latest.json` 已同步为 1.1.2。

下载入口：[Public 发布页](https://pay4dream.github.io/p4d-release/) · [1.1.2 Release](https://github.com/pay4dream/p4d-release/releases/tag/v1.1.2) · [使用手册](https://pay4dream.github.io/p4d-release/manual.html)。

本版重点包括：KV 创作第五工作区、参考选择生成静态 KV、3D 构图往返、一键动态 KV，以及随包 `p4d-cli` / `p4d`、`P4D_CLI.md` 与桌面 Agent API 的本机会话说明。动态 KV 使用静态图作为首帧；费用必须在应用内确认；失败或结果未知时不得自动重投。本机工具必须与桌面应用版本完全一致，付费、破坏性、敏感操作保留应用内确认，反馈提交仍只由用户在界面完成。

## 文件校验

- macOS Apple Silicon：`Pay4Dream-1.1.2-external-mac.dmg` · 37,051,095 字节 · SHA-256 `efdb294c8cdbab10945a754e77d49c467f97602c02b37b0c336d6ff39d645832`
- Windows x64：`Pay4Dream-1.1.2-external-win-x64-setup.exe` · 21,836,311 字节 · SHA-256 `991e91bbab6e4746167307d5b041a570ecf9bf03f2f27e07d2d6f1c435e9f6fe`

Release 同时提供 `SHA256SUMS.txt`、`release-manifest.json` 和 Windows 构建 provenance。

## 维护约定

只更新当前 Public 版本、公开下载入口、实际使用说明与安全边界。必须核对实际 Public 文件、来源、完整下载大小和 SHA256，再移除占位并提升 latest；未完成的构建不得标为可下载。公共元数据只包含 Public 链接。历史 Release、截图和视频保留原版本标注。

macOS 包为 ad-hoc 签名、未公证；Windows 包未签名，本版不得声称已完成 Windows 实机验收。
