<div align="center">

<h1>Hi, I'm KuaaMU 👋</h1>

<p>I like reading unfamiliar large codebases, fixing things, and sending the fixes upstream.</p>

<p>C is my strongest language — I hand-wrote bare-metal and RTOS code before the agent era. Now I work on AI infra.</p>

<p>
<a href="https://x.com/X_SwarmMind"><img src="https://img.shields.io/badge/-@X_SwarmMind-181717?style=flat-square&logo=x&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/kuaamu/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="https://gitcode.com/KuaaMU"><img src="https://img.shields.io/badge/-GitCode-2E9FFF?style=flat-square&logo=git&logoColor=white"/></a>
<a href="https://www.zhihu.com/people/92-64-7-12-70"><img src="https://img.shields.io/badge/-知乎-0066FF?style=flat-square&logo=zhihu&logoColor=white"/></a>
</p>

</div>

## Merged upstream

- **[cann/ops-gnn](https://gitcode.com/cann/ops-gnn)** — `radius` / `radius_graph` operators for Huawei Ascend NPU (SIMT kernels, host-side tiling, PyBind bindings), API-aligned with `torch_cluster`. Passed all 25 official acceptance tests, merged into main.
- **[Infrasys-AI/AIInfra](https://github.com/Infrasys-AI/AIInfra)** — 3rd of 67 contributors. ZeRO, Megatron-LM tensor parallelism, GPipe, VRAM benchmarks — 11 of 12 PRs merged, each reviewed by the author himself.
- **[anthropics/claude-agent-sdk-python](https://github.com/anthropics/claude-agent-sdk-python)** — fixed `--agents` silently breaking on Windows (path separators + `cmd.exe` command-line length limit). Merged #219, #245.
- **[warpdotdev/warp](https://github.com/warpdotdev/warp)** — Hermes CLI agent detection and configuration. Merged #9833, #9916.

## Things I built

Everything listed here works — I don't keep unfinished demos around.

- **[mcp-vision-bridge](https://github.com/KuaaMU/mcp-vision-bridge)** — an MCP server that routes images to your existing multimodal model and injects results back as text, so images never enter agent context. Born from my own pain: passing images to a text-only model crashed my coding agent. 7,957 npm downloads in its first month.
- **[agent-plugins](https://github.com/KuaaMU/agent-plugins)** — my agent workflow toolkit, published as installable skills: task routing, verification discipline, long-horizon skills, a mentor that teaches instead of doing, and personal data-ops.


## Now

- Preparing for China's CS postgraduate entrance exam (Dec 2026).
- Open to internships in AI infra / agent engineering — Shenzhen · Hangzhou · Xiamen · Quanzhou.
