# Build with IteraCompute

Start with free Qwen through an OpenAI-compatible API. Install dependencies, configure an IteraCompute key, and verify a non-empty reply.

| Project | Start here |
| --- | --- |
| [migration-kit](https://github.com/IteraCompute/migration-kit) | Python and TypeScript quickstarts plus two complete projects: a [text summarizer](https://github.com/IteraCompute/migration-kit/tree/main/examples/summarizer) and an [OpenCode coding task](https://github.com/IteraCompute/migration-kit/tree/main/examples/opencode). Includes run instructions, expected output, troubleshooting and an explicit [acceptance record](https://github.com/IteraCompute/migration-kit/blob/main/docs/acceptance.md). |
| [pricing](https://github.com/IteraCompute/pricing) | A Python CLI for inspecting the public model catalog and pricing metadata. Check the [official pricing page](https://iteracompute.com/pricing/) for current published rates. |

API base URL: `https://api.iteracompute.com/v1` · Free model ID: `qwen/qwen3.8-27b` · Key: `ITERACOMPUTE_API_KEY`.

Use exact API model IDs; do not add an `iteracompute/` prefix to API requests. Follow each coding tool's provider-selector rules separately.

[Create an API key](https://platform.iteracompute.com/api-keys) · [API documentation](https://iteracompute.com/docs.html) · [Integrations](https://iteracompute.com/integrations/) · [Free allowance and limits](https://iteracompute.com/free/)

## Upstream contributions

[huggingface.js](https://github.com/IteraCompute/huggingface.js) and [huggingface_hub](https://github.com/IteraCompute/huggingface_hub) are contribution forks for work with the Hugging Face ecosystem. For IteraCompute application setup, start with migration-kit above.
