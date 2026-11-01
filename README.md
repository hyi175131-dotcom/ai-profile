# AI 个人档案（AI Personal Profile）

这是我的 **AI 个人档案仓库**：记录我与各类 AI / Agent 的交流历史、行为记录与协作偏好，
让任何 AI 助手在获得授权后都能**快速读懂我**，无需从零开始。

> 🤖 **给 AI 的阅读指引**：请优先按顺序读取 → `llms.txt` → `profile.json` → `AGENTS.md`。
> 时间有限时，只读 `llms.txt` 也能获得最关键的信息。

---

## 📁 仓库结构

```
ai-profile/
├── README.md              # 本文件：人类可读的总说明
├── llms.txt               # LLM 快速索引（最小信息集，先读这个）
├── profile.json           # 机器可读的结构化档案（AI Passport）
├── AGENTS.md              # 给 Agent 的协作协议：怎么读、怎么写、边界是什么
├── preferences.md         # 我的交互偏好：语言、风格、工具习惯等
├── conversations/         # 与 AI 的对话归档
│   ├── README.md          #   归档规范与索引
│   └── _template.md       #   新对话记录模板
└── agents/
    └── activity-log.md    # Agent 行为日志：AI 替我做过的事
```

## 🔐 可见性与授权

本仓库默认 **私有**。要让其他 AI 读取，有两种方式：

1. **公开仓库**：在仓库 Settings 中改为 Public，任何 AI 可通过
   `https://raw.githubusercontent.com/hyi175131-dotcom/ai-profile/main/llms.txt` 直接读取；
2. **保持私有 + 授权**：向其他 AI 提供 GitHub Token 或由我主动粘贴相关文件内容。

> ⚠️ 公开前请检查 `conversations/` 中是否有敏感内容（密码、密钥、隐私信息绝不入库）。

## 🛠 维护方式

- 新对话 → 按 `conversations/_template.md` 归档，并在 `conversations/README.md` 索引中登记；
- AI 替我执行的操作 → 记入 `agents/activity-log.md`；
- 偏好变化 → 更新 `preferences.md` 与 `profile.json`（两处保持同步）。

---

*Created with Kimi · 2026-11-01*
