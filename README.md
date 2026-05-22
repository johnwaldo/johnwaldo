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
| User AI session hours | 1.8h | 4.8h | 10.0h | 10.0h |
| AI worker hours | 1.3h | 9.1h | 18.4h | 18.4h |
| AI concurrency hours | 3.6h | 15.5h | 32.2h | 32.2h |
| Interactive sessions | 2 | 6 | 13 | 13 |
| Worker sessions | 20 | 149 | 301 | 301 |

_Screen time from macOS display events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-7 | 4,767 | 8K | 4.2M | 652.8M | $2,225.17 | $8,812.92 | $0.00 |
| gpt-5.5 | 13,144 | 59.3M | 2.4M | 712.4M | $378.82 | $1,923.69 | $1,711.69 |
| claude-sonnet-4-6 | 6,751 | 7K | 3.5M | 559.7M | $301.98 | $1,511.38 | $885.18 |
| claude-opus-4-6 | 296 | 313 | 132K | 26.0M | $77.39 | $352.31 | $0.00 |
| minimax-m2.5-free | 120 | 509K | 55K | 6.2M | $4.24 | $0.00 | $21.20 |
| big-pickle | 57 | 51K | 19K | 2.9M | $2.11 | $0.00 | $6.70 |
| **Total** | **25,135** | **59.9M** | **10.3M** | **1,960.3M** | **$2,989.71** | **$12,600.29** | **$2,624.77** |

_2,103.4M total tokens processed. 93.2% cache hit rate._

_$15,225.07 total saved ($12,600.29 caching + $2,624.77 model routing vs all-Opus)._

_Model savings are modest because ~93.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 14,531 | 17K | 4.9M | 1,684.3M | $4,599.79 | $22,738.07 | $0.00 |
| claude-opus-4-7 | 9,028 | 15K | 7.7M | 1,224.4M | $3,977.42 | $16,529.43 | $0.00 |
| claude-sonnet-4-6 | 73,152 | 76K | 23.7M | 5,972.3M | $3,088.59 | $16,125.37 | $8,593.70 |
| gpt-5.5 | 13,144 | 59.3M | 2.4M | 712.4M | $378.82 | $1,923.69 | $1,711.69 |
| claude-opus-4-5 | 808 | 231 | 217K | 60.8M | $194.28 | $822.04 | $0.00 |
| big-pickle | 595 | 1.9M | 130K | 27.8M | $22.35 | $0.00 | $81.17 |
| minimax-m2.5-free | 120 | 509K | 55K | 6.2M | $4.24 | $0.00 | $21.20 |
| claude-haiku-4-5 | 22 | 107 | 4K | 639K | $0.10 | $0.46 | $1.22 |
| **Total** | **111,400** | **61.9M** | **39.2M** | **9,689.2M** | **$12,265.59** | **$58,139.06** | **$10,408.99** |

_12,932.0M total tokens processed. 94.6% cache hit rate._

_$68,548.05 total saved ($58,139.06 caching + $10,408.99 model routing vs all-Opus)._

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
_Stats auto-updated 2026-05-22 20:34 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
