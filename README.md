# Hi, I'm Dan 🐱👋

Researcher and data scientist working at the intersection of economics, data science, and AI evaluation. I bring an economist's causal-inference toolkit to questions about how AI systems behave and what we can reliably learn from large-scale data — dual graduate training in Economics (Iowa State) and Information/Data Science (Michigan).

### 🔭 Currently

Running an ongoing weekly **LLM calibration & uncertainty evaluation program** — original evaluations of whether frontier models represent their own uncertainty, spanning probabilistic forecast calibration, interval calibration as question specificity decreases, and cross-level belief consistency. Scored with proper scoring rules (CRPS, log loss, pinball), ECE, and ground-truth-free self-consistency checks; power-analyzed rather than anecdotal (effect sizes, scenarios-needed-for-80%-power, multiple-comparison caveats). Across three rounds to date: frontier models stay overconfident on rare/underspecified cases, and self-reported confidence is largely uninformative.

### 📊 The eval program

An ongoing weekly program on whether LLMs can represent their own uncertainty.
Each round reuses the previous round's design or data — newest first.

| Round | Eval | Question | Builds on |
|---|---|---|---|
| **R6–R7** | [llm-anchoring-evals](https://github.com/drkalexander1/llm-anchoring-evals) | Does an irrelevant anchor shift a model's estimate *and* its stated interval? | R3 taxon substrate |
| **R5** | [eval-meta-consistency](https://github.com/drkalexander1/eval-meta-consistency) | In a fresh context, does a model know where its own uncertainty is highest? | R3 p10/p50/p90 CIs |
| **R3** | [bird-taxonomy-evals](https://github.com/drkalexander1/bird-taxonomy-evals) | Are independent beliefs about genus/family/order mutually coherent? | R1 species domain |
| **R2** | [florida-weather-evals](https://github.com/drkalexander1/florida-weather-evals) | Do intervals widen as questions get less specific? (*known* unknowns) | R1 design |
| **R1** | [michigan-bird-evals](https://github.com/drkalexander1/michigan-bird-evals) | Probabilistic calibration against eBird ground truth (*unknown* unknowns) | — |

**Side branch (R4)** — same harness, different question: model output quality and judge bias rather than uncertainty.
[haiku-evals](https://github.com/drkalexander1/haiku-evals) (5-7-5 form + subject grounding via embedding similarity) →
[haiku-judge-evals](https://github.com/drkalexander1/haiku-judge-evals) (blind pairwise judging — does a model pick its own haiku more often than an independent judge would?)

### 🗂️ Other work

- [plagiarism-detection-ir](https://github.com/drkalexander1/plagiarism-detection-ir) — multi-signal (BM25 + SBERT + Jaccard) reuse detection, PAN 2011 benchmark
- [sandhill-crane-migration-networks](https://github.com/drkalexander1/sandhill-crane-migration-networks) — max-flow min-cut migration bottlenecks over 3.2M observations
- [ebird-species-prediction](https://github.com/drkalexander1/ebird-species-prediction) — collaborative-filtering and multi-task models over 13.6B observations (SLURM/HPC)

### 🧭 Background

- **Research integrity & reproducibility** — independent statistical replications and forensic data analysis at Cornell supporting institutional research-integrity investigations; co-launched a cross-disciplinary reproducibility initiative, independently reproducing 15+ peer-reviewed studies across economics, sociology, communication, and veterinary medicine; presented methodology at IASSIST 2019.
- **Large-scale applied ML** — billion-observation HPC pipelines (SLURM, Great Lakes cluster) for ecological modeling: collaborative-filtering and multi-task neural models over 13.6B observations, directed-network migration bottleneck analysis via max-flow min-cut over 3.2M observations.
- **Information retrieval** — multi-signal (BM25 + SBERT + Jaccard) plagiarism/reuse detection pipeline evaluated on the PAN 2011 benchmark, addressing a gap standard tools like Turnitin miss.
- **Agentic systems** — technical lead on an LLM-powered natural-language-to-simulation-code interface for a biological cell-modeling platform (Compucell3D / UMich).

### 🛠️ Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit--learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat-square&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![HPC/SLURM](https://img.shields.io/badge/-SLURM%2FHPC-000000?style=flat-square&logo=gnubash&logoColor=white)

### 📫 Reach me

[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:dan.rk.alexander@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/dan-alex)
