# 🌐 Mapping Web3: A Multi-Stage NLP Framework
**Decoding Trust, Sentiment, and Intent in Decentralized Communities**

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97-Transformers-orange)](https://huggingface.co/)
[![Scopus Q1](https://img.shields.io/badge/Research-Scopus%20Q1-gold)](https://link-to-your-paper.com)

## 📌 Project Overview
Web3 communities move at high velocity across fragmented platforms like X, Reddit, and Discord. Understanding the health of these communities requires more than simple sentiment analysis; it requires understanding context.

This project introduces a **Three-Stage AI Framework** that utilizes fine-tuned Transformer models (**CryptoBERT** and **RoBERTa**) to categorize discourse into Domain, Tone, and Intent. This allows stakeholders to identify trust signals and community shifts in real-time.

---

## 🛠️ The Three-Stage Architecture

To capture the true nuance of Web3 discussions, the framework processes user-generated content sequentially through three distinct analytical layers.

![Web3 Decision Analytics Framework](visuals/pipeline_framework.png)

### 1. Stage 1: Web3 Industry Domain (Multi-label Classification)
* **Goal:** Identify which specific sectors of the ecosystem are being discussed.
* **Target Categories:** * Core Infrastructure and Protocols
  * Decentralized Finance (DeFi) and Financial Applications
  * Digital Assets and Collectibles (NFTs)
  * Decentralized Applications (DApps) and Gaming
  * DAO and Governance Mechanisms

### 2. Stage 2: Emotional Tone in Public Discourse (Multi-label Classification)
* **Goal:** Detect nuanced, non-binary emotional layers within the discussion.
* **Target Categories:** Optimism, Skepticism, Frustration, Curiosity, and Concern.

### 3. Stage 3: Communicative Intent in Public Discourse (Multi-Class Classification)
* **Goal:** Determine the ultimate practical purpose behind the message.
* **Target Categories:** Informational, Expressive, or Promotional.

---

## 📈 Model Performance and Results
I benchmarked **CryptoBERT** against **RoBERTa** to determine which architecture handles blockchain-specific vernacular more effectively.

| Stage | Best Model | F1-Score | Key Insight |
| :--- | :--- | :--- | :--- |
| **Domain** | RoBERTa | **0.81 ± 0.0048** | Domain-specific pre-training significantly improved NFT and DeFi classification. |
| **Tone** | RoBERTa | **0.80 ± 0.0043** | Successfully identified institutional trust versus retail hype. |
| **Intent** | CryptoBERT | **0.82 ± 0.0108** | High accuracy in distinguishing Governance from Socializing or Promotion. |

---

🎓 Academic Rigor
This project is the technical portfolio implementation of research published in a Q1 Scopus-indexed journal.

Paper Title: A decision analytics framework for interpreting trust signals in decentralized digital communities

Scientific Repo: For raw datasets, stratified splits, and training logs, visit the Journal Reproducibility Repository.

🧰 Tech Stack
Language: Python

Libraries: HuggingFace Transformers, PyTorch, Pandas, Scikit-Learn

Models: CryptoBERT, RoBERTa-base

Data Sources: X (Twitter), Reddit, YouTube, ENS DAO Forum
