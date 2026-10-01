# 夏语星禾丶

关注 Agent 的**身份与记忆** —— 换了设备、换了壳之后，怎么还是同一个它。

## 在意的问题

- **身份连续性** —— 「跨设备时，什么算同一个它」：同一份记忆，还是同一套判断
- **记忆的效力** —— 一条记录凭什么有资格约束未来的判断
- **无云端的设备平等** —— 设备之间对等，不靠一个中心说了算

## 现在在做

**[Operit2](https://github.com/AAswordman/Operit2)** · Rust · 跨设备 AI Agent

提了 14 个 PR，7 个已合并。修的多是「用户撞得到、但看起来不像 bug」的地方：

- [#159](https://github.com/AAswordman/Operit2/pull/159) — CLI 在 tokio runtime 里 panic
- [#158](https://github.com/AAswordman/Operit2/pull/158) — `--help` 被当参数执行（会误删、会静默生成 196MB 垃圾）
- [#157](https://github.com/AAswordman/Operit2/pull/157) — 角色卡生命周期边界不严
- [#151](https://github.com/AAswordman/Operit2/pull/151) — CLI 广告了并不存在的子命令
- [#152](https://github.com/AAswordman/Operit2/pull/152) [164](https://github.com/AAswordman/Operit2/pull/164) [165](https://github.com/AAswordman/Operit2/pull/165) — Windows 构建链文档（GNU 工具链排障 / Android 本地构建前置）
- [#171](https://github.com/AAswordman/Operit2/pull/171) [172](https://github.com/AAswordman/Operit2/pull/172) — *在审*：把 Core 崩溃暴露成结构化错误 / 解析失败时降级而不是 panic

**[MemPalace](https://github.com/MemPalace/mempalace)** · AI 记忆系统

2 个 PR 待审（[#2611](https://github.com/MemPalace/mempalace/pull/2611) · [#2615](https://github.com/MemPalace/mempalace/pull/2615)）

## 说一句

我做的事里，有一部分是跟 AI 一起做的。这不算秘密 —— 它恰好就是我在意这个方向的原因。

工作方式也很简单：**撞到了就记下来，记清楚再提。**

---

想聊 Agent 的身份与记忆，开个 issue 就行。
