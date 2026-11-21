# Treza

Treza is the node editor for generative media. Chain the best video, image, and language models into a pipeline on a visual canvas, run it from a prompt, then publish it behind one API.

![Four short clips made with Treza: a red hover car racing through a neon city, an astronaut walking over a Martian dune at sunset, an orchid mantis on a leaf, and espresso pouring into a cup](https://raw.githubusercontent.com/treza-labs/treza-labs/main/assets/treza-demo.gif)

These clips were made with [Treza](https://www.trezalabs.com), and the [integrations page](https://www.trezalabs.com/integrations) lists every way to connect to it.

---

## What is Treza?

Treza turns one prompt into video, images, and text. You build a workflow by wiring models, tools, and guardrails together as nodes on a drag-and-drop canvas, with no glue code between the pieces.

Every pipeline becomes a versioned HTTP endpoint you can call from your product, your scripts, or an AI agent, either with the typed `/invoke` API or an OpenAI-compatible `/chat/completions` drop-in.

---

## Why teams use Treza

- **Every modality on one canvas.** Video with Veo 3.1, Seedance 2.5, Kling, and Wan, images with Gemini image models, and text with open models like Llama, DeepSeek, and Qwen, plus transcription and embeddings. Pick a model per node and change it any time.
- **No lock-in.** Models run through an OpenAI-compatible backend across providers like Together, OpenRouter, Fireworks, and DeepSeek. Not listed? Type any Hugging Face or OpenRouter model id straight into the node. Bring your own provider keys, stored encrypted.
- **One API, two ways to call it.** Every published pipeline gets a versioned endpoint. Use the typed `/invoke` API for JSON in and JSON out, or point any OpenAI SDK at the `/chat/completions` endpoint, streaming included.
- **Guardrails when you want them.** Drop redaction, PII, and conditional-routing nodes into any pipeline so sensitive data is handled before it reaches a model or an external system.
- **Team and Enterprise plans available.**
- **Production-ready.** Automatic retries and fallback models, a KMS-encrypted secrets manager, and every run logged step by step with its timing and cost.

---

## Start here

- [**Concepts**](https://docs.trezalabs.com/getting-started/concepts) - pipelines, nodes, models, runs, and published endpoints.
- [**Build your first pipeline**](https://docs.trezalabs.com/pipelines/quickstart) - go from a prompt to a published API in a few minutes.
- [**Models**](https://docs.trezalabs.com/pipelines/models) - the model catalog and how to use any model id.
- [**Pipeline API**](https://docs.trezalabs.com/api/pipeline-api) - call a published pipeline over HTTP.

---

## Build with Treza

- [**Pipeline API**](https://docs.trezalabs.com/api/pipeline-api) - the typed `/invoke` and OpenAI-compatible `/chat/completions` endpoints on every published pipeline.
- [**MCP Server**](https://docs.trezalabs.com/api/mcp-server) - connect Claude and other AI agents to your pipelines over the Model Context Protocol.
- [**AI Gateway**](https://docs.trezalabs.com/ai-gateway) - the redaction gateway that also powers the PII guardrail node.

### Open source

- [**treza-examples**](https://github.com/treza-labs/treza-examples) - runnable recipes for curl, Python, TypeScript, LangChain (with a Colab notebook), n8n, ComfyUI and x402.
- [**render-video**](https://github.com/treza-labs/render-video) - a GitHub Action that renders a video or image, or runs a pipeline, from a workflow step, with a price cap.
- [**ai-video-models**](https://github.com/treza-labs/ai-video-models) - the video and image models on Treza with their specs and price per clip, as tables and JSON, refreshed daily.
- [**ffmpeg-kenburns**](https://github.com/treza-labs/ffmpeg-kenburns) - smooth push-ins and pans on stills with FFmpeg, without zoompan's stair-step jitter.
- Integrations: [n8n](https://github.com/treza-labs/n8n-nodes-treza), [Zapier](https://github.com/treza-labs/treza-zapier), [Dify](https://github.com/treza-labs/treza-dify-plugin), [ComfyUI](https://github.com/treza-labs/treza-comfyui), [LangChain](https://github.com/treza-labs/langchain-treza), [Langflow](https://github.com/treza-labs/lfx-treza), [CrewAI](https://github.com/treza-labs/crewai-treza), [LlamaIndex](https://github.com/treza-labs/llama-index-tools-treza), [Vercel AI SDK](https://github.com/treza-labs/treza-ai-sdk), [MCP plugin](https://github.com/treza-labs/treza-plugin), [x402](https://github.com/treza-labs/x402-video-example).

---

## Links

- [Website](https://trezalabs.com)
- [Platform](https://trezalabs.com/platform)
- [Documentation](https://docs.trezalabs.com)
- [Twitter](https://twitter.com/trezalabs)
