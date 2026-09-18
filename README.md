# Awesome Chinese Model APIs

A curated list of APIs and gateways for **China-origin** LLMs, image, and video models — especially options that work **without a Chinese mainland account**.

> For developers comparing OpenRouter-style unified APIs. Contributions welcome.

## Contents

- [Unified gateways](#unified-gateways)
- [LLM APIs / families](#llm-apis--families)
- [Video APIs / families](#video-apis--families)
- [Image APIs / families](#image-apis--families)
- [Agent & tool integrations](#agent--tool-integrations)
- [Contributing](#contributing)

## Unified gateways

Low-friction ways to call many models through one API (often OpenAI-compatible).

| Gateway | Focus | OpenAI-compatible | CN mainland account | Notes |
|---------|-------|-------------------|---------------------|-------|
| [PowerTokens](https://www.powertokens.ai/?utm_source=github&utm_medium=readme&utm_campaign=awesome) | Qwen, MiniMax, GLM, Seed, DeepSeek, video & more | Yes (`https://api.powertokens.ai`) | No | [Docs](https://docs.powertokens.ai) · [Models](https://www.powertokens.ai/en/models) · [Python examples](https://github.com/PowerTokens/python-examples) · [TS examples](https://github.com/PowerTokens/typescript-examples) |
| [OpenRouter](https://openrouter.ai) | Multi-provider catalog | Yes | No | Broad third-party routing |
| [Kie](https://kie.ai) | Generative APIs | Check docs | Check docs | Competitor gateway |
| [fal](https://fal.ai) | Media / generative | Check docs | No | Strong on media pipelines |

## LLM APIs / families

Model IDs change — always verify on the provider or gateway catalog. Prefer live catalog over this list.

### Qwen (Alibaba)

- Typical use: chat, coding, general reasoning
- Gateway example IDs (PowerTokens): `qwen3-max`, `qwen3-coder-plus`, `qwen3.5-flash`, …
- Direct: DashScope / Model Studio — often needs Alibaba Cloud account (CN friction for some users)

### GLM (Zhipu)

- Typical use: chat, tools, Anthropic-style agent paths
- Gateway example IDs (PowerTokens): `glm-5.2`, `glm-5`, `glm-4.7`, …

### DeepSeek

- Typical use: reasoning / coding
- Prefer **Flash / V3.2** ids on gateways, for example:
  - `deepseek-v4-flash`
  - `deepseek-v3-2-251201`
  - `deepseek-v3.2` (where listed)
- Avoid recommending retired / pending-retirement ids in public guides (confirm live catalog before copying any id)

### MiniMax

- Typical use: chat + multimodal stack
- Gateway example IDs (PowerTokens): `MiniMax-M3`, `MiniMax-M2.7`, …

### Seed / BytePlus

- Typical use: chat / agent workloads
- Gateway example IDs (PowerTokens): `seed-2-0-pro-260328`, `seed-1-8-251228`, …

## Video APIs / families

Use **currently offered** catalog ids only; do not copy retired omni/o1-style ids from old docs.

### Kling

- Text-to-video / image-to-video style workloads
- Access via official Kling account **or** a unified gateway — pick model ids from the live [PowerTokens models](https://www.powertokens.ai/en/models) / Kling landing pages

### Wan (Alibaba)

- Video / image generation family
- Direct DashScope path may have CN account friction; gateways reduce that

### Seedance / BytePlus video

- Video generation via Seedance-class models
- See PowerTokens docs Seedance quick starts when available

## Image APIs / families

- Qwen image / edit APIs
- Wan image generation
- MiniMax image generation
- Seedream-class image models (via gateways)

Exact endpoints differ by provider — prefer a gateway with a model catalog when you need one key for many families.

## Agent & tool integrations

Useful when wiring China-origin models into coding agents:

| Tool | Notes |
|------|-------|
| [opencode](https://docs.powertokens.ai/en/ecosystem-tools/opencode) | OpenAI-compatible custom provider |
| [Claude Code](https://docs.powertokens.ai/en/ecosystem-tools/claude-code) | Anthropic Messages-compatible path |
| [Kilo Code](https://docs.powertokens.ai/en/ecosystem-tools/kilo-code) | OpenAI Compatible or Anthropic |
| [Hermes Agent](https://docs.powertokens.ai/en/ecosystem-tools/hermes-agent) | OpenAI-compatible endpoint |
| [OpenClaw](https://docs.powertokens.ai/en/ecosystem-tools/openclaw) | OpenAI or Anthropic path |

Protocol overview: [Text model protocols](https://docs.powertokens.ai/en/ecosystem-tools/text-model-protocols)

## Contributing

Open a PR with:

1. Category (gateway / LLM / video / image / tool)
2. Whether a **CN mainland account** is required
3. OpenAI-compatible: yes / no / partial
4. Docs or pricing link
5. Model ids that are **live** (do not add retired ids)

Keep entries factual. Soft promo is fine in the Gateway row; do not turn the whole list into a single-vendor page.

## License

CC0 / public domain for the list structure; linked products keep their own trademarks.
