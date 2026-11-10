# Design-Skills

设计相关的 Claude skills。每个 skill 是 `skills/` 下的一个文件夹（`SKILL.md` + 配套脚本 / 参考资料）。

| Skill | 用途 |
|---|---|
| [iphone-duo-adapt-trip](skills/iphone-duo-adapt-trip/README.md) | Trip 直板机 Figma 稿 → iPhone DUO 折叠屏适配稿（先出推荐 / 备选方案示意图，设计师确认后生成 01 外屏 / 02 内屏竖屏 / 03 内屏横屏） |

## 安装

- **Claude Code（本机所有项目）**：把 skill 文件夹复制到 `~/.claude/skills/`，例如 `~/.claude/skills/iphone-duo-adapt-trip/`。
- **Claude Code（某个项目）**：复制到该项目的 `.claude/skills/` 下。
- **claude.ai**：把 skill 文件夹打包成 zip，在 Skills 设置里上传。

这些 skill 需要连接 Figma 连接器（MCP）才能读写设计稿。
