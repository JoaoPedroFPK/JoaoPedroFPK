# João Pedro Ferreira Pereira

**AI Engineer · production LLM agents, retrieval at scale, evaluation and observability**

Porto Alegre, Brazil · [joaopedroferreirapereirakonig@gmail.com](mailto:joaopedroferreirapereirakonig@gmail.com)
[LinkedIn](https://www.linkedin.com/in/jo%C3%A3o-pedro-ferreira-2661561b8/) · [GitHub @JoaoPedroFPK](https://github.com/JoaoPedroFPK)

---

Engineer with four years of professional experience, first in data science and backend engineering and, for the past two years, in AI engineering, delivering cloud-native LLM products. I own the full AI engineering cycle: scoping which problems justify an AI system, building the agentic workflow, measuring it with evaluation frameworks, and operating it with tracing, alerting and incident response. Comfortable in industry, consulting and academia. M.Sc. student at UFRGS researching interpretability of transformer language models.

---

## Experience

**AI Engineering Consultant · Euphrates (founding team)** · Porto Alegre, Brazil · 2025 to present

Part of the founding team of an AI consultancy. Take part in commercial meetings, turn clients' open problems into AI proposals they can act on, present technical approaches to client stakeholders, and then build what is sold. Deliver cloud-native AI systems end to end; representative engagements below.

**Legal AI platform (production).** Co-built a production legal AI assistant for Brazilian lawyers over a retrieval index of tens of millions of case-law vectors, sourced from 60+ courts. Owned the knowledge layer end to end (building, evaluating and operating it), the data platform and CI/CD; co-owned agent orchestration.

- **Agentic workflows:** multi-step, tool-using LangGraph agents with function calling and async LLM execution; multi-provider model routing; context engineering.
- **Guardrails:** human-in-the-loop approval gates, provider fallbacks, prompt-injection hardening, and citation grounding that keeps every generated reference traceable to its source.
- **Retrieval-augmented generation:** index design and binary quantization, multi-tenant search under latency budgets, hybrid dense and lexical retrieval, reranking.
- **Evaluation:** LLM-as-judge framework on Langfuse with rubric and grounding metrics, benchmarks built from production traffic, regression gates on prompt changes, and controlled model experiments with cost tracking.
- **Observability and reliability:** tracing, cost attribution, metrics and alerting; incident response and root-cause analysis; admission control, circuit breakers and typed data contracts.
- **Data platform and delivery:** medallion ingestion pipeline on Spark and serverless embedding orchestration over millions of documents; CI/CD with smoke tests and production approval gates; set team engineering norms on typing, testing and cost.

**E-commerce analytics SaaS.** Built the generative AI layer over a multi-store analytics backend: conversational agents with authenticated tool access to each store's sales and marketing data, and the access-control model behind them.

**Precision agriculture data platform.** Designed and built a microservice pipeline that turns drone flight paths into zones of interest and models multi-sensor satellite and weather data into agronomic metrics.

**AI Engineer · Clinia** (health-tech) · 2024 to 2025

- Helped pivot the product from rule-based chatbots to an LLM-led, agent-style conversational experience for health centers, redesigning the interaction model around tool-using agents.
- Built and shipped the LLM and ML components end to end, from data pipelines through deployment and integration into product features.

**Data Science Consultant · Poatek (now TELUS Digital)** · 2022 to 2024

- Built PII-detection models over sensitive text using embeddings and NER pipelines.
- Delivered backend services and data-intensive applications for international clients as part of distributed global engineering teams.

---

## Education

**M.Sc. in Computer Science** · PPGC, Universidade Federal do Rio Grande do Sul (UFRGS) · 2026 to present

- Research line: Machine Learning, Knowledge Representation and Reasoning. Advisor: Prof. Dr. Bruno Iochins Grisci.
- Focus: interpretability of transformer language models, in particular the geometry of hidden representations across layers and architectures.

**B.Sc. in Computer Science** · UFRGS · 2026

- Thesis: *Cross-Architectural Analysis of Layer-wise Representations in Transformer Language Models on a Word Association Task*. Compared seven transformer architectures to isolate how attention type and positional encoding shape layer-wise semantic geometry; found a consistent non-monotonic depth profile and a large gap between embedding-similarity rankings and generated outputs in causal LMs. Preprint in preparation.

---

## Teaching and mentoring

**Guest lecturer and mentor · Amanhã Tech (Fundo Amanhã, UFRGS)** · retention program for low-income computer science students

- Lecture on AI engineering careers and the path from university to industry; mentor students through their first technical roles.

---

## Technical skills

- **Agentic engineering:** LangGraph, LangChain, tool use and function calling, model routing and multi-provider fallback, structured outputs, human-in-the-loop interrupts, context engineering, prompt management (Langfuse); OpenAI, Anthropic, Gemini, Cohere APIs
- **Retrieval and RAG:** Qdrant (HNSW, binary quantization, tenant indexes, alias swaps), hybrid BM25 and dense search, reranking, chunking strategy, embedding pipelines
- **Evaluation and guardrails:** LLM-as-judge rubrics, grounding detectors, prompt-injection hardening, Langfuse datasets and experiments, regression gates in CI, A/B designs with noise-floor controls, cost ledgers
- **Observability and SRE:** Langfuse tracing, CloudWatch metrics and alarms, Slack alerting, runbooks and incident write-ups, circuit breakers, admission control, capacity planning
- **Data engineering:** Apache Spark, EMR Serverless, Athena and Glue, S3 medallion pipelines, Step Functions, Lambda, BigQuery, DynamoDB, MongoDB, PostgreSQL; geospatial processing (Rasterio, GeoPandas)
- **Cloud and delivery:** AWS (ECS and Fargate, EC2, S3, Lambda, Step Functions, CodePipeline, CloudFormation, CDK, CloudWatch), GCP (Cloud Run, App Engine, Cloud Functions, BigQuery), Docker, GitHub Actions, mypy and ruff
- **Languages and ML:** Python (primary), TypeScript, SQL, Bash, C#; PyTorch, Hugging Face Transformers

---

## Languages

Portuguese (native) · English (fluent) · Spanish (intermediate) · Italian (intermediate)
