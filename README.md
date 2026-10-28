<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Lyra: AI-native builder of generative and agentic systems" src="assets/header-light.svg" width="100%">
</picture>

<p align="center">AI native · 可灵基模组实习 · 东南大学研究生 · 图像 / 视频生成 · 多模态 · Agentic LLM workflow</p>

I'm a master's student at Southeast University and an intern on the Kling foundation model team. I work on image and video generation, multimodal models, and the agent workflows that sit around them: harnesses that let a model carry a long task on its own, evaluation loops that tell you whether a change actually helped, and pipelines that chain generation steps together.

Most of my code is written with coding agents now. The card further down counts how many tokens they used, straight from my session logs.

## What I work on

- Image and video generation: controllable diffusion transformers, multi-stage video editing, long video
- Multimodal models: fusing audio, face and video features, e.g. for blended emotion recognition
- Agentic systems: coding-agent harnesses, multi-agent content generation, self-iterating eval loops
- LLM workflows: hooks, guards and memory that keep an agent productive over days instead of minutes

## Selected projects

| Project | What it is |
|---|---|
| [LyHarness](https://github.com/lyra-planet/LyHarness) | A local, interactive coding-agent harness. The model decides what to do; the harness supplies the workspace, file and shell tools, tasks, worktrees, team coordination, MCP, permissions and the feedback loop. |
| [BlendEmo](https://github.com/lyra-planet/BlendEmo) | Code for our BlendEmo paper: blended emotion recognition on BLEMORE as structured set prediction plus pair-conditioned ratio modeling, fusing WavLM, OpenFace, VideoMAEv2 and HiCMAE features. |
| [GAL-Dreamer](https://github.com/lyra-planet/GAL-Dreamer) | A multi-agent system that turns one conversation into a complete galgame: world-building, timeline, characters, story outline and consistency checks. |
| [Pipline](https://github.com/lyra-planet/Pipline) | Multi-stage video editing with MiniMax-H3, through a hosted API or a local ComfyUI workflow, with retries and failure repair. |

Before generative models I built web front ends in React and Vue and spent a while on computer graphics with Vulkan and a software rasterizer. [Twin-Automata](https://github.com/lyra-planet/Twin-Automata) and [winter_sweet](https://github.com/lyra-planet/winter_sweet) are from that time.

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
  <img alt="ComfyUI" src="https://img.shields.io/badge/ComfyUI-1f2328?style=flat-square">
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
  <img alt="Claude Code" src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
  <img alt="Vue" src="https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white">
</p>

## AI-native, in numbers

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/tokens-dark.svg">
  <img alt="Claude Code token usage: total tokens, daily chart for the last 30 days, activity calendar and split by model" src="assets/tokens-light.svg" width="100%">
</picture>

A script on my dev machine reads the Claude Code session logs, counts each API response once, and pushes only daily totals here twice a day. No prompts, code or project names leave the machine.

<!-- usage:start -->
<details>
<summary>Daily numbers (updated 2026-10-28 13:49, UTC+8)</summary>

| Date | Total | Output | Cache read | API calls | Sessions |
|---|--:|--:|--:|--:|--:|
| 2026-10-28 | 1.23B | 4.28M | 1.20B | 3,909 | 21 |
| 2026-10-27 | 5.44B | 18.2M | 5.34B | 15,120 | 29 |
| 2026-10-26 | 4.05B | 15.4M | 3.98B | 12,718 | 25 |
| 2026-10-25 | 2.88B | 12.2M | 2.79B | 13,795 | 20 |
| 2026-10-24 | 2.02B | 12.2M | 1.96B | 10,847 | 19 |
| 2026-10-23 | 999M | 3.87M | 983M | 2,722 | 15 |
| 2026-10-22 | 961M | 3.15M | 945M | 2,801 | 10 |
| 2026-10-21 | 317M | 1.61M | 308M | 1,224 | 25 |
| 2026-10-20 | 139M | 437k | 135M | 906 | 8 |

Raw data: [`data/claude-code-usage.json`](data/claude-code-usage.json)
</details>
<!-- usage:end -->
