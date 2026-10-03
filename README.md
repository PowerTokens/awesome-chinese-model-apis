# Awesome Chinese Model APIs

A curated list of APIs and gateways for Chinese AI models, including LLM, image, video, and multimodal models.

> For developers exploring Chinese AI model APIs, unified gateways, and OpenAI-compatible integrations.

Last updated: 2026-10

## Contents

- [Unified AI APIs](#unified-ai-apis)
- [LLM APIs](#llm-apis)
- [AI Video APIs](#ai-video-apis)
- [Image Generation APIs](#image-generation-apis)
- [Multimodal APIs](#multimodal-apis)
- [Using Chinese model APIs from outside China](#using-chinese-model-apis-from-outside-china)
- [Tool setup guides](#tool-setup-guides)
- [Developer Tools](#developer-tools)
- [How to choose an AI API](#how-to-choose-an-ai-api)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License](#license)

## Unified AI APIs

| Platform | Focus | OpenAI-compatible | Notes |
|---|---|---:|---|
| [PowerTokens](https://www.powertokens.ai/?utm_source=github&utm_medium=readme&utm_campaign=awesome) | LLM, image, video and more | Yes | [Docs](https://docs.powertokens.ai) · [Models](https://www.powertokens.ai/en/models) |
| [OpenRouter](https://openrouter.ai) | Multi-provider AI APIs | Yes | Broad model catalog |
| [Kie](https://kie.ai) | Generative AI APIs | Check docs | Media and AI generation APIs |
| [fal](https://fal.ai) | Media and generative AI | Check docs | Generative media APIs |

## LLM APIs

Official API platforms of Chinese model developers. Where a developer runs separate international and mainland China sites, both are listed in the same row; the other columns describe the international site.

| Platform | Models | OpenAI-compatible | English console | Overseas signup and payment |
|---|---|---|---|---|
| [Alibaba Cloud Model Studio](https://www.alibabacloud.com/en/product/modelstudio) (DashScope API; China site: [Bailian](https://www.aliyun.com/product/bailian)) | Qwen (text, vision, coder, omni); also hosts DeepSeek, Kimi, GLM and MiniMax models | Yes | Yes | International site with Singapore, US (Virginia), Hong Kong and Tokyo regions. Visa, Mastercard, AMEX or JCB cards enabled for international payments, or PayPal registered outside mainland China. Prepaid and virtual cards are not accepted. |
| [Z.ai](https://z.ai/model-api) (Zhipu; China site: [BigModel](https://bigmodel.cn)) | GLM (text, vision), GLM-Image, CogVideoX | Yes | Yes | International site. Credit card top-up; the FAQ says 3DS verification is not supported. Phone requirements: Check docs. |
| [MiniMax](https://platform.minimax.io) (China site: [platform.minimaxi.com](https://platform.minimaxi.com)) | MiniMax-M text models, Hailuo / H video, image-01, speech, music | Yes (also Anthropic-compatible) | Yes | International site. Top-up by online payment or bank transfer. Accepted card types: Check docs. |
| [DeepSeek](https://platform.deepseek.com) | DeepSeek chat and reasoning models | Yes (also Anthropic-compatible) | Yes | One platform for all regions. Email or Google sign-in. Top-up via PayPal, bank card, Alipay or WeChat Pay (per FAQ). |
| [BytePlus ModelArk](https://www.byteplus.com/en/product/modelark) (ByteDance; China site: [Volcengine Ark](https://www.volcengine.com/product/ark)) | Seed / Doubao LLMs, Seedream, Seedance; also hosts third-party open models | Yes ("largely compatible", per docs) | Yes | BytePlus is the international site. Visa, Mastercard, AMEX or Maestro in the listed countries and regions; PayPal and bank transfer are also documented. |
| [Moonshot AI Kimi API](https://platform.kimi.ai) (China site: [platform.kimi.com](https://platform.kimi.com)) | Kimi K series (text, vision, coding) | Yes (also Anthropic-compatible) | Yes | International site with email or Google sign-in. The account FAQ lists WeChat Pay and Alipay for individual online top-ups; business accounts may use online payment or bank transfer depending on region. International cards: Check docs. |
| [Tencent Cloud TokenHub](https://intl.cloud.tencent.com/document/product/1300/80695) (Hunyuan / Hy) | Hy (Hunyuan) LLMs, Hy-MT translation, Hy image and video | Yes (also Responses and Anthropic Messages) | Yes | Tencent Cloud International. Visa, Mastercard, JCB, Discover, AMEX or UnionPay credit/debit cards. Prepaid, virtual and gift cards are not supported. |
| [StepFun](https://platform.stepfun.ai) (China site: [platform.stepfun.com](https://platform.stepfun.com)) | Step series (text, vision, audio) | Yes | Yes | International site. Signup and payment methods: Check docs. |
| [Baidu AI Cloud Qianfan](https://cloud.baidu.com/product-s/qianfan_home) | ERNIE; also hosts third-party models | Yes (v2 API) | Check docs | Check docs (China platform; docs are in Chinese). |
| [iFlytek Spark](https://xinghuo.xfyun.cn/sparkapi) | Spark (Lite, Pro, Ultra) | Yes | No | Check docs (China platform; docs are in Chinese). iFlytek's [global site](https://global.xfyun.cn) is mainly for speech and translation APIs. |

"Check docs" means the official pages did not confirm the detail when this list was last updated. Signup rules and payment methods change often, so check the provider's own pages before you rely on them.

<details>
<summary>Sources (official pages, checked 2026-10)</summary>

- Alibaba Cloud: [OpenAI compatible – Chat](https://www.alibabacloud.com/help/en/model-studio/compatibility-of-openai-with-dashscope), [Get an API key](https://www.alibabacloud.com/help/en/model-studio/get-api-key), [Payment methods](https://www.alibabacloud.com/help/en/user-center/instruction-of-payment-management/), [Payment FAQ](https://www.alibabacloud.com/help/en/user-center/support/payment-faq)
- Z.ai: [OpenAI Python SDK](https://docs.z.ai/guides/develop/openai/python), [Quick start](https://docs.z.ai/guides/overview/quick-start), [FAQ](https://docs.z.ai/help/faq)
- MiniMax: [OpenAI SDK](https://platform.minimax.io/docs/api-reference/text-openai-api), [Prerequisites](https://platform.minimax.io/docs/guides/quickstart-preparation), [About Account](https://platform.minimax.io/docs/faq/about-account)
- DeepSeek: [API docs](https://api-docs.deepseek.com/), [FAQ](https://api-docs.deepseek.com/faq)
- BytePlus: [Compatible with OpenAI API](https://docs.byteplus.com/en/docs/ModelArk/1330626), [Payment methods](https://docs.byteplus.com/en/docs/byteplus-platform/docs-managing-payment-methods)
- Kimi: [Start using Kimi API](https://platform.kimi.ai/docs/guide/start-using-kimi-api), [Account and Billing](https://platform.kimi.ai/docs/guide/account-and-payments), [Email and Google sign-in](https://platform.kimi.ai/docs/guide/account-security-and-sign-in)
- Tencent Cloud: [Hy API Guide](https://intl.cloud.tencent.com/document/product/1300/80695), [Payment Methods](https://intl.cloud.tencent.com/document/product/555/7425)
- StepFun: [Quickstart](https://platform.stepfun.ai/docs/en/overview/quickstart)
- Baidu: [OpenAI SDK compatibility](https://cloud.baidu.com/doc/qianfan/s/Hmh4suq26)
- iFlytek: [Spark HTTP API](https://www.xfyun.cn/doc/spark/HTTP%E8%B0%83%E7%94%A8%E6%96%87%E6%A1%A3.html)

</details>

When evaluating an API, check:

- Model availability
- API compatibility
- Pricing
- Rate limits
- Streaming support
- Tool calling
- Availability by region
- Account requirements

## AI Video APIs

| Model family | Developer | API | Description |
|---|---|---|---|
| Wan | Alibaba | [Model Studio video generation](https://www.alibabacloud.com/help/en/model-studio/text-to-video-guide) · [Open weights](https://github.com/Wan-Video/Wan2.2) | Text-to-video and image-to-video; some versions are also released as open weights. |
| Kling | Kuaishou | [Kling AI Developer Platform](https://kling.ai/dev) | Video and image generation APIs from Kling AI. |
| Hailuo / MiniMax H | MiniMax | [Video generation guide](https://platform.minimax.io/docs/guides/video-generation) | Text-to-video, image-to-video (first/last frame) and reference-based generation. |
| Seedance | ByteDance | [BytePlus Seedance](https://www.byteplus.com/en/product/seedance) | Multimodal video generation, served through BytePlus ModelArk (and Volcengine Ark in China). |
| Vidu | ShengShu | [Vidu API](https://platform.vidu.com) | Text-, image- and reference-to-video and start/end-frame generation, plus image and audio APIs. |
| CogVideoX | Zhipu | [CogVideoX on Z.ai](https://docs.z.ai/guides/video/cogvideox-3) | Text-to-video, image-to-video and start/end-frame generation. |
| HunyuanVideo (Hy Video) | Tencent | [Hy video API](https://intl.cloud.tencent.com/document/product/1300/83716) · [Open weights](https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5) | Text- and image-to-video through Tencent Cloud TokenHub; open-weight models on GitHub. |

Useful criteria for comparison:

- Text-to-video
- Image-to-video
- Video duration
- Resolution
- Generation speed
- API availability
- Pricing
- Developer documentation

## Image Generation APIs

| Model family | Developer | API | Description |
|---|---|---|---|
| Qwen-Image, Wan | Alibaba | [Model Studio text-to-image](https://www.alibabacloud.com/help/en/model-studio/text-to-image) | Text-to-image and image editing with Qwen-Image and Wan image models. |
| Seedream | ByteDance | [BytePlus Seedream](https://www.byteplus.com/en/product/seedream) | Image generation and editing, served through BytePlus ModelArk (and Volcengine Ark in China). |
| GLM-Image | Zhipu | [GLM-Image on Z.ai](https://docs.z.ai/guides/image/glm-image) | Text-to-image. Zhipu's current image API; earlier CogView models are no longer listed in the Z.ai docs. |
| image-01 | MiniMax | [Image generation guide](https://platform.minimax.io/docs/guides/image-generation) | Text-to-image and image-to-image. |
| Kling | Kuaishou | [Kling AI Developer Platform](https://kling.ai/dev) | Image generation alongside Kling's video APIs. |
| HunyuanImage (Hy Image) | Tencent | [Hy image API](https://intl.cloud.tencent.com/document/product/1300/83708) · [Open weights](https://github.com/Tencent-Hunyuan/HunyuanImage-3.0) | Text-to-image through Tencent Cloud TokenHub; open-weight models on GitHub. |
| Vidu Image | ShengShu | [Vidu API](https://platform.vidu.com) | Reference-to-image generation on the Vidu platform. |

## Multimodal APIs

Multimodal model capabilities may include:

- Text and image understanding
- Vision-language models
- Image analysis
- Document understanding
- Audio and video understanding

Most platforms in [LLM APIs](#llm-apis) offer vision-language models through the same chat endpoint (for example Qwen-VL, GLM vision models, Kimi, Step and MiniMax-M models).

## Using Chinese model APIs from outside China

A short practical guide. Rules change often, so check each provider's current docs.

**Phone verification.** Many providers run a separate international site (Alibaba Cloud international, Z.ai, MiniMax `minimax.io`, Kimi `platform.kimi.ai`, BytePlus, Tencent Cloud International, StepFun `stepfun.ai`). These are built for overseas users; DeepSeek and Kimi, for example, offer email or Google sign-in. The China sites (Bailian, BigModel, Volcengine, Qianfan, Spark) are built for users in mainland China and may require a mainland phone number or real-name verification. Start with the international site when there is one.

**Payment.** International sites usually take Visa/Mastercard (and sometimes AMEX, JCB or PayPal). Several cloud providers (Alibaba Cloud, Tencent Cloud) state that prepaid, virtual or gift cards are not accepted. 3DS handling also differs; Z.ai's FAQ, for example, says cards using 3DS verification are not supported. Some platforms are prepaid (top up a balance first) and others bill a card after use. A few still list only Alipay or WeChat Pay for individual top-ups, so check the billing page before you build on one.

**International vs mainland endpoints.** International and China sites often have different base URLs, accounts, API keys, model lists and pricing. A key from one region usually does not work on another (Alibaba Cloud, for example, binds each API key to its region). Use the base URL from the same console where you created the key.

**Latency and region.** Choose the region closest to your servers (for example Alibaba Cloud Singapore, US (Virginia) or Tokyo). Calling mainland endpoints from abroad can add latency and cross-border network variability. For production, measure time to first token from your own region.

**Docs language.** The international sites and docs listed above are in English. Some China-only platforms document their APIs only in Chinese; browser translation is usually enough for API references.

**Data and compliance.** Read each provider's terms and privacy policy for where requests are processed and stored, how long data is kept, and whether inputs are used for training. Mainland-hosted services follow Chinese law, including content moderation that can filter some prompts or outputs. If you handle personal or regulated data, check data-residency and cross-border transfer requirements (for example GDPR) before sending it.

**Direct vs gateway.** You can integrate with each provider directly, or use a unified OpenAI-compatible gateway such as [PowerTokens](https://www.powertokens.ai/?utm_source=github&utm_medium=readme&utm_campaign=awesome) or [OpenRouter](https://openrouter.ai) to reach several Chinese models with one account, one API key and one billing method. Going direct gives you each provider's full feature set and terms. A gateway reduces integration and payment overhead but adds an intermediary, so compare model coverage, pricing, rate limits and data handling for your use case.

## Tool setup guides

Step-by-step guides for connecting popular AI coding and agent tools to an OpenAI- or Anthropic-compatible endpoint. The setup guides are from the PowerTokens docs; the official provider docs explain each tool's generic custom-provider settings.

| Tool | What it is | Setup guide | Official provider docs |
|---|---|---|---|
| Claude Code | Anthropic's agentic coding tool for the terminal and IDE | [Claude Code setup](https://docs.powertokens.ai/en/ecosystem-tools/claude-code?utm_source=github&utm_medium=readme&utm_campaign=awesome) | [LLM gateways](https://code.claude.com/docs/en/llm-gateway) |
| opencode | Open-source AI coding agent | [opencode setup](https://docs.powertokens.ai/en/ecosystem-tools/opencode?utm_source=github&utm_medium=readme&utm_campaign=awesome) | [Providers](https://opencode.ai/docs/providers/) |
| Kilo Code | Open-source AI coding agent for IDE, CLI and cloud | [Kilo Code setup](https://docs.powertokens.ai/en/ecosystem-tools/kilo-code?utm_source=github&utm_medium=readme&utm_campaign=awesome) | [OpenAI-compatible providers](https://kilo.ai/docs/ai-providers/openai-compatible) |
| Hermes Agent | Open-source agent from Nous Research | [Hermes Agent setup](https://docs.powertokens.ai/en/ecosystem-tools/hermes-agent?utm_source=github&utm_medium=readme&utm_campaign=awesome) | [AI providers](https://hermes-agent.nousresearch.com/docs/integrations/providers) |
| OpenClaw | Open-source AI assistant | [OpenClaw setup](https://docs.powertokens.ai/en/ecosystem-tools/openclaw?utm_source=github&utm_medium=readme&utm_campaign=awesome) | [Model providers](https://docs.openclaw.ai/concepts/model-providers) |

Background reading: [Text model protocols and endpoints](https://docs.powertokens.ai/en/ecosystem-tools/text-model-protocols?utm_source=github&utm_medium=readme&utm_campaign=awesome) compares Chat Completions, Anthropic Messages and Responses for text models.

## Developer Tools

- [Chinese Model Picker](https://powertokens.github.io/chinese-model-picker/) ([source](https://github.com/PowerTokens/chinese-model-picker)) - Compare GLM, Qwen, MiniMax, DeepSeek V3.2, ByteDance Seed and Xiaomi MiMo models by context length, tool calling, reasoning, input types and price per 1M tokens, with a monthly cost calculator.

Developers may also want to evaluate:

- OpenAI-compatible SDKs
- AI agent frameworks
- Model gateways
- API aggregators
- CLI tools
- MCP integrations

## How to choose an AI API

Before integrating an API, compare:

1. Supported models
2. API format
3. Authentication
4. Pricing
5. Rate limits
6. Streaming support
7. Tool calling
8. Documentation quality
9. Regional availability
10. Reliability

## FAQ

### How do I use Qwen, GLM or MiniMax APIs from outside China?

Sign up on each developer's international site: [Alibaba Cloud Model Studio](https://www.alibabacloud.com/en/product/modelstudio) for Qwen, [Z.ai](https://z.ai/model-api) for GLM and [platform.minimax.io](https://platform.minimax.io) for MiniMax, all with English consoles. Alternatively, a unified gateway such as [PowerTokens](https://www.powertokens.ai/?utm_source=github&utm_medium=readme&utm_campaign=faq) or [OpenRouter](https://openrouter.ai) reaches several of these models with one account and one API key. See [Using Chinese model APIs from outside China](#using-chinese-model-apis-from-outside-china) for details.

### Is there an OpenAI-compatible API for Chinese AI models?

Yes. Every official platform in the [LLM APIs](#llm-apis) table offers an OpenAI-compatible endpoint, so the OpenAI SDK works after you change the base URL, API key and model name. Unified gateways such as PowerTokens (`https://api.powertokens.ai/v1`) and OpenRouter put models from several providers behind one OpenAI-compatible endpoint.

### Do I need a Chinese phone number to use Chinese model APIs?

Usually not on the international sites (Alibaba Cloud international, Z.ai, MiniMax, BytePlus, Tencent Cloud International and others), which are built for overseas users. The mainland China sites, such as Bailian, BigModel, Volcengine, Qianfan and Spark, may require a mainland phone number or real-name verification.

### Can I pay with an international credit card or PayPal?

Most international sites accept Visa or Mastercard, and Alibaba Cloud, BytePlus and DeepSeek also list PayPal; Alibaba Cloud and Tencent Cloud say prepaid and virtual cards are not accepted. Gateways bill all models in one place; PowerTokens, for example, accepts credit card or PayPal.

### Can I use Chinese models with Claude Code, opencode or other coding agents?

Yes, through an OpenAI- or Anthropic-compatible endpoint. MiniMax, DeepSeek, Moonshot AI and Tencent Cloud offer Anthropic-compatible APIs directly, and the [Tool setup guides](#tool-setup-guides) section links step-by-step setup for Claude Code, opencode, Kilo Code, Hermes Agent and OpenClaw (for example the [PowerTokens Claude Code guide](https://docs.powertokens.ai/en/ecosystem-tools/claude-code?utm_source=github&utm_medium=readme&utm_campaign=faq)).

### Which Chinese AI video generation APIs are available?

The main families are Wan (Alibaba), Kling (Kuaishou), Hailuo / MiniMax H (MiniMax), Seedance (ByteDance), Vidu (ShengShu), CogVideoX (Zhipu) and HunyuanVideo (Tencent). Each has an official API, listed with links in [AI Video APIs](#ai-video-apis).

### Should I call providers directly or use a gateway?

Going direct gives you each provider's full feature set and terms. A gateway reduces integration and payment overhead with one key and one bill, but adds an intermediary, so compare model coverage, pricing, rate limits and data handling for your use case.

## Contributing

Contributions are welcome.

When adding a new API or gateway, please include:

- Platform name
- Supported model families
- API documentation
- OpenAI compatibility
- Pricing information when available
- Account or regional requirements

Please keep entries factual and avoid promotional claims.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the entry format.

## License

CC0 / public domain for the list structure. Linked products and trademarks remain the property of their respective owners.

Curated by [@uselesssoso](https://github.com/uselesssoso) for [PowerTokens](https://powertokens.ai).
