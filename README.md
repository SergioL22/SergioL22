# Hi, I'm Sergio Lozano 👋

### Software Engineering · Machine Learning · Biomedical AI

I'm a Computer Science master's graduate from **UTRGV (May 2026, GPA 3.80)** with a **B.S. in Biology**. I build AI applications, try to understand the models underneath, and make systems run efficiently—from a transformer trained from scratch to retrieval-backed LLM agents.

My work is Python-first, with Rust, C++, JAX, and SQL alongside. A wet-lab biology background shapes how I work: ask good questions, test assumptions, and report what the evidence actually says.

**Open to software engineering, ML engineering, and data roles. Willing to relocate anywhere.**

[![Portfolio](https://img.shields.io/badge/Portfolio-7ae1c3?style=flat-square&logo=vercel&logoColor=0b1014)](https://sergio-lozano.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sergio-lozano-20021b239)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:sergioa_la@hotmail.com)

## Featured projects

### ⚙️ [Forge — From-scratch LLM training (JAX) + Rust inference](https://github.com/SergioL22/Forge)

A **13.69M-parameter decoder-only transformer** written from scratch in JAX—hand-rolled attention, RoPE, and RMSNorm, no HuggingFace `AutoModel`—trained on TinyStories for 20,000 steps. Inference is reimplemented in **Rust**, numerically verified against the JAX model, then optimized step by step.

- **7.7× faster** than the Python baseline (105.2 vs 13.7 tok/s); KV caching alone is a **5.2×** speedup.
- **INT8 quantization** cuts model size 58% for +0.01% perplexity.
- Optimizations that didn't pay off on this hardware (static batching on CPU) are reported, not hidden.

**Built with:** JAX · Rust · Axum · Python  ·  📊 **[Full benchmark results](https://sergiol22.github.io/Forge/)**

### 🧬 [BioLyra — Agentic Biomedical AI Assistant](https://github.com/SergioL22/BioLyra)

A biomedical assistant that routes each question between conversation, retrieval over approximately **2,500 PubMed abstract chunks**, and live **NCBI Entrez search** for recent topics.

- LangGraph routing; ChromaDB retrieval with BioBERT embeddings.
- **Phi-3.5-mini fine-tuned with QLoRA on PubMedQA** (4-bit NF4, LoRA rank 16), evaluated against the base model with BERTScore.
- Shipped as a **Gradio chat interface** and a **FastAPI endpoint**; runs tracked in Weights & Biases.

**Built with:** Python · PyTorch · LangGraph · ChromaDB · BioBERT · FastAPI · Gradio  ·  🔗 **[Try it live](https://biolyra-orbscaelxwlx7utxth6nue.streamlit.app)** *(may take ~30s to wake up)*

### 📈 [Stock & ETF Analyzer](https://github.com/SergioL22/Crypto-Price-Analyzer)

A research dashboard for U.S. stocks and ETFs—price and volume charts, technical indicators, and watchlists—with a **FastAPI backend**, reproducible data snapshots, and a **prediction journal** that scores forecasts against what actually happened. It grew out of my earlier Crypto Price Analyzer CLI and lives in the same repo.

**Built with:** Python · FastAPI · pandas

### More projects

| Project | Focus | Tools |
| --- | --- | --- |
| 🩺 [Disease Prediction](https://github.com/SergioL22/disease-prediction) | Tuned Logistic Regression vs. Random Forest on the UCI heart disease dataset, served in Streamlit with SHAP explanations | Python, scikit-learn, SHAP, Streamlit |
| 📝 Job Application Pipeline | Scrapes Greenhouse, Lever, and USAJobs postings, scores them against résumé profiles, and tailors applications with the Claude API—only submitting after explicit confirmation | Python, SQLite, Claude API |
| 🎲 [D&D Discord Bot](https://github.com/SergioL22/DND-Discord-Bot) | D&D 5e bot with character sheets, initiative combat, spell tracking, and an AI Dungeon Master with campaign memory | Python, discord.py, OpenAI |
| 🎵 [Spotify Analysis](https://github.com/SergioL22/Spotify-Analysis) | Streamlit dashboard over my own streaming history: top artists, trends, listening heatmap, genre enrichment | Python, pandas, Streamlit |
| 🧩 [Still Sudoku](https://sudokuuuuu-e6684.web.app) | Browser Sudoku built for friends, with real-time Race and Co-op modes and leaderboards | JavaScript, Firebase |

## What I'm working on

- Keeping my **[portfolio](https://sergio-lozano.vercel.app)** current—it has a chat assistant that answers questions about my projects.
- Extending **Forge** and the **Stock & ETF Analyzer**.
- Finishing Ed Donner's **AI Engineer Agentic Track** (OpenAI Agents SDK, LangGraph, CrewAI, MCP, AutoGen), alongside regular algorithms and SQL practice.

## Technical toolkit

| Area | Technologies |
| --- | --- |
| **Languages** | Python, Rust, SQL, C++, JavaScript |
| **Machine learning** | PyTorch, JAX, scikit-learn, Hugging Face |
| **LLM applications** | LangGraph, RAG, QLoRA fine-tuning, ChromaDB, Claude API |
| **Data & analysis** | pandas, NumPy, Matplotlib, Jupyter |
| **Backend & interfaces** | FastAPI, Flask, Gradio, Streamlit, SQLite |
| **Development tools** | Git, Docker, Linux, Weights & Biases |

## Let's connect

I'm interested in building useful software, putting ML models into working applications, and solving problems at the intersection of computing and biology.

**[Portfolio](https://sergio-lozano.vercel.app)** · **[Résumé](https://sergio-lozano.vercel.app/assets/Sergio_Lozano_Resume.pdf)** · **[LinkedIn](https://www.linkedin.com/in/sergio-lozano-20021b239)** · **[Email](mailto:sergioa_la@hotmail.com)**

<details>
<summary>GitHub activity</summary>

[![GitHub Streak](https://streak-stats.demolab.com?user=SergioL22&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D)](https://git.io/streak-stats)

</details>
