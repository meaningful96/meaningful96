<h1 align="center">Youmin Ko</h1>

<p align="center">
  <strong>Integrated M.S./Ph.D. Student · Artificial Intelligence · Hanyang University</strong><br>
  <a href="https://sites.google.com/view/hyudatalab">Data Mining &amp; Algorithm Laboratory (DMAL)</a>
</p>

<p align="center">
  <a href="https://scholar.google.com/citations?user=hssP614AAAAJ&amp;hl=en">Google Scholar</a> ·
  <a href="https://www.linkedin.com/in/%EC%9C%A0%EB%AF%BC-%EA%B3%A0-92a763252/">LinkedIn</a> ·
  <a href="https://meaningful96.github.io/">Research Blog</a> ·
  <a href="https://huggingface.co/meaningful96">Hugging Face</a> ·
  <a href="mailto:minkk0213@gmail.com">Email</a>
</p>

<p align="center">
  <a href="#research-interests">Research</a> ·
  <a href="#ongoing-projects">Projects</a> ·
  <a href="#research-funding">Funding</a> ·
  <a href="#publications">Publications</a> ·
  <a href="#datasets-and-research-resources">Datasets</a>
</p>

## About Me

I am an integrated M.S./Ph.D. student in the **Department of Artificial Intelligence at Hanyang University** and a member of the **Data Mining & Algorithm Laboratory (DMAL)**. I have been in the program since **September 2022**.

My research focuses on how language models **retrieve, represent, and reason over external knowledge**. Building on my work in retrieval-augmented generation, multi-hop question answering, and knowledge graph reasoning, my current research also spans **tool-using multi-agent systems**, **web-search-based multi-agent systems**, **machine translation**, and **task-oriented multi-turn dialogue**.

I study how models and agents gather evidence, coordinate their actions, and use context to produce grounded responses. My ongoing projects include strategy-guided counseling support and translation grounded in Korean cultural context. My published work also includes applying knowledge graphs and retrieval-augmented generation to clinical risk prediction.

## Research Interests

- **Multi-Agent Systems (MAS)** — Tool-using agents, web-search-based MAS, agent collaboration, and coordinated information gathering for tasks that require multiple reasoning steps.
- **Question Answering & Reasoning** — Knowledge-base QA, open-domain QA, multi-hop QA, and multimodal QA; retrieving and connecting evidence needed to answer complex questions.
- **Retrieval-Augmented Generation** — Cooperation between retrievers and generators, document reranking, retrieval representations, and continuous interfaces that carry retrieval signals into generation.
- **Machine Translation** — Translation with language models, use of linguistic and cultural context, and preserving meaning across languages.
- **Task-Oriented Multi-Turn Dialogue (TOD)** — Dialogue strategy selection, conversational context, and goal-directed interaction, including applications to counseling support.
- **Knowledge Graphs & Representation Learning** — Knowledge graph completion and reasoning, graph structure in language-model training, subgraph sampling, and contrastive learning.
- **Clinical Applications of Knowledge and Retrieval** — Combining medical knowledge graphs, clinical notes, and patient trajectories for clinical risk prediction.

## Ongoing Projects

### Tool-Using and Web-Search-Based Multi-Agent Systems

Research on systems in which multiple agents use tools and web search to gather information and collaborate on multi-step tasks. I am interested in connecting agent cooperation with retrieval and evidence-based reasoning.

### Strategy-Guided Agentic RAG for Real-Time Counseling Support

**July 2026 – June 2027** · **Seoul Business Agency (SBA)**

Research on **task-oriented multi-turn dialogue** and **strategy selection** for a real-time counseling support system. The project combines Agentic RAG with dialogue strategies to support counseling competency development.

**Project title:** 상담 역량 향상을 위한 전략 선택형 Agentic RAG 기반 실시간 상담 지원 AI 시스템 개발  
[Project information](https://sites.google.com/view/hyudatalab/projects)

### Machine Translation Grounded in Korean Cultural Context

**April 2026 – December 2028** · **Korea Creative Content Agency (KOCCA)**

Research on AI translation that accounts for **Korean cultural context**, connecting my interests in language models and contextual reasoning with machine translation.

**Project title:** 한국문화 맥락 기반 인공지능 번역 기술 개발  
[Project information](https://sites.google.com/view/hyudatalab/projects)

## Research Funding
### NRF Research Subsidies for Ph.D. Candidates
**September 2025 – August 2027** · **Principal Investigator**

My doctoral research is supported by the **Basic Science Research Program** through the **National Research Foundation of Korea (NRF)**, funded by the **Ministry of Education**.
- **Program:** [Research Subsidies for Ph.D. Candidates](https://eng.nrf.re.kr/page/5301bb32-ad33-4031-8de1-a8b3275956a2) (박사과정생연구장려금지원사업)
- **Project:** Domain-agnostic question answering with cooperative retrieval-augmented generation, mutual information exchange, and layer-contrastive reranking.

## Publications
### 2026
**ShiftRAG: Bypassing the Textual Bottleneck via Decoupled Learning and Continuous Soft Tokens**  
- **Youmin Ko**, Jihong Jeong, and Hyunjoon Kim  
- **NeurIPS 2026** · Accepted
- Separates retrieval and generation training, then translates question–document embeddings and relevance scores into continuous soft knowledge tokens for the generator.

[Code](https://github.com/meaningful96/ShiftRAG) · [Project Page](https://meaningful96.github.io/ShiftRAG/) · Paper link forthcoming

**Trajectory-Aware Clinical Risk Prediction via Severity-Grounded Knowledge Graphs and Retrieval-Augmented Generation**  
- Kyunghoon Jeon, **Youmin Ko**, Woohwan Jung, and Hyunjoon Kim  
- **KDD 2026** · Proceedings of the 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining V.2
- **TRACER** combines severity-weighted knowledge graph trajectories, clinical notes, and similar patient cases for clinical risk prediction from sparse electronic health records.

[Paper](https://doi.org/10.1145/3770855.3818040) · [arXiv](https://arxiv.org/abs/2607.18270) · [Code](https://github.com/KyunghoonJeon/TRACER)

### 2025

**Cooperative Retrieval-Augmented Generation for Question Answering: Mutual Information Exchange and Ranking by Contrasting Layers**  
- **Youmin Ko**, Sungjong Seo, and Hyunjoon Kim  
- **NeurIPS 2025** · Advances in Neural Information Processing Systems 38
- **CoopRAG** coordinates retrieval and generation through question decomposition and masked reasoning chains. **Ranking by Contrasting Layers (RaLa)** uses differences between retriever layers to rerank evidence for question answering.

[Paper](https://proceedings.neurips.cc/paper_files/paper/2025/hash/daafafb5cf0229f0d1e01db3d72c2942-Abstract-Conference.html) · [arXiv](https://arxiv.org/abs/2512.10422) · [Code](https://github.com/meaningful96/CoopRAG)

**Subgraph-Aware Training of Language Models for Knowledge Graph Completion Using Structure-Aware Contrastive Learning**  
- **Youmin Ko**<sup>*</sup>, Hyemin Yang<sup>*</sup>, Taeuk Kim, and Hyunjoon Kim  
- **WWW 2025** · Proceedings of the ACM Web Conference 2025
- **SATKGC** incorporates graph structure into language-model training through subgraph-aware mini-batching and structure-aware contrastive learning, addressing entity-frequency imbalance and structurally challenging training examples.

[Paper](https://doi.org/10.1145/3696410.3714946) · [arXiv](https://arxiv.org/abs/2407.12703) · [Code](https://github.com/meaningful96/SATKGC)

<sup>*</sup> Equal contribution.

## Datasets and Research Resources

I share research code on GitHub and datasets on [Hugging Face](https://huggingface.co/meaningful96).

| Resource | Purpose | Link |
| --- | --- | --- |
| **ShiftRAG_Emb** | Data for the retrieval / encoder training stage of ShiftRAG. | [Dataset](https://huggingface.co/datasets/meaningful96/ShiftRAG_Emb) |
| **ShiftRAG_Gen** | Data for the generation / decoder training stage of ShiftRAG. | [Dataset](https://huggingface.co/datasets/meaningful96/ShiftRAG_Gen) |
| **CoopRAG** | Preprocessed QA resources for CoopRAG, including question decomposition and reasoning-chain annotations. | [Dataset](https://huggingface.co/datasets/meaningful96/CoopRAG) |

## Research Notes

I write paper reviews and implementation notes on **[Meaningful AI](https://meaningful96.github.io/)**. The blog covers natural language processing, graph learning, language models, multi-agent systems, and practical lessons from implementing research ideas.

Writing these notes helps me connect methods across papers and turn what I read into questions I can investigate through experiments.

## Contact

I welcome research discussions and collaboration on multi-agent systems, retrieval-augmented generation, question answering, machine translation, task-oriented dialogue, and knowledge graphs.

- **Email:** [minkk0213@gmail.com](mailto:minkk0213@gmail.com)
- **LinkedIn:** [Youmin Ko](https://www.linkedin.com/in/%EC%9C%A0%EB%AF%BC-%EA%B3%A0-92a763252/)
- **Google Scholar:** [Publications](https://scholar.google.com/citations?user=hssP614AAAAJ&hl=en)
- **Blog:** [Meaningful AI](https://meaningful96.github.io/)
- **Lab:** [Hanyang Data Mining & Algorithm Laboratory](https://sites.google.com/view/hyudatalab)
