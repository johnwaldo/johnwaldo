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
| User AI session hours | 3.8h | 10.5h | 17.5h | 17.5h |
| AI worker hours | 1.5h | 9.8h | 19.2h | 19.2h |
| AI concurrency hours | 6.6h | 25.4h | 44.5h | 44.5h |
| Interactive sessions | 4 | 14 | 19 | 19 |
| Worker sessions | 21 | 151 | 302 | 302 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7 | 3,222 | 5K | 2.8M | 445.8M | $1,524.10 | $6,018.81 | $0.00 |
| gpt-5.5 | 15,612 | 69.6M | 2.9M | 871.7M | $454.84 | $2,353.59 | $2,056.14 |
| claude-sonnet-4-6 | 2,786 | 2K | 1.3M | 238.0M | $119.92 | $642.83 | $369.41 |
| claude-opus-4-6 | 89 | 87 | 43K | 7.5M | $22.51 | $102.09 | $0.00 |
| minimax-m2.5-free | 120 | 509K | 55K | 6.2M | $4.24 | $0.00 | $21.20 |
| big-pickle | 57 | 51K | 19K | 2.9M | $2.11 | $0.00 | $6.70 |
| **Total** | **21,886** | **70.1M** | **7.2M** | **1,572.4M** | **$2,127.72** | **$9,117.32** | **$2,453.45** |

_1,692.1M total tokens processed. 92.9% cache hit rate._

_$11,570.78 total saved ($9,117.32 caching + $2,453.45 model routing vs all-Opus)._

_Model savings are modest because ~92.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 14,531 | 17K | 4.9M | 1,684.3M | $4,599.79 | $22,738.07 | $0.00 |
| claude-opus-4-7 | 9,028 | 15K | 7.7M | 1,224.4M | $3,977.42 | $16,529.43 | $0.00 |
| claude-sonnet-4-6 | 73,152 | 76K | 23.7M | 5,972.3M | $3,088.59 | $16,125.37 | $8,593.70 |
| gpt-5.5 | 15,612 | 69.6M | 2.9M | 871.7M | $454.84 | $2,353.59 | $2,056.14 |
| claude-opus-4-5 | 808 | 231 | 217K | 60.8M | $194.28 | $822.04 | $0.00 |
| big-pickle | 595 | 1.9M | 130K | 27.8M | $22.35 | $0.00 | $81.17 |
| minimax-m2.5-free | 120 | 509K | 55K | 6.2M | $4.24 | $0.00 | $21.20 |
| claude-haiku-4-5 | 22 | 107 | 4K | 639K | $0.10 | $0.46 | $1.22 |
| **Total** | **113,868** | **72.2M** | **39.7M** | **9,848.4M** | **$12,341.61** | **$58,568.97** | **$10,753.44** |

_13,104.9M total tokens processed. 94.6% cache hit rate._

_$69,322.41 total saved ($58,568.97 caching + $10,753.44 model routing vs all-Opus)._

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
_Stats auto-updated 2026-05-27 12:43 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
