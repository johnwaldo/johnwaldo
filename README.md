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

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Mac) | 0h | 0h | 0h | ~0h* |
| User AI session hours | 1.6h | 21.9h | 50.7h | 50.7h |
| AI worker hours | 1.4h | 5.4h | 17.7h | 17.7h |
| AI concurrency hours | 3.4h | 41.4h | 103.1h | 103.1h |
| Interactive sessions | 7 | 44 | 136 | 136 |
| Worker sessions | 9 | 44 | 157 | 157 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7 | 8,864 | 15K | 7.5M | 1,204.1M | $3,896.60 | $16,255.57 | $0.00 |
| claude-opus-4-6 | 4,632 | 6K | 1.7M | 639.0M | $1,681.14 | $8,626.66 | $0.00 |
| claude-sonnet-4-6 | 22,809 | 24K | 9.6M | 1,826.3M | $960.78 | $4,931.06 | $2,771.87 |
| gpt-5.5 | 311 | 1.4M | 49K | 15.4M | $8.62 | $41.81 | $39.05 |
| minimax-m2.5-free | 81 | 341K | 47K | 5.2M | $3.33 | $0.00 | $16.66 |
| big-pickle | 55 | 31K | 19K | 2.9M | $2.04 | $0.00 | $6.40 |
| **Total** | **36,752** | **1.8M** | **19.0M** | **3,693.1M** | **$6,552.51** | **$29,855.10** | **$2,833.98** |

_3,898.5M total tokens processed. 94.7% cache hit rate._

_$32,689.08 total saved ($29,855.10 caching + $2,833.98 model routing vs all-Opus)._

_Model savings are modest because ~94.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 14,531 | 17K | 4.9M | 1,684.3M | $4,599.79 | $22,738.07 | $0.00 |
| claude-opus-4-7 | 8,864 | 15K | 7.5M | 1,204.1M | $3,896.60 | $16,255.57 | $0.00 |
| claude-sonnet-4-6 | 73,152 | 76K | 23.7M | 5,972.3M | $3,088.59 | $16,125.37 | $8,593.70 |
| claude-opus-4-5 | 808 | 231 | 217K | 60.8M | $194.28 | $822.04 | $0.00 |
| big-pickle | 593 | 1.9M | 130K | 27.8M | $22.28 | $0.00 | $80.87 |
| gpt-5.5 | 311 | 1.4M | 49K | 15.4M | $8.62 | $41.81 | $39.05 |
| minimax-m2.5-free | 81 | 341K | 47K | 5.2M | $3.33 | $0.00 | $16.66 |
| claude-haiku-4-5 | 22 | 107 | 4K | 639K | $0.10 | $0.46 | $1.22 |
| **Total** | **98,362** | **3.8M** | **36.7M** | **8,970.9M** | **$11,813.59** | **$55,983.33** | **$8,731.51** |

_12,141.7M total tokens processed. 94.8% cache hit rate._

_$64,714.84 total saved ($55,983.33 caching + $8,731.51 model routing vs all-Opus)._

_Model savings are modest because ~94.8% of tokens are cache reads, where price differences between models are small._
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
_Stats auto-updated 2026-05-05 04:51 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
