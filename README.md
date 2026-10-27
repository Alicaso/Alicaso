<a href="https://stepaudiollm.github.io/step-audio-3-music/"><img src="assets/banner.svg" width="100%" alt="Boyang Wang — Music × Audio × AI. Foundation models, understanding and generation, and agentic reasoning." /></a>

I'm an M.S. Data Science student at **UC San Diego**, graduating in December 2026. My research centers on **music and audio AI**, with two connected directions: **foundation models for understanding and generation**, and **agents that reason with tools and structured knowledge**.

My work spans model training, large-scale data pipelines, controllable generation, and evaluation. Earlier, I studied contrastive representation learning for medical imaging at Lanzhou University.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-475569?style=for-the-badge)](https://www.linkedin.com/in/boyang-wang-199142268/)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-475569?style=for-the-badge)](mailto:wangby76@gmail.com)

---

# 01 · Foundation Models

> **Music & audio understanding and generation**

At **StepFun**, my work spans **music-understanding model development** and **data and inference infrastructure**.

**Music-understanding models:** As a **core contributor**, I help drive **model training, experiments and validation, and evaluation**. My work includes multi-task training across audio, text, and symbolic music, full-parameter fine-tuning with **Megatron**, and comparative evaluation to guide model iteration.

**Data and inference infrastructure:** In parallel, I worked on music data pipelines used by internal services and production music-generation and understanding products. This included annotation workflows across **10M+ tracks**, model serving with **StepCloud and vLLM**, and inference acceleration through **Ray, parallel processing, and CPU/GPU task coordination**.

## StepAudio 3 Music · Controllable Music Generation

**My contribution:** Co-designed music Chain-of-Thought (CoT) data and **ABC notation-based conditioning** for controllable generation. Built supporting data pipelines and collaborated on experiments and validation, connecting symbolic musical structure with audio generation.

[![Paper](https://img.shields.io/badge/Paper-TR-2563EB?style=for-the-badge)](https://arxiv.org/abs/2609.16034)
[![Project](https://img.shields.io/badge/Project-StepAudio_3_Music-0F766E?style=for-the-badge)](https://stepaudiollm.github.io/step-audio-3-music/)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-Demo-D97706?style=for-the-badge)](https://huggingface.co/spaces/stepfun-ai/StepAudio-3-Music)

## StepAudio 3 Gen · General Audio Generation

A unified generation model spanning speech, vocals, sound effects, and music. **My contribution focused on music data pipelines** supporting the broader audio-generation effort.

[![Paper](https://img.shields.io/badge/Paper-TR-2563EB?style=for-the-badge)](https://arxiv.org/abs/2609.12945)
[![Project](https://img.shields.io/badge/Project-StepAudio_3_Gen-0F766E?style=for-the-badge)](https://stepaudiollm.github.io/step-audio-3-gen/)

## HMU-Bench · Hierarchical Music Understanding Benchmark

**Co-first author.** Co-developed a bilingual benchmark spanning symbolic notation and audio, with hierarchical tasks covering extraction, reasoning, and global/local analysis. Evaluation of seven omni models exposes gaps in audio understanding and differences between the two modalities. I also worked on linear-probe evaluation of audio-tokenizer representations.

[![Paper](https://img.shields.io/badge/Paper-Preprint-2563EB?style=for-the-badge)](https://arxiv.org/abs/2610.15773)

## Multimodal Music Understanding · Coming Soon

I'm working on a model that connects **audio, text, and symbolic music** through multi-task training. The work brings together full-song transcription, fine-grained MIR annotation, and music-theory question answering, with full-parameter fine-tuning in **Megatron**. More details will follow with the public release.

<br>

---

# 02 · Agentic Reasoning

> **Tools, retrieval & structured knowledge**

At **UC San Diego**, advised by **Dr. Julian McAuley**, I study how LLM agents can use executable tools and reusable knowledge to answer compositional questions about music.

## CSyMR · Compositional Music Retrieval & Reasoning

**First author · SIGIR 2026.** Built a benchmark of **126 score-grounded questions** and a ReAct agent with **16 music21 analysis tools**. The tool-augmented agent reached **66.67% accuracy**, a **5.56 percentage-point** improvement over ReAct without music tools.

The open-source Python system includes modular tool interfaces, JSON Schema argument validation, standardized error handling, configurable retries and timeouts, and reproducible benchmark runners.

[![Paper](https://img.shields.io/badge/Paper-SIGIR_2026-2563EB?style=for-the-badge)](https://doi.org/10.1145/3805712.3809923)
[![Code](https://img.shields.io/badge/Code-GitHub-475569?style=for-the-badge)](https://github.com/Alicaso/CSyMR-Agent)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-Dataset-D97706?style=for-the-badge)](https://huggingface.co/datasets/wangby76/CSyMR-Bench)

## SymSkill · Skill Graphs for Symbolic Music Understanding

**Second author · ISMIR 2026.** Co-developed a system that distills music curricula into a **skill graph of reusable analytical protocols**, enabling retrieval-guided reasoning. Evaluated on three benchmarks, with Qwen3.5-4B improvements of **4.76** and **3.27 percentage points** over the strongest baselines on CSyMR and MusicTheoryBench, respectively.

[![Paper](https://img.shields.io/badge/Paper-ISMIR_2026-2563EB?style=for-the-badge)](https://ismir2026program.ismir.net/poster_477.html#details)

<br>

---

# 03 · Earlier Research

> **Medical imaging & representation learning**

## Perinatal Brain Morphology · Contrastive Representation Learning

**Co-first author · Brain Imaging and Behavior, 2025.** During my undergraduate research at **Lanzhou University**, I helped develop a framework combining **quasi-conformal mapping** of 3D cortical meshes to 2D with **contrastive learning** for individual identification from brain morphology. My contributions included methodology, formal analysis, and manuscript preparation.

[![Paper](https://img.shields.io/badge/Paper-Brain_Imaging_%26_Behavior_2025-2563EB?style=for-the-badge)](https://link.springer.com/article/10.1007/s11682-025-00998-8)

## HRINet · Attention-Based Perinatal Brain Age Prediction

**Co-author · IEEE Journal of Biomedical and Health Informatics, 2024.** Contributed to research on attention-based modeling of hemispheric relationships for perinatal brain age prediction.

[![Paper](https://img.shields.io/badge/Paper-IEEE_JBHI_2024-2563EB?style=for-the-badge)](https://doi.org/10.1109/JBHI.2024.3411620)

<br>

---

# 04 · What I Work With

| Area | Methods & tools |
| :--- | :--- |
| **Modeling & training** | Python · PyTorch · Scikit-learn · Transformers · Multimodal learning · Contrastive learning · Representation learning · Supervised fine-tuning · Megatron |
| **Music & audio** | Music understanding & generation · MIR · Audio tokenization · Flow Matching / DiT · ABC / Kern / MusicXML / MIDI · music21 |
| **Agents & evaluation** | Tool-augmented LLMs · ReAct · Skill graphs · Retrieval-guided reasoning · LLM APIs · JSON Schema · Benchmark design · Linear probing · Error analysis |
| **Inference & systems** | vLLM · Ray · Model deployment · Parallel processing · Asynchronous execution · CPU/GPU workload coordination · Linux/Shell · Git · Docker |
| **Data & analysis** | SQL · Pandas · SparkSQL · Data/ETL pipelines · Large-scale annotation · Data validation |

<sub>Selected collaborative work is linked to its official project pages and publications. Descriptions distinguish my contributions from the broader team effort; code and models are maintained by the respective project teams.</sub>
