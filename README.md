# Agent Platform Samples

A curated list of code samples and tutorials for building agents on **Gemini Enterprise Agent Platform** (previously Vertex AI).

![AgentPlatform](AgentPlatform.png)

### Watch the Intro Video

[![What is Gemini Enterprise Agent Platform?](https://img.youtube.com/vi/j8qW5poBkEU/maxresdefault.jpg)](https://goo.gle/agent-platform-video)

## 🛠️ [Build](https://docs.cloud.google.com/gemini-enterprise-agent-platform/build) - Turning code into agents

*   **[Agent Development Kit (ADK)](https://adk.dev)** - Open-source framework for building agents.
    *   **[Agents CLI](https://goo.gle/agents-cli)** - Command-line tool for agent development.
*   **[Agent Studio](https://docs.cloud.google.com/gemini-enterprise-agent-platform/build/agent-studio)** - Low-code visual agent builder.
*   **[Agent Garden](https://docs.cloud.google.com/gemini-enterprise-agent-platform/build/agent-garden)** - Discover and deploy pre-built agents.
*   **[Models](https://docs.cloud.google.com/gemini-enterprise-agent-platform/models)** - Foundation models powering agent intelligence.
    *   **[Gemini API](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/getting-started/intro_gemini_3_1_pro.ipynb)** - Access Google's foundation models.
    *   **[Model Garden](https://docs.cloud.google.com/gemini-enterprise-agent-platform/models/model-garden/explore-models)** - Discover foundation and open-weight models.
    *   **[Model Inference](https://docs.cloud.google.com/vertex-ai/docs/predictions/overview)** - Enterprise-grade model serving infrastructure.
    *   **[Managed Training](https://docs.cloud.google.com/vertex-ai/docs/training-overview)** - Fully managed model fine-tuning.
*   **Tools, data, and other agents** - Connect and extend agent capabilities.
    *   **[Agent2Agent Protocol (A2A)](https://a2a-protocol.org)** - Secure multi-agent coordination standard.
    *   **[Grounding](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/grounding/intro-grounding-gemini.ipynb)** - Connect models to real-world data.
    *   **[RAG Engine](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/rag-engine/intro_rag_engine.ipynb)** - Retrieve relevant enterprise information.
    *   **[Model Context Protocol (MCP)](https://modelcontextprotocol.io/)** - Standard protocol for external tools.
    *   **[Vector Search](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/embeddings/vector-search-2-intro.ipynb)** - Managed vector embedding database.
    *   **[Agent Search (previously Vertex AI Search)](https://docs.cloud.google.com/generative-ai-app-builder/docs/try-enterprise-search)** - Custom search engines for your own data.
    *   **[Agent-to-UI (A2UI)](https://a2ui.org)** - Dynamic user interface generation protocol.
    *   **[Agent Payments Protocol (AP2)](https://ap2-protocol.org)** - Secure automated payment execution protocol.
    *   **[Universal Commerce Protocol (UCP)](https://ucp.dev/)** - Standard for managing e-commerce operations.

## 📈 [Scale](https://docs.cloud.google.com/gemini-enterprise-agent-platform/scale) - Reliability over time

*   **[Agent Runtime (previously Agent Engine)](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/agent-engine/intro_agent_engine.ipynb)** - Managed platform for serving agents.
*   **[Agent Sessions](https://docs.cloud.google.com/gemini-enterprise-agent-platform/scale/sessions)** - Track interactions across multiple conversations.
*   **[Agent Memory Bank](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/agents/agent_engine/memory_bank/get_started_with_memory_bank.ipynb)** - Persistent long-term agent memory.
*   **[Agent Sandbox](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/agents/agent_engine/tutorial_get_started_with_code_execution.ipynb)** - Secure environment for code execution and computer use.

## 🔐 [Govern](https://docs.cloud.google.com/gemini-enterprise-agent-platform/govern) - Trust as a feature

*   **[Agent Gateway](https://docs.cloud.google.com/gemini-enterprise-agent-platform/govern/gateways/agent-gateway-overview)** - Central control, authentication, and rate-limiting. (Private Preview)
*   **[Agent Identity](https://docs.cloud.google.com/iam/docs/principals-overview#agent-identity)** - Unique credentials for agents.  
*   **[Agent Policies](https://docs.cloud.google.com/gemini-enterprise-agent-platform/govern/policies/overview)** - IAM Policies for agents. (Private Preview)
*   **[Agent Registry](https://docs.cloud.google.com/agent-registry/overview)** - Single source of approved tools and agents.
*   **[Model Armor](https://docs.cloud.google.com/model-armor/overview)** - Prevents prompt injections and leaks.

## ⚙️ [Optimize](https://docs.cloud.google.com/gemini-enterprise-agent-platform/optimize) - Evaluation and enhancement

*   **[Agent Evaluation](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/evaluation/create_agent_and_run_evaluation.ipynb)** - Automatically test complex agent interactions.
*   **[Agent Simulation]()** - Generate synthetic interactions for stress-testing.
*   **[Agent Observability](https://docs.cloud.google.com/gemini-enterprise-agent-platform/optimize/observability/overview)** - Forensic visibility into agent reasoning.
*   **[Agent Optimizer]()** - Automate improvements based on failures.

## Developer's guides
*  **[Onboarding Guide](https://goo.gle/agent-platform-onboard)** - A quick-start guide accelerates your onboarding to Agent Platform

## 🪜 Other Tutorials & Notebooks

*   [Gemini](https://docs.cloud.google.com/vertex-ai/generative-ai/docs/models)
    *   [Intro to Gemini 3.1 Pro](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/getting-started/intro_gemini_3_1_pro.ipynb)
    *   [Intro to Gemini 3 Flash](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/getting-started/intro_gemini_3_flash.ipynb)
    *   [Intro to Gemini 3.1 Flash-Lite](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/getting-started/intro_gemini_3_1_flash_lite.ipynb)
    *   [Intro to Agent Runtime](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/agent-engine/intro_agent_engine.ipynb)
    *   [Intro to Batch Prediction](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/batch-prediction/intro_batch_prediction.ipynb)
    *   [Intro to Code Execution](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/code-execution/intro_code_execution.ipynb)
    *   [Intro to Agentic Vision](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/code-execution/intro_agentic_vision.ipynb)
    *   [Intro to Computer Use](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/computer-use/intro_computer_use.ipynb)
    *   [Intro to Context Caching](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/context-caching/intro_context_caching.ipynb)
    *   [Intro to Evaluation](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/evaluation/quick_start_gen_ai_eval.ipynb)
    *   [Intro to Grounding](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/grounding/intro-grounding-gemini.ipynb)
    *   [Intro to Live API](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/multimodal-live-api/live_api_quickstart.ipynb)
    *   [Intro to LangGraph](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/orchestration/intro_langgraph_gemini.ipynb)
    *   [Intro to Prompt Attacks and Mitigation](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/responsible-ai/gemini_prompt_attacks_mitigation_examples.ipynb)
    *   [Intro to Supervised Fine Tuning](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/tuning/sft_gemini_summarization.ipynb)
    *   [Intro to Document Processing](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/use-cases/document-processing/document_processing.ipynb)
    *   [Intro to Spatial Understanding](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/use-cases/spatial-understanding/spatial_understanding.ipynb)
    *   [YouTube Video Analysis](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/use-cases/video-analysis/youtube_video_analysis.ipynb)
*   [Image Generation (Nano Banana)](https://docs.cloud.google.com/vertex-ai/generative-ai/docs/models/gemini/3-1-flash-image)
    *   [Gemini 3.1 Flash Image (Nano Banana 2 🍌)](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/getting-started/intro_gemini_3_1_flash_image_gen.ipynb)
    *   [Gemini 3 Pro Image (Nano Banana Pro 🍌)](http://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/getting-started/intro_gemini_3_image_gen.ipynb)
*   [Veo](https://docs.cloud.google.com/vertex-ai/generative-ai/docs/models/veo/3-1-generate)
    *   [Veo 3.1 Video Generation](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/vision/getting-started/veo3_video_generation.ipynb)
    *   [Veo 3.1 Advanced Controls](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/vision/getting-started/veo3_advanced_controls.ipynb)
*   [Lyria](https://docs.cloud.google.com/vertex-ai/generative-ai/docs/models/lyria/lyria-3)
    *   [Lyria 3 Music Generation](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/audio/music/getting-started/lyria3_music_generation.ipynb)
*   [Embeddings](https://docs.cloud.google.com/vertex-ai/generative-ai/docs/embeddings)
    *   [Getting Started with Text Embeddings + Vector Search](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/embeddings/intro-textemb-vectorsearch.ipynb)
    *   [Introduction to Multimodal Embeddings](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/embeddings/intro_multimodal_embeddings.ipynb)
    *   [Introduction to Vertex AI Vector Search 2.0](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/embeddings/vector-search-2-intro.ipynb)
    *   [Combining Semantic & Keyword Search: A Hybrid Search Tutorial](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/embeddings/hybrid-search.ipynb)
*   [Model Garden](https://docs.cloud.google.com/vertex-ai/generative-ai/docs/model-garden/explore-models)
    *   [Intro to Model Garden](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/open-models/get_started_with_model_garden_sdk.ipynb)

---

This is not an officially supported Google product. This project is not
eligible for the [Google Open Source Software Vulnerability Rewards Program](https://bughunters.google.com/open-source-security).
