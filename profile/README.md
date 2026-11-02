# Build with IteraCompute

Start with free Qwen through an OpenAI-compatible API. Install dependencies, configure an IteraCompute key, and verify a non-empty reply.

| Project | Start here |
| --- | --- |
| [migration-kit](https://github.com/IteraCompute/migration-kit) | Python and TypeScript quickstarts plus two complete projects: a [text summarizer](https://github.com/IteraCompute/migration-kit/tree/main/examples/summarizer) and an [OpenCode coding task](https://github.com/IteraCompute/migration-kit/tree/main/examples/opencode). Includes run instructions, expected output, troubleshooting and an explicit [acceptance record](https://github.com/IteraCompute/migration-kit/blob/main/docs/acceptance.md). |
| [pricing](https://github.com/IteraCompute/pricing) | A Python CLI for inspecting the public model catalog and pricing metadata. Check the [official pricing page](https://iteracompute.com/pricing/) for current published rates. |

API base URL: `https://api.iteracompute.com/v1` · Free model ID: `qwen/qwen3.8-27b` · Key: `ITERACOMPUTE_API_KEY`.

Use exact API model IDs; do not add an `iteracompute/` prefix to API requests. Follow each coding tool's provider-selector rules separately.

[Create an API key](https://platform.iteracompute.com/api-keys) · [API documentation](https://iteracompute.com/docs.html) · [Integrations](https://iteracompute.com/integrations/) · [Free allowance and limits](https://iteracompute.com/free/)

## Open weights from IteraCompute

[**IteraCompute Qwen3.8-27B NVFP4 — Deployment Edition**](https://huggingface.co/IteraCompute/Qwen3.8-27B-NVFP4) provides downloadable checkpoint weights. IteraCompute maintains the distribution and deployment documentation, preserving the original tensors and upstream licenses.

[Qwen4-27B NVFP4 toolkit](https://github.com/IteraCompute/qwen4-27b-nvfp4) remains a preparation project. The currently deployed and downloadable checkpoint is Qwen3.8-27B; Qwen4 weights have not been published.

## Upstream contributions

The forks below support IteraCompute provider integrations and directory submissions. Upstream authors retain ownership of their projects; the IteraCompute products and downloadable checkpoint are linked above.

- Active provider work: [huggingface.js](https://github.com/IteraCompute/huggingface.js), [Vercel AI SDK](https://github.com/IteraCompute/ai), [LiteLLM](https://github.com/IteraCompute/litellm), and [LiteLLM docs](https://github.com/IteraCompute/litellm-docs).
- Active directory submissions: [awesome-freellm-apis](https://github.com/IteraCompute/awesome-freellm-apis), [Free-LLM](https://github.com/IteraCompute/Free-LLM), [awesome-free-llm-apis-amardeeplakshkar](https://github.com/IteraCompute/awesome-free-llm-apis-amardeeplakshkar), [itsfree.ai](https://github.com/IteraCompute/itsfree.ai), and [free-llm-atlas](https://github.com/IteraCompute/free-llm-atlas).
- Archived contribution history: [huggingface_hub](https://github.com/IteraCompute/huggingface_hub), [awesome-free-llm-apis](https://github.com/IteraCompute/awesome-free-llm-apis), and [Free-LLM-Collection](https://github.com/IteraCompute/Free-LLM-Collection). Their previous upstream proposals are closed; code and history remain available.
