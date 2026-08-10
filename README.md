# TOP AI APIs

**A collective list of cloud AI APIs with an ongoing free tier.**



Please star this repo.
Build AI applications without paying for API usage.

> **Important:** “Free forever” means the provider currently offers a recurring/free tier rather than a one-time promotional credit. Providers can change pricing or discontinue free tiers, so always verify the provider's current pricing page before deploying.

---

## Contents

* [LLM / Text Generation](#llm--text-generation)
* [AI Model Routers](#ai-model-routers)
* [Vision / Image Understanding](#vision--image-understanding)
* [Image Generation](#image-generation)
* [Speech-to-Text](#speech-to-text)
* [Text-to-Speech](#text-to-speech)
* [Embeddings](#embeddings)
* [Reranking / Semantic Search](#reranking--semantic-search)
* [OCR / Document AI](#ocr--document-ai)
* [Translation](#translation)
* [Search / Web Research](#search--web-research)
* [RAG / Web Extraction](#rag--web-extraction)
* [Moderation / Safety](#moderation--safety)
* [Face / Image Analysis](#face--image-analysis)
* [Video / Media Analysis](#video--media-analysis)
* [Audio / Music](#audio--music)
* [AI Coding](#ai-coding)
* [ML Inference / Model Hosting](#ml-inference--model-hosting)
* [AI Platforms / Cloud](#ai-platforms--cloud)
* [Specialized AI APIs](#specialized-ai-apis)
* [Free vs Trial](#free-vs-trial)

---

# Legend

| Field            | Meaning                                        |
| ---------------- | ---------------------------------------------- |
| **API**          | Provider/service                               |
| **What it does** | Main capability                                |
| **Free tier**    | Ongoing free allocation/access                 |
| **Auth**         | API key, OAuth, or other authentication        |
| **Cloud**        | Hosted API; no local GPU required              |
| **Status**       | 🟢 Ongoing free tier / 🟡 verify current terms |

---

# LLM / Text Generation

|  # | API                                  | What it does                       | Free access                            | Auth         |
| -: | ------------------------------------ | ---------------------------------- | -------------------------------------- | ------------ |
|  1 | **Google Gemini API**                | Gemini text, reasoning, multimodal | 🟢 Free tier                           | API key      |
|  2 | **Groq**                             | Very fast LLM inference            | 🟢 Free plan                           | API key      |
|  3 | **Mistral AI**                       | Mistral language models            | 🟢 Free mode                           | API key      |
|  4 | **Cerebras**                         | High-speed LLM inference           | 🟢 Free tier                           | API key      |
|  5 | **NVIDIA NIM**                       | Hosted NVIDIA/open models          | 🟢 Free endpoints                      | API key      |
|  6 | **Cloudflare Workers AI**            | Serverless model inference         | 🟢 10,000 Neurons/day                  | API token    |
|  7 | **GitHub Models**                    | Multiple commercial/open models    | 🟢 Rate-limited free use               | GitHub token |
|  8 | **Cohere**                           | Command language models            | 🟢 Free developer access               | API key      |
|  9 | **OpenRouter**                       | Multi-provider model API           | 🟢 Free models                         | API key      |
| 10 | **Hugging Face Inference Providers** | Open-model inference               | 🟢 Monthly free credits                | API token    |
| 11 | **Z.AI / Zhipu AI**                  | GLM models                         | 🟢 Free models/tier where available    | API key      |
| 12 | **Puter AI**                         | Browser/cloud AI access            | 🟢 Free access                         | Varies       |
| 13 | **AIML API**                         | Unified model API                  | 🟡 Free tier availability varies       | API key      |
| 14 | **Hyperbolic**                       | Open-model inference               | 🟢 Free/community access where offered | API key      |
| 15 | **SambaNova Cloud**                  | Fast open-model inference          | 🟢 Free access where offered           | API key      |
| 16 | **SiliconFlow**                      | Open-model inference               | 🟢 Free models/tier where offered      | API key      |
| 17 | **Novita AI**                        | LLM and multimodal APIs            | 🟡 Free allowance varies               | API key      |
| 18 | **Pollinations**                     | Open AI generation APIs            | 🟢 Free public endpoints               | API          |
| 19 | **Featherless AI**                   | Serverless open models             | 🟡 Free access varies                  | API key      |
| 20 | **FriendliAI**                       | LLM inference                      | 🟢 Developer/free access where offered | API key      |

**Note:** Groq publishes explicit RPM/RPD/TPM-style limits; Mistral explicitly documents its Free mode and says no credit card is required; Cloudflare currently documents 10,000 free Workers AI Neurons per day.

---

# AI Model Routers

These are especially useful because one API can expose multiple models.

|  # | API                                  | What it does                           | Free access                               |
| -: | ------------------------------------ | -------------------------------------- | ----------------------------------------- |
| 21 | **OpenRouter**                       | Multi-model LLM routing                | 🟢 Free models                            |
| 22 | **Hugging Face Inference Providers** | Routes to multiple inference providers | 🟢 Monthly free credits                   |
| 23 | **GitHub Models**                    | Unified model catalog/API              | 🟢 Free rate-limited usage                |
| 24 | **Puter AI**                         | Multiple AI models through one API     | 🟢 Free access                            |
| 25 | **LiteLLM Proxy providers**          | Unified OpenAI-compatible interface    | 🟢 Software is free; provider cost varies |
| 26 | **AI/ML API**                        | Multi-model API                        | 🟡 Free allocation varies                 |
| 27 | **Cloudflare Workers AI**            | Unified model catalog                  | 🟢 Daily allocation                       |
| 28 | **NVIDIA NIM**                       | NVIDIA-hosted model endpoints          | 🟢 Free endpoints                         |
| 29 | **SiliconFlow**                      | Open-model gateway                     | 🟢 Selected free models                   |
| 30 | **Hyperbolic**                       | Open-model gateway                     | 🟢 Selected free access                   |

OpenRouter currently has a dedicated free-model router that automatically selects from its available free models.

---

# Vision / Image Understanding

|  # | API                              | Capability                | Free access                              |
| -: | -------------------------------- | ------------------------- | ---------------------------------------- |
| 31 | **Google Gemini Vision**         | Image understanding       | 🟢 Gemini free tier                      |
| 32 | **Groq Vision**                  | Vision-language models    | 🟢 Free plan                             |
| 33 | **Mistral Vision**               | Image understanding       | 🟢 Free mode                             |
| 34 | **Cohere Vision-capable models** | Multimodal understanding  | 🟢 Where included                        |
| 35 | **Hugging Face Vision Models**   | VLM inference             | 🟢 Monthly credits                       |
| 36 | **Cloudflare Workers AI Vision** | Hosted vision models      | 🟢 Daily allocation                      |
| 37 | **NVIDIA NIM Vision**            | Vision-language models    | 🟢 Selected endpoints                    |
| 38 | **OpenRouter Vision**            | Multi-provider vision     | 🟢 Free models                           |
| 39 | **GitHub Models Vision**         | Multimodal models         | 🟢 Rate-limited                          |
| 40 | **Roboflow**                     | Computer vision inference | 🟢 Developer/free plan                   |
| 41 | **Clarifai**                     | Image/video recognition   | 🟢 Developer tier                        |
| 42 | **Google Cloud Vision**          | OCR/object detection      | 🟢 Free monthly quota                    |
| 43 | **Azure AI Vision**              | Computer vision           | 🟢 Free quota where available            |
| 44 | **AWS Rekognition**              | Image/video analysis      | 🟡 Free quota depends on service/account |
| 45 | **Imagga**                       | Image recognition/tagging | 🟢 Free developer tier                   |

---

# Image Generation

|  # | API                                    | Capability                 | Free access                        |
| -: | -------------------------------------- | -------------------------- | ---------------------------------- |
| 46 | **Pollinations**                       | Image generation           | 🟢 Free public API                 |
| 47 | **Hugging Face Image Models**          | FLUX/SD/open models        | 🟢 Monthly credits                 |
| 48 | **Cloudflare Workers AI Image Models** | FLUX and other models      | 🟢 Daily allocation                |
| 49 | **Google Gemini image-capable models** | Image generation/editing   | 🟢 Selected free-tier access       |
| 50 | **OpenRouter image models**            | Image-capable models       | 🟢 Selected free models            |
| 51 | **NVIDIA image models**                | Hosted image models        | 🟢 Selected endpoints              |
| 52 | **Leonardo AI API**                    | Image generation           | 🟡 Free allowance may be available |
| 53 | **Ideogram API**                       | Image generation           | 🟡 Verify current developer tier   |
| 54 | **Stability AI**                       | Stable Diffusion ecosystem | 🟡 Verify current free allocation  |
| 55 | **Craiyon API**                        | Image generation           | 🟡 Free access may be limited      |

**Strict-list recommendation:** keep #46–51 in the permanent-free section and put the others in a “verify” section because free image-generation APIs change particularly often.

---

# Speech-to-Text

|  # | API                               | Capability                | Free access                               |
| -: | --------------------------------- | ------------------------- | ----------------------------------------- |
| 56 | **Google Cloud Speech-to-Text**   | Speech recognition        | 🟢 Free monthly quota                     |
| 57 | **Groq Whisper**                  | Very fast transcription   | 🟢 Free plan                              |
| 58 | **Hugging Face Whisper**          | Whisper inference         | 🟢 Monthly credits                        |
| 59 | **Cloudflare Workers AI Whisper** | Hosted speech recognition | 🟢 Daily allocation                       |
| 60 | **NVIDIA NIM speech models**      | Hosted speech models      | 🟢 Selected endpoints                     |
| 61 | **Deepgram**                      | Speech recognition        | 🟡 Trial credits; verify ongoing tier     |
| 62 | **AssemblyAI**                    | Transcription/analysis    | 🟡 Trial/free allowance varies            |
| 63 | **Gladia**                        | Speech recognition        | 🟢 Developer/free access where offered    |
| 64 | **Speechmatics**                  | Speech recognition        | 🟡 Free developer access varies           |
| 65 | **Soniox**                        | Speech-to-text            | 🟢 Free developer allowance where offered |

---

# Text-to-Speech

|  # | API                                  | Capability               | Free access                      |
| -: | ------------------------------------ | ------------------------ | -------------------------------- |
| 66 | **Google Cloud Text-to-Speech**      | Neural TTS               | 🟢 Free monthly quota            |
| 67 | **ElevenLabs**                       | High-quality TTS         | 🟢 Recurring free plan           |
| 68 | **Hugging Face TTS models**          | Open-model TTS           | 🟢 Monthly credits               |
| 69 | **Cloudflare Workers AI TTS models** | Hosted TTS               | 🟢 Daily allocation              |
| 70 | **Kokoro via hosted providers**      | Open TTS model           | 🟢 Selected free endpoints       |
| 71 | **PlayHT**                           | Voice synthesis          | 🟡 Verify current developer tier |
| 72 | **Cartesia**                         | Low-latency voice        | 🟡 Free access varies            |
| 73 | **Murf**                             | Voice generation         | 🟡 Free access varies            |
| 74 | **Resemble AI**                      | Voice generation/cloning | 🟡 Free access varies            |
| 75 | **LOVO**                             | AI voice                 | 🟡 Free access varies            |

---

# Embeddings

|  # | API                                  | Capability              | Free access                  |
| -: | ------------------------------------ | ----------------------- | ---------------------------- |
| 76 | **Google Gemini Embeddings**         | Text embeddings         | 🟢 Free-tier access          |
| 77 | **Cohere Embed**                     | Multilingual embeddings | 🟢 Developer/free tier       |
| 78 | **Hugging Face Embeddings**          | Open embedding models   | 🟢 Monthly credits           |
| 79 | **Jina AI Embeddings**               | Retrieval embeddings    | 🟢 Free developer allocation |
| 80 | **Nomic Embed API**                  | Open embeddings         | 🟢 Free tier where available |
| 81 | **Voyage AI**                        | High-quality embeddings | 🟡 Free allowance varies     |
| 82 | **Cloudflare Workers AI Embeddings** | BGE/Qwen embeddings     | 🟢 Daily allocation          |
| 83 | **NVIDIA NIM Embeddings**            | Hosted embeddings       | 🟢 Selected endpoints        |
| 84 | **Mistral Embeddings**               | Text embeddings         | 🟢 Free mode                 |
| 85 | **SiliconFlow Embeddings**           | Open embedding models   | 🟢 Selected free models      |

---

# Reranking / Semantic Search

|  # | API                        | Capability                 | Free access                      |
| -: | -------------------------- | -------------------------- | -------------------------------- |
| 86 | **Cohere Rerank**          | Document reranking         | 🟢 Developer tier                |
| 87 | **Jina AI Reranker**       | Neural reranking           | 🟢 Free allowance                |
| 88 | **Hugging Face Rerankers** | Open reranking models      | 🟢 Monthly credits               |
| 89 | **NVIDIA NIM Reranking**   | Hosted rerankers           | 🟢 Selected endpoints            |
| 90 | **Cloudflare Workers AI**  | Reranking/embedding models | 🟢 Daily allocation              |
| 91 | **Voyage AI Rerank**       | Search reranking           | 🟡 Verify current free allowance |

---

# OCR / Document AI

|   # | API                                | Capability                | Free access                   |
| --: | ---------------------------------- | ------------------------- | ----------------------------- |
|  92 | **Google Cloud Vision OCR**        | OCR                       | 🟢 Monthly quota              |
|  93 | **Google Document AI**             | Document extraction       | 🟢 Limited free quota         |
|  94 | **Azure AI Document Intelligence** | OCR/forms                 | 🟢 Free tier where available  |
|  95 | **OCR.Space**                      | Online OCR API            | 🟢 Free API tier              |
|  96 | **Nanonets**                       | OCR/document processing   | 🟡 Free allowance varies      |
|  97 | **Mindee**                         | Document extraction       | 🟢 Developer/free access      |
|  98 | **Veryfi**                         | Receipt/invoice OCR       | 🟡 Developer allowance varies |
|  99 | **Hugging Face OCR models**        | OCR inference             | 🟢 Monthly credits            |
| 100 | **Roboflow**                       | Vision/document workflows | 🟢 Developer tier             |

---

# Translation

|   # | API                                    | Capability               | Free access              |
| --: | -------------------------------------- | ------------------------ | ------------------------ |
| 101 | **DeepL API Free**                     | High-quality translation | 🟢 Monthly free quota    |
| 102 | **Google Cloud Translation**           | Machine translation      | 🟢 Monthly quota         |
| 103 | **Microsoft Translator**               | Translation              | 🟢 Free monthly tier     |
| 104 | **LibreTranslate**                     | Open translation API     | 🟢 Free/public instances |
| 105 | **MyMemory**                           | Translation memory       | 🟢 Free usage            |
| 106 | **Hugging Face translation models**    | NMT models               | 🟢 Monthly credits       |
| 107 | **Mistral translation-capable models** | LLM translation          | 🟢 Free mode             |
| 108 | **Gemini translation**                 | LLM translation          | 🟢 Free tier             |
| 109 | **Cohere multilingual models**         | Multilingual generation  | 🟢 Free developer tier   |
| 110 | **Jina AI multilingual models**        | Multilingual retrieval   | 🟢 Free allocation       |

---

# Search / Web Research

|   # | API                      | Capability                 | Free access                 |
| --: | ------------------------ | -------------------------- | --------------------------- |
| 111 | **Brave Search API**     | Web search                 | 🟢 Free monthly allowance   |
| 112 | **Tavily**               | AI-agent search            | 🟢 Free monthly credits     |
| 113 | **Exa**                  | Neural/web search          | 🟢 Free developer allowance |
| 114 | **Jina Reader**          | Web-to-markdown extraction | 🟢 Free public access       |
| 115 | **SearXNG-hosted APIs**  | Metasearch                 | 🟢 Public instances vary    |
| 116 | **Wikipedia API**        | Knowledge retrieval        | 🟢 Free                     |
| 117 | **Wikidata API**         | Structured knowledge       | 🟢 Free                     |
| 118 | **MediaWiki API**        | Wikipedia/wiki data        | 🟢 Free                     |
| 119 | **Crossref API**         | Academic metadata          | 🟢 Free                     |
| 120 | **OpenAlex API**         | Research metadata          | 🟢 Free                     |
| 121 | **Semantic Scholar API** | Academic search            | 🟢 Free quota               |
| 122 | **arXiv API**            | Research papers            | 🟢 Free                     |
| 123 | **Europe PMC API**       | Biomedical literature      | 🟢 Free                     |
| 124 | **PubMed/NCBI APIs**     | Medical literature         | 🟢 Free                     |
| 125 | **Open Library API**     | Book metadata              | 🟢 Free                     |

---

# RAG / Web Extraction

|   # | API                           | Capability                | Free access                             |
| --: | ----------------------------- | ------------------------- | --------------------------------------- |
| 126 | **Jina Reader**               | URL → clean text/Markdown | 🟢 Free                                 |
| 127 | **Firecrawl**                 | Web crawling/extraction   | 🟡 Free allowance; verify current terms |
| 128 | **Crawl4AI hosted services**  | AI web crawling           | 🟢 Depends on provider                  |
| 129 | **Unstructured**              | Document parsing          | 🟢 Developer access varies              |
| 130 | **LlamaIndex cloud services** | RAG infrastructure        | 🟡 Free tier varies                     |
| 131 | **Pinecone**                  | Vector database/RAG       | 🟢 Free tier                            |
| 132 | **Weaviate Cloud**            | Vector search             | 🟢 Free tier where available            |
| 133 | **Qdrant Cloud**              | Vector database           | 🟢 Free tier                            |
| 134 | **Zilliz Cloud**              | Milvus vector DB          | 🟢 Free tier                            |
| 135 | **Chroma Cloud**              | Vector database           | 🟡 Verify current free tier             |

---

# Moderation / Safety

|   # | API                                  | Capability               | Free access                                |
| --: | ------------------------------------ | ------------------------ | ------------------------------------------ |
| 136 | **Google Gemini safety classifiers** | Content safety           | 🟢 Included with eligible API usage        |
| 137 | **Google Cloud Natural Language**    | Text analysis            | 🟢 Free quota                              |
| 138 | **Azure AI Content Safety**          | Content moderation       | 🟢 Free quota where available              |
| 139 | **OpenAI Moderation**                | Text/image moderation    | 🟢 Moderation endpoint availability varies |
| 140 | **Perspective API**                  | Toxicity detection       | 🟢 Free/rate limited                       |
| 141 | **Hugging Face moderation models**   | Toxicity/safety          | 🟢 Monthly credits                         |
| 142 | **Clarifai moderation models**       | Image/text moderation    | 🟢 Developer tier                          |
| 143 | **Cloudflare AI safety models**      | AI safety/classification | 🟢 Daily allocation                        |

---

# Face / Image Analysis

|   # | API                              | Capability                   | Free access                            |
| --: | -------------------------------- | ---------------------------- | -------------------------------------- |
| 144 | **Google Cloud Vision**          | Face/image analysis          | 🟢 Monthly quota                       |
| 145 | **Azure AI Face**                | Face detection/analysis      | 🟢 Limited free access where available |
| 146 | **Clarifai**                     | Image recognition            | 🟢 Developer tier                      |
| 147 | **Roboflow**                     | Object detection             | 🟢 Developer tier                      |
| 148 | **Imagga**                       | Image tagging/categorization | 🟢 Free developer tier                 |
| 149 | **Hugging Face vision models**   | Classification/detection     | 🟢 Monthly credits                     |
| 150 | **Cloudflare Workers AI vision** | Vision models                | 🟢 Daily allocation                    |

---

# Video / Media Analysis

|   # | API                                 | Capability                     | Free access                        |
| --: | ----------------------------------- | ------------------------------ | ---------------------------------- |
| 151 | **Google Gemini**                   | Video understanding            | 🟢 Free-tier models                |
| 152 | **Google Cloud Video Intelligence** | Video analysis                 | 🟢 Free quota                      |
| 153 | **Azure AI Video Indexer**          | Video understanding            | 🟡 Free allocation varies          |
| 154 | **Cloudflare Workers AI**           | Video-capable models/workflows | 🟢 Daily allocation                |
| 155 | **Hugging Face video models**       | Video understanding            | 🟢 Monthly credits                 |
| 156 | **Twelve Labs**                     | Video understanding/search     | 🟡 Free developer allowance varies |

---

# Audio / Music

|   # | API                                    | Capability                      | Free access                      |
| --: | -------------------------------------- | ------------------------------- | -------------------------------- |
| 157 | **Google Gemini**                      | Audio understanding             | 🟢 Free tier                     |
| 158 | **Groq Whisper**                       | Audio transcription             | 🟢 Free plan                     |
| 159 | **Hugging Face audio models**          | Audio classification/generation | 🟢 Monthly credits               |
| 160 | **Cloudflare Workers AI audio models** | Speech/audio inference          | 🟢 Daily allocation              |
| 161 | **Google Cloud Speech**                | Speech recognition              | 🟢 Monthly quota                 |
| 162 | **Google Cloud TTS**                   | Speech synthesis                | 🟢 Monthly quota                 |
| 163 | **ElevenLabs**                         | TTS/voice                       | 🟢 Free plan                     |
| 164 | **Murf API**                           | Voice generation                | 🟡 Verify current free tier      |
| 165 | **AssemblyAI**                         | Audio intelligence              | 🟡 Verify current free allowance |

---

# AI Coding

|   # | API                          | Capability                | Free access                 |
| --: | ---------------------------- | ------------------------- | --------------------------- |
| 166 | **GitHub Models**            | Coding LLMs               | 🟢 Free rate-limited API    |
| 167 | **Groq**                     | Fast coding inference     | 🟢 Free plan                |
| 168 | **Google Gemini**            | Code generation/reasoning | 🟢 Free tier                |
| 169 | **Mistral Codestral**        | Code generation           | 🟢 Free mode where eligible |
| 170 | **Cerebras**                 | High-speed coding models  | 🟢 Free tier                |
| 171 | **Hugging Face Code Models** | StarCoder/Qwen/etc.       | 🟢 Monthly credits          |
| 172 | **NVIDIA NIM coding models** | Hosted code models        | 🟢 Selected endpoints       |
| 173 | **OpenRouter coding models** | Multiple coding models    | 🟢 Free models              |
| 174 | **Cohere**                   | Code/text generation      | 🟢 Developer tier           |
| 175 | **Cloudflare Workers AI**    | Hosted code models        | 🟢 Daily allocation         |

---

# ML Inference / Model Hosting

|   # | API                        | Capability               | Free access                  |
| --: | -------------------------- | ------------------------ | ---------------------------- |
| 176 | **Hugging Face Inference** | Hosted open models       | 🟢 Monthly credits           |
| 177 | **Cloudflare Workers AI**  | Serverless inference     | 🟢 10,000 Neurons/day        |
| 178 | **NVIDIA NIM**             | GPU model serving        | 🟢 Selected free endpoints   |
| 179 | **Cerebras**               | Hosted inference         | 🟢 Free tier                 |
| 180 | **Groq**                   | Hosted inference         | 🟢 Free plan                 |
| 181 | **Mistral AI**             | Hosted inference         | 🟢 Free mode                 |
| 182 | **Google Gemini API**      | Hosted inference         | 🟢 Free tier                 |
| 183 | **GitHub Models**          | Hosted model catalog     | 🟢 Free rate limits          |
| 184 | **OpenRouter**             | Multi-provider inference | 🟢 Free models               |
| 185 | **Hyperbolic**             | Open-model inference     | 🟢 Selected free access      |
| 186 | **SiliconFlow**            | Open-model inference     | 🟢 Selected free access      |
| 187 | **SambaNova Cloud**        | Open-model inference     | 🟢 Free access where offered |
| 188 | **Z.AI**                   | GLM inference            | 🟢 Selected free access      |

---

# AI Platforms / Cloud

|   # | Platform                  | AI capability                    | Free access                                                    |
| --: | ------------------------- | -------------------------------- | -------------------------------------------------------------- |
| 189 | **Cloudflare Workers AI** | Edge AI inference                | 🟢 10K Neurons/day                                             |
| 190 | **Google AI Studio**      | Gemini API/playground            | 🟢 Free tier                                                   |
| 191 | **Hugging Face**          | Models/inference/datasets        | 🟢 Free account + monthly credits                              |
| 192 | **GitHub Models**         | Model experimentation/API        | 🟢 Free rate-limited use                                       |
| 193 | **NVIDIA NIM**            | Model inference                  | 🟢 Selected endpoints                                          |
| 194 | **Google Colab**          | Cloud ML notebooks               | 🟢 Free compute availability                                   |
| 195 | **Kaggle**                | ML notebooks/GPUs                | 🟢 Free quotas                                                 |
| 196 | **Cloudflare AI Gateway** | AI request routing/observability | 🟢 Free features/limits                                        |
| 197 | **Firebase AI Logic**     | Gemini integration               | 🟢 Free quotas where applicable                                |
| 198 | **Google Vertex AI**      | Cloud AI platform                | 🟡 Some services have free quotas; verify billing requirements |

---

# Specialized AI APIs

|   # | API                  | Use case                 | Free access          |
| --: | -------------------- | ------------------------ | -------------------- |
| 199 | **Roboflow**         | Computer vision          | 🟢 Developer plan    |
| 200 | **Clarifai**         | AI workflows/vision/NLP  | 🟢 Developer plan    |
| 201 | **Mindee**           | Document extraction      | 🟢 Developer access  |
| 202 | **Imagga**           | Image analysis           | 🟢 Free tier         |
| 203 | **Perspective API**  | Toxicity analysis        | 🟢 Free              |
| 204 | **OCR.Space**        | OCR                      | 🟢 Free API          |
| 205 | **DeepL API**        | Translation              | 🟢 Free monthly tier |
| 206 | **Brave Search API** | Search                   | 🟢 Free allowance    |
| 207 | **Tavily**           | Agent search             | 🟢 Free allowance    |
| 208 | **Exa**              | AI search                | 🟢 Free allowance    |
| 209 | **Jina AI**          | Search/reader/embeddings | 🟢 Free allocation   |
| 210 | **Pinecone**         | Vector search            | 🟢 Free tier         |
| 211 | **Qdrant Cloud**     | Vector search            | 🟢 Free tier         |
| 212 | **Weaviate Cloud**   | Vector database          | 🟢 Free tier         |
| 213 | **Zilliz Cloud**     | Vector database          | 🟢 Free tier         |
| 214 | **Semantic Scholar** | Academic search          | 🟢 Free API quota    |
| 215 | **OpenAlex**         | Academic metadata        | 🟢 Free              |
| 216 | **Crossref**         | Scholarly metadata       | 🟢 Free              |
| 217 | **Europe PMC**       | Biomedical search        | 🟢 Free              |
| 218 | **NCBI/PubMed**      | Biomedical literature    | 🟢 Free              |
| 219 | **Wikidata**         | Knowledge graph          | 🟢 Free              |
| 220 | **Wikipedia**        | Knowledge/search         | 🟢 Free              |

---

# Best 20 to Start With

If your goal is to build AI applications for **$0/month**, these are the providers I would test first:

| Rank | Provider                         | Best for                      |
| ---: | -------------------------------- | ----------------------------- |
| 🥇 1 | **Google Gemini API**            | Overall                       |
| 🥈 2 | **Groq**                         | Speed                         |
| 🥉 3 | **Mistral AI**                   | Large free allowance / coding |
|    4 | **Cerebras**                     | Very high inference speed     |
|    5 | **NVIDIA NIM**                   | Model variety                 |
|    6 | **Cloudflare Workers AI**        | Serverless AI                 |
|    7 | **GitHub Models**                | Developers                    |
|    8 | **OpenRouter**                   | Many models                   |
|    9 | **Hugging Face**                 | Open-source models            |
|   10 | **Cohere**                       | RAG/search                    |
|   11 | **Z.AI**                         | GLM models                    |
|   12 | **Jina AI**                      | Search + embeddings           |
|   13 | **Brave Search API**             | Web search                    |
|   14 | **Tavily**                       | AI-agent search               |
|   15 | **Exa**                          | Neural search                 |
|   16 | **DeepL API**                    | Translation                   |
|   17 | **ElevenLabs**                   | TTS                           |
|   18 | **Google Cloud Vision**          | OCR/vision                    |
|   19 | **Roboflow**                     | Computer vision               |
|   20 | **Pinecone / Qdrant / Weaviate** | RAG/vector search             |

---

# Recommended Free AI Stack

A strong $0/month developer stack can be built by combining several independent free quotas:

```text
                    YOUR AI APP
                        │
              ┌─────────┴─────────┐
              │   AI ROUTER       │
              │                   │
              │   OpenRouter      │
              │   / LiteLLM       │
              └─────────┬─────────┘
                        │
        ┌───────────────┼────────────────┐
        │               │                │
      Gemini           Groq           Mistral
        │               │                │
     General          Speed          Coding/LLM
        │               │                │
        └───────────────┼────────────────┘
                        │
                 Fallback models
                        │
              ┌─────────┴─────────┐
              │                   │
           Cerebras             NVIDIA
              │                   │
          High speed          More models


       RAG / SEARCH
            │
     ┌──────┼─────────┐
     │      │         │
    Jina   Tavily    Exa
     │      │         │
     └──────┼─────────┘
            │
        Vector DB
            │
     ┌──────┼─────────┐
     │      │         │
 Qdrant  Pinecone  Weaviate


       MULTIMODAL
            │
     ┌──────┼────────────┐
     │      │            │
   Gemini  HF       Cloudflare
     │      │            │
   Vision  OSS       Vision/AI


        VOICE
          │
     ┌────┴─────┐
     │          │
   Groq      ElevenLabs
  Whisper       TTS


        OCR
          │
     ┌────┴─────┐
     │          │
 Google       OCR.Space
 Vision
```

---

# Free Forever vs Free Trial

## 🟢 Keep in the main list

These have an ongoing free allocation/free mode rather than merely giving a signup balance:

* Google Gemini API
* Groq
* Mistral Free mode
* Cloudflare Workers AI
* GitHub Models
* OpenRouter free models
* Hugging Face monthly credits
* Cohere developer access
* NVIDIA NIM selected free endpoints
* Cerebras free tier
* DeepL API Free
* ElevenLabs free plan
* Brave Search free allowance
* Tavily free allowance
* Exa free allowance
* Jina AI free allocation
* Pinecone free tier
* Qdrant free tier
* Weaviate free tier
* Roboflow developer/free tier
* Clarifai developer tier
* OCR.Space free tier
* Google Cloud Vision free quota
* Google Cloud Translation free quota
* Google Cloud TTS free quota
* Google Cloud Speech free quota

## 🔴 Do NOT label these "free forever"

These are commonly advertised as free but are primarily **trial/promotional credit** or otherwise shouldn't be presented as permanently free without qualification:

* Together AI signup credits
* Fireworks signup credits
* Replicate signup credits
* DeepInfra promotional credits
* Baseten trial credits
* Nebius promotional credits
* Stability promotional credits
* Other "$5 free", "$10 free", "$200 free" signup offers

A $5 signup balance is **not the same thing as a permanent free API tier**.

---

# Verification Notes

Free API limits change frequently. For example:

* **Groq** publishes model-specific RPM, RPD, TPM and other limits.
* **Mistral** currently says Free mode is enabled by default and does not require a credit card.
* **Cloudflare Workers AI** currently provides 10,000 Neurons/day on the Free plan, resetting daily.
* **GitHub Models** provides rate-limited free usage to GitHub accounts, with paid usage disabled unless explicitly enabled.
* **Hugging Face** currently gives free users $0.10/month in Inference Provider credits; the amount is subject to change.
* **OpenRouter** currently maintains a collection of free models and a free-model router, but explicitly notes that the available free models can change.

---

# Contribution Rules

A provider should be added to the **Free Forever** section only if:

1. It has an actual API.
2. The API can be called from code.
3. There is an ongoing free allocation or free model.
4. The free allocation is not merely a one-time signup credit.
5. No paid subscription is required to consume the free allocation.
6. The provider publishes documentation or pricing information.
7. The free access is currently available.
8. Rate limits are clearly stated when available.

### Do not submit

* Expired promotions
* One-time trial credits
* "Free" chat websites with no API
* APIs that require payment before any free usage
* Scraped/unofficial APIs
* Stolen API keys
* Shared public API keys
* Services whose only free access is a temporary promotion

---

# Disclaimer

**Free does not mean unlimited.**

Every provider can impose rate limits, quotas, model restrictions, fair-use rules, geographic restrictions, account verification, or other conditions.

"Free forever" should therefore be interpreted as:

> **An ongoing free tier currently offered by the provider, rather than a temporary signup promotion.**

Always check the provider's official pricing and rate-limit documentation before using an API in production.

---

## Total

**220 entries/categories listed above**

**Core permanent/ongoing-free candidates:** 25+
**Specialized free APIs:** 100+
**Free infrastructure/model platforms:** 20+
**Search/RAG/data APIs:** 30+

The directory intentionally contains some cross-category entries because the same API can legitimately provide multiple AI capabilities.
