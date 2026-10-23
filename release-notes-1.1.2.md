# Pay4Dream 1.1.2 Public

macOS Apple Silicon 与 Windows x64 Public 1.1.2 已放入同一个公开 Release。请按系统下载，并核对 `SHA256SUMS.txt` 或 `release-manifest.json`。

## 更新

- **KV 创作成为第五工作区**：与图片生成、3D 分镜、视频生成、剪辑并列，在同一草稿中组合角色、场景、构图和风格参考，生成完整静态 KV。
- **一键动态 KV**：选中已生成的静态 KV，以它为图生视频首帧；提交前确认内容与费用，结果回到同一张 KV 卡，不覆盖静态原图，不自动重投。
- **3D 构图往返**：从 KV 草稿进入 3D 构图并捕获当前机位，返回后保留已选角色、场景和风格参考。
- **本机 Agent 工作流**：安装包内含同版本 `p4d-cli` / `p4d` 与 `P4D_CLI.md`；Agent 只连接本机正在运行的桌面会话，付费、破坏性和敏感操作仍受应用确认与风险策略约束。
- **稳定性修复**：改善项目切换、Canvas 节点交互、未知工程文件缩略图、剪辑恢复和付费确认竞态。

## 下载与校验

`Pay4Dream-1.1.2-external-mac.dmg` · 37,051,095 字节

SHA-256: `efdb294c8cdbab10945a754e77d49c467f97602c02b37b0c336d6ff39d645832`

`Pay4Dream-1.1.2-external-win-x64-setup.exe` · 21,836,311 字节

SHA-256: `991e91bbab6e4746167307d5b041a570ecf9bf03f2f27e07d2d6f1c435e9f6fe`

macOS 应用使用 ad-hoc 签名，未经过 Apple 公证。Windows 安装包未签名，本版尚未完成真实 Windows 机器上的安装启动验收。请只从本 Release 下载并核对校验值；不要关闭系统安全保护。

[命令行使用说明](https://github.com/pay4dream/p4d-release/releases/download/v1.1.2/Pay4Dream-1.1.2-P4D_CLI.md) · [官方主页](https://pay4dream.github.io/) · [Public 下载页](https://pay4dream.github.io/p4d-release/) · [试用手册](https://pay4dream.github.io/p4d-release/manual.html)
