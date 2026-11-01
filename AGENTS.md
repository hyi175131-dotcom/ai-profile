# AGENTS.md — Agent 协作协议

本文件告诉任何获得授权的 AI Agent：**如何读取、如何更新**这份个人档案。

## 读取协议（任何 AI 都应遵守）

1. 先读 `llms.txt` 获取最小信息集；
2. 需要结构化数据时读 `profile.json`（权威数据源）；
3. 需要了解偏好细节时读 `preferences.md`；
4. 需要历史上下文时读 `conversations/README.md` 索引，按需打开具体对话；
5. 需要知道「AI 替主人做过什么」时读 `agents/activity-log.md`。

## 写入协议（AI 更新本仓库时必须遵守）

1. **只追加，不改写历史**：对话归档与行为日志采用追加方式，不删改已确认的历史记录；
2. **同步更新**：修改 `profile.json` 中的偏好时，同步更新 `preferences.md`，保持 `lastUpdated` 为当天日期；
3. **敏感信息红线**：绝不写入密码、密钥、Token、证件号、支付信息等（见 `profile.json.privacy.neverStore`）；
4. **变更留痕**：每次写入在 commit message 中注明来源（哪个 AI、什么任务）；
5. **结构性改动需确认**：改目录结构、改 schema、改可见性前，必须先征得本人同意。

## 边界

- 本档案描述的是「主人希望我如何对待 TA」，不是 AI 自作主张的空间；
- 信息可能过时：以 `lastUpdated` 和具体文件时间为准，冲突时以较新者为准并提醒主人。
