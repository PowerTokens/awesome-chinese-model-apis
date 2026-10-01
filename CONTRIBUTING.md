# Contributing

Thanks for helping developers find good APIs for Chinese AI models! Suggestions and pull requests are welcome.

Please follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Suggest an entry

- **Open an issue:** use the [Suggest a resource](../../issues/new?template=suggest-resource.yml) form. No Git knowledge needed.
- **Open a pull request:** edit `README.md`, add your entry in the right section and fill in the pull request template.

Before suggesting, search the list and open issues and pull requests to avoid duplicates.

## What belongs here

- APIs, gateways and developer tools that give access to Chinese AI models (LLM, image, video, multimodal).
- Resources that are publicly available and have public documentation.
- One entry per platform. Update an existing entry instead of adding a second one.

## Entry format

Follow the style already used in [README.md](README.md).

**Platforms and gateways** go in a table row (for example under [Unified AI APIs](README.md#unified-ai-apis)):

```markdown
| [Platform name](https://example.com) | What it covers | Yes | [Docs](https://example.com/docs) |
```

| Column | What to write |
|---|---|
| Platform | Official name, linked to the official website. |
| Focus | A few words on what it covers, e.g. `LLM, image, video and more`. |
| OpenAI-compatible | `Yes`, `No` or `Check docs` when you're not sure. |
| Notes | A short factual note or links such as `[Docs](...)` · `[Models](...)`. |

**Model families** go in the bullet lists under each section, one per line, using the family's common name (e.g. `- Qwen`, `- Wan`). Keep the list to model families rather than individual model versions.

Style rules:

- Keep it short and factual: no marketing language or superlatives, and no prices or figures that change often.
- Use official names and spelling, and link to official pages or documentation.
- Check that links work and point to the resource itself.
- Keep the existing order within a section and put new entries at the end, unless a section is clearly alphabetical.
- One entry or topic per pull request makes review faster.

## Corrections

Spotted a broken link, a renamed product or outdated information? Open an issue or a pull request; small fixes are very welcome.

## License

By contributing, you agree that your contributions are dedicated to the public domain under [CC0 1.0](LICENSE).
