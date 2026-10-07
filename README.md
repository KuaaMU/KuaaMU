<!-- Snake Animation -->
<img src="https://raw.githubusercontent.com/KuaaMU/KuaaMU/output/github-contribution-grid-snake-dark.svg" width="100%"/>

<br/>

<p align="center">
  智能科学与技术本科生 · 2027 届<br/>
  <a href="https://x.com/x_swarmmind"><img src="https://img.shields.io/badge/-@x__swarmmind-181717?style=flat-square&logo=x&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/kuaamu/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
</p>

---

## 🔥 Currently

- 🧠 **MCP 生态** — 给纯文本 coding agent 补上视觉、记忆与工具能力
- ⚡ **分布式训练** — Megatron-LM 张量并行、ZeRO 内存优化、流水线并行
- 🔬 **Ascend C 算子** — 对齐 `torch_cluster` 的 NPU kernel

---

## 🛠️ Projects

- 👁️ **[mcp-vision-bridge](https://github.com/KuaaMU/mcp-vision-bridge)** `13★` `MIT` `npm` —
  一个 MCP server，把图片路由给你已有的多模态模型，再以文本回注 —— 图片不进入 agent 上下文。
  起因是我自己踩的坑：用纯文本模型驱动 coding agent 时传图会直接报错。
  适配 Claude Code / Codex / opencode / Kimi 等 6 种 agent。
- 🔁 **[auto-pr-workflow](https://github.com/KuaaMU/auto-pr-workflow)** `MIT` —
  面向陌生仓库的 agent PR 提交流水线。我用它回答「这事到底行不行」，
  答案是**不行**：合并率明显低于我手写时期的水平，于是停手。
  踩过的坑连同真实仓库和 PR 编号都记在 `anti-patterns/` 里。
- 📦 **[agent-plugins](https://github.com/KuaaMU/agent-plugins)** `MIT` — 一个 Claude Code 插件市场。

---

## 🤝 Open Source

- 💠 **[Infrasys-AI/AIInfra](https://github.com/Infrasys-AI/AIInfra)** `8.3k★` `67 contributors` —
  贡献者排名第 3，为排名最高的外部贡献者。ZeRO、Megatron-LM 张量并行、GPipe、显存 benchmark。
- 🔶 **[cann/ops-gnn](https://gitcode.com/cann/ops-gnn)** —
  为昇腾 NPU 实现 `radius` / `radius_graph` 算子（SIMT kernel、host 侧 tiling、PyBind 绑定），
  接口对齐 `torch_cluster`，通过官方验收测试并合入主干。
- 🔧 **[anthropics/claude-agent-sdk-python](https://github.com/anthropics/claude-agent-sdk-python)** —
  Windows 路径分隔符与 `cmd.exe` 命令行长度上限导致 `--agents` 静默失效的修复。
- ⚙️ **[warpdotdev/warp](https://github.com/warpdotdev/warp)** — Hermes CLI agent 检测与配置。

---

## 💡 一些我认定的标准

**证据优先于叙述。** 简历上每个数字都应该能点开链接自己验证。
写「我做了很多」没有意义，写「第 3/67 名、PR #27 已合入主干」才有意义。

**如实写负结果。** 自动化 PR 的合并率低于我手写期 —— 这个事实比任何成功案例都更能说明
我在用数据做判断，而不是在攒战绩。停手本身是结论。

**工具用了就说用了。** 哪些代码是我写的、哪些是 coding agent 生成的，逐个项目标注。
把 agent 说成「独立实现」，第一轮追问就会穿。

**门槛票不是区分度。** 当所有人都在做同一件事时，它证明的是流程要求，不是你比别人强。

---

<p align="center"><sub>2026-10-07</sub></p>
