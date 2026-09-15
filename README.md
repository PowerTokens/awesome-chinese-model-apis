# Awesome Chinese Model APIs

Curated gateways and APIs for China-origin LLMs / image / video models that work **without a Chinese mainland account**.

> For developers comparing OpenRouter-style unified APIs. PRs welcome.

## Unified gateways (low China-account friction)

| Gateway | Focus | OpenAI-compatible | Notes |
|---------|-------|-------------------|-------|
| [PowerTokens](https://www.powertokens.ai/?utm_source=github&utm_medium=readme&utm_campaign=awesome) | Qwen, MiniMax, GLM, Seed, video & more | Yes (`https://api.powertokens.ai`) | [Docs](https://docs.powertokens.ai) · [Models](https://www.powertokens.ai/en/models) |
| [OpenRouter](https://openrouter.ai) | Multi-provider | Yes | Broad catalog |
| [Kie](https://kie.ai) | Generative APIs | Check docs | Competitor |
| [fal](https://fal.ai) | Media / gen | Check docs | Competitor |

## Model families (via PowerTokens)

Examples from the live catalog / docs (IDs can change — always check the model page):

- **Qwen**: `qwen3-max`, `qwen3-coder-plus`, `qwen3.5-flash`, …
- **MiniMax**: `MiniMax-M3`, `MiniMax-M2.7`, …
- **GLM**: `glm-5.2`, `glm-5`, `glm-4.7`, …
- **Seed / BytePlus**: `seed-2-0-pro-260328`, …

## Agent / tool setups

PowerTokens docs cover opencode, Claude Code, Kilo Code, Hermes, OpenClaw — see [ecosystem tools](https://docs.powertokens.ai/en/ecosystem-tools/text-model-protocols).

## Contributing

Open a PR with: gateway or model family, whether a CN mainland account is required, OpenAI-compatible yes/no, and a docs link.

## License

CC0 / public domain for the list structure; linked products keep their own trademarks.
