# AI Provider Pricing Dataset (125 providers)

Open, machine-readable pricing dataset for **125 AI providers** (2025 snapshot) — text, image, video, code, audio and vision models — compiled and maintained by [GigTry](https://www.gigtry.com), an all-in-one AI tools platform.

**Formats:** [`data/providers.json`](data/providers.json) · [`data/providers.csv`](data/providers.csv)

## What's inside

| Type | Providers |
|------|-----------|
| free | 32 |
| freemium | 44 |
| paid | 49 |
| **total** | **125** |

### Coverage by capability

| Category | Providers |
|----------|-----------|
| audio | 18 |
| code | 14 |
| image | 22 |
| text | 43 |
| video | 19 |
| vision | 9 |

Included are providers such as OpenAI, Anthropic, Google, Groq, Mistral, xAI, DeepSeek, Qwen, Baidu ERNIE, ByteDance Doubao, Tencent Hunyuan, MiniMax, ElevenLabs, Stability, fal.ai, Suno, Deepgram, AssemblyAI, Recraft and more (125 rows).

## Schema

| Field | Meaning |
|-------|---------|
| `providerId` | Stable machine identifier |
| `name` | Human-readable provider/model name |
| `category` | Primary capability: text / image / video / code / audio / vision |
| `type` | `free`, `freemium` or `paid` |
| `capabilities` | All supported capabilities |
| `costPerUseUSD` | Modeled wholesale cost per standard request (USD) |
| `costPer1KTokensUSD` | Modeled cost per 1K tokens where applicable (USD) |
| `pricingNote` | Provider-published pricing summary |
| `freeTier` | Published free-tier limits |

## Honest methodology

- Costs are **modeled estimates** compiled for comparison and unit-economics planning, snapshot 2025. Provider list prices change frequently — always confirm with the provider for authoritative, current pricing.
- The dataset intentionally contains **no proprietary business fields** (no resale markups, no API endpoints, no credentials). It is safe, public, comparative data.
- Corrections welcome: open an issue or a PR.

## Why we published this

[GigTry](https://www.gigtry.com) runs a multi-provider AI platform (89 AI tools, 4,450+ localized pages) and needed a normalized cost model across every major AI vendor to keep tools affordable and sustainable. The normalized view is shared here so other builders don't have to repeat the research. Try the free tools at [www.gigtry.com/tools](https://www.gigtry.com/tools) — no signup required for most tools.

## License

Data: [CC BY 4.0](LICENSE) — attribute "GigTry" and link to https://www.gigtry.com when reusing.
