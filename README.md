<svg width="100%" viewBox="0 0 960 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Moksh Buddhadev — AI/ML Engineer">
  <defs>
    <linearGradient id="bar" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#4338CA"/>
      <stop offset="100%" stop-color="#818CF8"/>
    </linearGradient>
  </defs>
  <rect x="0" y="0" width="960" height="220" rx="14" fill="#07070C"/>
  <g stroke="#312E81" stroke-width="1.2" fill="none">
    <line x1="690" y1="55" x2="750" y2="35"/>
    <line x1="750" y1="35" x2="815" y2="85"/>
    <line x1="815" y1="85" x2="755" y2="125"/>
    <line x1="755" y1="125" x2="695" y2="145"/>
    <line x1="815" y1="85" x2="860" y2="145"/>
    <line x1="860" y1="145" x2="815" y2="180"/>
    <line x1="695" y1="145" x2="690" y2="55"/>
  </g>
  <g>
    <circle cx="690" cy="55" r="5" fill="#818CF8"/>
    <circle cx="750" cy="35" r="4" fill="#6366F1"/>
    <circle cx="815" cy="85" r="6" fill="#A5B4FC"/>
    <circle cx="755" cy="125" r="4" fill="#6366F1"/>
    <circle cx="695" cy="145" r="5" fill="#818CF8"/>
    <circle cx="860" cy="145" r="4" fill="#6366F1"/>
    <circle cx="815" cy="180" r="5" fill="#A5B4FC"/>
  </g>
  <text x="48" y="92" font-family="Consolas, Menlo, monospace" font-size="38" font-weight="700" fill="#F5F5F7">MOKSH BUDDHADEV</text>
  <text x="48" y="126" font-family="Consolas, Menlo, monospace" font-size="15" fill="#A5B4FC">AI/ML Engineer — Retrieval Systems &amp; LLM Infrastructure</text>
  <text x="48" y="156" font-family="Consolas, Menlo, monospace" font-size="12" fill="#6B7280">B.Tech CS, Manipal University Jaipur — 2027</text>
  <rect x="0" y="214" width="960" height="6" fill="url(#bar)"/>
</svg>

<div align="right"><sub><i>a running log, not a highlight reel</i></sub></div>

<br/>

### 01 · INGEST

I'm a third-year CS student working in the gap between "the model runs in a notebook" and "the system holds up when someone else's data hits it." Most of what I build sits somewhere in the retrieval → generation pipeline — the ingestion, the chunking decisions, the part where a demo either survives contact with messy documents or quietly falls apart.

I care more about whether a system fails predictably than whether it demos well.

<br/>

### 02 · EMBED

| | |
|---|---|
| **Languages** | Python, C++ |
| **ML / AI** | PyTorch, TensorFlow, scikit-learn, Sentence-Transformers, FAISS |
| **Backend** | FastAPI, Streamlit, PostgreSQL |
| **Infra** | Docker, Qdrant, Ollama, Git |

<br/>

### 03 · RETRIEVE

**[ReguLens-AI](https://github.com/MokshBuddhadev/regulens-ai)**
End-to-end RAG system for regulatory and financial document Q&A. Ingest → chunk → embed → retrieve → generate, with FAISS handling retrieval and Groq serving inference behind a FastAPI backend.
`python` `fastapi` `faiss` `rag`

**[NLP Chatbot + Emotion Detection](https://github.com/MokshBuddhadev/nlp-chatbot-emotion-system)**
Dialogue system that classifies sentiment in real time and adjusts response generation accordingly, instead of treating tone as static.
`python` `nlp` `emotion-ai`

**[S&P 500 Volatility Regime Analysis](https://github.com/MokshBuddhadev/sp500-volatility-regime-analysis)**
Time-series modeling of regime-switching volatility behavior in the S&P 500 — the market doesn't move under one model, so the analysis doesn't assume one.
`python` `jupyter` `time-series`

**[FRL for D2D Digital Twin Edge Networks](https://github.com/MokshBuddhadev/FRL-Based-Resource-Allocation-for-D2D-Aided-Digital-Twin-Edge-Networks-in-6G-Industrial-IoT)**
Federated Reinforcement Learning applied to resource allocation across device-to-device links in a 6G industrial IoT digital twin setup.
`frl` `6g` `research`

<details>
<summary><b>Also in the repo list</b></summary>
<br/>

**[Sentiment Analysis Mini Project](https://github.com/MokshBuddhadev/sentiment-analysis-mini-project)** — a smaller, earlier pass at text classification: preprocessing and evaluation fundamentals.

</details>

<br/>

### 04 · EVALUATE

| status | in progress |
|---|---|
| `building` | RAG evaluation & observability tooling — Next.js, FastAPI, Qdrant, Ollama |
| `learning` | ML fundamentals from first principles: vectorized Python → statistics → core algorithms |
| `searching` | AI/ML engineering internships, 2026 |

<br/>

### 05 · SERVE

open to AI/ML internships and anything touching RAG, LLM infra, or evaluation systems.

→ [linkedin.com/in/mokshbuddhadev12](https://linkedin.com/in/mokshbuddhadev12)
→ [mokshbuddhadev@gmail.com](mailto:mokshbuddhadev@gmail.com)

<br/>

<svg width="130" height="24" viewBox="0 0 130 24" xmlns="http://www.w3.org/2000/svg">
  <line x1="10" y1="12" x2="65" y2="12" stroke="#6366F1" stroke-width="1.5"/>
  <line x1="65" y1="12" x2="120" y2="12" stroke="#312E81" stroke-width="1.5"/>
  <circle cx="10" cy="12" r="4" fill="#818CF8"/>
  <circle cx="65" cy="12" r="4" fill="#6366F1"/>
  <circle cx="120" cy="12" r="4" fill="#A5B4FC"/>
</svg>

<sub>no external service calls on this page — nothing above depends on an API staying up.</sub>
