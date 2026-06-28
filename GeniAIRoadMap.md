# Documents — Curated AI & ML Resources

> A curated collection of links (videos, articles, playlists) grouped by topic with one-line summaries. Organized for easy browsing and contribution.

---

## Table of Contents

- [Multimodal RAG / Retrieval-Augmented Generation](#multimodal-rag--retrieval-augmented-generation)
- [Statistical models, embeddings & clustering](#statistical-models-embeddings--clustering)
- [Transformers & attention](#transformers--attention)
- [Reinforcement Learning (RL) & Policy Gradients](#reinforcement-learning-policy-gradient-ppo-rl-for-agents)
- [Fine-tuning, Hugging Face & LLM development](#fine-tuning--hugging-face--llm-development)
- [Agent design, workflows & reasoning](#agent-design-workflows-reasoning--skills)
- [Courses, playlists & compiled resources](#courses-playlists--compiled-resources)
- [Misc / Glossary / Roadmap](#misc--glossary--roadmap)

---

## Multimodal RAG / Retrieval-Augmented Generation (document, image, video RAG)
A collection of tutorials and playlists covering multimodal retrieval-augmented pipelines (PDFs, images, video, audio).

- Multimodal RAG: Chat with PDFs (Images & Tables) [2025] — https://www.youtube.com/watch?v=uLrReyH5cu0
  - A hands-on tutorial demonstrating a multimodal RAG pipeline to query PDFs with text, images, and tables using LangChain/unstructured and LLMs.
- Step By Step Process To Build MultiModal RAG With Langchain (PDF And Images) — https://www.youtube.com/watch?v=BV0YUeam4y8
  - Step-by-step walkthrough for building a multimodal RAG system that ingests PDFs and images with LangChain.
- Build an AI Document (PDF, DOC, XML) Processing Pipeline for RAG | Docling, OCR, Chunking, Images — https://www.youtube.com/watch?v=B5XD-qpL0FU
  - Tutorial showing document ingestion pipeline (OCR, chunking, image handling) for RAG.
- Multi-Modal RAG: Chat with Text and Images in Documents — https://www.youtube.com/watch?v=EwtoG-f1mLk
  - Demonstrates combining text and images inside documents for conversational retrieval.
- VideoRAG: ✈️Advanced Retrieval-Augmented Generation with Videos 📺 — https://www.youtube.com/watch?v=LtcHVLkkxjk
  - Advanced techniques for applying RAG to video content.
- Multimodal RAG: Text, Images, Tables & Audio Pipeline — https://www.youtube.com/watch?v=D5iKsvK7cXg
  - Full multimodal pipeline handling text, images, tables, and audio for retrieval tasks.
- RAG 3.0 Agency (playlist) — https://www.youtube.com/playlist?list=PLgy71-0-2-F14IUR3hh765J16Q-SrHHcq
  - Playlist focused on RAG 3.0 and agent-style architectures for retrieval + generation.

> Note: README previously contained a broken/partial duplicate: "om/playlist?list=PLgy71-0-2-F14IUR3hh765J16Q-SrHHcq" — I've removed the broken fragment here.

---

## Statistical models, embeddings & clustering
- Gaussian Mixture Models Explained — https://medium.com/data-science/gaussian-mixture-models-explained-6986aaf5a95
  - Intuitive explanation of Gaussian Mixture Models and how mixtures of Gaussians model complex data distributions.
- Evaluation of Clustering Algorithms for Information Retrieval — https://leehanchung.github.io/blogs/2020/11/17/Document-Clustering-Evaluation/
  - Discussion of methods to evaluate document clustering quality for information retrieval tasks.

---

## Transformers, attention & positional encoding
- Positional Encoding (Medium) — https://medium.com/@sujangyawali177/positional-encoding-5eaf9471d1e2
  - Explains positional encoding (sine/cosine) for transformers and why token position signals matter.
- The Illustrated Transformer — https://jalammar.github.io/illustrated-transformer/
  - Visual, step-by-step walkthrough of the Transformer architecture: self-attention, multi-head, encoder/decoder.

---

## Reinforcement Learning (Policy Gradient / PPO / RL for agents)
- Policy Gradient in 30 min (video) — https://www.youtube.com/watch?v=26j1Cn8AECs
  - Short primer on policy gradient methods.
- Reinforcement Learning playlist — https://www.youtube.com/playlist?list=PLRYer4Da-4mJfRHI-1EIGNdhLsnwGPlz7
  - Playlist with reinforcement learning concept tutorials.
- A Comprehensive Guide to Proximal Policy Optimization (PPO) in AI — https://medium.com/@oleglatypov/a-comprehensive-guide-to-proximal-policy-optimization-ppo-in-ai-82edab5db200
  - In-depth article about PPO: motivations, math intuition, and practical implementation notes.
- Introduction to Deep Reinforcement Learning · Hugging Face Deep RL Course — https://huggingface.co/learn/deep-rl-course/unit0/introduction
  - Course intro that lays out foundational ideas for practical deep RL training.
- A Taxonomy of RL Environments for LLM Agents — https://leehanchung.github.io/blogs/2026/03/21/rl-environments-for-llm-agents/
  - Structured taxonomy showing how RL environment design shapes what LLM agents can learn.

---

## Fine-tuning · Hugging Face · LLM development
- Hugging Face Tutorial (2024) - Sentiment Analysis, Text Generation, LLM — https://www.youtube.com/watch?v=cWpgaIeF8pU
  - Hands-on Hugging Face tutorial covering sentiment analysis and text generation.
- Fine tuning GPT-2 | Transformers huggingface | conversational chatbot | GPT2LMHeadModel — https://www.youtube.com/watch?v=elUCn_TFdQc
  - Tutorial on fine-tuning GPT-2 for conversational chatbot tasks.
- Build your own LLM chatbot from scratch | End to End Gen AI | Mistral 7B LLM — https://www.youtube.com/watch?v=yISaV2vp-Fk
  - End-to-end walkthrough building an LLM chatbot with a Mistral-style 7B model.

---

## Agent design, workflows, reasoning & skills (blogs)
- Agents Are Workflows — https://leehanchung.github.io/blogs/2025/05/09/agent-is-workflow/
  - Argues that agents should be designed as workflows with explicit state, memory, and incremental reasoning steps.
- MCP is not REST API — https://leehanchung.github.io/blogs/2025/05/17/mcp-is-not-rest-api/
  - Explains why Model Context Protocol (MCP) differs conceptually from REST and common pitfalls.
- Claude Agent Skills: A First Principles Deep Dive — https://leehanchung.github.io/blogs/2025/10/26/claude-skills-deep-dive/
  - Deep-dive analysis of Claude's agent skill/extension model and how prompt-based meta-tools can extend capabilities.
- Reasoning Series, Part 4: Reasoning with Compound AI Systems and Post-Training — https://leehanchung.github.io/blogs/2024/11/22/reasoning-agents-post-training/
  - Strategies to improve model reasoning through post-training approaches and system composition.

---

## Courses, playlists & compiled resources
- ⭐ **[MUST DO]** Machine Learning Theory - Part 1: Introduction — https://mostafa-samir.github.io/ml-theory-pt1/
  - Comprehensive introduction to machine learning theory covering fundamental concepts and foundations.
- An Ultimate Compilation of AI Resources for Mathematics, Machine Learning and Deep Learning (GitHub) — https://github.com/nivu/ai_all_resources
  - Curated repository of learning resources covering math, ML, and deep learning topics for self-study.
- Carnegie Mellon University Deep Learning (YouTube playlist) / CMU Fall 2023 Multimodal Machine Learning (11-777) — https://www.youtube.com/playlist?list=PL-Fhd_vrvisMYs8A5j7sj8YW1wHhoJSmW
  - University lecture playlists for deep learning and multimodal ML course material.

---

## Misc / Glossary / Roadmap
- Machine Learning Glossary | Google for Developers — https://developers.google.com/machine-learning/glossary
  - Definitions and explanations of common machine learning terms for developers.
- The Roadmap to Mastering AI Agent Evaluation — https://machinelearningmastery.com/the-roadmap-to-mastering-ai-agent-evaluation/
  - Guide for evaluating AI agents by inspecting intermediate steps and using structured frameworks.

---

## Notes on coverage & metadata
- Titles/summaries come from a combination of the original README, web metadata, and curated descriptions.
- Several YouTube links used README-provided titles when public metadata could not be fetched automatically.
- I removed an obvious broken/partial duplicate link and grouped every URL by topic for readability.

---

## Contributing
- PRs welcome: add links, correct titles, or improve summaries.
- If you want me to fetch live page titles for YouTube links (to replace README-provided titles), I can do that before committing.

---

_Last updated: 2026-06-28_
