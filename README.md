# Awesome Local AI with stars

If you tried [Jan Desktop](https://github.com/janhq/jan?tab=readme-ov-file#download) ⭐ 44,206 | 🐛 493 | 🌐 TypeScript | 📅 2026-08-27 and liked it, please also check out the following **awesome collection of open source and/or local AI tools and solutions.**

Your contributions are always welcome!

## Lists

* [awesome-local-llms](https://github.com/vince-lam/awesome-local-llms) ⭐ 803 | 🐛 6 | 🌐 Python | 📅 2026-08-24 - Table of open-source local LLM inference projects with their GitHub metrics.
* [llama-police](https://huyenchip.com/llama-police.html) - A list of Open Source LLM Tools from [Chip Huyen](https://huyenchip.com)

## Inference Engine

| Repository                                                                                                       | Description                                                                          | Supported model formats  | CPU/GPU Support | UI | language    | Platform Type |
| ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | ------------------------ | --------------- | -- | ----------- | ------------- |
| [llama.cpp](https://github.com/ggerganov/llama.cpp) ⭐ 125,886 \| 🐛 2,226 \| 🌐 C++ \| 📅 2026-08-27             | - Inference of LLaMA model in pure C/C++                                             | GGML/GGUF                | Both            | ❌  | C/C++       | Text-Gen      |
| [Cortex](https://github.com/janhq/cortex.cpp) ⚠️ Archived                                                        | - Multi-engine engine embeddable in your apps. Uses llama.cpp and more               | Both                     | Both            | ❌  | Text-Gen    |               |
| [ollama](https://github.com/jmorganca/ollama) ⭐ 179,544 \| 🐛 3,801 \| 🌐 Go \| 📅 2026-08-27                    | - CLI and local server. Uses llama.cpp                                               | Both                     | Both            | ❌  | Text-Gen    |               |
| [koboldcpp](https://github.com/LostRuins/koboldcpp) ⭐ 11,550 \| 🐛 503 \| 🌐 C++ \| 📅 2026-08-26                | - A simple one-file way to run various GGML models with KoboldAI's UI                | GGML                     | Both            | ✅  | C/C++       | Text-Gen      |
| [LoLLMS](https://github.com/ParisNeo/lollms) ⭐ 96 \| 🐛 14 \| 🌐 Vue \| 📅 2026-08-27                            | - Lord of Large Language Models Web User Interface.                                  | Nearly ALL               | Both            | ✅  | Python      | Text-Gen      |
| [ExLlama](https://github.com/turboderp/exllama) ⭐ 2,937 \| 🐛 65 \| 🌐 Python \| 📅 2023-09-30                   | - A more memory-efficient rewrite of the HF transformers implementation of Llama     | AutoGPTQ/GPTQ            | GPU             | ✅  | Python/C++  | Text-Gen      |
| [vLLM](https://github.com/vllm-project/vllm) ⭐ 90,207 \| 🐛 7,106 \| 🌐 Python \| 📅 2026-08-27                  | - vLLM is a fast and easy-to-use library for LLM inference and serving.              | GGML/GGUF                | Both            | ❌  | Python      | Text-Gen      |
| [SGLang](https://github.com/sgl-project/sglang) ⭐ 32,552 \| 🐛 4,997 \| 🌐 Python \| 📅 2026-08-27               | - 3-5x higher throughput than vLLM (Control flow, RadixAttention, KV cache reuse)    | Safetensor / AWQ / GPTQ  | GPU             | ❌  | Python      | Text-Gen      |
| [LmDeploy](https://github.com/InternLM/lmdeploy) ⭐ 8,027 \| 🐛 599 \| 🌐 Python \| 📅 2026-08-27                 | - LMDeploy is a toolkit for compressing, deploying, and serving LLMs.                | Pytorch / Turbomind      | Both            | ❌  | Python/C++  | Text-Gen      |
| [Tensorrt-llm](https://github.com/NVIDIA/TensorRT-LLM) ⭐ 14,484 \| 🐛 1,453 \| 🌐 Python \| 📅 2026-08-27        | - Inference efficiently on NVIDIA GPUs                                               | Python / C++ runtimes    | Both            | ❌  | Python/C++  | Text-Gen      |
| [CTransformers](https://github.com/marella/ctransformers) ⭐ 1,885 \| 🐛 113 \| 🌐 C \| 📅 2024-01-28             | - Python bindings for the Transformer models implemented in C/C++ using GGML library | GGML/GPTQ                | Both            | ❌  | C/C++       | Text-Gen      |
| [llama-cpp-python](https://github.com/abetlen/llama-cpp-python) ⭐ 10,587 \| 🐛 680 \| 🌐 Python \| 📅 2026-08-17 | - Python bindings for llama.cpp                                                      | GGUF                     | Both            | ❌  | Python      | Text-Gen      |
| [llama2.rs](https://github.com/srush/llama2.rs) ⭐ 1,063 \| 🐛 15 \| 🌐 Rust \| 📅 2023-11-30                     | - A fast llama2 decoder in pure Rust                                                 | GPTQ                     | CPU             | ❌  | Rust        | Text-Gen      |
| [ExLlamaV2](https://github.com/turboderp/exllamav2) ⭐ 4,611 \| 🐛 158 \| 🌐 Python \| 📅 2026-03-04              | - A fast inference library for running LLMs locally on modern consumer-class GPUs    | GPTQ/EXL2                | GPU             | ❌  | Python/C++  | Text-Gen      |
| [LoRAX](https://github.com/predibase/lorax) ⭐ 3,826 \| 🐛 185 \| 🌐 Python \| 📅 2026-05-28                      | - Multi-LoRA inference server that scales to 1000s of fine-tuned LLMs                | Safetensor / AWQ / GPTQ  | GPU             | ❌  | Python/Rust | Text-Gen      |
| [text-generation-inference](https://github.com/huggingface/text-generation-inference) ⚠️ Archived                | - Inference serving toolbox with optimized kernels for each LLM architecture         | Safetensors / AWQ / GPTQ | Both            | ❌  | Python/Rust | Text-Gen      |

## Inference UI

* [Automatic1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui) ⭐ 164,682 | 🐛 2,501 | 🌐 Python | 📅 2026-03-02 - Stable Diffusion web UI.
* [ComfyUI](https://github.com/comfyanonymous/ComfyUI) ⭐ 130,244 | 🐛 4,721 | 🌐 Python | 📅 2026-08-27 - A powerful and modular stable diffusion GUI with a graph/nodes interface.
* [LocalAI](https://github.com/go-skynet/LocalAI) ⭐ 48,701 | 🐛 215 | 🌐 Go | 📅 2026-08-27 - LocalAI is a drop-in replacement REST API that’s compatible with OpenAI API specifications for local inferencing.
* [oobabooga](https://github.com/oobabooga/text-generation-webui) ⭐ 47,587 | 🐛 838 | 🌐 Python | 📅 2026-08-17 - A Gradio web UI for Large Language Models.
* [ChatUI](https://github.com/huggingface/chat-ui) ⭐ 10,914 | 🐛 272 | 🌐 TypeScript | 📅 2026-08-27 - Open source codebase powering the HuggingChat app.
* [petals](https://github.com/bigscience-workshop/petals) ⭐ 10,522 | 🐛 113 | 🌐 Python | 📅 2024-09-07 - Run LLMs at home, BitTorrent-style. Fine-tuning and inference up to 10x faster than offloading.
* [LLM as a Chatbot Service](https://github.com/deep-diver/LLM-As-Chatbot) ⭐ 3,319 | 🐛 19 | 🌐 Python | 📅 2023-11-20 - LLM as a Chatbot Service.
* [LLMFarm](https://github.com/guinmoon/LLMFarm) ⭐ 2,062 | 🐛 46 | 🌐 C | 📅 2026-01-30 - llama and other large language models on iOS and MacOS offline using GGML library.
* [QA-Pilot](https://github.com/reid41/QA-Pilot) ⭐ 326 | 🐛 8 | 🌐 Svelte | 📅 2025-08-24 - An interactive chat app that leverages Ollama(or openAI) models for rapid understanding and navigation of GitHub code repository or compressed file resources
* [Wordflow](https://github.com/poloclub/wordflow) ⭐ 271 | 🐛 3 | 🌐 TypeScript | 📅 2026-04-07 - Run, share, and discover AI prompts in your browsers
* [everything-rag](https://github.com/AstraBert/everything-rag) ⚠️ Archived - Interact with (virtually) any LLM on Hugging Face Hub with an asy-to-use, 100% local Gradio chatbot.
* [Taskyon](https://github.com/Xyntopia/taskyon) ⭐ 54 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-19 - Vue3 based Chat UI, integratable in webpages. Focused on "local first" principle. Any OpenAI API compatible endpoint.
* [AI-Mask](https://github.com/pacoccino/ai-mask) ⭐ 32 | 🐛 1 | 🌐 TypeScript | 📅 2024-04-09 - Browser extension to provide model inference to web apps. Backed by web-llm and transformers.js
* [LmScript](https://github.com/lucasavila00/LmScript/) ⭐ 10 | 🐛 5 | 🌐 TypeScript | 📅 2024-05-17 - UI for SGLang and Outlines
* [LM Studio](https://lmstudio.ai/) - Discover, download, and run local LLMs.
* [FireworksAI](https://app.fireworks.ai/) - Experience the world's fastest LLM inference platform deploy your own at no additional cost.
* [faradav](https://faraday.dev/) - Chat with AI Characters Offline, Runs locally, Zero-configuration.
* [GPT4All](https://gpt4all.io) - A free-to-use, locally running, privacy-aware chatbot.
* [LlamaChat](https://llamachat.app/) - LlamaChat allows you to chat with LLaMa, Alpaca and GPT4All models1 all running locally on your Mac.
* [FuLLMetalAi](https://www.fullmetal.ai/) - Fullmetal.Ai is a distributed network of self-hosted Large Language Models (LLMs).
* [HammerAI](https://www.hammerai.com/desktop) - Simple character-chat interface to run LLMs on Windows, Mac, and Linux. Uses Ollama under the hood and is offline, free to chat, and requires zero configuration.
* [GPTLocalhost](https://gptlocalhost.com/demo/) - A local Word Add-in for you to use local LLM servers in Microsoft Word. Alternative to "Copilot in Word" and much more affordable.

## Platforms / full solutions

* [H2OAI](https://h2o.ai/#tabs-320f3fc63d-item-aa19ad7787-tab) - H2OGPT The fastest, most accurate AI Cloud Platform.
* [BentoML](https://github.com/bentoml/BentoML) ⭐ 8,809 | 🐛 217 | 🌐 Python | 📅 2026-08-26 - BentoML is a framework for building reliable, scalable, and cost-efficient AI applications.
* [Predibase](https://predibase.com/) - Serverless LoRA Fine-Tuning and Serving for LLMs.

## Developer tools

* [gpt4all](https://github.com/nomic-ai/gpt4all) ⭐ 77,396 | 🐛 772 | 🌐 C++ | 📅 2025-05-27 - A chatbot trained on a massive collection of clean assistant data including code, stories and dialogue.
* [LiteLLM](https://github.com/BerriAI/litellm) ⭐ 57,383 | 🐛 4,868 | 🌐 Python | 📅 2026-08-27 - Call all LLM APIs using the OpenAI format.
* [Langfuse](https://langfuse.com/) - Open-source LLM monitoring platform that helps teams collaboratively debug, analyze, and iterate on their LLM applications. [#opensource](https://github.com/langfuse/langfuse) ⭐ 33,801 | 🐛 839 | 🌐 TypeScript | 📅 2026-08-27
* [Shell-Pilot](https://github.com/reid41/shell-pilot) ⭐ 117 | 🐛 2 | 🌐 Shell | 📅 2025-01-28 - Interact with LLM using Ollama models(or openAI, mistralAI)via pure shell scripts on your Linux(or MacOS) system, enhancing intelligent system management without any dependencies
* [code-collator](https://github.com/tawanda-kembo/code-collator) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2024-10-09: Creates a single markdown file that describes your entire codebase to language models.
* [Jan Framework](https://jan.ai/docs/) - At its core, Jan is a **cross-platform, local-first and AI native** application framework that can be used to build anything.
* [Pinecone](https://www.pinecone.io) - Long-Term Memory for AI.
* [PoplarML](https://www.poplarml.com) - PoplarML enables the deployment of production-ready, scalable ML systems with minimal engineering effort.
* [Datature](https://datature.io) - The All-in-One Platform to Build and Deploy Vision AI.
* [One AI](https://www.oneai.com/) - MAKING GENERATIVE AI BUSINESS-READY.
* [Gooey.AI](https://gooey.ai/) - Create Your Own No Code AI Workflows.
* [Mixo.io](https://mixo.io/?via=futurepedia) - AI website builder.
* [Safurai](https://www.safurai.com) - AI Code Assistant that saves you time in changing, optimizing, and searching code.
* [GitFluence](https://www.gitfluence.com) - The AI-driven solution that helps you quickly find the right command. Get started with Git Command Generator today and save time.
* [Haystack](https://haystack.deepset.ai/) - A framework for building NLP applications (e.g. agents, semantic search, question-answering) with language models.
* [LangChain](https://langchain.com/) - A framework for developing applications powered by language models.
* [LMQL](https://lmql.ai/) - LMQL is a query language for large language models.
* [LlamaIndex](https://www.llamaindex.ai/) - A data framework for building LLM applications over external data.
* [Phoenix](https://phoenix.arize.com/) - Open-source tool for ML observability that runs in your notebook environment, by Arize. Monitor and fine tune LLM, CV and tabular models.
* [trypromptly](https://trypromptly.com/) - Create AI Apps & Chatbots in Minutes.
* [BentoML](https://www.bentoml.com/) - BentoML is the platform for software engineers to build AI products.
* [Tune Studio](https://studio.tune.app/playground) - Playground for software developers to finetune and deploy large language models.

## User Tools

* [llmcord.py](https://github.com/jakobdylanc/discord-llm-chatbot) ⭐ 826 | 🐛 5 | 🌐 Python | 📅 2026-08-14 - Discord LLM Chatbot - Talk to LLMs with your friends!

## Agents

* [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT) ⭐ 186,921 | 🐛 503 | 🌐 Python | 📅 2026-08-27 - An experimental open-source attempt to make GPT-4 fully autonomous.
* [MetaGPT](https://github.com/geekan/MetaGPT) ⭐ 70,064 | 🐛 133 | 🌐 Python | 📅 2026-01-21 - The Multi-Agent Framework: Given one line requirement, return PRD, design, tasks, repo.
* [Open Interpreter](https://github.com/KillianLucas/open-interpreter) ⭐ 68,162 | 🐛 7 | 🌐 Rust | 📅 2026-08-20 - Let language models run code. Have your agent write and execute code.
* [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) ⚠️ Archived - Specify what you want it to build, the AI asks for clarification, and then builds it.
* [BabyAGI](https://github.com/yoheinakajima/babyagi) ⭐ 22,357 | 🐛 30 | 🌐 Python | 📅 2026-01-31 - Baby AGI is an autonomous AI agent developed using Python that operates through OpenAI and Pinecone APIs.
* [GPT Prompt Engineer](https://github.com/mshumer/gpt-prompt-engineer) ⭐ 9,674 | 🐛 33 | 🌐 Jupyter Notebook | 📅 2025-10-16 - Automated prompt engineering. It generates, tests, and ranks prompts to find the best ones.
* [SuperAGI](https://superagi.com/) - Opensource AGI Infrastructure.
* [AgentGPT](https://agentgpt.reworkd.ai/) -Assemble, configure, and deploy autonomous AI Agents in your browser.
* [HyperWrite](https://www.hyperwriteai.com/) - HyperWrite helps you work smarter, faster, and with ease.
* [AI Agents](https://aiagent.app/) - AI Agent that Power Up Your Productivity.
* [AgentRunner.ai](https://www.agentrunner.ai) - Leverage the power of GPT-4 to create and train fully autonomous AI agents.
* [CrewAI](https://crewai.io) - Cutting-edge framework for orchestrating role-playing, autonomous AI agents.

## Training

* [DeepSpeed](https://github.com/microsoft/DeepSpeed) ⭐ 43,005 | 🐛 1,325 | 🌐 Python | 📅 2026-08-27 - DeepSpeed is a deep learning optimization library that makes distributed training and inference easy, efficient, and effective.
* [FastChat](https://github.com/lm-sys/FastChat) ⭐ 39,526 | 🐛 1,040 | 🌐 Python | 📅 2026-05-01 - An open platform for training, serving, and evaluating large language models.
* [PEFT](https://github.com/huggingface/peft) ⭐ 21,599 | 🐛 70 | 🌐 Python | 📅 2026-08-27 - Parameter efficient fine-tuning (LoRA, DoRA, model merger and more)
* [TRL](https://github.com/huggingface/trl) ⭐ 19,158 | 🐛 289 | 🌐 Python | 📅 2026-08-27 - Language model alignment with reinforcement learning.
* [Megatron-LM](https://github.com/NVIDIA/Megatron-LM) ⭐ 17,625 | 🐛 1,253 | 🌐 Python | 📅 2026-08-27 - Ongoing research training transformer models at scale.
* [Ludwig](https://github.com/ludwig-ai/ludwig) ⭐ 11,745 | 🐛 1 | 🌐 Python | 📅 2026-08-24 - Low-code framework for building custom LLMs, neural networks, and other AI models.
* [Alpa](https://github.com/alpa-projects/alpa) ⚠️ Archived - Alpa is a system for training and serving large-scale neural networks.
* [Nanotron](https://github.com/huggingface/nanotron) ⭐ 2,800 | 🐛 150 | 🌐 Python | 📅 2026-05-26 - Minimalistic large language model 3D-parallelism training.
* [BMTrain](https://github.com/OpenBMB/BMTrain) ⭐ 623 | 🐛 10 | 🌐 Python | 📅 2026-07-07 - Efficient Training for Big Models.

## LLM Leaderboard

* [Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) - aims to track, rank and evaluate LLMs and chatbots as they are released.
* [Chatbot Arena Leaderboard](https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard) - a benchmark platform for large language models (LLMs) that features anonymous, randomized battles in a crowdsourced manner.
* [AlpacaEval Leaderboard](https://tatsu-lab.github.io/alpaca_eval/) - An Automatic Evaluator for Instruction-following Language Models.
* [LLM-Leaderboard-streamlit](https://llm-leaderboard.streamlit.app/) - A joint community effort to create one central leaderboard for LLMs.
* [lmsys.org](https://chat.lmsys.org/) - Benchmarking LLMs in the Wild with Elo Ratings.

## Research

* Attention Is All You Need (2017): Presents the original transformer model. it helps with sequence-to-sequence tasks, such as machine translation. [\[Paper\]](https://arxiv.org/abs/1706.03762)
* BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (2018): Helps with language modeling and prediction tasks. [\[Paper\]](https://arxiv.org/abs/2307.00526)
* FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness (2022): Mechanism to improve transformers. [\[paper\]](https://arxiv.org/abs/2205.14135)
* Improving Language Understanding by Generative Pre-Training (2019): Paper is authored by OpenAI on GPT. [\[paper\]](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)
* Cramming: Training a Language Model on a Single GPU in One Day (2022): Paper focus on a way too increase the performance by using minimum computing power. [\[paper\]](https://arxiv.org/abs/2212.14034)
* LaMDA: Language Models for Dialog Applications (2022): LaMDA is a family of Transformer-based neural language models by Google. [\[paper\]](https://arxiv.org/abs/2201.08239)
* Training language models to follow instructions with human feedback (2022): Use human feedback to align LLMs. [\[paper\]](https://arxiv.org/abs/2203.02155)
* TurboTransformers: An Efficient GPU Serving System For Transformer Models (PPoPP'21) [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3437801.3441578)
* Fast Distributed Inference Serving for Large Language Models (arXiv'23) [\[paper\]](https://arxiv.org/pdf/2305.05920.pdf)
* An Efficient Sparse Inference Software Accelerator for Transformer-based Language Models on CPUs (arXiv'23) [\[paper\]](https://arxiv.org/abs/2306.16601)
* Accelerating LLM Inference with Staged Speculative Decoding (arXiv'23) [\[paper\]](https://arxiv.org/abs/2308.04623)
* ZeRO: Memory optimizations Toward Training Trillion Parameter Models (SC'20) [\[paper\]](https://ieeexplore.ieee.org/abstract/document/9355301)
* TensorGPT: Efficient Compression of the Embedding Layer in LLMs based on the Tensor-Train Decomposition 2023 [\[Paper\]](https://arxiv.org/abs/2307.00526)

## Community

* [LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/)
* [singularity](https://www.reddit.com/r/singularity/)
* [ChatGPTCoding](https://www.reddit.com/r/ChatGPTCoding/)
* [StableDiffusion](https://www.reddit.com/r/StableDiffusion/)
* [Hugging Face](https://discord.gg/hugging-face-879548962464493619)
* [JanAI](https://discord.gg/WWjdgYw9Fa)
* [oobabooga](https://www.reddit.com/r/Oobabooga/)
* [GPT4](https://www.reddit.com/r/GPT4/)
* [Artificial Intelligence](https://www.reddit.com/r/artificial/)
* [CrewAI](https://discord.com/invite/X4JWnZnxPb)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
