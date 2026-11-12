# Awesome-Conversational-AI-Digital-Assistant

## Top Conversational AI & Digital Assistant Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Enterprise Assistants, Personal AI Agents & Multimodal Conversational Interfaces*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Conversational AI & Digital Assistants**. These tools help organizations and individuals deploy AI-powered assistants that understand natural language, automate tasks, retrieve knowledge, and engage users across chat, voice, and messaging channels—covering everything from enterprise copilots to self-hosted personal assistants.

**Examples** include Microsoft Copilot, OpenAI ChatGPT Enterprise, Google Gemini Enterprise, IBM watsonx Assistant, Kore.ai, Amelia, Zoho Zia, and open-source alternatives like Pipecat, Khoj, and LibreChat (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted conversational AI, open-source voice frameworks, and community-driven personal assistants—ideal for organizations and individuals seeking data sovereignty and transparent model behavior over opaque enterprise SaaS.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Microsoft Copilot](https://www.microsoft.com/en-us/microsoft-copilot)** | Enterprise AI assistant integrated across Microsoft 365 (Word, Excel, Teams, Outlook) and Windows. Grounded in organizational data via Microsoft Graph. Requires Microsoft 365 licensing plus Copilot add-on. | Quote-only (add-on to M365 subscription) | No free tier for enterprise Copilot; consumer Copilot free |
| **[OpenAI ChatGPT Enterprise](https://openai.com/enterprise)** | Enterprise-grade ChatGPT with advanced security, admin controls, unlimited high-speed GPT access, and data analysis. Does not train on business data. | Quote-only (custom enterprise contract) | No free tier; demo via sales |
| **[Google Gemini Enterprise](https://cloud.google.com/gemini)** | Enterprise AI assistant integrated with Google Workspace and Google Cloud. Grounded in organizational data, with Vertex AI model garden access. | Quote-only (Workspace/Cloud add-on) | No free tier; trial via Google Cloud |
| **[IBM watsonx Assistant](https://www.ibm.com/products/watsonx-assistant)** | Enterprise conversational AI platform for building AI assistants across channels. **Lite plan is free**; **Plus starts at $140/month** including 1,000 MAUs, with additional MAUs at $14 per 100 and voice at $9 per 100 voice MAUs [citation:5][citation:12]. Enterprise adds data isolation and HIPAA support. | Plus: **$140/month** (1,000 MAUs); Enterprise: quote-only | **Lite (free)**: basics for building chatbots; **Plus**: paid with 1,000 MAUs included [citation:5] |
| **[Kore.ai](https://kore.ai/)** | Enterprise conversational AI platform for building, deploying, and managing AI assistants across voice and digital channels. **Pay-as-you-go model with 5,000 free sessions per account** (up to 5 bots); account reload from $100 [citation:6][citation:13]. | Pay-as-you-go (from $100 reload); Enterprise: quote-only | **Free**: 5,000 sessions per account (up to 5 bots); free trial plan available [citation:6] |
| **[Amelia](https://amelia.ai/)** | Enterprise AI assistant (formerly IPsoft, now part of SoundHound AI) for IT operations, customer service, and HR. **Enterprise-only custom pricing**; no free tier or self-serve option [citation:7][citation:14]. | Custom enterprise pricing only [citation:7] | **No free tier**; enterprise sales process required [citation:7][citation:14] |
| **[Zoho Zia](https://www.zoho.com/zia/)** | AI assistant embedded across Zoho applications. Includes predictive analytics, voice assistant, and workflow automation within the Zoho ecosystem. | Included with Zoho subscriptions | **Free** with Zoho free plans; limited AI capabilities |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Pipecat](https://github.com/pipecat-ai/pipecat)** | [![Stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=social&color=white)](https://github.com/pipecat-ai/pipecat/stargazers) | **The leading open-source framework for real-time voice and multimodal AI agents.** BSD-2 licensed Python framework orchestrating speech-to-text, LLMs, and text-to-speech into ultra-low latency pipelines (500–800ms round-trip). Supports 150+ AI service integrations including Deepgram, OpenAI, Anthropic, ElevenLabs, and Cartesia. Multi-agent ready with handoff and parallel fan-out. Client SDKs for JavaScript, React, Swift, Kotlin, and ESP32. Deployable on your own infrastructure or Pipecat Cloud [citation:2][citation:9]. |
| **[LibreChat](https://github.com/LibreChat-AI/LibreChat)** | [![Stars](https://img.shields.io/github/stars/LibreChat-AI/LibreChat?style=social&color=white)](https://github.com/LibreChat-AI/LibreChat/stargazers) | Enhanced open-source ChatGPT clone (~46.6k stars). Features Agents, MCP, Skills, multi-provider support (DeepSeek, Anthropic, AWS, OpenAI, Gemini, Groq, Mistral, OpenRouter), model switching, message search, Code Interpreter, DALL-E-3, secure multi-user auth, and self-hosting. The most mature open-source alternative to ChatGPT Enterprise for teams wanting full control [citation:11]. |
| **[Khoj](https://github.com/khoj-ai/khoj)** | [![Stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=social&color=white)](https://github.com/khoj-ai/khoj/stargazers) | Self-hostable personal AI assistant (~37.9k stars). Acts as a "second brain" that searches and chats across your notes, documents, and images. Supports web search, custom agents, scheduled automations, and deep research. Works with any online or local LLM (GPT, Claude, Gemini, Llama, Qwen, Mistral). Free to self-host [citation:11]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Herzen](https://github.com/pavel-arkharov/herzen)** | [![Stars](https://img.shields.io/github/stars/pavel-arkharov/herzen?style=social&color=white)](https://github.com/pavel-arkharov/herzen/stargazers) | **Local-first AI voice assistant runtime** for private, on-device orchestration. TypeScript monorepo using whisper.cpp for local STT, Ollama/llama-server for local LLM, and Silero VAD for endpointing. Integrates with Home Assistant for device control. Explicitly not a hosted product—focused on privacy, runtime control, and debuggable integration boundaries [citation:15]. |
| **[PersonalJarvis](https://github.com/alvinreal/awesome-opensource-ai/blob/main/README.md#10)** | — | Desktop voice and chat assistant for Windows, macOS, and Linux with custom wake phrase, local speech-to-text, and a workspace that runs CLI coding agents side by side. Works with any model provider key or local models via Ollama [citation:1]. |
| **[Off Grid AI Desktop](https://github.com/alvinreal/awesome-opensource-ai/blob/main/README.md#10)** | — | Local-first macOS AI app running LLM chat, image generation, voice transcription, and personal memory/RAG fully on-device via llama.cpp—nothing leaves the machine [citation:1]. |

**Frameworks for building custom systems**: Combine **Pipecat** for real-time voice pipelines with low latency, **LibreChat** for a multi-user chat assistant with provider flexibility, and **Khoj** for personal knowledge retrieval across documents—all deployable locally or via Docker without per-MAU SaaS licensing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Conversational AI assistants process potentially sensitive organizational knowledge and user conversations; enforce data residency controls, access logging, and compliance with applicable privacy regulations.
- **Pricing transparency varies dramatically.** IBM watsonx Assistant publishes Plus at $140/month with 1,000 MAUs [citation:5], and Kore.ai offers 5,000 free sessions before requiring reload [citation:6]. Microsoft Copilot, ChatGPT Enterprise, Google Gemini Enterprise, and Amelia are quote-only with no public pricing. Open-source alternatives like **Pipecat** and **LibreChat** provide genuine voice and chat capabilities but require engineering effort for production hardening, observability, and security controls.

---

**Made for AI engineers, platform teams, personal productivity enthusiasts, and developers building conversational assistants.**  
Let's make conversational AI more open, grounded, and controllable.
