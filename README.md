# johnwaldo

![Ruby](https://img.shields.io/badge/-Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | Yesterday | Prior 7 Days | Prior 28 Days | Prior 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Mac) | 0.6h | 8.4h | 28.5h | /Users/justin612h* |
| Interactive human attention | 0.0h | 0.9h | 3.1h | 299.9h |
| Interactive AI generation | 0.0h | 0.6h | 1.2h | 272.8h |
| Worker-classified human attention | 0.0h | 0.0h | 0.0h | 8.3h |
| Worker/headless AI generation | 0.8h | 11.3h | 40.6h | 341.8h |
| Additive observed work | 0.8h | 12.9h | 45.0h | 921.0h |
| Interactive sessions | 2 | 4 | 12 | 918 |
| Worker sessions | 37 | 246 | 882 | 4,092 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 154 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 5,840 | 19.4M | 897K | 221.7M | $250.15 | $598.59 | $553.56 |
| gpt-5.5 | 4,226 | 12.2M | 557K | 112.9M | $70.68 | $305.05 | $316.41 |
| big-pickle | 24 | 112K | 4K | 472K | $0.58 | $0.00 | $2.76 |
| **Total** | **10,090** | **31.8M** | **1.4M** | **335.1M** | **$321.41** | **$903.64** | **$872.73** |

_368.4M total tokens processed. 91% cache hit rate._

_$1,776.37 total saved ($903.64 caching + $872.73 model routing vs all-Opus)._

_Model savings are modest because ~91% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 14,531 | 17K | 4.9M | 1,684.3M | $4,599.79 | $22,738.07 | $0.00 |
| claude-opus-4-7 | 9,028 | 15K | 7.7M | 1,224.4M | $3,977.42 | $16,529.43 | $0.00 |
| claude-sonnet-4-6 | 73,152 | 76K | 23.7M | 5,972.3M | $3,088.59 | $16,125.37 | $8,593.70 |
| gpt-5.5 | 23,201 | 95.5M | 4.0M | 1,113.6M | $604.62 | $3,006.80 | $2,727.50 |
| gpt-5.6-sol | 5,840 | 19.4M | 897K | 221.7M | $250.15 | $598.59 | $553.56 |
| claude-opus-4-5 | 808 | 231 | 217K | 60.8M | $194.28 | $822.04 | $0.00 |
| big-pickle | 619 | 2.0M | 135K | 28.3M | $22.93 | $0.00 | $83.93 |
| minimax-m2.5-free | 120 | 509K | 55K | 6.2M | $4.24 | $0.00 | $21.20 |
| claude-haiku-4-5 | 22 | 107 | 4K | 639K | $0.10 | $0.46 | $1.22 |
| **Total** | **127,321** | **117.7M** | **41.8M** | **10,312.5M** | **$12,742.12** | **$59,820.76** | **$11,981.11** |

_10,903.1M total tokens processed. 94.6% cache hit rate._

_$71,801.88 total saved ($59,820.76 caching + $11,981.11 model routing vs all-Opus)._

_Model savings are modest because ~94.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[aidevops-dashboard](https://github.com/johnwaldo/aidevops-dashboard)** -- AI DevOps Dashboard
## Contributions

- **[dspyground](https://github.com/karthikscale3/dspyground)** -- A tool kit for generating high quality prompts using DSPy GEPA optimizer
- **[autoresearch](https://github.com/karpathy/autoresearch)** -- AI agents running research on single-GPU nanochat training automatically
- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. AI DevOps automates your software, business, and personal development, with managed infrastructure, through AI chat in OpenCode. Opinionated tools, services, CLI & API tech-stack for speed, security, and 24/7 results. Open-source-preferred, and SOTA everything.
- **[osaurus](https://github.com/osaurus-ai/osaurus)** -- AI edge infrastructure for macOS. Run local or cloud models, share tools across apps via MCP, and power AI workflows with a native, always-on runtime.
- **[NextDNS-Config](https://github.com/yokoffing/NextDNS-Config)** -- Setup guide for NextDNS, a DoH proxy with advanced capabilities. 3/9/23
- **[nanoclaw](https://github.com/qwibitai/nanoclaw)** -- A lightweight alternative to Clawdbot / OpenClaw that runs in containers for security. Connects to WhatsApp, has memory, scheduled jobs, and runs directly on Anthropic's Agents SDK
- **[sharetribe](https://github.com/sharetribe/sharetribe)** -- Open source marketplace platform

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/johnwaldo)

---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-23 19:46 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
