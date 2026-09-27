<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=venom&height=200&color=0:2563EB%2C100:06B6D4&text=Uday%20Bhan&fontSize=55&animation=fadeIn&fontAlignY=35&desc=Senior%20Applied%20AI%20Engineer&descSize=20&descAlignY=55&fontColor=ffffff">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=venom&height=200&color=0:2563EB%2C100:06B6D4&text=Uday%20Bhan&fontSize=55&animation=fadeIn&fontAlignY=35&desc=Senior%20Applied%20AI%20Engineer&descSize=20&descAlignY=55&fontColor=1f2328">
  <img width="100%" alt="Uday Bhan, Senior Applied AI Engineer" src="https://capsule-render.vercel.app/api?type=venom&height=200&color=0:2563EB%2C100:06B6D4&text=Uday%20Bhan&fontSize=55&animation=fadeIn&fontAlignY=35&desc=Senior%20Applied%20AI%20Engineer&descSize=20&descAlignY=55&fontColor=1f2328">
</picture>

<p align="center">
  <a href="https://github.com/udaybhan05"><img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=20&duration=3000&pause=1000&color=2563EB&center=true&vCenter=true&repeat=true&width=520&lines=Senior+Applied+AI+Engineer;Multi-Agent+AI+on+Google+ADK+%C2%B7+MCP+%C2%B7+A2A;Enterprise+RAG+%26+GraphRAG;Document+AI+%26+Ingestion+Benchmarking;LLM+Evals+%26+Observability;Shipping+on+AWS+%C2%B7+GCP+%C2%B7+Azure;7%2B+Years+in+ML+%26+NLP" alt="Senior Applied AI Engineer · Multi-Agent AI · Enterprise RAG · Document AI · LLM Evals" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/7%2B_years-ML_%26_NLP-2563EB?style=flat-square" alt="7+ years in ML"/>
  &nbsp;
  <img src="https://img.shields.io/badge/cloud-AWS_%C2%B7_GCP_%C2%B7_Azure-0891B2?style=flat-square" alt="AWS · GCP · Azure"/>
  &nbsp;
  <a href="https://github.com/udaybhan05?tab=followers"><img src="https://img.shields.io/github/followers/udaybhan05?style=flat-square&logo=github&label=followers&color=2563EB" alt="GitHub followers"/></a>
</p>

<p align="center">
  <sub>Production agentic AI &nbsp;·&nbsp; RAG &amp; GraphRAG &nbsp;·&nbsp; Document AI &nbsp;·&nbsp; LLM evaluation &nbsp;·&nbsp; research to rollout</sub>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/h-about-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/h-about-light.svg">
  <img alt="About" src="assets/h-about-light.svg" width="100%">
</picture>

I'm a **Senior Applied AI Engineer with 7+ years in ML**. My foundation is data science and transformer-era NLP; for the last ~2 years I've focused on **production agentic and RAG systems, end to end**: multi-agent platforms on Google ADK (MCP · A2A · Skills), enterprise RAG with hybrid retrieval and knowledge graphs, document-AI ingestion, and LLM evaluation stacks on Phoenix, Langfuse and MLflow.

I own the full lifecycle, from research and data design to evaluation, cost tuning and production rollout on **AWS, GCP and Azure**, and I've ramped engineers on RAG and agent workflows along the way.

| Focus area | Working with |
|:-----------|:-------------|
| **Agentic AI & orchestration** | <code>Google ADK</code> <code>A2A</code> <code>MCP</code> <code>Skills</code> <code>LangGraph</code> <code>CrewAI</code> <code>AutoGen</code> <code>DSPy</code> |
| **RAG & retrieval** | <code>Hybrid (dense + BM25)</code> <code>Cross-encoder reranking</code> <code>GraphRAG</code> <code>Contextual retrieval</code> <code>HyDE</code> <code>RAPTOR</code> <code>Self / Corrective RAG</code> <code>NL2SQL</code> |
| **Document AI** | <code>Azure Document Intelligence</code> <code>Docling</code> <code>Unstructured</code> <code>LlamaParse</code> <code>Marker</code> <code>AWS Textract</code> |
| **Evaluation & observability** | <code>RAGAs</code> <code>DeepEval</code> <code>TruLens</code> <code>LLM-as-judge</code> <code>Phoenix</code> <code>Langfuse</code> <code>OpenTelemetry</code> <code>MLflow</code> |
| **LLMOps & fine-tuning** | <code>LoRA / QLoRA / DoRA</code> <code>DPO / RLHF</code> <code>INT4 / INT8</code> <code>vLLM</code> <code>Triton</code> <code>TensorRT-LLM</code> <code>Guardrails</code> |
| **Chatbots & connectors** | <code>Conversational RAG</code> <code>Streaming</code> <code>Agent memory</code> <code>MCP tool routing</code> <code>Structured outputs</code> |
| **Classical ML & data** | <code>NLP</code> <code>Computer vision</code> <code>Time series</code> <code>Spark</code> <code>Databricks</code> <code>Kafka</code> <code>Airflow</code> |
| **Cloud & deployment** | <code>AWS SageMaker / Lambda</code> <code>GCP Vertex AI</code> <code>Azure DevOps / App Service</code> <code>Docker</code> <code>Kubernetes</code> |

### In production

- **Document-ingestion benchmarking:** benchmarked Azure Document Intelligence, Docling, Unstructured, LlamaParse, Marker and PyMuPDF across regulatory PDFs, DOCX, scanned images and tables/forms. A hybrid per-document-class strategy became the default ingestion policy, cutting parsing cost while keeping table fidelity and lifting retrieval quality.
- **Agentic platform on Google ADK:** chose ADK for Skills, A2A cross-agent delegation and observability maturity; shipped selective MCP tool routing for enterprise system access, structured-output contracts gating tool calls, and typed chart payloads that turned text answers into interactive analytics.
- **Launch-gate eval harness:** hybrid retrieval with metadata-aware filtering and per-corpus reranking, scored with Precision@K, Recall@K, MRR and NDCG plus LLM-as-judge with position, verbosity and self-preference bias audits. Adopted as the default pre-production launch gate.
- **Observability & rollouts:** end-to-end traces with Phoenix + OpenTelemetry (agent spans, tool-call attribution, token cost), MLflow experiment tracking, model registry and prompt versioning, and blue-green rollouts gated by automated evals on AWS with Azure DevOps.

### Now building

| Project | What it is |
|:--------|:-----------|
| [Retrieval Agent (Thinky)](https://github.com/udaybhan05/Agentic_Graph_Rag_Fusion_30_may) | Agentic retrieval service: LangGraph + Weaviate/Neo4j hybrid search fused with RRF, multi-model via LiteLLM |
| [RAG_Mastery](https://github.com/udaybhan05/RAG_Mastery) | A collection of RAG techniques, from basic to advanced |

### Tracking the frontier

Where AI engineering is heading, and where I'm hands-on:

| Frontier | My work there |
|:---------|:--------------|
| **Multi-agent systems:** agents that delegate to agents | <ul><li>Multi-agent platform on Google ADK with A2A cross-agent delegation</li><li>Two-tier LangGraph agent with a parallel judge in <a href="https://github.com/udaybhan05/Agentic_Graph_Rag_Fusion_30_may">Thinky</a></li></ul> |
| **Agent skills & MCP:** portable capabilities and one protocol for tools | <ul><li>ADK Skills plus selective MCP tool routing into enterprise systems</li><li>Structured-output contracts that gate tool calls in regulated settings</li></ul> |
| **GraphRAG & advanced retrieval** | <ul><li>Knowledge-graph + vector retrieval (Neo4j + Weaviate, RRF fusion)</li><li>Contextual retrieval, HyDE, RAPTOR, Self-RAG and Corrective RAG</li></ul> |
| **Document AI:** turning messy documents into reliable context | <ul><li>Six-parser benchmark and per-document-class ingestion policy</li></ul> |
| **Context engineering:** memory and state over longer prompts | <ul><li>Agent memory, context compression, prompt and semantic caching</li></ul> |
| **Evals & reliability:** proving answers are grounded | <ul><li>Launch-gate evals with bias-audited LLM-as-judge</li><li>Phoenix + OpenTelemetry tracing, trace replay, cost views</li></ul> |

### The journey

| Stage | Era | What I worked on |
|:------|:----|:-----------------|
| Foundation | Data science & classical ML | Time series, topic modelling, anomaly detection, A/B testing, causal inference, BI |
| Deepening | Transformer-era NLP & deep learning | BERT / RoBERTa, computer vision, fine-tuning, Spark-scale data |
| Last ~2 years | Production agentic AI & RAG | Multi-agent platforms, GraphRAG, document AI, eval harnesses, cloud rollouts |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/h-featured-work-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/h-featured-work-light.svg">
  <img alt="Featured work" src="assets/h-featured-work-light.svg" width="100%">
</picture>

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/udaybhan05/Agentic_Graph_Rag_Fusion_30_may">Retrieval Agent (Thinky)</a></h3>
<ul>
<li>Two-tier LangGraph agent: cheap gate model, strong agent model, parallel judge for grounding</li>
<li>Hybrid Weaviate + Neo4j retrieval fused with RRF, plus web, SQL and Cypher tools</li>
</ul>
<p><code>LangGraph</code> <code>Weaviate</code> <code>Neo4j</code> <code>LiteLLM</code></p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/udaybhan05/Agentic_Graph_Rag_Fusion_30_may">Evals &amp; observability layer</a></h3>
<ul>
<li>Arize Phoenix tracing on every node, online hallucination and faithfulness scoring</li>
<li>Per-surface golden suites and Vertex AI pointwise metrics</li>
</ul>
<p><code>Phoenix</code> <code>LLM-as-judge</code> <code>Vertex AI</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/udaybhan05/RAG_Mastery">RAG Mastery</a></h3>
<ul>
<li>RAG techniques end to end, from naive retrieval to advanced patterns</li>
<li>Each technique as a runnable, documented example</li>
</ul>
<p><code>Python</code> <code>RAG</code> <code>Vector DB</code></p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/udaybhan05/RAG_Bot">RAG Bot</a></h3>
<ul>
<li>Conversational chatbot answering questions over a CSV dataset</li>
<li>Retrieval-grounded answers instead of guesses</li>
</ul>
<p><code>Python</code> <code>RAG</code> <code>Chatbot</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/udaybhan05/LeetCodeRepo">LeetCode Solutions</a></h3>
<ul>
<li>My solutions to LeetCode problems</li>
<li>Arrays, strings, trees, graphs, dynamic programming</li>
</ul>
<p><code>Java</code> <code>DSA</code></p>
</td>
<td width="50%" valign="top">
<h3>Cloud deployments</h3>
<ul>
<li>Production rollouts on AWS (SageMaker, Lambda, EC2, S3), GCP (Vertex AI, Dataflow) and Azure</li>
<li>Blue-green releases gated by automated evals, containerised with Docker and Kubernetes</li>
</ul>
<p><code>AWS</code> <code>GCP</code> <code>Azure</code> <code>Kubernetes</code></p>
</td>
</tr>
</table>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/h-open-source-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/h-open-source-light.svg">
  <img alt="Open source" src="assets/h-open-source-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://github.com/pulls?q=is%3Apr+author%3Audaybhan05+is%3Amerged"><img src="https://img.shields.io/badge/Merged_PRs-view_all-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="My merged pull requests"/></a>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/h-tech-stack-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/h-tech-stack-light.svg">
  <img alt="Tech stack" src="assets/h-tech-stack-light.svg" width="100%">
</picture>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=python%2Cjava%2Cscala%2Cr%2Cts%2Creact%2Cfastapi%2Cflask&theme=dark">
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=python%2Cjava%2Cscala%2Cr%2Cts%2Creact%2Cfastapi%2Cflask&theme=light">
    <img src="https://skillicons.dev/icons?i=python%2Cjava%2Cscala%2Cr%2Cts%2Creact%2Cfastapi%2Cflask&theme=light" alt=""/>
  </picture>
  <br/>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=pytorch%2Ctensorflow%2Csklearn%2Caws%2Cazure%2Cgcp%2Cdocker%2Ckubernetes&theme=dark">
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=pytorch%2Ctensorflow%2Csklearn%2Caws%2Cazure%2Cgcp%2Cdocker%2Ckubernetes&theme=light">
    <img src="https://skillicons.dev/icons?i=pytorch%2Ctensorflow%2Csklearn%2Caws%2Cazure%2Cgcp%2Cdocker%2Ckubernetes&theme=light" alt=""/>
  </picture>
  <br/>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=kafka%2Cpostgres%2Cgit%2Cgithub%2Clinux&theme=dark">
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=kafka%2Cpostgres%2Cgit%2Cgithub%2Clinux&theme=light">
    <img src="https://skillicons.dev/icons?i=kafka%2Cpostgres%2Cgit%2Cgithub%2Clinux&theme=light" alt=""/>
  </picture>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OpenAI-2563EB?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Anthropic_Claude-1D4ED8?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Gemini-0891B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
  <img src="https://img.shields.io/badge/Meta_Llama-06B6D4?style=for-the-badge&logo=meta&logoColor=white"/>
  <img src="https://img.shields.io/badge/Mistral-2563EB?style=for-the-badge&logo=mistralai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hugging_Face-1D4ED8?style=for-the-badge&logo=huggingface&logoColor=white"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Google_ADK-2563EB?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/A2A_Protocol-1D4ED8?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/MCP-0891B2?style=for-the-badge&logo=modelcontextprotocol&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-06B6D4?style=for-the-badge&logo=langgraph&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-2563EB?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/LlamaIndex-1D4ED8?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/CrewAI-0891B2?style=for-the-badge&logo=crewai&logoColor=white"/>
  <img src="https://img.shields.io/badge/AutoGen-06B6D4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/DSPy-2563EB?style=for-the-badge"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Neo4j-2563EB?style=for-the-badge&logo=neo4j&logoColor=white"/>
  <img src="https://img.shields.io/badge/Weaviate-1D4ED8?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Qdrant-0891B2?style=for-the-badge&logo=qdrant&logoColor=white"/>
  <img src="https://img.shields.io/badge/Milvus-06B6D4?style=for-the-badge&logo=milvus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pinecone-2563EB?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/FAISS-1D4ED8?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/pgvector-0891B2?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OpenSearch-06B6D4?style=for-the-badge&logo=opensearch&logoColor=white"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Azure_Document_Intelligence-2563EB?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docling-1D4ED8?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Unstructured-0891B2?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LlamaParse-06B6D4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AWS_Textract-2563EB?style=for-the-badge&logo=amazonwebservices&logoColor=white"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Arize_Phoenix-2563EB?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Langfuse-1D4ED8?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LangSmith-0891B2?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAGAs-06B6D4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/DeepEval-2563EB?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/MLflow-1D4ED8?style=for-the-badge&logo=mlflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Weights_%26_Biases-0891B2?style=for-the-badge&logo=weightsandbiases&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenTelemetry-06B6D4?style=for-the-badge&logo=opentelemetry&logoColor=white"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/vLLM-2563EB?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Triton-1D4ED8?style=for-the-badge&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorRT--LLM-0891B2?style=for-the-badge&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/LoRA%2FQLoRA-06B6D4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Apache_Spark-2563EB?style=for-the-badge&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Databricks-1D4ED8?style=for-the-badge&logo=databricks&logoColor=white"/>
  <img src="https://img.shields.io/badge/Airflow-0891B2?style=for-the-badge&logo=apacheairflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power_BI-06B6D4?style=for-the-badge&logo=powerbi&logoColor=white"/>
</p>

<details>
<summary><b>Full tech breakdown</b></summary>
<br/>

```
Agents             Google ADK · A2A · MCP · Skills · LangGraph · LangSmith · LangChain · LlamaIndex · CrewAI · AutoGen · DSPy · Haystack
Agent patterns     Multi-agent design · tool routing · structured outputs · function calling · context compression · memory · trace replay
RAG                Hybrid (dense + BM25) · cross-encoder reranking · GraphRAG · contextual retrieval · HyDE · RAPTOR · Self-RAG · Corrective RAG
                   NL2SQL · semantic caching · metadata engineering · query rewriting / decomposition
Document AI        Azure Document Intelligence · Docling · Unstructured · LlamaParse · Marker · PyMuPDF · AWS Textract
Vector / graph DBs FAISS · Pinecone · Weaviate · Qdrant · Milvus · pgvector · OpenSearch · Neo4j
Evaluation         RAGAs · TruLens · DeepEval · LLM-as-judge (position / verbosity / self-preference audits) · golden & synthetic sets
Observability      Phoenix (Arize) · Langfuse · OpenTelemetry (GenAI) · MLflow · W&B
LLMOps             LoRA · QLoRA · DoRA · DPO · RLHF · INT4 / INT8 · vLLM · Triton · TensorRT-LLM · continuous batching
                   semantic + prompt caching · model routing · guardrails (NeMo, LlamaGuard, Presidio)
Classical ML       Deep learning · NLP · computer vision · time series (SARIMA, LSTM) · topic modelling · SHAP · A/B testing · causal inference
Data & BI          Spark · Hadoop · Kafka · Databricks · Dask · Airflow · Kedro · Tableau · Power BI · Looker · Metabase
Cloud              AWS (SageMaker, Lambda, EC2, S3) · GCP (Vertex AI, Dataflow) · Azure (Databricks, DevOps, App Service) · Docker · Kubernetes
Models             GPT-4 / 4o · Gemini · Claude · Llama 3.1 · Mistral · RoBERTa · BERT · ViT
Languages          Python · PySpark · SQL · Scala · R · TypeScript · Java
Frameworks         FastAPI · Flask · Streamlit · React · Recharts
```

</details>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/h-activity-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/h-activity-light.svg">
  <img alt="Activity" src="assets/h-activity-light.svg" width="100%">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/udaybhan05/udaybhan05/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/udaybhan05/udaybhan05/output/github-snake.svg">
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/udaybhan05/udaybhan05/output/github-snake.svg" width="100%">
</picture>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=udaybhan05&hide_border=true&theme=dark&background=00000000&ring=60A5FA&fire=06B6D4&currStreakLabel=60A5FA">
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=udaybhan05&hide_border=true&background=00000000&ring=2563EB&fire=0891B2&currStreakLabel=2563EB">
  <img alt="GitHub streak" src="https://streak-stats.demolab.com?user=udaybhan05&hide_border=true&background=00000000&ring=2563EB&fire=0891B2&currStreakLabel=2563EB" width="70%">
</picture>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/divider-light.svg">
  <img alt="" src="assets/divider-light.svg" width="100%">
</picture>

<p align="center">
  <b>Building agentic AI, RAG or document-AI systems? Let's talk.</b>
  <br/><br/>
  <a href="https://github.com/udaybhan05"><img src="https://img.shields.io/badge/GitHub-udaybhan05-2563EB?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
</p>
