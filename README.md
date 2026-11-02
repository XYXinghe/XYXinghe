# 夏语星禾

做跨设备的 AI Agent。往 [Operit2](https://github.com/AAswordman/Operit2) 上游持续提修复，也碰 [MemPalace](https://github.com/MemPalace/mempalace) 的记忆层。

在意一件事：**换了设备、换了壳，怎么还是同一个它。**

---

**26** 个 PR · **14** 个已合并 · [逐个可查](https://github.com/search?q=is%3Apr+author%3AXYXinghe&type=pullrequests)

## 在修的东西

**[Operit2](https://github.com/AAswordman/Operit2)** · Rust / Dart · 跨设备 Agent 框架　—　22 PR，14 已合并

挑的多是「用户撞得到、但看着不像 bug」的：

| PR | 修了什么 |
|---|---|
| [#158](https://github.com/AAswordman/Operit2/pull/158) | `--help` 被当成参数执行 —— 会误删文件，会静默生成 196MB 垃圾 |
| [#159](https://github.com/AAswordman/Operit2/pull/159) | CLI 在 tokio runtime 里 panic |
| [#186](https://github.com/AAswordman/Operit2/pull/186) | Core 崩溃改成结构化 `FATAL_CORE_PANIC`，不再静默死掉 |
| [#188](https://github.com/AAswordman/Operit2/pull/188) | 日志轮转与批量写入串行化 |
| [#157](https://github.com/AAswordman/Operit2/pull/157) | 角色卡生命周期边界不严 |
| [#151](https://github.com/AAswordman/Operit2/pull/151) | CLI 广告了并不存在的子命令 |
| [#210](https://github.com/AAswordman/Operit2/pull/210) · [#211](https://github.com/AAswordman/Operit2/pull/211) | Android 定时调度校验 · 畸形通知按正常启动处理 |
| [#152](https://github.com/AAswordman/Operit2/pull/152) · [#164](https://github.com/AAswordman/Operit2/pull/164) · [#165](https://github.com/AAswordman/Operit2/pull/165) | Windows 构建链：GNU 工具链排障、Android 本地构建前置 |

**[MemPalace](https://github.com/MemPalace/mempalace)** · Python · AI 记忆系统　—　3 PR 待审

- [#2611](https://github.com/MemPalace/mempalace/pull/2611) — 记忆归一化，读 WorkBuddy JSONL 记录
- [#2615](https://github.com/MemPalace/mempalace/pull/2615) — 非 legacy palace 下的 KG 文件解析
- [#2672](https://github.com/MemPalace/mempalace/pull/2672) — 支持 WorkBuddy harness 的 hooks

## 在意的问题

- **身份连续性** — 跨设备时，什么算同一个它：同一份记忆，还是同一套判断
- **记忆的效力** — 一条记录凭什么有资格约束未来的判断
- **无云端的设备平等** — 设备之间对等，不靠一个中心说了算

## 怎么干活

撞到了就记下来，记清楚再提。

这些 PR 里有相当一部分是和 AI 一起做的。这恰好是我在意这个方向的原因，不是需要绕开的部分。

---

聊 Agent 的身份与记忆，开个 issue 就行。
